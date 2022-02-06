# Notes from Read: 01 Introductory HTML and JavaScript

# Introduction, Pages 2-11

Brief run down of what to expect with the book. <br>
-Touches on HTML/CSS <br>
-How the web is accessed and websites are created <br>
-The broad way the web works <br>

# Chapter 1: Structure, Pages 12-39
-Understanding structure <br>
-learning about markup <br>
-Tags and elements <br>

Structure is made of elements that are made up of a but usually 2 tags. <br>
-example: \<html\>\</html\> this is an element with an opening tag, and a closing tag indicated with a /. <br>

Adding attributes can modifiy what the element is doing. <br>
-example: \<p attributename=\"value\"\>Text in Paragraph\</p\>. <br>

Basic HTML elements set up most web pages (all reflect the above html formate): <br>
-body: will have all elements that appear on the web page. <br>
-head: contains information about the page. <br>
-title: titles the page, typically only displayed in the URL. <br>

-example: Pg 27 displays the typical layout of a web page. <br>

## Structure Summary
-HTML is made up of elements, which are made up of tags. <br>
-Tags usually come in pairs (an open and a close tag). <br>
-Attributes entered into the opening tag can edit elements. <br>
-Attributes need a name and a value. <br>

# Chapter 8: Extra Markup, Pages 176-199
-Specifying different versions of HTML <br>
-Identifying and grouping elements <br>
-Comments, meta information and iframes <br>

DOCTYPES <br>
-example: \<!DOCTYPE html\> <br>
-Used to declare which version of HTML to the browser. <br>

Comments in HTML <br>
example: \<!-- commented text --\> <br>
-comments are used to identify specific parts of the code without effecting the code <br>

ID and Class attributes <br>
-example: \<p id=\"identity\"\>Hi This is me!\<p\> || \<p class=\"unity\"\>Hi This is us!\<p\> <br>
-these attributes add specific identifys to any element they are attached to. <br>
-id is used for 1 specific element while class is used for multiple elements <br>

Block elements <br>
-example: h1, p, ul, li <br>
-these elements will create there own area on a new line on the page <br>

Inline elements <br>
-example: a, b, em, img <br>
-these elements will appear on the page one after another only breaking at the end of the page <br>

Some notable elements Pgs 187-192 <br>
-div: used to group other elements and turn them into block-level elements. <br> 
-span: used much like the div element but instead to turn them into inline-level elements. <br>
-iframe: creates a windown in the webpage, think of google maps when looking for a store. <br>
-meta: multiple very useful purposes such as search engine optimization, and when browsers clear a users cashe. <br>

Escape Characters <br>
-example: \<, \", and(unironically) \&. <br>
-items in HTML are reserved for the code and require special code to be displayed. <br>
-list of common ones and their respective calls on Pg 194. <br>

## Extra Markup Summary <br>
-DOCTYPES tell the browser what version of HTML is to be used <br>
-To comment \<!-- text here --\> <br>
-id and class identify elements <br>
-div and span all you to edit the block-level of its continents <br>
-iframe cut windows into your web page <br>
-meta allows you to supply info about your page <br>
-escape characters have work arounds <br>

# Chapter 17: HTML5 Layout, Pages 428-451 <br>
-HTML5 layout elements <br>
-How old browsers understand new elements <br>
-Styling HTML5 layout elements with CSS <br>

Headers and Footers <br>
-example: \<header\>\</header\> || \<footer\>\</footer\> <br>
-these appear at the top and bottom of your site. <br>
-Headers typicall have the title and the nav bar. <br>
-the footer usually has the copyright and contact information. <br>

Navagation <br>
-example: \<nav\>\</nav\> <br>
-nav bars are the primary search engine of your website. <br>
-they can be at the top, bottom or sides of the page. <br>

Articles <br>
-example: \<article\>\</article\>
-It is for any section that can stand on its own <br>
-A page can have multiple articles if need be <br> 

Aside <br>
-example: \<aside\>\</aside\> <br>
-when the aside element is placed inside an article it supplies addition information about it. <br>
-when outside of an article it is used as a container to explain content on the page. <br>

Section <br>
-example: \<section\>\</section\> <br>
-the section element is for grouping related content on the page. <br>

Heading Groups <br>
-example: \<hgroup\>\</hgroup\> <br>
-the hgroup is used to group as many headers together on the page. <br>

Figures <br>
-example: \<figure\>\</figure\> || \<figcaption\>\</figcaption\> <br>
-the figure and figcaption elements are used to contain and caption an image on the page. <br>

Sectioning Elements <br>
-example: \<div\>\</div\> <br>
-the layout elements mentioned above are for specific, any other sectioning should be done with the div element. <br>

Linking Around Block-Level Elements <br>
-this is using the a element(or linking element) to link and entire block-level element. <br>

Helping Older Browsers Understand <br>
-example: \<!--[if lt IE 9]\> .... \<![endif]--\> <br>
-this is a comment that that is a prevenative measure incase the user is using an old browser. <br>

## HTML5 Layout Summary <br>
-new HTML5 elements to show more accuratly what each element is for <br>
-old browsers need to be told what are block elements <br>
-make old browsers work with your updated HTML <br>


# Chapter 18: Process & Design, Pages 452-475 <br>
-How to approach building a site <br>
-Understanding your audience and their needs <br>
-How to present information visitors want to see <br>

Who is the site for? <br>
1. target audience: individuales <br>
   -age range? <br>
   -men or women? both? <br>
   -where do they live? <br>
   -device that it will likely be used on? <br>
2. target audiance: company <br>
   -size of the company? <br>
   -who in the company will utilize? <br>
   -is it for the company or the customers? <br>
  
Why people visit your website? <br>
1. key modivations <br>
   -are they looking for entertainment? <br>
   -personal or professional? <br>
   -essential or luxury? <br>
2. Goals <br>
   -do they want general info/reserch/ or something specific? <br>
   -are they familiar or new to your product or service? <br>
   -is the service time sensitive? <br>
   -do they need to contact you?  <br>
 
Important Factors <br>
-What your visitors are trying to achieve <br>
-what information your visitors need <br>
-how often people will visit your site <br>
-organizing the site to optimize these things <br>
-using wireframes to get a visualization of the complete product <br>

Getting your message across using design
-







# JS Book

# Introduction

-talks aboout the broad concepts of programming and what roles it has to play in the user experiance. <br>
-discribes what content will be in the book such as diagrams, referances, and examples. <br>
-shows some examples of Javascript in websites. <br>
-structure of the book, core concepts and then practical applications. <br>

# Chapter 1: The ABC of Programming, Pages 11-52
-becoming familiary with the basics of reading and writing JavaScript <br>


## 1/a What is a script and how do i create one?
-a script is a set of instructions. <br>
-example: recipes, handbooks, manuals. <br>

Writing a script <br>
-in order to write a script, you need a goal to achieve. <br>
-to acomplish the goal, you need as simple steps as possible in as specific of an order as you can. <br>
-define goal, design script, code each step. <br>
-first you need to define the tasks, and then break down the steps you need to do each one. <br>

Vocabulary = the words computers understand | Syntax = how those words come together to create instructions a computer understands. <br>

### 1/a Summary
What is a script and how do i create one? <br>
-a script is a set of instructions for a computer to follow. <br>
-each script may only use some of the code. <br>
-computers dont approach tasks like humans, they need a specific language in a programmatical manner. <br>
-to approach writing a script, breaking it down in an simple manner(flowchart or something) can simplify the process. <br>

## 1/b How do computers fit in with the world around them?

Objects and Prioreties
-objects(things): things around the world are objects when it comes to data. <br>
-each object has: properties, events, and methods. <br>
-properties are characteristics of an object. <br>
-events are the common ways that objects interact with eachother. <br>
-methods are how objects interact with the real world. <br>

How A browser sees a page: receive a page as HTML, Create a model, and Render the page on the screen <br>
 
### 1/b Summary
How do computers fit in with the world around them? <br>
-create models of the world with data. <br>
-code = when this, execute this. <br>
-browsers use HTML for format. <br>

## 1/c How do i write a script for a web page

How HTML, CSS, and JavaScript Fit Together <br>
-content layer(HTML), presentation layer(CSS), Behavior Layer(JavaScript) <br>
-page should be build from left to right to ensure minimal conflict. <br>

Creating a Basic JavaScript <br>
-JavaScript files are saved with a .js to designate the launguage. <br>
-.js files are called to the page with a script element and source(src=\"\") to the specific script. <br>

Using Objects and Methods <br>
-order sytax: object, member operator, method(parameters) <br>
-object: is what is being manipulated <br>
-member operator: separates the object from the method <br>
-method: allows new content to be introduced to the page <br>
-parameters: the info methods need to work <br>

### 1/c Summary
How do I write a script for a web page? <br>
-its best to keep JavaScript cod in its own file. <br>
-the HTML script element is used to call the JavaScript code. <br>
-the source code of the page is not changed by the JavaScript. It works with the web. <br>

