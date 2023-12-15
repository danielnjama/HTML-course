# HTML-course || HTML Basics

Welcome to the HTML Basics guide! This document will introduce you to the fundamentals of HTML (Hypertext Markup Language), which is the standard language for creating web pages.

## Introduction to HTML

HTML is a markup language used to structure content on the web. It consists of elements represented by tags that define the structure of a web page.

## HTML Document Structure

A basic HTML document structure includes the following:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Document Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

**HTML Elements**
Elements are the building blocks of HTML. They are represented by tags.
1. Paragraph -

```html
<p>This is a paragraph.</p>
```

2. Image - 

```html
<img src="https://dtechnologys.com/wp-content/uploads/2023/01/cropped-android-chrome-512x512-1.png" alt="Description">

#The image can be fetched from the local server or from a remote server.
```
3. Headings - 
HTML provides heading tags from h1 to h6 for defining headings.
```html
<h1> Heading one </h1>  
<h2> Heading one </h2>
<h3> Heading one </h3>
<h4> Heading one </h4>
<h5> Heading one </h5>
<h6> Heading one </h6>
#Best SEO practices recommends 1 H1 tag for each page.
#Other heading levels should be distributed as needed. 

```
4. Lists - 
Use ul for unordered lists and ol for ordered lists. List items are represented by li.

**Unordered list**
```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
</ul>
```
**Ordered List**

```html
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
</ol>
```

5. Links - 
Links provide a lint/path to another resource. Create hyperlinks using the <a> tag:

```html
<a href="https://dtechnologys.com/">Visit Dynamic Technologies</a>
```
6. Forms - 
HTML forms allow user input. Use tags like <form>, <input>, and <button>.

```html
<form method="" action="">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">
    <button type="submit">Submit</button>
</form>
```
7. Inputs -
User input fields are used to collect information for website users. 
```html
<input type="text">
<input type="password">
<input type="radio">
<input type="checkbox">
<input type="submit">
<input type="reset">
<input type="file">
<input type="date">
<input type="email">
<input type="url">
<input type="number">
<input type="range">
<input type="color">
```
8. Tables -
Create tables with the ```<table>, <tr>, <th>, and <td> tags```.

```html
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Row 1, Cell 1</td>
        <td>Row 1, Cell 2</td>
    </tr>
</table>
```
9. div -
div tag is used to group related elements together for easier styling
```html
<div>
<p> some paragraph </p>
<h1> Heading 1 </h1>
<div>
<p> more content and or tags </p>
</div>
</div>
#For styling purposes, all other elements are grouped into divs. 
```
## HTML5 tags
Use semantic elements like ```<header>, <nav>, <article>, <section>, <footer>, etc.```, to add meaning to the content.
```html
<!-- To enclose header content -->
<header>
</header>
<!-- To enclose navigation bar content -->
<nav>
</nav>
<!-- To enclose general content -->
<section>
</section>
<!-- To enclose the footer content -->
<footer>
</footer>
```

## HTML Comments
Comments are important in any language. They help explain whatever is happening. Comments are not executed when the rest of the code is being executed.
```html
<!--Single Line comment-->

<!--
This is a multiline
comment in HTML.
-->
```






