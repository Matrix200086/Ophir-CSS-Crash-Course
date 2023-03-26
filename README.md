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


























