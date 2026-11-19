JAVA SCRIPT


* JavaScript (js) is a light- weight object- oriented programming language which is used by several websites for scripting the webpages.
* JavaScript was initially created to





1\) code between the body tag

Simple example of JavaScript that displays alert dialog box

<html>

<body>

<script type="text/javascript">

alert("Hello Javatpoint");

</script>

</body>

</html>



2\) code between the head tag

<html>

<head>

<script type="text/javascript">

function msg(){

alert("hello Javatpoint");

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


-----------------------------------------------------------------------------------------


JavaScript Values

The JavaScript syntax defines two types of values:

1. Fixed values
2. Variable values

Fixed values are called Literals.
Variable values are called Variables.

------------------------------------------------------------------------------------------

JavaScript Literals

The two most important syntax rules for fixed values are:

1. Numbers are written with or without decimals.
2. Strings are text, written within double or single quotes.

------------------------------------------------------------------------------------------


There are some rules while declaring a javascript variable:

* Name must start with a letter(a to z or A to Z), underscore(_), or dollar($) sign.
* After first letter we can use digits(0 to 9), for example value1.
* JavaScript variables are case sensitive, for example x and X are different variables.




A variable can be declared multiple times using a var keyword. This is possible in only JavaScript.

-------------------------------------------------------------------------------------------------------------------------------

JavaScript let keyword

* let is a keyword that is used to declare a block scoped variable.
* the var keyword is used to declare a variable in JavaScript whis is treated as a normal variable.
* Variables declared using let have scope in the block in which they are declared as well as any sub- blocks within it.

Block Scope

When a variable is declared inside the block then it cannot 

--------------------------------------------------------------------------------------------------------------------------------


JavaScript Const

* The value of the variable cannot be changed

---------------------------------------------------------------------------------------------------------------------------------

JavaScript primitive data types

String: represents sequence of characters e.g."hello"
Number: represents numeric values e.g.100
Boolean: represents Boolean value either false or true
Undefined: represents undefined value
Null: represents null i.e. no value at all




JavaScript Assignment Operators


Operators                            example                                  Same As

=                                     x=y                                      x=y
+=                                    x+=y                                     x=x+y
-=                                    x-=y                                     x=x-y





JavaScript Special Operators

Operation     Description
(?:)          Conditional Operator returns value based on the condition. It is like if-else.
,             Comma Operator allows multiple expressions to be evaluated as single statement.
delete        Delete Operator deletes a property from the object.
in            In operator checks if object has the given property.
inatanceof    checks if the object is an instance of given type
new           creates an instance(object)
typeof        checks the type of object.
void          if discards the expression's return value. 
yield         checks what is returned in a generator by the generator's iterator.
