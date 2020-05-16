
# Diff between cpp and java script
> + JavaScript is a scripting whereas C++ is a programming language.
 > + C++ program is to be compiled and executed, whereas a script in JavaScript is interpreted. 
 > + JavaScript supports Java virtual machine implementation
 > + Whereas C++ does not support Java virtual machine implementation

 # Difference in JavaScript, HTML, and CSS

> + Lets consider a web page as a human body. Now let's see what each of these language really do:

> + ***HTML*** is a structural language that build the structure of a website as the skeletal system form the structure of the human body. Heading, paragraphs,
   > + images, text all are the part of HTML that creates the basic structure of a website.

> + ***CSS*** is a styling language that gives styling of a website. With the help of front color, background color and border styling CSS furnishes the 
   look of the site as the skin gives look to the human body.

> + JavaScript is a programming language that gives motion and logics to the website for example a popup window alert. It is just like the motion of human body.

# Why is JavaScript called a client side scripting program?

> + JavaScript is a client-side scripting language, which means the source code is processed by the client's web browser rather than on the web server. 
> + This means JavaScript functions can run after a webpage has loaded without communicating with the server
 programs written for a special run-time environment that automate the execution of tasks that could alternatively be executed one-by-one by a human operator. 

# For javascript do we need  compiler?
 > + NO,
JavaScript is an interpreted language, not a compiled language

# How does browser run JavaScript?

> + JavaScript is called a Client-side Scripting Language.

> + When the browser loads the page, the browser has a built-in interpreter
 that reads the JavaScript code it finds in the page and runs it. Web page designers use JavaScript in many different ways. One of the most
 common is to do field validation in a form.

# Can we store different data type in array?
> + Arrays can contain any type of element value (primitive types or objects), but you can't store different types in a single array. 

# Difference between == and ===

> + = is used for assigning values to a variable in JavaScript.
 > + == is used for comparison between two variables irrespective of the datatype of variable.\ 
> +  === is used for comparision between two variables but this will check strict type, which means it will check datatype and compare two values

# What is meant of document.write();

> + The output of document.write is inserted into the document at that point. Later, though, once the page is fully loaded, if you use document.write, it implicitly performs a document.open,
 which wipes out the page and starts writing a new one from scratch.

# Data type in JavaScript
> + String-	represents sequence of characters e.g. "hello"
> + Number-	represents numeric values e.g. 100
> + Boolean-	represents boolean value either false or true
> + Undefined-	represents undefined value
> + Null-	represents null i.e. no value at all

# Event used in JavaScript

JavaScript's interaction with HTML is handled through events that occur when the user or the browser manipulates a page.

Event	            Description
> + onchange- An HTML element has been changed
> + onclick-The user clicks an HTML element
> + onmouseover-The user moves the mouse over an HTML element
> + onmouseout-The user moves the mouse away from an HTML element
> + onkeydown-The user pushes a keyboard key
> + onload- The browser has finished loading the page

Event handlers can be used to handle, and verify, user input, user actions, and browser actions:

Things that should be done every time a page loads
Things that should be done when the page is closed
Action that should be performed when a user clicks a button
Content that should be verified when a user inputs data



JavaScript	        C++

Built for the web	Built for everything
Multi-paradigm      	Object oriented
Dynamically typed	Statically typed
Runs slower than C++	Runs faster than JavaScript
Easy to learn	        Challenging to learn
Interpreted	        Compiled

#  What is array in js?

> + JavaScript arrays are used to store multiple values in a single variable. 
> + An array is a special variable, which can hold more than one value at a time.
> + Unlike most languages where array is a reference to the multiple variable

#  Difference between getElementByid() and innerhtml

> + innerHTML property refers to the literal HTML markup that is, once assigned, interpreted and incorporated 
into the DOM (Document Object Model) for the current document.
> + The getElementById() method returns the element that has the ID attribute with the specified value. This method is one of 
the most common methods in the HTML DOM, and is used almost every time you want to manipulate, or get info from, an element on your document.

# What is console.log()
> + The console. log() is a function that writes a message to log on the debugging console, such as Webkit or Firebug. In a browser you will 
not see anything on the screen. It logs a message to a debugging console


# Why array prints all the elements ?

> + values() function is an inbuilt function in JavaScript which is used to returns a new array Iterator object that contains the values 
for each index in the array i.e, it prints all the elements of the array.

# What are the methods of window class 

> + alert()	Displays an alert box with a message and an OK button
> + atob()	Decodes a base-64 encoded string
> + blur()	Removes focus from the current window
> + btoa()	Encodes a string in base-64
> + clearInterval()	Clears a timer set with > + setInterval()
> + clearTimeout()	Clears a timer set with setTimeout()
> + close()	Closes the current window
> + confirm()	Displays a dialog box with a message and an OK and a Cancel button
> + focus()	Sets focus to the current window
> + getComputedStyle()	Gets the current computed CSS styles applied to an element
> + getSelection()	Returns a Selection object representing the range of text selected by the user
> + matchMedia()	Returns a MediaQueryList object representing the specified CSS media query string
> + moveBy()	Moves a window relative to its current position
> + moveTo()	Moves a window to the specified position
> + open()	Opens a new browser window
> + print()	Prints the content of the current window
> + prompt()	Displays a dialog box that prompts the visitor for input
> + requestAnimationFrame()	Requests the browser to call a function to update an animation before the next repaint
> + resizeBy()	Resizes the window by the specified pixels
> + resizeTo()	Resizes the window to the specified width and height
> + scroll()	Deprecated. This method has been replaced by the scrollTo() method.
> + scrollBy()	Scrolls the document by the specified number of pixels
> + scrollTo()	Scrolls the document to the specified coordinates
> + setInterval()	Calls a function or evaluates an expression at specified intervals (in milliseconds)
> + setTimeout()	Calls a function or evaluates an expression after a specified number of milliseconds
> + stop()	Stops the window from loading


# is JavaScript object oriented or not?

> + JavaScript is object-oriented, but is not a class-based object-oriented language like Java, C++, C#, etc.
> +  It can support OOP because it supports inheritance through prototyping as well as properties and methods. 

#  What are the user defined data types in js?

> + Two Kinds of Data
In JavaScript there are two different kinds of data: primitives, and objects. 
> + A primitive is simply a 
data type that is not an object, and has no methods.
> + > + What about Objects?
> + Objects are not a primitive data Type.
> + An object is a collection of properties. > + These properties are stored in key/value pairs.
> + Properties can reference any type of data, including objects and/or primitive values.

#  Built-in functions
> + JavaScript has five functions built in to the language. They are eval, parseInt, parseFloat, escape, and unescape.

# js is procedural or object oriented

> + JavaScript is neither an object-oriented nor a functional programming language. It's a procedural language. Yes, it has 
support for object-oriented programming (OOP) using prototypes. However, prototypes are not a common way to do OOP.


# why js is dynamic types

> + In dynamically-typed languages, the errors occur only once the program is executed. That is, at runtime. This means that 
a program written in a dynamically-typed language (like JavaScript or Python) can compile even if it contains type errors 
that would otherwise prevent the script from running properly.
> + Dynamically-typed languages are those (like JavaScript) where the interpreter assigns variables a type at runtime based on the variable's value at the time.


# How to sort strings in JavaScript?
> + We can sort the strings in JavaScript by following methods described below:

> + Using sort() method
> + Using loop
> + Using sort() method: In this method, we use predefined sort() method of JavaScript to sort the array of string. 
This method is used only when the string is alphabetic. It will produce wrong results if we store numbers in an array and apply this method.

# Math
> + is is built in class than can not use to create object.purpose is to give all sorts of math function and constants.
> + all member of math are defined as static,u can call them directly by using math obj.attempting to create math object on math class may result in error.
> + we can call math static using dot operator

eg.E Euler constant 2.7183
   pi 3.1416
SQRT2 etc.

# when we write array why js print array

> + The array. values() function is an inbuilt function in JavaScript which is used to returns a new array Iterator object that contains the values for each
 index in the array i.e, it prints all the elements of the array. Return values: It returns a new array iterator object i.e, elements of the given array.

# Undefined:-
> + There are certain cases when undefined value is returned in javascript as follows:-
1)Whenever we declare a variable without assigning any value to it, javascript implicitly assigns its value as undefined.
let name;
console.log(name); //undefined
2) When value is not assigned in array or object
let numArray = [1,2,,4];
console.log(numArray);  
//[1, 2, empty, 4]
typeof(numArray[2])
//"undefined"
3) When functions don’t have a return statement but are called for assigning a value to a variable.

# Null:-
> + null is a reserved keyword in javascript. We can assign a null value to a variable explicitly using the keyword null.
 > +  Null essentially represents a non-existent 
or an empty value i.e. we explicitly tell javascript interpreter that the variable has no value.

# Include JS file in HTML
> +  By using ***Script src*** attribute

# Is JavaScript object oriented or not
> + JavaScript is object-oriented, but is not a class-based object-oriented language like Java, C++, C#, etc. Class-based OOP languages are a subset of the larger family of OOP languages which also include prototype-based languages like JavaScript and Self