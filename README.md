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
- ভ্যারিয়েবলের ভ্যালু কম্পিউটারের একটি অ্যাড্রেসে বা মেমোরিতে অ্যালোকেট হয়।

***example script.js***
```javascript
var myName;
myName = 30;
let myName = 30;
```
#### 3.2 JavaScript Variables Part - 2
***Example - script.js***
```javascript
var a;
a = 45;
console.log(a);
a =35;
console.log(a);
a = "simanta"
console.log(a)
```

***Example - 2 script.js***
```javascript
var a = 20; // a-এর ভ্যালু ২০
var b = a; // b-এর ভ্যালু ২০
console.log(a); // ২০ প্রিন্ট হবে
console.log(b); // ২০ প্রিন্ট হবে
a = 30; // a-এর ভ্যালু ৩০ হবে
console.log(a); // ৩০ প্রিন্ট হবে
console.log(b); // কিন্তু এখানে ২০ ই প্রিন্ট হবে কারণ a এর ভ্যালু বদলানোর পর b এর চেঞ্জ আনতে কোনো কোড লেখা হয়নি।
```

***Example - 3 script.js***
```javascript

var a = 20; 
var b = 10; 
var c= a+b;
console.log(c); // যোগফল প্রিন্ট হবে
```
***ভ্যারিয়েবল লেখার নিয়মঃ***
- $ বা _ দিয়ে ভ্যারিয়েবল শুরু করতে পারবো।
- ভ্যারিয়েবল কেসসেন্সিটিভি। মানে  জাভাস্ক্রিপ্ট ক্যাপিটেল লেটার বা স্মল লেটারকে ভিন্ন ভ্যারিয়েবল হিসেবে ধরবে।
- ভ্যারিয়েবলের নাম নাম্বার দিয়ে শুরু করা উচিৎ না।

#### 3.3 JavaScript Constants and Keywords
- const -এর ভ্যালু চেঞ্জ হবে না।
- ধরুন const a = 3 লিখেছেন। তাহলে a এর মান সবসময় 3 থাকবে। এটা চেঞ্জ করা সম্ভব না।
- জাভাস্ক্রিপ্টে রিজার্ভড কিওয়ার্ড আছে যেমন var, let, const, abstract, break, await, class ইত্যাদি। এগুলো রিজার্ভ কি-ওয়ার্ড। এইগুলো ব্যবহার করে ভ্যারিয়েবলের নাম লেখা যাবে না।
#### 3.4 Complete the quiz and post the result on facebook group

## 4. Operators
### 4.1 Arithmetic Operators
- কোনো অপারেশন যার মাধ্যমে হয় তা-ই অপারেটর যেমন +, -, / ইত্যাদি।
- যে অপারেটর দুইটা অপারেন্ড নিয়ে কাজ করে তাকে বাইনারি অপারেটর বলেন। যেমন 2 + 3 এখানে + অপারেটর দুইটা অপারেন্ডকে যোগ করছে তাই এটা বাইনারি অপারেটর। 
- +, -, *, /, *, % হলো অ্যারিথমেটিক অপারেশন। এগুলো অ্যালজেব্রিক অপারেশন করে।
- % দিয়ে ভাগশেষ বের করে হয়।
- ** দিয়ে পাওয়া অপারেটর বুঝায় যেমন 2**3 হলো টু কিউব।
- ++ হলো ইনক্রিমেন্ট অপারেটর।
- -- হলো ডিক্রিমেন্ট অপারেটর।

- সরল অংকের BODMAS রুলস অনুযায়ী একাধিক অপারেটর কাজ করে।

***এক্সাম্পল***
```javascript
var a = 20; 
var b = 10; 
var add = a+b; //add এর মান হবে ৩০
var sub = a-b; // sub এর মান হবে ১০
var multi = a*b; // multi এর মান হবে ২০০
var div = a/b; //div এর মান হবে ২
var c = 11;
var mod = a%c; // mod এর মান হবে ৯

a = a + 1; //একেই সংক্ষেপে a++ বলা হয়
b = 1 + b; // একে সংক্ষেপে ++b বলা হয়
```
#### 4.2 String Operators
***এক্সাম্পল***
```javascript
var line1 = "Hello";
var line2 = "World";
console.log(line1+" "+ line2);

var num1 = 6;
var num2 = 5;
var num3 = "8";
var num4 ="3";
console.log(num1+num2);// আউটপুট হবে 11 এটি নাম্বার রেজাল্ট দিবে
var str = "Bangladesh" 
console.log(num1+str)// আউটপুট হবে "6Bangladesh"  সম্পূর্ণটা স্ট্রিং হয়ে যাবে
console.log(num1+num3)// আউটপুট হবে "68"  সম্পূর্ণটা স্ট্রিং হয়ে যাবে
console.log(num3-num2)// নরমাল বিয়োগ করে রেজাল্ট '5' দেখাবে কিন্তু তা স্ট্রিং আকারে থাকবে।
console.log(num3-str)// আউটপুট আসবে NaN - নট এ নাম্বার
```
#### 4.3 Comparison, Logical and Conditional Operators

***Comparison Operators***
- == অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষ সমান কিনা।
- != অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষ অসমান কিনা।
- === অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষে আর ডানপক্ষে ভ্যালু ও টাইপ দুটোই সমান কিনা
- !== অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষে আর ডানপক্ষে ভ্যালু ও টাইপ দুটোই অসমান কিনা
- < অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষের চেয়ে ছোট কিনা।
- '>' অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষের ছেয়ে বড় কিনা।
- <= অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষের চেয়ে ছোট কিংবা সমান কিনা
- '>=' অপারেটর দিয়ে কম্পেয়ার করা হয় বামপক্ষ আর ডানপক্ষের চেয়ে বড় কিংবা সমান কিনা।
```javascript
var a = 4;
var b= '4';
var c = 5;
a == b; //true
a === b; //false
a != c; //true
a != b; //false
a !==b  //true
c>a; //true
a>c true
a<c //true
c<a //false
c>=a; //true
a>=c; // false
c<=a; //false
a<=c //true
```
***Logical Oparetor***
- লজিকাল অপারেটর বামপক্ষ ও ডানপক্ষের লজিক মিলেছেন কিনা চেক করবে।
- || হল or অপারেটর। বামপক্ষ ও ডানপক্ষের যেকোনো একটি true হলেই এটি true রিটার্ন করবে। 
- && হল and অপারেটর। এটি কেবলমাত্র তখনই true রিটার্ন করবে যখন বামপক্ষ ও ডামপক্ষ দুটিই true। কিন্তু বামপক্ষ ও ডানপক্ষের যেকোনো একটি true না হলে এটি false রিটার্ন করবে। 

- ! হলো not অপারেটর। এ অপারেটর বিপরীত কিছু বুঝাতে ব্যবহার করা হয়। সহজ বাংলা উদাহরণ দেই। ধরুন আমি বলতে চাই, 'ছেলেটি খারাপ'। এটাকে not অপারেটর ব্যবহার করলে এভাবে লিখবো 'ছেলেটি !ভালো' বা আমি যদি বলতে চাই,'ছেলেটি ভালো' তাহলে not অপারেটরব্যবহার করে লিখবো,'ছেলেটি !খারাপ' 

```javascript
true || true //returns true
true || false // returns true
false || true // returns true
false || false // return false

true && true // returns true
true && false // returns flase
false && true // returns false
false && false // returns false

!true //returns false
!false //returns true

(4>6) || (1<7) // returns true
(4>6) && (1<7) // return false
!(4>6) //returns true
!(1<7) // returns false
```
***Conditional Oparetor***

```javascript
a =(1<8)? "hello" : "world";
console.log(a) //output 'hello';
```

#### 4.4 Assignment Operators

```javascript
var a =19;
var b = 12;
a = b;
console.log(a); //output 19
a +=12;
a -=10;
a *=10;
a /=2;
a %=3;
var name = 'hello';
name = name+ ' world';
console.log(name) // output 'Hello World'
```

## 5. Data Types
#### 5.1 Different Types of Data
#### 5.2 Numbers 
#### 5.3 Strings
#### 5.4 Booleans
