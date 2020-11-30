# Pling.js
A light Javascript library for displaying a customized pop-ups or alert.
It can be used like a Javascript alert() function.
#### *example*
alert("hello world");<br>
Pling ("hello world");

It can also be used inline in HTML to createa pop-up on an element click.\
`<button onclick = 'Pling("hello world")'> demo </button>`

### To start using pling.js in your project.

#### source link
https://rawcdn.githack.com/stonny71/pling/95d346c1c9ad0faa10c73ee3c041ea8e1fb8a4e8/pling.js

Put the pling.js source link inside a `<script>` and place inside the `<head>` of your HTML document.

You can also place your Pling.js `<script>` below the `<body>` section.
**sample** <br>
`<script src='   '> <script>`
`<script>`
 `your javaScript codes here`
`<script>`
`</body>`

### Full Documentation

**Displaying alert with a title**\
To display alerts with a title, the Pling() function should have two arguments.
where:
argument1 is the content of the alert &
argument2 is the title.

`<button onclick='pling( "Hello world", "greetings" )'></button>`

**Displaying alert with no title**<br>
The Pling() function should have only one argument.<br>
`<button onclick='pling( "Hello world" )'></button>`

**Adding more styles to your alert**<br>
To add more css styles to the alert, the Pling() function should have three arguments<br>
where:
argument1 is the content of the alert <br>
argument2 is the title & <br>
argument3 is a className you will use inside your css section.<br>

pling.js has provided four classnames to use to actually customise the alert.<br>
`.btn`  is the "ok" button <br>
`.title` is the title of the alert <br>
`.content` is the text content of the alert <br>
`.argument3` is the alert box itself <br>

**sample code to give your alert a customized look**<br>
`<button onclick = 'Pling( "content", "title", "custom")'>`
`</button>`

_Inside your css sheet:_
`<style>`

`/**main container**/`
`.custom .box{
background:#333 !important;
color:#fff !important;
}`

`/**title of the alert**/`
`.custom .title{
background:#64B5F6 ! important;
color:#fff !important;
}`

`/**content of the alert**/`
`.custom .content{
color:#fff !important;
}`

`/**ok button**/`
`.custom .btn{
background:#333 !important;
color:#fff !important;
}`

`</style>`

**Note**
argument3 can take any name.
in the above code, I used `custom`
You are free to use any name of your choice.
