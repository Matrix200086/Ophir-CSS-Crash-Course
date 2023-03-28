# **Ophir Crash Course on CSS**
Welcome to the repository for the Ophir Course - Beginner to Advance class on CSS | by Ophir. 
      <br>Guides</br>
This article will take you through all the basic theory of CSS, and provide opportunities for you to test out some skills.
#  **Resources For This Course**
### Basic Knowledge
* 	Basic familiarity with using computers and using the Web passively (i.e. looking at it, consuming the content).
* A basic work environment set up, as detailed in Installation basic software, and an understanding of how to create and manage files.
* Basic Familiarities with HTML as it will be discussed by other tutor in Ophir in the introduction to HTML module.
# **Table of Contents**
<details>
<summary> Resources</summary>
<br>Guides
<br> Basic Knowledge
</details>
<details>
<summary>Module 1: Introduction to CSS </summary>
<br>Getting Started with CSS
<br> Adding CSS to our document  
<br> Understanding Basics CSS Selectors
<br> CSS Properties and Value
</details>
<details>
<summary>Module 2: Applying CSS style to HTML elements </summary>
<br>CSS External Stylesheet and it's Application
<br> CSS Internal Stylesheet and it's Application
<br> CSS Inline Styles and it's Application
<br>Playing with the CSS in this article
<br>Summary
</details>
<details>
<summary>Module 3: The box Model and Layout </summary>
<br>Objectives 
<br> Box MOdel Behaviour
<br> Standard and Alternative box model
<br> Playing with the CSS in this article
<br> Block Model References 
</details>
<details>
<summary>Module 4: Working with Typography and Color </summary>
<br>CSS Typography Properties in CSS 
<br> Font Property
<br> Spacing Property
<br> Conclusion
</details>
<details>
<summary>Module 5:Responsive And Adaptive Design</summary>
<br> Advanced CSS techniques such as CSS Grid and Flexbox
<br> Flexible Layouts and Grid
<br> Conclusion
</details>

#  **Module 1: Introduction to CSS**
#  **Prerequisites**
Before starting this module,you should have:
1.	Basic familiarity with using computers and using the Web passively (i.e. looking at it, consuming the content).
2. A basic work environment set up, as detailed in Installation [Basic Software Installation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Installing_basic_software), and an understanding of how to create and manage [File creation](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/Dealing_with_files) 
3. Basic Familiarities with HTML as it will be discussed by other tutor in Ophir in the introduction to HTML module.
#  **Guides**
This module contains the articles which will take you through all the basic theory of CSS, and provide opportunities for you to test out some skills, I will urge you to pay much attention and follow religiously.
<br>Here, we will be using Vscode as a text-editor,you can simply use anyone of your choice as they simply work the same way.
Download Vscode and install Go live in your extension.
#  What is CSS ?
* CSS (Cascading Style Sheets) is used to style and lay out web pages e.g , to alter the font, color, size, and spacing of your content, split it into multiple columns, or add animations and other decorative features. This module provides a gentle beginning to your path towards CSS mastery with the basics of how it works, what the syntax looks like, and how you can start using it to add styling to HTML.<br>
* It is a declarative language that controls how webpages look in the browser.<br>
* The browser applies CSS style declarations to selected elements to display them properly. A style declaration contains the properties and their values, which determine how a webpage looks.<br>
* CSS is one of the three core Web technologies, along with HTML and JAVASCRIPT, CSS usually styles HTML elements, but can be also used with other markup languages like SVG or XML.<br>
* A CSS rule is a set of properties associated with a selector. Here is an example that makes every HTML paragraph yellow against a black background:
``` /* The selector "p" indicates that all paragraphs in the document will be affected by that rule */
p {
  /* The "color" property defines the text color, in this case yellow. */
  color: yellow;

  /* The "background-color" property defines the background color, in this case black. */
  background-color: black;
}
```
* "Cascading" refers to the rules that govern how selectors are prioritized to change a page's appearance. This is a very important feature, since a complex website can have thousands of CSS rules. 
# **Getting started with CSS**
In this article, we will take a simple HTML document and apply CSS to it, learning some practical things about the language along the way.
You can copy the code from below if you want to work on your own computer. Save the code below as index.html in a folder on your machine.
```<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <title>Getting started with CSS</title>
  </head>
  <body>
    <h1>I am a level one heading</h1>
    <p>
      This is a paragraph of text. In the text is a
      <span>span element</span> and also a
      <a href="https://example.com">link</a>.
    </p>
    <p>
      This is the second paragraph. It contains an <em>emphasized</em> element.
    </p>
    <ul>
      <li>Item <span>one</span></li>
      <li>Item two</li>
      <li>Item <em>three</em></li>
    </ul>
  </body>
</html>
```
# Adding CSS to our document
The very first thing we need to do is to tell the HTML document that we have some CSS rules we want it to use. There are three different ways to apply CSS to an HTML document that you'll commonly come across, however, for now, we will look at the most usual and useful way of doing so — linking CSS from the head of your document.

Create a file in the same folder as your HTML document and save it as styles.css. The .css extension shows that this is a CSS file.

To link styles.css to index.html, add the following line somewhere inside the <head> of the HTML document:<br>
      ```<link rel="stylesheet" href="styles.css" />```
This [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) element tells the browser that we have a stylesheet, using the rel attribute, and the location of that stylesheet as the value of the href attribute. You can test that the CSS works by adding a rule to ```style.css``` Using your code editor, add the following to your CSS file:
```
      h1 {
  color: red;
}
```
Save your HTML and CSS files and go live. The level one heading at the top of the document should now be red. If that happens, congratulations — you have successfully applied some CSS to an HTML document. If that doesn't happen, carefully check that you've typed everything correctly.

You can continue to work in ```style.css``` locally, or you can use our interactive editor below to continue with this tutorial. The interactive editor acts as if the CSS in the first panel is linked to the HTML document, just as we have with our document above.
# **Understanding Basics CSS Selectors**
# CSS Selectors
* A CSS selector is the first part of a CSS Rule. It is a pattern of elements and other terms that tell the browser which HTML elements should be selected to have the CSS property values inside the rule applied to them. The element or elements which are selected by the selector are referred to as the subject of the selector.<br>
```
      h1{
      color:blue;
      background-color: yellow;}
         p{
      color:red;
      }
```
* In other articles you may have met some different selectors, and learned that there are selectors that target the document in different ways — for example by selecting an element such as ```h1```, or a class such as ```.special```.<br>
* In CSS, selectors are defined in the CSS Selectors specification; like any other part of CSS they need to have support in browsers for them to work. The majority of selectors that you will come across are defined in the [Level 3 Selectors Specification](https://www.w3.org/TR/selectors-3/) and [Level 4 Selectors Specification](https://www.w3.org/TR/selectors-4/) which are both mature specifications, therefore you will find excellent browser support for these selectors.<br>
# Selector lists
* If you have more than one thing which uses the same CSS then the individual selectors can be combined into a selector list so that the rule is applied to all of the individual selectors. For example, if I have the same CSS for an ```h1``` and also a class of ```.special```, I could write this as two separate rules.<br>
 ```
 h1 {
  color: blue;
}

.special {
  color: blue;
}
  ```  
I could also combine these into a selector list, by adding a comma between them.

```h1, .special {
  color: blue;
}
```
White space is valid before or after the comma. You may also find the selectors more readable if each is on a new line.
```
h1,
.special {
  color: blue;
}
```
When you group selectors in this way, if any selector is syntactically invalid, the whole rule will be ignored.

In the following example, the invalid class selector rule will be ignored, whereas the ```h1``` would still be styled.
```
h1 {
  color: blue;
}

..special {
  color: blue;
}
```
When combined however, neither the ```h1``` nor the class will be styled as the entire rule is deemed invalid.
```
h1, ..special {
  color: blue;
}
```
# Types of selectors
There are a few different groupings of selectors, and knowing which type of selector you might need will help you to find the right tool for the job. In this article's subarticles we will look at the different groups of selectors in more detail.

# Type, class, and ID selectors
This group includes selectors that target an HTML element such as an ```<h1>```.
```
h1 {
}
```
It also includes selectors which target a class:
```
.box {
}
```
or, an ID:
```
#unique {
}
```
# Attribute selectors
This group of selectors gives you different ways to select elements based on the presence of a certain attribute on an element:
```
a[title] {
}
```
Or even make a selection based on the presence of an attribute with a particular value:
```
a[href="https://example.com"]
{
}
```
# Pseudo-classes and pseudo-elements
This group of selectors includes pseudo-classes, which style certain states of an element. The ```:hover ``` pseudo-class for example selects an element only when it is being hovered over by the mouse pointer:
```
a:hover {
}
```
It also includes pseudo-elements, which select a certain part of an element rather than the element itself. For example, ```::first-line``` always selects the first line of text inside an element (a ```<p>``` in the below case), acting as if a ```<span>``` was wrapped around the first formatted line and then selected.
```
p::first-line {
}
```
# Combinators
The final group of selectors combine other selectors in order to target elements within our documents. The following, for example, selects paragraphs that are direct children of ```<article>``` elements using the child combinator (```>```):
```
article > p {
}
```
# Summary
  In this article we've introduced CSS selectors, which enable you to target particular HTML elements. Next, we'll take a closer look at
[type](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Type_Class_and_ID_Selectors),[class](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Type_Class_and_ID_Selectors),[and ID Selectors](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Type_Class_and_ID_Selectors)
# Module 2: Applying CSS styles to HTML elements
* Here,the very first thing we need to do is to tell the HTML document that we have some CSS rules we want it to use. There are three different ways to apply CSS to an HTML document that you'll commonly come across, Here we will treating them one after the other, then discuss on the most beautiful  ways of linking CSS from the head of your document 
 # External stylesheet
* An external stylesheet contains CSS in a separate file with a ```.css``` extension. This is the most common and useful method of bringing CSS to a document.<br>
 You can link a single CSS file to multiple web pages, styling all of them with the same CSS stylesheet.<br> 
 In the Getting started with CSS, we linked an external stylesheet to our web page.<br>
You reference an external CSS stylesheet from an HTML ```<link>``` element:
```
<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
 ```      
The CSS stylesheet file might look like this:
```
   h1 {
  color: blue;
  background-color: yellow;
  border: 1px solid black;
}p {color: red;
}
```
      
The ```href``` attribute of the ```<link>``` element needs to reference a file on your file system.<br>
In the example above, the CSS file is in the same folder as the HTML document, but you could place it somewhere else and adjust the path. Here are three examples:
```
<!-- Inside a subdirectory called styles inside the current directory -->
<link rel="stylesheet" href="styles/style.css" />
<!-- Inside a subdirectory called general, which is in a subdirectory called styles, inside the current directory -->
<link rel="stylesheet" href="styles/general/style.css" />
<!-- Go up one directory level, then inside a subdirectory called styles -->
<link rel="stylesheet" href="../styles/style.css" />
```
      
# Internal stylesheet
* An internal stylesheet resides within an HTML document. To create an internal stylesheet, you place CSS inside a ```<style>``` element contained inside the HTML ```<head>```.
The HTML for an internal stylesheet might look like this:
```
 <!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
    <style>
      h1 {
        color: blue;
        background-color: yellow;
        border: 1px solid black;
      }
      p {
        color: red;
      }
    </style>
  </head>
  <body>
    <h1>Hello World!</h1>
    <p>This is my first CSS example</p>
  </body>
</html>
 ```
      
In some circumstances, internal stylesheets can be useful. For example, perhaps you're working with a content management system where you are blocked from modifying external CSS files.<br>
But for sites with more than one page, an internal stylesheet becomes a less efficient way of working.<br> To apply uniform CSS styling to multiple pages using internal stylesheets, you must have an internal stylesheet in every web page that will use the styling. The efficiency penalty carries over to site maintenance too. With CSS in internal stylesheets, there is the risk that even one simple styling change may require edits to multiple web pages.
# Inline styles
* Inline styles are CSS declarations that affect a single HTML element, contained within a style attribute. The implementation of an inline style in an HTML document might look like this:
```
<!DOCTYPE html>
<html lang="en-GB">
  <head>
    <meta charset="utf-8" />
    <title>My CSS experiment</title>
  </head>
  <body>
    <h1 style="color: blue;background-color: yellow;border: 1px solid black;">
      Hello World!
    </h1>
    <p style="color:red;">This is my first CSS example</p>
  </body>
</html>
 ```
      
Avoid using CSS in this way, when possible. It is the opposite of a best practice.<br>
      
 * First, it is the least efficient implementation of CSS for maintenance. One styling change might require multiple edits within a single web page.<br>
      
 * Second, inline CSS also mixes (CSS) presentational code with HTML and content, making everything more difficult to read and understand. Separating code and content makes maintenance easier for all who work on the website.<br>
      
There are a few circumstances where inline styles are more common. You might have to resort to using inline styles if your working environment is very restrictive. For example, perhaps your CMS only allows you to edit the HTML body. You may also see a lot of inline styles in HTML email to achieve compatibility with as many email clients as possible.
# Assessment
# Playing with the CSS in this article
For the exercise that follows, create a folder on your computer. You can name the folder whatever you want. Inside the folder, copy the text below to create two files:
* index.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width" />
    <title>My CSS experiments</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <p>Create your test HTML here</p>
  </body>
</html>
```
* styles.css:
```
/* Create your test CSS here */
p {color: red;}
```
When you find CSS that you want to experiment with, replace the HTML <body> contents with some HTML to style, and then add your test CSS code to your CSS file.
# Summary
In this article, we have  looked at a number of ways in which you can style a document using CSS. We will be developing this knowledge as we move through the rest of the lessons. However, you now already know enough to style text, apply CSS based on different ways of targeting elements in the write-up.
# Module:3 The box model and layout
* Everything in CSS has a box around it, and understanding these boxes is the key to being able to create more complex layouts with CSS, or to align items with other items.<br>
 In this lesson, we will take a look at the CSS Box Model.<br> You'll get an understanding of how it works and the terminology that relates to it.
# Objectives
* To learn about the CSS Box Model, what makes up the box model and how to switch to the alternate model.
# What is the CSS box model?
 The CSS box model as a whole applies to block boxes and defines how the different parts of a box — margin, border, padding, and content — work together to create a box that you can see on a page. Inline boxes use just some of the behavior defined in the box model
# Parts of a box
Making up a block box in CSS we have the:
* Content box: The area where your content is displayed; size it using properties like inline-size and block-size or width and height.
* Padding box: The padding sits around the content as white space; size it using padding and related properties.
* Border box: The border box wraps the content and any padding; size it using border and related properties.
* Margin box: The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.<br>
      
You can visit [Ophir css ](https://www.w3schools.com/css/css_boxmodel.asp)to see the diagram and more structure.
# Box Model Behaviour
## To discuss on box model behaviour, we shall treat this below:
### Block and inline boxes
In CSS we have several types of boxes that generally fit into the categories of block boxes and inline boxes. The type refers to how the box behaves in terms of page flow and in relation to other boxes on the page. Boxes have an inner display type and an outer display type.<br>
      
In general, you can set various values for the display type using the display property, which can have various values.
### Outer display type
If a box has an outer display type of block, then:
* The box will break onto a new line.
* The width and height properties are respected.
* Padding, margin and border will cause other elements to be pushed away from the box.<br>
      
If width is not specified, the box will extend in the inline direction to fill the space available in its container. In most cases, the box will become as wide as its container, filling up 100% of the space available.<br>
      
Some HTML elements, such as ```<h1>```and ```<p>```, use block as their outer display type by default.
      
### Inner display type
Boxes also have an inner display type, which dictates how elements inside that box are laid out.<br>
      
Block and inline layout is the default way things behave on the web. By default and without any other instruction, the elements inside a box are also laid out in normal flow and behave as block or inline boxes.<br>
      
You can change the inner display type for example by setting display: flex;. The element will still use the outer display type block but this changes the inner display type to flex. Any direct children of this box will become flex items and behave according to the Flexbox specification.<br>
      
When you move on to learn about CSS Layout in more detail, you will encounter flex, and various other inner values that your boxes can have, for example grid.<br>
      
Note: To read more on this, you can visit [Ophir css](https://www.w3schools.com/css/css_boxmodel.asp).
# Examples of different display types
The example below has three different HTML elements, all of which have an outer display type of block.
* A paragraph with a border added in CSS. The browser renders this as a block box. The paragraph starts on a new line and extends the entire available width.
* A list which is laid out using display: flex. This establishes flex layout for the children of the container, which are flex items. The list itself is a block box and — like the paragraph — expands to the full container width and breaks onto a new line.
* A block-level paragraph, inside which are two ```<span>``` elements. These elements would normally be inline, however, one of the elements has a class of "block" which gets set to display: block.<br>
      
**Create two files, one as css file and another as html file in your interactive editor and type this as your CSS file**
      
``` 
p, ul {border: 2px solid rebeccapurple; padding: .5em;}
.block,li {border: 2px solid blue;padding: .5em;}
ul {display: flex;list-style: none;}
.block {display: block;}
      
```   
**Also,type this as your html file**
      
```
<!Doctype html>
<html>
<head></head>
<body>
<p>I am a paragraph. A short one.</p>
<ul>
  <li>Item One</li>
  <li>Item Two</li>
  <li>Item Three</li>
</ul>
<p>I am another paragraph. Some of the <span class="block">words</span> have been wrapped in a <span>span element</span>.</p>
 </body>     
 </html>
 ```
**In the next example, we can see how inline elements behave**
      
* The ```<span>``` elements in the first paragraph are inline by default and so do not force line breaks.
* The ```<ul>``` element that is set to display: inline-flex creates an inline box containing some flex items.
* The two paragraphs are both set to display: inline. The inline flex container and paragraphs all run together on one line rather than breaking onto new lines (as they would do if they were displaying as block-level elements).<br>
      
To toggle between the display modes, you can change display: inline to display: block or display: inline-flex to display: flex.<br>
      
**Create a CSS file and paste this**
      
```
p, ul {border: 2px solid rebeccapurple;}
span,li {border: 2px solid blue;}
ul {display: inline-flex; list-style: none;padding: 0;} 
.inline {display: inline;}     
```
**Also create an html file and paste**

```  
<!Doctype html>
<html>
<head></head>
<body>
 <p> I am a paragraph. Some of the<span>words</span> have been wrapped in a
<span>span element</span>.
</p> <ul><li>Item One</li>
<li>Item Two</li>
<li>Item Three</li></ul><p class="inline">I am a paragraph. A short one.</p>
<p class="inline">I am another paragraph. Also a short one.</p></body></html> 
```
The key thing to remember for now is: Changing the value of the display property can change whether the outer display type of a box is block or inline. This changes the way it displays alongside other elements in the layout.
# To add complexity, there is a standard and an alternate box model.
# By default, browsers use the standard box model.
# The standard CSS box model
In the standard box model, if you give a box an inline-size and a block-size (or width and a height) attributes, this defines the inline-size and block-size (width and height in horizontal languages) of the content box. Any padding and border is then added to those dimensions to get the total size taken up by the box.
# The alternative CSS box model
In the alternative box model, any width is the width of the visible box on the page. The content area width is that width minus the width for the padding and border . No need to add up the border and padding to get the real size of the box.
To turn on the alternative model for an element, set box-sizing: border-box on it:<br>
```.box {box-sizing: border-box;}```
To use the alternative box model for all of your elements (which is a common choice among developers), set the box-sizing property on the ```<html>``` element and set all other elements to inherit that value, see this :
```
html {box-sizing: border-box;}
*,
*::before,
*::after {
  box-sizing: inherit;}
```
To understand the underlying idea, you can read [Ophir Box Model](https://css-tricks.com/inheriting-box-sizing-probably-slightly-better-best-practice/),[Ophir Box Model write-up](https://www.washington.edu/accesscomputing/webd2/student/unit3/module4/lesson1.html),[Ophir write-up on Box Model Application](https://www.washington.edu/accesscomputing/webd2/student/unit3/module4/lesson2.html),[OPhir Page Layout with CSS Article](https://www.washington.edu/accesscomputing/webd2/student/unit3/module6/lesson1.html),[Ophir Stylizing Navigation Menu With CSS](https://www.washington.edu/accesscomputing/webd2/student/unit3/module6/lesson2.html)
