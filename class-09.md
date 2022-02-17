# Notes from Read: 09 Forms and Events
[Home](README.md)

# Chapter 7: Forms pg 144-175
- how to collect information from visitors <br>
- different kinds of form controls <br>
- new html5 form controls <br>

How forms work <br>
- a user fill out a blank or partially filled out form. <br>
- the form can be filled out with text or filling in pre loaded info. <br>
- the server processes the information via programing language. <br>
- the server creates a new page and returns it to the user. <br>

Form Structure <br>
- form: element declared when starting a form. <br>
- action: required attribute, its value is the URL for the page on the server that will receive the information in the form when it is submitted. <br>
- method: forms can be sent using one of two methods, get or post. <br>

text input <br>
- input: element used to look for an input from the user. <br>
- text: says it creates a single-line text input. <br>
- password: input that is makes whatever entered hidden. <br>
- area: used to create a box that take input, think comment section. <br>
- radio button: allows you to pick bubbles to fill in. <br>
- checkbox: kinda self explanitory. <br>
- drop down list box, multiple select box, file input box, submit button, image button, button & hidden controls. <br>
- labelling form controls, grouping form elements, html5: form validation, html5: date input, html5: email & url input, html5: search input. <br>

## Forms Summary
- whenever you want to collect information from visitors you will need a form, which lives inside a form element <br> 
- information ffom a form is sent in name/value pairs. <br>
- each form control is given a name, and the text the user types in or the values of the options they selec are sent to the server. <br>
- html5 intorduces new form elements which make it easier for visitors to fill in forms. <br>

# Chapter 14: Lists, Tables and Forms pg 330-357

- specifying bullet point styles <br>
- adding borders and backgrounds to tables <br>
- changing the appearance of form elements  <br>

Bullets <br>
- list-style-type: allows you to add some detail or change bullets. <br>
- list-style-image: allows you to change bullets out for an image. <br>
- list-style-position: allows you to change the position. <br>

table properties <br>
- ref page 337 for long list of different property calls. <br>

Styling Forms <br>
- common to style text inputs, text areas, submit buttons, labels on forms. <br>
- you can find a referance for the styles on pg 342. <br>
- styling submit buttons, styling fieldsets and legends, aligning form controls. <br>

## Lists, Tables, and Forms Summary

- in addition to the CSS properties covered in other chapters which work with the contents of all elements, there are several others that are specifically used to control the appearance of lists, tables, and forms. <br>
- list markers can be given different appearances using the list-style-type and list-style image properties. <br>
- table cells can have different borders and spacing in different browsers, but there are properties you can use to control them and make them more consistent. <br>
- forms are easier to use if the form controls are vertically aligned using CSS.
- forms benifit from styles that make them feel more interactive. <br>

JS Book <br>

# Chapter 6: Events pg 243-292

how events trigger javascript code <br>
- select the element nodes you want the script to respond to. <br>
- indicate which even on the selecte nodes will trigger the response.  <br>
- state the code you want to run when the event occurs.  <br>

Three ways to bind an event to an element  <br>
- HTML Event handler attributes(dont use) pg 251.  <br>
- traditional dom event handlers pg 252.  <br>
- Event listeners pg 254.  <br>

event flow  <br>
- html events nest inside other elements.
- hover or click on a link, you will be hover or clicking on its parent elements.  <br>
- flow events matter when your code has event handlers on the element and on of its ancestors or descendants. <br>

types of events  <br>
- load, unload, error, resize, scroll  <br>
- load: commonly used to trigger scripts that access the contents of the page.  <br>
- focus/blur: often used to change apearances of elements.  <br>
- mouse events: list are on page 276.  <br>

where events occur  <br>
- screen: on the x/y. position on the screen.  <br>
- page: page x and y. which page.  <br>
- client: client x and y indicat the position of the cursor.  <br>

# Event Summary
- events are the browser's way of indicating when something has happened (such as when a page has finished loading or a button has been clicked.).  <br>
- binding is the processs of stating which event you are waiting for to happen upon.  <br>
- when an event occurs on an element, it can trigger a javascript function. when this functuion then changes the web page in some way, it feels interactive because it has responded to the user.  <br>
- you can use event delegation to monitor for events that happen on all of the children of an element.  <br>
- the most commonly used events are w3c dom events although there are others in the html5 specification as well as browser-specific events.  <br>