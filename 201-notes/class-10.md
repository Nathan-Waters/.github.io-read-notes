# Notes from Read: 10 Forms and Events
[Home](README.md)

JS Book

# Chapter 10: Error Handling & Debugging pg 449-

Execution contents
- global context: code thaqt is in the script, but not in a function. <br>
- funtion context: code that is being run within a function. each function has its own context. <br>
- eval context(not shown): text is executed like code in an internal function called eval().

variable scope
- global scope: if declared outside of a function, it can be used anywhere. <br>
- function-level scope: variable declared in a function can only be used in that function. <br>

execution content and hoisting <br>
- prepare: the new scope is created, variables functions and arguments are created. <br>
- execute: now it can assign values to variables, ref functions and run their code. <br>

errors
- if a javascript statement generates an error, then it throws an exception. <br>
- error objects liested on pg 459.<br>

dealing with errors
- 1: debug the script to find/fix errors. <br>
- 2: handle errors gracefully using try, catch, throw, and finally. <br>

A debugging workflow
- look at the error message. <br>
  - the relevant script that caused the problem. <br>
  - the line number where it became a problem. <br>
  - the type of error. <br>
- check how far the script is running. <br>
- use breakpoints where things are going wrong. 

Browser work pgs 464-478

Handling exceptions
- try: specify the code that you think might throw an exception. <br>
- catch: if the try code block throws an exception, catch steps in with an alternative set of code. <br>
- finally: the contents of the finally code blocke will run either way, whether the try block succeeded or failed. <br>

debugging tips
- use another browser: some problems are browser specific. <br>
- add numbers: it allows you to see how far you code gets before failing. <br>
- more on pg 484.<br>

Common errors pg 485 <br>

## Error Handling & Debugging Summary
- if you understand execution contents (which have two stages) and stacks, you are more likely to find the error in your code. <br>
- debugging is the proccess of finding errors. It involves a process of deduction. <br>
- the console helps narrow down the area in which the error is located, so you can try to find the exact error. <br>
- JavaScript has 7 different types of errors. Each creates its own error object, which can tell you its line number and gives a descritpion of the error. <br>
- if you know that you may get an error, you can handle it gracefully using the try, catch, finally statements. use them to give your users helpful feedback. <br>