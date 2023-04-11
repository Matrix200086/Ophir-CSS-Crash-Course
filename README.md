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
<summary> <a href="https://github.com/Matrix200086/Ophir-write-up/blob/main/README.md#prerequisites" target="_blank">Resources</a></summary>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#guides" target="_blank">Guides </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#what-is-css-" target="_blank">Basic Knowledge </a>
</details>
<details>
<summary><a href="https://github.com/Matrix200086/Ophir-write-up/blob/main/README.md#module-1-introduction-to-css" target="_blank">Module 1: Introduction to CSS </a></summary>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#getting-started-with-css" target="_blank">Getting Started with CSS </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#adding-css-to-our-document" target="_blank">Adding CSS to our document </a> 
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#understanding-basics-css-selectors" target="_blank">Understanding Basics CSS Selectors</a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#types-of-selectors" target="_blank">CSS Properties and Value</a>
</details>
<details>
<summary><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#module-2-applying-css-styles-to-html-elements" target="_blank">Module 2: Applying CSS style to HTML elements</a> </summary>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#external-stylesheet" target="_blank">CSS External Stylesheet and it's Application</a>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#internal-stylesheet" target="_blank"> CSS Internal Stylesheet and it's Application</a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#inline-styles" target="_blank">CSS Inline Styles and it's Application </a>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#playing-with-the-css-in-this-article" target="_blank">Playing with the CSS in this article </a>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#summary-1" target="_blank">Summary </a>
</details>
<details>
<summary><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#module3-the-box-model-and-layout" target="_blank">Module 3: The box Model and Layout </a></summary>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#objectives" target="_blank">Objectives </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#box-model-behaviour" target="_blank">Box MOdel Behaviour</a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#to-add-complexity-there-is-a-standard-and-an-alternate-box-model" target="_blank">Standard and Alternative box model</a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#the-standard-css-box-model" target="_blank">Playing with the CSS in this article </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#examples-of-different-display-types" target="_blank">Block Model References </a>
</details>
<details>
<summary><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#module4-working-with-typography-and-color" target="_blank">Module 4: Working with Typography and Color</a> </summary>
<br><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#typography-properties-in-css-are-as-follows" target="_blank">CSS Typography Properties in CSS </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#2-font-property" target="_blank">Font Property </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#3-spacing-property" target="_blank">Spacing Property </a>
<br> <a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#conclusion" target="_blank">Conclusion </a>
</details>
<details>
<summary><a href="https://github.com/Matrix200086/Ophir-write-up/edit/main/README.md#module-5-responsive-and-adaptive-design" target="_blank">Module 5:Responsive And Adaptive Design</a></summary>
<summary><a href="" target="_blank">Advanced CSS techniques such as CSS Grid and Flexbox</a></summary>
<br> 
<br> <a href="" target="_blank"> </a>
<br> <a href="" target="_blank"></a>
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
## To add complexity, there is a standard and an alternate box model.
### By default, browsers use the standard box model.
#### The standard CSS box model
In the standard box model, if you give a box an inline-size and a block-size (or width and a height) attributes, this defines the inline-size and block-size (width and height in horizontal languages) of the content box. Any padding and border is then added to those dimensions to get the total size taken up by the box.
#### The alternative CSS box model
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
# Module:4 Working with Typography and Color
The typography concept in CSS is defined as one of the essential components for designing websites. The typography concept is about styling the pages, spacing properties, and proportions.<br>
      
This concept is used for improving the text which is more readability using proper font properties, text color properties, etc. Typography allows the users to define color, the shape of text, size, and spacing which are CSS properties so that the text is easily legibility and readability. The main properties of typography in CSS are the color of the text, the font size of text, the spacing of the line, etc.
Here, I will be putting you through with working example
# Working with CSS Typography with Examples
Here, we will see about typography concept and its properties. The two main groups of this topography concept are font and text.
# Typography properties in CSS are as follows:
## 1. Color
This property is used for coloring the texts or elements in website layouts such as foreground color, background color, the color of the text, etc.<br>
      
Create an html file in Vscode or any text editor you are family with, and push this live
 ```
<!DOCTYPE html>
<html>
<title>Ophir Training</title>
<style>
body {
}
.text1 {
color: red
}
.text2 {
color: #71ffb0;
}
.text3 {
color: rgb(70, 98, 120);
}
.text4 {
color: rgba(0, 0, 0, 0.4);
}
.text5 {
color: hsl(15, 80%, 73%);
}
.text6 {
color: hsla(18, 130%, 43%, 0.5);
}
</style>
<body>
<div class="text1">Color name is given directly</div>
<div class="text2">This text have hexadecimal code for color</div>
<div class="text3">This text uses rgb() color codes </div>
<div class="text4">This text uses rgb color codes with alpha values like transparent or opaque</div>
<div class="text5">This text uses hsl() color codes </div>
<div class="text6">This text uses hsl color codes with alpha values like transparent or opaque </div>
</body>
</html>
```
      
This should print the class texts in  color varieties
 In the above program, we can see that we are specifying the color properties in topography which can be specified in different ways and shown in the above program with result if push live, color can be specified using its color name, hexadecimal code, rgb() color codes, hsl() color codes, etc.
## 2. Font Property
This property has other shorthand properties like font-family such as font-size, font-style, font-weight, etc in this topography concept.
### Example 1: font-size property
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output
```
<!DOCTYPE html>
<html>
<title>Ophir.CSS</title>
<style>
body {
}
.text1 {
font-size: medium;
}
.text2 {
font-size: 30px;
}
.text3 {
font-size: 5.2em;
}
.text4 {
font-size: 140%;
}
.text5 {
font-size: smaller;
}
.text6 {
font-size: x-large;
}
</style>
<body>
<div class="text1">Default size can be declared as medium </div>
<div class="text2">This text uses pixel values</div>
<div class="text3">This text uses em values </div>
<div class="text4">This text uses percentage values </div>
<div class="text5">This text uses some relative keywords </div>
<div class="text6">This text uses some absolute keywords </div>
</body>
</html>
```
### Example 2: font style
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output:
```
<!DOCTYPE html>
<html>
<title>Ophir Training </title>
<style>
body {
}
.text1 {
font-style: normal;
}
.text2 {
font-style: italic;
}
.text3 {
font-style: oblique;
}
</style>
<body>
<div class="text1">Default font style with normal value</div>
<div class="text2">This text uses italic font style values</div>
<div class="text3">This text uses more slanted text than italic and is declared as oblique</div>
</body>
</html>
```      
### Example 3: font weight property
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output:
```      
<!DOCTYPE html>
<html>
<title>Ophir Training</title>
<style>
body {
}
.text1 {
font-size: x-large;
font-weight: normal;
}
.text2 {
font-size: x-large;
font-weight: bold;
}
.text3 {
font-size: x-large;
font-weight: 800;
}
</style>
<body>
<div class="text1">Default font style with normal value and font size as x-large </div>
<div class="text2">This text uses bold for font weight values</div>
<div class="text3">This text uses numeric values for specifying font weight </div>
</body>
</html>
 ```     
### Example 4: font family property
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output:
```      
<!DOCTYPE html>
<html>
<title>Ophir Training</title>
<style>
body {
}
.text1 {
font-family: "Arial";
}
.text2 {
font-family: Courier New;
}
.text3 {
font-family: Times New Roman;
}
</style>
<body>
<div class="text1">This text displays in Areial font family </div>
<div class="text2">This text displays in Courier New font family</div>
<div class="text3">This text displays in Times New Roman font family</div>
</body>
</html>
```      
## 3. Spacing Property
This property is used where there is spacing required such as line spacing, letter spacing, word spacing, etc.
### Example 1
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output:
```      
<!DOCTYPE html>
<html>
<title>Ophir Training</title>
<style>
body {
}
.text1 {
font-size: x-large;
letter-spacing: normal;
}
.text2 {
font-size: x-large;
letter-spacing: 4px;
}
.text3 {
font-size: x-large;
letter-spacing: 1.2em;
}
.text4 {
font-size: x-large;
word-spacing: normal;
}
.text5 {
font-size: x-large;
word-spacing: 3px;
}
.text6 {
font-size: x-large;
word-spacing: 0.8em;
}
</style>
<body>
<div class="text1">Default letter spacing with normal value </div>
<div class="text2">This text uses pixel values for letter spacing</div>
<div class="text3">This text uses em values for letter spacing </div>
<div class="text4">Default word spacing with normal value </div>
<div class="text5">This text uses pixel values for word spacing</div>
<div class="text6">This text uses em values word spacing </div>
</body>
</html>
 ```     
### Example 2: Other typography properties
Other typography properties are not mostly used such as text alignment and text-decoration.
Create an html file, paste this code into the file created in your Vscode or any other text editor, save it and push it live and see the output.
```      
<!DOCTYPE html>
<html>
<title>Ophir Training</title>
<style>
body {
}
.text1 {
font-size: large;
text-align: left;
}
.text2 {
font-size: large;
text-align: right;
}
.text3 {
font-size: large;
text-decoration: underline;
}
</style>
<body>
<div class="text1">This text displays at left </div>
<div class="text2">This text displays at right </div>
<div class="text3">This text displays text decoration with the text underlined </div>
</body>
</html>
```      
# Conclusion
Here, we conclude that the CSS typography is used for the main property likes font, color, and spacing for text display.<br>
      
we have seen that the typography concept is used for designing website layout which contains text or elements with text that attracts the users to browse the websites. we have also seen the typography properties such as font properties like font- family, font-size, font-weight, and font-style, and the second main property is text properties like letter spacing, word spacing, text- alignment, etc.
# Module 5: Responsive And Adaptive Design 
# Objectives
To understand the fundamental purposed and CSS features used to implement responsive and reactive designs.
Generally, HTML is fundamentally responsive, or fluid. If you create a web page containing only HTML, with no CSS, and resize the window, the browser will automatically reflow the text to fit the viewport.
# Responsive web design   
Responsive web design (RWD) is a web design approach to make web pages that render well on all screen sizes and resolutions while ensuring good usability. It is the way to design for a multi-device web. In this article, we'll help you understand some techniques that can be used to master it. Responsive websites are websites that automatically resize to the screen size the website is being viewed on.
# Reactive websites      
Reactive websites (adaptive) displays a website especially designed for the device type the website is being viewed on.<br>
While the default responsive behavior may sound like no solution is needed, long lines of text displayed full screen on a wide monitor can be difficult to read. If wide screen line length is reduced with CSS, such as by creating columns or adding significant padding, the site may look squashed for the user who narrows their browser window or opens the site on a mobile device.<br>
      
Creating a non-resizable web page by setting a fixed width doesn't work either; that leads to scroll bars on narrow devices and too much empty space on wide screens.<br>
      
Responsive web design is a design approach that addresses the range of devices and device sizes, enabling automatic adaption to the screen, whether the content is viewed on a tablet, phone, television, or watch.it isn't a separate technology — it is an approach, It is a term used to describe a set of best practices used to create a layout that can respond to any device being used to view the content.<br>
    
Note: Responsive websites are not always the best solution for web design.<br>
      
Firstly, understand the explanation of what a responsive website means and what it isn’t. There is much misunderstanding that the only way a website can be a mobile friendly website is to design it to be responsive, as in a WordPress website. This is wrong, you can design a website that adapts or provides an alternate display on mobile devices such as smartphones or tablets.  The difference is that responsive websites automatically display correctly on mobile devices as they resize to the display screen size.<br>
      
Reactive – Adaptive websites gives a totally different website version for the screen size allowing specific design for desktop, tablet or mobile.  Both the responsive and adaptive approaches are endorsed by the Google Mobile Friendly test.<br>
Also, With adaptive websites you can choose what to display on your desktop version and what you want to display on mobile versions.  For instance you may have strong ‘call to action’ for mobile users such as “download our mobile app here” or even giving your mobile version a more app feel and look, click [here](http://mickkenyon.com/Micks_Blog/wp-content/uploads/2015/09/Screens.jpg) to see gadget different display.
In creating a responsive and Adaptive design, Currently the most popular technique lies within responsive web design, favoring design that dynamically adapts to different browser and device viewports, changing layout and content along the way. This solution has the benefits of being either responsive or adaptive.
To further our explanation on building a responsive and adaptive design, refer to CSS techniques in Module 6
# Module 6: Advanced CSS techniques such as CSS Grid and Flexbox
To explain the CSS Flexbox and Grid, we are going to build a simple landing page for an Ophir Institute platform
This tutorial will also teach you how to use and implement CSS Flexbox and CSS Grid alignment.<br> 
      
We'll also cover many other CSS concepts. And finally, we'll learn how to make the page responsive so that it works on all screen sizes. 
# The tutorial is divided into five parts:
* How to Build the Navigation Bar
* How to Build the Showcase Section
* How to Build the Lower Section
* How to Build the Footer Section
* How to Make the Page Responsive
Each of these sections will teach you some new CSS and web development skills and tools. So let's jump right in.
# How to Create the HTML Boilerplate
If you have emmet installed in your IDE, you can generate an HTML boilerplate for your project by typing ! and clicking the enter or tab key on your keyboard.
If not, you can copy this boilerplate code and paste it into your code editor:
      
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="ie=edge">
  <title>Document</title>
  <link rel="stylesheet" href="styles.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ=="
  crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
 
</body>
</html>
```  
      
# How to Use Font Awesome Icons
Here, we will be using some font icons to give better swap to our service section.<br>
      
For this, we will be using font awesome from the CDN. If you created an HTML biolerplate by yourself, copy the following link tag and paste it into your head tag:
```
`<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ=="
  crossorigin="anonymous" referrerpolicy="no-referrer" />
```   
      
# Let's Get Started
First, make sure that your stylesheet file (.css) is properly linked to your HTML page. <br>
      
Mind you: You should have go live installed in your VsCode extension, this will give you access to push everytime to see the visual of the website you're building
# How to Build the Navigation Bar
The Navigation Bar section is going to be comprised of our site's name as well as two navigation links: 
Log in and check courses.<br>
      
Here is the markup for our navbar:
```      
<div class="navbar">
        <div class="container flex">
          <h1 class="logo">Ophir Institute</h1>
            <nav>
              <ul>
                <li class="nav"><a class="outline" href="">Log in</a></li>
                <li class="nav"><a href="" class="outline">Check courses</a 				</li>
              </ul>
            </nav>
        </div>
      </div>
```
      
On the div wrapping the elements inside this section (the navbar), <br>
      
we register the container and flex class.<br>
      
.container: we will use this utility class in every section to make sure that the inner elements do not exceed a certain width which we'll specify in CSS<br> 
      
.flex: we will use this utility class to display children elements in a horizontally aligned manner (side-by-side) using CSS Flexbox.<br>

Inside the div we have an ```h1``` with class of logo and two navigation links ```li>a``` with the outline classes, respectively.<br>
      
# How to Apply CSS Styling to our Page
We now have to apply some CSS rules to style our nav section the way we want. What we want to do first is set the base styling for our web page with the following code:
      
```      
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0
}

/* White text throughout */

body {
  font-family: "lato", sans-serif;
  color: white;
}

/* Make all link text black with no text decoration */
a {
  color: black;
  text-decoration: none;
}


h1 {
  font-size: 30px;
  font-weight: 600;
  margin: 10px 0;
  line-height: 1.2;
}

h2 {
  font-size: 25px;
  font-weight: 300;
  margin: 10px 0;
  line-height: 1.2;
}

p {
  font-size: 30px;
}

/* All images must not be larger than parent container */
img {
  width: 100%;
}

/* No styling on list items */
li {
  list-style-type: none;
}

p {
  font-size: 20px;
  margin: 10px 0;
}
```
     
Next, we need to define the styling for our container class:
      
```      
/* Centers it, sets a maximum width and makes sure elements can flow past it*/

.container {
  margin: 0 auto;
  max-width: 1200px;
  overflow: visible;
}
```

After that, we need to set the background color of our navbar section to purple:
      
```      
/* Sets background color, height and padding*/
.navbar {
  background-color: purple;
  height: 70px;
  padding: 0 30px;
}
```
      
Then we target only the h1 element inside the navbar and specify the following styles:
```      
/* Sets font size, reduces font-weight, adds margin and line height */
.navbar h1 {
  font-size: 30px;
  font-weight: 300;
  margin: 10px 0;
  line-height: 1.2;
}
```
      
Now we need to display both child elements inside the container h1 and nav side-by-side using Flexbox.
```      
navbar .flex {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100%;
}
```
      
First, we set the display mode to flex. This will align the elements side by side by default.<br>
      
We then justify the content, adding a considerable space between each item using the space-between value. We align the items to appear at the center (middle) of the container and set its height to take up the entire container. <br>
      
However, we also do not want both of our navigation link stacked on top of each other. Instead, we want them to be displayed side-by-side. Guess how we do that? With Flexbox!
```      
.navbar ul {
  display: flex;
}

/* Changes the color of both links to white, adds padding between them and margin as well */

.navbar a {
  color: white;
  padding: 9px;
  margin: 0 10px;
}
```
      
If you watched the brief intro video, you will notice that whenever I hover over any of the links, the text color changes to a lighter shade of purple and a solid border appears below it. <br>
      
We can implement this transition using the CSS :hover pseudo-element:
```      
.navbar a:hover {
  color: #9867C5;
  border-bottom: 3px solid #9867C5;
}
```
      
And with that, we have come to the end of the navbar section.
# How to Build the Showcase Area
The showcase area is going to house the headline text, supporting text, a form for signing up new users, as well as a headline image. <br>
      
This section is going to be divided in two: the left side and the right side. In other words, it will be displayed as a grid of two units.<br>
      
Here is the markup for this section:
```      
<section class="showcase">
        <div class="container">
            <div class="grid">
              <div class="grid-item-1">
                <div class="showcase-text">
                  <h1>Learn any digital skill of your choice today</h1>
                  <p class="supporting-text"> Over 30,000 students currently learn with us</p>
                </div>
                <div class="showcase-form">
                  <form action="">
                    <input type="email" placeholder="Enter your email address">
                    <input type="submit" class="btn" value="Start Learning">
                  </form>
                  <p class="little-info">Try out our free courses today. No risk, no credit card required</p>
                </div>
              </div>

              <div class="grid-item-2">
                <div class="image">
                  <img src="./images/transparent.png" alt="">
                </div>
              </div>
           </div>

        </div>
      </section>
```
      
Note: Download a computer setup image and rename it as transparent.png
# How to Apply CSS Styling to our Showcase Area
First, we set the height of the showcase section as well as a background color:
```     
.showcase {
  height: 300px;
  background-color: purple;
}
```      
Note: I changed the color of h1 to white <br>
      
Next, we apply the following styles:
```
 /* Adds margin below the text */
.showcase p {
  margin-bottom: 30px;
}

/* Adds a shadow below the image */
.showcase img {
  box-shadow: 7px 7px 7px rgba(0, 0, 0, 0.2);
}

/* Adds some padding on the form content */
.showcase-form {
  padding-left: 7px;
}
```      
This brings us to the main activity. If you remember, I said that we were going to be creating two sections (grids) inside the showcase container. With the grid class registered on that container, we can align its content using CSS grid display like this:
```      
.grid {
  overflow: visible;
  display: grid;
  grid-template-columns: 60% 40%;
}
```
      
This will create two columns inside of our showcase container. The first part will take up 60 percent of the container, and the second part will take up the remaining 40 percent of the container.<br>
      
The overflow visible will ensure that the image (if bigger than the container) will flow beyond the container.<br>
      
Next, we need to set some space between the navigation area and the showcase area.
```
 grid-item-1,
.grid-item-2 {
  position: relative;
  top: 50px;
}
```
      
Now, we need to style both of our form inputs because they don't look so nice. We select the first input by its type (email) and select the second by its class name, btn.
```      
.showcase input[type='email'] {
  padding: 10px 70px 10px 0;
  font-size: 14px;
  border: none;
  border-radius: 6px;
  padding-left: 6px;
}

.btn {
  border-radius: 6px;
  padding: 12px 20px;
  background: #9867C5;
  border: none;
  margin-left: 10px;
  color: white;
  font-size: 16px;
  cursor: pointer;
  box-shadow: 0 10px 10px rgba(0, 0, 0, 0.2);
}
```      
Also maybe change the font of the supporting text:
```     
.showcase-form {
  margin: auto;
}

/* Change typeface and its size */
.little-info {
  font-size: 15px;
  font-family: "poppins", sans-serif;

}
```
# How to Build the Lower Part of the Page
The lower part of the page is going to contain two sections, the stats section and the testimonials section.<br>
      
The stats container which displays the services offered by OPhir Institute will be made up of three divs, each of which houses a font awesome icon, an ```h3 ``` of class title, and a paragraph ```p``` of class text.
The testimonial container will hold the testimonials of three random people who learned using Ophir Institute. I grabbed the pictures from unsplash.
# How to Build the Stats Section
First, we are going to work on the stats section. The text is just a dummy 'lorem50' text to act as a filler for this demo.<br>
      
Here is the markup for it:
```      
<div class="lower-container container">
      <section class="stats">
        <div class="flex">
          <div class="stat">
            <i class="fa fa-folder-open fa-2x" aria-hidden="true"></i>
            <h3 class="title">Over 6 available courses</h3>
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="stat">
            <i class="fa fa-graduation-cap fa-2x" aria-hidden="true"></i>
            <h3 class="title">Free certificate offered on all courses</h3>
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
          <div class="stat">
            <i class="fa fa-credit-card-alt fa-2x" aria-hidden="true"></i>
            <h3 class="title">Book 1on1 session for as low as $5</h3>
            <p class="text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          </div>
        </div>
      </section>
```      
This section will be displayed as a blank page. This is because we had set the color of our text in the whole body to white. So we have to add some styling.
# How to Apply CSS Styling to the Stats Section
First we need to apply the following styles:
```      
/* Centers the container, sets a maximum width
.lower-container {
  margin: 120px auto;
  padding: 0;
  max-width: 1400px;
}


/* Targets all h3 with class of title */
.title {
  color: black;
  font-size: 20px;
  text-align: left;
  padding-left: 10px;
  padding-top: 10px;
}

/* Targets the paragraphs with class name of text */
.text {
  color: black;
  font-size: 19px;
  width: 100%;
  padding: 10px;
  margin: 0, 20px;
  text-align: justify;
}
```  
     
Notice: If you push live you see that the font icons from Font Awesome are not visible. We will be working on that pretty soon.<br>
      
But before then, we will need to do something important. We do intend for all of the three stat divs to be aligned horizontally (side-by-side). To achieve that, we will once again be using CSS Flexbox:
```      
/* Display horizontally, put a little space around them */
.flex {
  display: flex;
  justify-content: space-around;
}

/* Add some padding around the container. Align text centrally */
.stats {
  padding: 45px 50px;
  text-align: center;
}

/* Set margin and width */
.stat {
  margin: 0 30px;
  text-align: center;
  width: 800px;
}
.stats .fa {
  color: purple;
}
```      
# How to Build the Testimonials Section
The second section inside of the lower container div of the page is the testimonials section. This section is going to be made up of three cards, each of which contains the image of the person (clipped inside a circle), their name, and the person's testimonial.<br>
      
Here is the markup for that:
```      
<section class="testimonials">
      <div class="container">
        <div class="testimonial grid-3">
          <div class="card">
            <div class="circle">
              <img src="./images/4.jpg" alt="">
            </div>
            <h3>Aston</h3>
            <p>I have learnt web development using this platfrom and I am going to say this is the best platform for learning. Absolutely
            worth the investment!</p>
          </div>
          <div class="card">
            <div class="circle">
              <img src="./images/5.jpg" alt="">
            </div>
            <h3>Beth</h3>
            <p>I have learnt copywriting using this platfrom and I am going to say this is the best platform for learning. Absolutely
            worth the investment!</p>
          </div>
          <div class="card">
            <div class="circle">
              <img src="./images/6.jpg" alt="">
            </div>
            <h3>Chris</h3>
            <p>I have learnt affilitate marketing using this platfrom and I am going to say this is the best platform for learning. Absolutely
            worth the investment!</p>
          </div>
        </div>
      </div>
    </section>
```
# How to Apply CSS Styling to it
First, we set the text color to black so we can see it:
```      
.testimonial {
  color: black;
  padding: 40px;
}
``` 
Note: Add Student Images with name  4.jpg, 5.jpg,6.jpg, and all this images should be in a folder named images  <br>
      
When applied, it should make the text visible and add some padding to the section:<br>

Next, we set the image to take up the height of its parent container:
```
/* Wrap the image inside a cirle shape and set height to take up all of parent element */

.testimonial img {
    height: 100%;
    clip-path: circle();
}

/* Align text centrally */

.testimonial h3{
  text-align: center;
}
```      
If you push live and  check the final layout in the gif, you will notice that all three testimonial cards are aligned side-by-side on the same line.
So we will need to create a div of three equal columns using the CSS grid arrangement.
```      
/* Create a grid of three equal columns. Set a gap of 40 px between them */

.grid-3 {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 40px;
}


/* Create a white card with some shadow around it */
.card {
  padding: 10px;
  background-color: white;
  border-radius: 10px;
  box-shadow: -7px -7px 20px rgba(0, 0, 0, 0.2),
               7px  7px 20px rgba(0, 0, 0, 0.2)
}
```      
Finally, we style the circle div and position it relative to the top border of the card using CSS:
 ```     
.circle {
    background-color: transparent;
    border:3px solid purple;
    height:90px;
    position: relative;
    top: -30px;
    left: 120px;
    border-radius:50%;
    -moz-border-radius:50%;
    -webkit-border-radius:50%;
    width:90px;
}
```      
Alright, now we're ready to move on to the footer section. Then we'll learn how to make the site responsive.
# How to build the Footer Section
The final part of our landing page building process is to create the footer section. The footer section will comprise some copyright text, three extra navigation links, and a group of social media icons from Font Awesome.<br>
      
Here is the HTML Markup for the footer section of our landing page:
```      
<footer>
   <div class="container grid-3">
     <div class="copyright">
       <h1>Ophir Institute</h1>
       <p>Copyright &copy; 2022</p>
     </div>
     <nav class="links">
       <ul>
         <li><a href="" class="outline">Home</a></li>
         <li><a href="" class="outline">Tutors</a></li>
         <li><a href="" class="outline">Categories</a></li>
       </ul>
     </nav>
     <div class="profiles">
       <a href=""><em class="fab fa-twitter fa-2x"></em></a>
       <a href=""><em class="fab fa-instagram fa-2x"></em></a>
       <a href=""><em class="fab fa-facebook fa-2x"></em></a>
       <a href=""><em class="fab fa-whatsapp fa-2x"></em></a>
     </div>
   </div>
 </footer>
```
# How to Style the Footer
First, we need to set the background colour for the footer section (as well as the color for all links) to white, like this:
```      
/* Add padding around the footer as well */

footer {
  background-color: purple;
  padding: 20px 10px;
}

/* Sets all link texts to white and puts margin to the left and right */

footer a {
  color: white;
  margin: 0 10px;
}
```      
If you push and check the first gif, you will notice that when I hover over any of the links inside of the footer, their color changes to a lighter shade of purple and a border also appears below them.<br>
      
We can make this happen using a :hover selector:
```     
footer a:hover {
  color: #9867C5;
  border-bottom: 2px solid #9867C5;
}
```      
# How to Set Media Queries to Make the Page Responsive
It's now time to make our landing page more responsive. When building a website, it is important to have in mind that users will be viewing the site from different devices. So it is imperative to make the site layout responsive to improve the user experience across multiple devices.<br>
      
In our CSS, we will define media queries which set breakpoints for the various screen widths of different devices and map a set of CSS rules for each screen size.
# How to Design for Tablets and Smaller Screens
First, we will optimize our site's layout for users viewing from a tablet. In our CSS, we define the following style:
```      
/* Tablets and Under */

@media(max-width: 768px) {
  .grid,
  .grid-3 {
    grid-template-columns: 1fr;
  }
```      
Initially we had set two columns for the ```.grid class```and 3 columns for the grid-3 class. Now, we want to make sure that all grid items take up just a single line.
```      
/* Align all text to the center. This will move all text, including form centrally */

.showcase {
    height: auto;
    text-align: center;
  }

/* This resets the width of the image container and adds margin space to the left */ 

.image {
    width: 600px;
    margin-left: 80px;
  }

/* Changes the service sections from side-by-side orientation to each taking its own line. Aligns text to the center */

.stats .flex {
    flex-direction: column;
  }

  .stats {
    text-align: center;
  }

/* Makes sure each stat section does not exceed the width of parent */

.stat {
    width: 100%;
    padding-right: 80px;
  }

/* (re)Moves the cirle to the center of the card */

.circle {
      background-color: transparent;
      border:3px solid purple;
      height:90px;
      position: relative;
      top: -30px;
      left: 270px;
      border-radius:50%;
      -moz-border-radius:50%;
      -webkit-border-radius:50%;
      width:90px;
  }
```
# How to Design for Mobile Devices
Many people may view the site from a mobile device which typically has the smallest screen size out of all devices. Because of this, creating a layout for mobile-sized screens is very important.<br>
      
First, we increase the height of our navigation area. Since it will be viewed from a smaller screen, we want the area more accentuated for the user.<br>
      
Then, we define the following styles:
```      
/* Changes the alignment. The logo title stays at the top, the nav links will be below it */

.navbar .flex {
    flex-direction: column;
  }


/* When hovered on, retain white color and change border to black */

  .navbar a:hover {
    color: white;
    border-bottom: 2px solid black;
  }
/* Set light purple background on nav links, make it a bit round and add some spacing */

  .navbar ul {
    background: #9867C5;
    border-radius: 5px;
    padding: 10px 0;
  }
/* Align text to center */

  .showcase {
    height: auto;
    text-align: center;
  }
/* Reduce font size */

.little-info {
    font-size: 13px;
  }
/* Reduce image width */

  .image {
    width: 350px;
    margin-left: 70px;
  }

  .stat {
    margin-bottom: 40px;
  }
/* Move circle once again */

.circle {
      background-color: transparent;
      border:3px solid purple;
      height:90px;
      position: relative;
      top: -30px;
      left: 150px;
      border-radius:50%;
      -moz-border-radius:50%;
      -webkit-border-radius:50%;
      width:90px;
  }
}
```      
# Wrapping Up
FlexBox and Grid alignment are very powerful tools for laying out a web page however you want it to look.<br>
      
Responsive web design is arguably one of the most important design principles in web development. We have to consider the fact that our site will be viewed from various kinds of devices with different screen resolutions. Optimizing our site's layout for different screens will improve the user experience.<br>
      
In this tutorial, we have designed a simple landing page using CSS Flexbox, Grid, and many other CSS properties. We have also made the page look good on Tablets and Mobile Screens.<br>
      
If you have any issues in your journey of buiding this responsive project, you can hint us up at our twitter handle [@instituteOphir](https://linktr.ee/Institute.Ophir), we will respond there.
