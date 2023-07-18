# javascript-documentation-bohubrihi
- prerequisities: HTML & CSS

## 1. Getting Started With JavaScript

#### 1.1 Introduction & Course Overview
**What is JavaScript**
- JavaScript is a Programming Language of Browser
- It gives life to the web pages
- Client-Side Scripting Language
- Used along with HTML
- JavaScript can be executed on Server also (Thanks next.js and node.js)
- Even Android and IOS App can be developed with JavaScript
- JavaScript's version is maintained by it's Community
- Version 1 or ECMAscript 1 released on 1997
- Modern JavaScript version is ECMAscript 6 or ES 6 and it released on 2015

**What will we learn from this Course?**
- Fundamentals of JavaScript
- Object Oriented Programming
- Document Object Model (DOM)
- Regular Expression
- Error Handling
- Asynchronous Programming, Promises
- AJAX, Fetch API
- ECMAscript 6 

**What do we need to run JavaScript?**
- Code Editor (Visual Studio)
- Browser (Google Chrome or Mozilla Firefox)

**JavaScript Engine**
- Google Chrome - V8
- Mozilla - SpiderMonkey
- Safari - JavaScriptCore
- Internet Explorer - Chakra
- 
#### 1.2 Installing Visual Studio Code


## 2. Now Start Coding!

#### 2.1 JavaScript Outputs
**Displaying Output**
- window.alert()
- document.write()
- innerHTML
- console.log()
  
**Exmaple:**
  ```html
//This is a index.html file
<body>
   <h1 id="idH1"></h1>
   <h3 id="idH3"></h3>
   <p id="root"></p>
   <script>
      window.alter("Hello World");
      document.write("Hello Bangladesh");
      document.getElementById("root").innerHTML = "I Love Dhaka";
      document.getElementById("idH1").InnerHTML = "I am H1";
      document.getElementById("idH3").InnerHTML = "I am H3";
      console.log("Hello Bohubrihi");
   </script>
</body>
  ```
#### 2.2 Connect JS to HTML File
**Exmaple:**
***index.html File***
  ```html
<body>
   <h1 id="idH1"></h1>
   <h3 id="idH3"></h3>
   <p id="root"></p>
   <script src="script.js"></script>
</body>
  ```
***script.js File***
```javascript
window.alter("Hello World");
document.write("Hello Bangladesh");
document.getElementById("root").innerHTML = "I Love Dhaka";
document.getElementById("idH1").InnerHTML = "I am H1";
document.getElementById("idH3").InnerHTML = "I am H3";
console.log("Hello Bohubrihi");
```
#### 2.3 Statement, Syntax, Comments
**Statement**
- In javascript every line is a statement. It's a good practice to use semicolon to close a statement.
**Syntax**
- Strings should be written inside single and double quotation.
- Number does not need quotation.
- Using // you can comment about your code.
- To comment multiple line of you code, select codes using mouse and press 'ctrl + /' in keyboard
  
#### 2.4 User Input
**prompt function**
***example script.js***
```javascript
var x; 
x = prompt("Enter you name"); 
console.log(x);
```
***উপরের প্রোগ্রামটি স্টেপগুলো হলো***
- x একটি ভ্যারিয়েবল যেখানে আপনি কোনো মান রাখতে পারবেন
- prompt এর মাধ্যমে যে ভ্যালু আপনি লিখবেন তা x-এর ভেতরে স্টোর হবে
- browser-এ রাইট ক্লিক দিয়ে inpect element-এ যান। এরপর console এ গিয়ে দেখুন আপনি x-এর মান যা লিখেছিলেন তা console.log(x) লেখার কারণে সেখানে পোষ্ট হয়েছে।
#### 2.5 Complete the quiz and post the result on facebook group

## 3. Variables & Contstants

#### 3.1 JavaScript Variables Part - 1
**variable declaration**
- আপনি var, let ও const লিখে ভ্যারিয়েবল ডিক্লেয়ার করতে পারবেন।
- এই let ও const-এর ব্যবহার অ্যাডভান্সড লেভেলে শিখানো হবে।
- ভ্যারিয়েবলের ভ্যালু কম্পিউটারের একটি অ্যাড্রেসে বা মেমোরিতে অ্যালোকেট হয়।

***example script.js***
```javascript
var myName;
myName = 30;
var myName = 30;
```
#### 3.2 JavaScript Variables Part - 2
***Example - 1***
***example script.js***
```javascript
var a;
a = 45;
console.log(a);
a =35;
console.log(a);
a = "simanta"
console.log(a)
```

***Example - 2***
```javascript
var a = 20; // a-এর ভ্যালু ২০
var b = a; // b-এর ভ্যালু ২০
console.log(a); // ২০ প্রিন্ট হবে
console.log(b); // ২০ প্রিন্ট হবে
a = 30; // a-এর ভ্যালু ৩০ হবে
console.log(a); // ৩০ প্রিন্ট হবে
console.log(b); // কিন্তু এখানে ২০ ই প্রিন্ট হবে কারণ a এর ভ্যালু বদলানোর পর b এর চেঞ্জ আনতে কোনো কোড লেখা হয়নি।
```
#### 3.3 JavaScript Constants and Keywords
#### 3.4 Complete the quiz and post the result on facebook group
