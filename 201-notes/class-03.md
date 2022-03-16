# Notes from Read: 03 HTML Lists, CSS Boxes, JS Control Flow
[Home](README.md)
# Chapter 3: Lists, Pages 42-73
- Numbered lists <br>
- Bullet lists <br>
- definition lists <br>

ordered lists <br>
- ol: element the starts an ordered list. <br>  
- li element inside the ol to make items on the list. <br>

unordered lists <br>
- ul: element that declars the unordered list. <br>
- li: li element inside the ul to make items on the list.<br>

definition lists <br>
- dl: element that declars the Definition list. <br>
- dt: element to contain the word being defined. <br>
- dd: element to contain the definition of the word. <br>

nested lists <br>
- you can have a ul/ol inside of one of another

## Lists Summary
- three types of lists. ordered, unordered, and definition
- ol use numbers
- ul us bullets
- df are used to define terminology
- lists can be nested inside one another

# Chapter 13: Boxes, Pages 300-329 
- controlling size of boxes <br>
- box model for borders, margin and padding <br>
- displaying and hiding boxes  <br>

Dimensions and width/height limits and overflow
- by default boxes are big enough to fit their content. <br>
- limiting max and min widths helps adjust for screen size. <br>
- overflow can be hidden or given its own scroll bar. <br>

border, margin and padding <br>
- they are applied in that order within the page. <br>
- they adjust how much space is in between each element and where. <br>
- width can be adjusted as a whole, or individuale portions. <br>
- style will change what the border looks like, see pg 310 for examples. <br>
 
Centering content <br>
- set right and left margins to auto <br>
- text-align center <br>

Changing inline/block <br>
- display will allow you to change between inline and block. <br>
- inline-block and none are also options. <br>

Hiding Boxes <br>
- sometimes you may want entire boxes to be invisible. <br>
- visibilty is the call for that. <br>

CSS3 <br>
- border-image: see page 319. <br>
- box shadow: many different ways to add shadow pg 320. <br>
- border-radius: allows you to rownd the ends of corners on the border. <br>
- additionaly you can eclips them with more specific assignments. <br>

## Boxes Summary
- CSS treats each HTML element as if it has its own box. <br>
- you can use CSS to control the dimentions of a box. <br>
- you can also control the borders, margins and padding for each box with CSS. <br>
- it is possible to hide elements using the display and visibility properties. <br>
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes. <br>
- legibility can be improved by controlling the width of boxes containing text and the leading. <br>
- CSS3 has introduced the ability to create image borders and rounded borders. <br>

# JS book

# Review from Reading 02: chapter 2, Pages 70-73

Main things to keep in mind <br>
- Arrays: creating, editing, reading. <br>
- evaluation: expressions, operators, arithmetic. <br>
- string operator: mainly use concatenation. <br>

# Chapter 4: Decisions and loops, Pages 162-182

Switch Statements
- starts with what is called a switch value. <br>
- has a code block that runs through possible opritons before finding a match. <br>

Type coercion and weak typing
- javascript will try to figure out what data type you ment if they dont match. <br>
- this is refered to as weak typing. it is strong if it requires a data type. <br>
- examples of truthy and falsy values pg 167. checking equality and existence pg 168. <br>

Loops
- for: running code a specific number of times. <br>
- while: as long as a statement remains in one state, the code will run. <br>
- do while: like a while loop but the question is asked at the end of the statement. it will always run at least once. <br>
- loop counters: the loop has a variable that decides if the code should be excicuted. if should also have something that updates it eventually to leave the loop. <br>

loop keywords <br>
- break: allows you to end a loop regardless of condition. <br>
- continue: makes the loop check the condition again. <br>

Using Loops <br>
- for: good for sorting though data. needs an intial var/count, a condition to end the loop, and an iteration at the end. <br>
- while: good for verifying the data input is correct for the questions being asked. <br>
- do while: good for any while loop you always want to run at least 1 time. <br>

## Decisions and Loops Summary 
- conditional statements allow your code to make decisions about what to do next. <br>
- comparison operators are used to compare two operands. <br>
- logical operators allow you to combine more than one set of comparison operators. <br>
- if else statements allow you to run one set of code if a condition is true, and another if it is false. <br>
- switch statements allow you to compare a value against outcomes. <br>
- data types can be coerced from one type to another. <br>
- all values evaluate to either truthy or falsy. <br>
- there are three types of loop: for, while, do while. <br>