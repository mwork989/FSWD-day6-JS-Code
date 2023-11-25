
why do we need Javascript ?
------------------------------------
1. Making Websites Fun and interactive: JavaScript allows developers to add cool features to websites. It's what makes buttons change color when you hover over them, or pop-up boxes appear when you click on something.

2. No Page Reloads: Normally, when you click a link, the whole page reloads. JavaScript lets us change parts of the page without refreshing everything. It's like changing one page in a book without closing the whole book.(asynchronous programming)

3. It helps to retreive data or send data: Imagine a website that shows you the latest weather or news updates from your friends. JavaScript helps fetch and display this information in real-time without you having to do anything.


before 2007 Javascript was designed for webapps/websites

--------------

after 2007 Javasript can be executed outside browser with node js runtime


Building Apps : JavaScript is not just for websites; it's like a superhero that can also build mobile apps. So, when you're using an app on your phone that works on both iPhone and Android, it's likely powered by JavaScript.

Quick and Efficient: JavaScript handles tasks in the background, like checking for new messages or loading more pictures, without slowing down the main stuff you're doing. It's like a helpful assistant making sure everything runs smoothly.

In short, JavaScript is the secret sauce that makes the internet exciting and interactive. It's the reason websites can do more than just show information – they can engage you, respond to your actions, and make your online experience more enjoyable.

Javascript History
------------------------
European Computer Manufacturers Association ( ECMA)

 Brenden Eich creator of javscript during his time at netscape/ mozilla 
 he wanted to make all developers use his language and at that time 
 most modern and popular langauage was JAVA but it had copyright from 
 sun microsystems  Due to copyright issue with "JAVA" keyword the team of individuals came with a idea of ECMA due to legal issue in short span 

 JAVA is not JAVAscript - JAVA UI

current version of Javscript  - ECMAscript 2023/ ES14 only 7% support in current browsers/ compilers 

most popular and used version of Javascript - ECMAscript 2015 or ES6 97% support https://compat-table.github.io/compat-table/es6/

https://compat-table.github.io/compat-table/esnext/

Official documentation - https://ecma-international.org/publications-and-standards/standards/ecma-262/


Where we can use JS in  2023 
----------------------------------
 1. Browser - Chrome, mozilla, IE
 2. PLatform - Android, linux, ws, ios   with the help of Node js runtime 


 what all things we can build in 2023
-----------------------------------
 1. web apps and conduct transactions
 2. we can build servers and services
 3. we can build scripts to rund platform based apps
 4. we can connect to hardware read and control the hardware js

Which area Javascript should not be used
-----------------------------------

 1. High-Performance Computing: JavaScript is an interpreted language and may not be the best choice for computationally intensive tasks or applications that demand extremely high performance. For such cases, languages like C++, Rust, or languages designed for high-performance computing may be more appropriate.

 2. Resource-Intensive Applications:Applications that require a lot of system resources (CPU, memory) might face performance challenges with JavaScript. In such cases, languages like Java, C#, or languages that compile to native code might be more efficient.


 what is an interpreted language  or executed at run time ?
--------------------------------------
 An interpreted language is a type of programming language for which most of its implementations execute instructions directly, without the need for a separate compilation step 

 what is Compiling ? source code which is getting converted to machine code
and process of conversion we call compiling and mechasim which does this we call it as compiler


How to add js in web page ?
-----------------------------

1. embedded way we can add in head and body sections
2. exteernal way we can add in head and body sections

now js can be coming from local or third party server


How we can declare variables in ES5 or ECMAscript 2014

1. without keyword (bad practice)
variable name  value
fruit          ="apple" --> atuomatically allocated window.fruit (global object )


2. with keyword

var fruit ="apple" --> depending upon where you are declaring the variable
it can be global or local


var fruit1 ="apple"   --> window scope / global scope or object

function test(){
var fruit1 ="orange";   --> function scope / local scope or object
 console.log(fruit1)
}


How we can declare variables in ES6 or ECMAscript 2015

1. new keywords introduced  for variable declaration 

    let - 1.1 Variables declared with let are block-scoped rather than function scoped
         1.2 Variables declared with let can be reassigned basically change the values as needed but you cannot redelcare within that scope

    {
        let fruit1 ="orange"
    }
    c
    e.g.

    if (eligibility === true) {
        let x = 10;
        console.log(x); // 10
    }
    console.log(x); // Error: x is not defined (outside the block)


   2 const 

   e.g. const cost = 10
  
   2.1 Variables declared with const are block-scoped rather than function scoped

   2.2 const is short for "constant," indicating that the value of a const variable cannot be reassigned after it has been declared. It is a read-only variable. Methematical formulars and variables which you seem to not to change to value it that sitution use const 

   2.3A const variable must be initialized when it is declared. Once assigned, its value cannot be changed.


Note:
Both let and const improve JavaScript's handling of variable scoping and reduce common pitfalls associated with using var.

It's a good practice to prefer const whenever possible and only use let when you know the variable's value will change. This helps in writing more predictable and maintainable code.




