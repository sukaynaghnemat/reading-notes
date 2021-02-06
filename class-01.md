#  Introductory HTML and JavaScript

![image](https://e7.pngegg.com/pngimages/658/623/png-clipart-cascading-style-sheets-html-web-development-javascript-web-browser-vs-miscellaneous-blue.png)

**HTML** is the standard markup language for creating web pages.It stands for Hyper Text Markup Language, it describes the structure of web pages using markup,
HTML elements are the building blocks of HTML pages, it elements are represented by tags, it tags mark portions of content such as "heading", "paragraph paragraph", "table table", and so on Browsers do not display HTML tags, but rather use them to display page content.

*The HTML* code is made up of characters that live inside angledbrackets — these are called HTML elements. Elements are usuallymade up of two tags: an opening tag and a closing tag. (The closing taghas an extra forward slash in it.) Each HTML element tells the browsersomething about the information that sits between its opening and closing tags.


**CSS** is an abbreviation for Cascading Style Sheet, which means flowing style sheets, and CSS technology is used in designing web pages so that the entire look of the site is controlled in terms of the type, color, or size of the font used, and that without the need to write those codes or repeat them in Each page within the site, and therefore it is possible to make any modifications to all files through only one file, which saves a lot of effort and time. The function of this technology is to control how the web page is displayed without interfering with the content, which facilitates the process of managing the site, modifying a single CSS file will affect the design of all website pages. CSS files simplify the process of designing and managing websites, and solve many problems that any website developer may encounter.


*An example for using css code*

<style type="text/css">
.highlight {
	color: Blue;
	font-style: italic;
	font-weight: bold;
	font-size: 120%;
	font-family: Tahoma, Verdana, Arial;
}
</style>

This is a piece of
<span class="highlight">text</span> with
<span class="highlight">highlighted</span> elements in
<span class="highlight">it</span>.



**Javascript** JavaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.

*JavaScript* is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else. (Okay, not everything, but it is amazing what you can achieve with a few lines of JavaScript code.)

*An example for using javascript code *


const para = document.querySelector('p');

para.addEventListener('click', updateName);

function updateName() {
  let name = prompt('Enter a new name');
  para.textContent = 'Player 1: ' + name;
}






















