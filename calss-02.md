## Text
Structural markup: the elements that you can use todescribe both headings and paragraphs
Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on .
 
 ### CSS
 Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML
 CSS has a simple syntax and uses a number of English keywords to specify the names of various style properties.
 [CSS](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)
 [Selector](https://www.quertime.com/wp-content/uploads/2015/04/style-sheets.jpg)

 What is JavaScript
JavaScript (js) is a light-weight object-oriented programming language which is used by several websites for scripting the webpages. It is an interpreted, full-fledged programming language that enables dynamic interactivity on websites when applied to an HTML document.
JavaScript Example
<script>  
document.write("Hello JavaScript by JavaScript");  
</script>  

A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement.Statements should end with a semicolon

JavaScript is case sensitive so myFirst means something different to MyFirst
A statement is an individual instruction that the computer should follow. Each one should start on a new line and end with a semicolon this makes your code easier to read and follow.
Some statements are surrounded by curly braces; these are known as code blocks. The closing curly brace is not followed by a semicolon
** COMMENTS**
write comments to explain what your code does /* this is comment */

** DATA TYPES **
NUMERIC DATA TYPE The numeric data type handles numbers.
STRING : consists of letters and other characters.
BOOLEAN : have one of two values: true or false.
RULES FOR NAMING VARIABLES : 1 ) The name must begin with a letter, dollar sign ($),or an underscore (_). It must not startwith a number.
2) You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable
3) The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.

 #### 3 Places to put JavaScript code
Between the body tag of html
Between the head tag of html
In .js file (external javaScript)

Example :
html>  
<head>  
<script type="text/javascript">  
function msg(){  
 alert("Hello Javatpoint");  
}  
</script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
</body>  
</html>  

### LOOPS
In JavaScript we have the following conditional statements:

Use if to specify a block of code to be executed, if a specified condition is true
Use else to specify a block of code to be executed, if the same condition is false
Use else if to specify a new condition to test, if the first condition is false
Use switch to select one of many blocks of code to be executed

if (condition) {
  // block of code to be executed if the condition is true
} else {
  // block of code to be executed if the condition is false
}

I wrote this example to explain the idea :
var userBirth = prompt("Enter your brith date")

const currentYear = 2020;

if ( userBirth < currentYear ) {
     var age = currentYear - userBirth
     alert(age)
} else {
  alert("Enter your brith date correctly ")
}








