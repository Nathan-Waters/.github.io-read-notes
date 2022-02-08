# Notes from Read: 02 Basics of HTML, CSS and JS

# Chapter 2: Text, Pages 40-61

-headings and paragraphs <br>
-bold, italic, emphasis <br>
-structural and semantic markup <br>

headings <br>
-h1-h6 and the size gets smaller the larger the number. <br>

paragraphs <br>
-a p element surrounds the content of a paragraph. <br>

bold and italic <br>
-the b and i element wrap around text to edit it respectivly. <br>

superscript and subscript <br>
-sup/sub elements will provide exponents or foot notes, like elements. <br>

white space <br>
-the browser ignores white spaces if there is more than 1. <br>

Line Breaks and Horizontal rules <br>
-br and hr tags create breaks and horizonal breaks in the text. <br>

Semantic Markup: markup <br>
-strong: element that bolds a set of text to mark its importance. <br>
-em: element that emphasises text by making it italic. <br>

Quotations <br>
-backquote: indicates a quote of some sort and usually indents it. <br>
-q: element that creates quotations around the text. <br>

abbriviations and acronyms <br>
-abbr: used with a title declaration on things like Prof = professor. <br>
-acronym: will display what an acronym means. <br>

Citation and definitions <br>
-cite: for referancing a book, film, or newspaper. <br> 
-dfn: the first time you explain something you should make it as a definition. <br>

Author Details <br>
-address: contains the contact information for the author of the page. <br>

Changes to Content <br>
ins: shows new content introduced to the page showed with an underline. <br>
del: shows information has is no longer accurate, indicated with a line thorugh it. <br>
s: element that declares something is no longer accurate but should still be displayed. <br>

## Text Summary <br>
-HTML elements are used to describe the structure of the page <br>
-they also provide sematic info, where more information about the text is needed. <br> 

# Chapter 10: Intorducing CSS, Pages 226-245 
-what CSS does <br>
-how CSS works <br>
Rule, properties, and values <br>

Using External CSS <br>
-link: you must link to a CSS file for the page to know you need it. <br>
-link stuff: href = the file, type = type of doc, rel = the relationship to the page. <br>

using internal CSS <br>
-style: you can insert a style element in the header and not pull it from another file. <br>

CSS selectors <br>
-see page 237 <br>

CSS order of operations
-last rule: the last CSS applied to the element. <br>
-specificity: the more specific the selector will be used. <br>
-important: !important can  be used to make a selector the most important. <br>

Inheritance
-rules start from the top down. rules assigned to the body go to everything unless specified. <br>

## Introducing CSS Summary <br>
-CSS  treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look. <br>
-rules are made of selectors and declarations. whos effected and how. <br>
-declarations are med of two parts, properties that you want to change, and how to change them. <br>
-CSS rules usually appear in a separate document and are pulled in. <br>

# JS Book

# Chapter 2: Basic JavaScript Instructions, Pages 53-84

Statements and Comments <br>
-statement in javascript are case sensative. <br>
-everything inside of the curly brackets is part of the code block. <br>
-comments give explinations without effecting what the code is doing. <br>

what is a variable? <br>
-stored data that can be manipulated. <br>
-calling varables on pg 60, new practices are used currently. <br>

Data Types <br>
-numerical <br>
-string <br>
-boolean <br>

Variable to store a number <br>
-declare using no quotation marks. <br>

Variables to store a string <br>
-declare the variable inside quotation marks. <br>

Variable to store a boolean <br>
-only two values, true and false. <br>

Rules for naming variables <br>
-name begins with a letter, $, or underscore. <br>
-no - or . <br>
-no keyword or reserved words. <br>
-var's are case sensative, so you should not have multiple variables with the same name. <br>
-use related descriptive info to the var to name it. <br>
-use camel casing if it name is more than one word. <br>

Arrays <br>
-arrays work like lists of items. <br>
-create an array by making a variable and setting it with brackets. <br>
-each item in an array each element to it has an index and a value. <br>
-change an item in the array by declaring the which array and which index to change. then set it to the new value. <br>

expressions and operators <br>
-expressions assign a value or are used to evaluate two or more values. <br>
-operators allow a single value out of multiples, think math. <br>
-list of arithmetic operators pg 76. <br>

## Basic JavaScript Instructions Summary
-A script is a seriest of statments like a recipe. <br>
-variables to temporarly store info. <br>
-arrays are variale that store related information. <br>
-javascript distingushes between numbers, strings, and Boolean data types. <br>
-expressions evaluate into a single value. <br>
expressions rely on operators to calculate a value. <br>

# Chapter 4: Decisions and Loops -up to switch statements-, Pages 145-162

Evaluating Condition and Condition Statements
-conditions are specific parameters. <br>
-you can evaluate the condition with any datatype. <br>
-comparing operations pg 150. <br>

Using Comparison Operators <br>
-ultimatly it comes down to is the evaluation true or false. <br>
-you can compare two expressions. <br>
-local operators pg 156. <br>

Using Logical and || logical or <br>
-logical and means both need to be true. <br>
-logical or is either on need to be true for it to be true. <br>

if statements
-evaluates a conditions, if its true then the code is executed. <br>
-an else can be added at the end to run if the if statement is false. <br>
