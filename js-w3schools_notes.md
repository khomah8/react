from [**JavaScript** tutorial](https://www.w3schools.com/js/ 'try-code examples links are following') and <https://javascript.info/>: 

_Old JavaScript examples may use a type attribute: <script type="text/javascript">.
The type attribute is not required. JavaScript is the default scripting language in HTML._

Scripts can be placed in the <body>, or in the <head> section of an HTML page, or in both.

_Placing scripts at the bottom of the <body> element improves the display speed, because script interpretation slows down the display._
  
External scripts are practical when the same code is used in many different web pages. JavaScript files have the file extension **.js.**
To use an external script, put the name of the script file in the src (source) **attribute** of a <script> tag:
_Example: <script src="myScript.js"></script>_

External scripts cannot contain <script> tags.
  Placing scripts in external files has some advantages:
1) It separates HTML and code (versioning? )
2) It makes HTML and JavaScript easier to read and maintain (teamwork? debug? )
3) Cached JavaScript files **can speed up page loads** 

External scripts can be referenced with a **full URL** or with a **path relative** to the current web page.

JavaScript can "display" data in different ways:
1) Writing into an HTML element, using innerHTML.
To access an HTML element, JavaScript can use the **document.getElementById(id)**.innerHTML method. The id **attribute** defines the HTML element. The innerHTML **property** [defines the HTML content](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_dom ).

2) Writing into the HTML output using **document.write()**. For testing purposes, it is convenient to use. _Using document.write() [after an HTML document is loaded, will delete all existing HTML](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_write_over)_ 

3) Writing into [an alert box](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_alert), using **window.alert()** method.

4) Writing into the browser console, using **console.log()**. For debugging {F12} [purposes mainly](https://www.w3schools.com/js/tryit.asp?filename=tryjs_output_console).

JavaScript statements (programming instructions, code) are composed of:
+ Values, { Fixed values are called **literals**. Variable values are called **variables** }
+ Operators, { arithmetic ( + - * / ) to compute values, an assignment ( = ) to assign values to variables; [example of concat for strings](https://www.w3schools.com/js/tryit.asp?filename=tryjs_oper_concat4) }
+ Expressions, { An expression is a combination of **values, variables, and operators, which computes to a value** }
+ [Keywords](https://www.w3schools.com/js/js_reserved.asp), 
+ Comments. { // smth, /* smth else */ }

_Ending statements with [semicolon](- ';') is not required, but highly recommended._

If a JavaScript statement does not fit on one {visible} line, the best place [to break it is after an operator](https://www.w3schools.com/js/tryit.asp?filename=tryjs_statements_linebreak) 

JavaScript statements can be grouped together in **code blocks, inside curly brackets {...}**. The purpose of code blocks is to define statements to be executed together.

In JavaScript, the first character must be a **letter, or an underscore (_), or a dollar sign ($)**. Numbers are **not allowed as the first character**. This way JavaScript can easily distinguish identifiers from numbers. Hyphens are **not allowed** in JavaScript. They are reserved for subtractions. All JavaScript identifiers are **case sensitive**.  


