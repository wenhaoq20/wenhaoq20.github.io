---
layout: essay
type: essay
title: Clarity in Code
# All dates must be YYYY-MM-DD format!
date: 2021-09-23
labels:
  - Coding
  - Software Engineering
  - ESLint
  - Intellij
---
<img class="ui image" src="/images/codeS1.jpg">

The most common experience that most coders have come across in their career in programming is when you forget what the code you have written in the past actually did when you were reviewing a particular project from many weeks, months, or even years ago. This is where practicing good coding standards comes into play here. With good coding standards, reading the code will give you a good idea of what the code does and helps you troubleshoot any problems you might encounter in your program. For me, coding standards is like organizing a house. Everything in the house is organized in a way that it’s clean, easy to locate things, and aesthetically pleasing. Having good coding ethics and practices seems like a trivial thing to do, but it will help you a lot in the long term as well as others. 

## Example of code with different coding standards
```javascript
function functionOne(){
let i; i = 1 + 1;
let Testvariable = true
  if(Testvariable)
  return i + 1;
  else
  return i;
}
```

```javascript
function functionTwo(){
  let i;
  i = 1 + 1;
  let testVariable = true;
  if (testVariable) {
    return i + 1;
  } else {
    return i;
  }
}
```
These two functions share the same content but are formatted differently. obviously, that one of them is practicing good coding standards while the other is disregarding it completely. The first function is written in a way that there are fewer lines to type. Based on the content of the code the original author would definitely be able to read and understand the code properly, but when sharing for peer review the same sentiment would not be the same. The majority of people will spend more time trying to understand what each line of code does than actually peer review the program's code. The second function on the other hand is much easier to read compared with the first function. People will spend less time understanding and more time learning or improving the program, increasing the program's overall quality. 

## First week with ESLint and Intellij
My first impression when using ESLint and IntelliJ is that these two programs have some additional steps of coding ethics than the previous ones I have been exposed to in the past. In my first coding class, I was taught to always keep my code clean and easy to read. When I was coding Java using Eclipse, I always used the built-in code format tools to help me follow the proper coding standards of the class. When I was coding C and C++ using a terminal, I used the provided python script to check for violations of code standards and fixed it as I went. ESLint and Intellij are not different from what I had used previously; it’s just a different set of tools with the same functions. Getting those green checkmarks that signal a job well done is annoying and frustrating to get, but the long-term benefits outweigh the short-term pain. Learning how to code with good coding standards is very important and is an essential lesson to learn as you first learn to be a programmer. 

