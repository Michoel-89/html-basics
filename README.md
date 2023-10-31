# HTML-basics

Welcome to your guide for learning the basics of HTML and passing a set of tests that check the structure of your HTML code. HTML is the language used to create web pages, and it's an excellent skill to have.

## Getting Started

Before we dive into the tests, you'll need to set up your environment to run them. We'll be using Jest, a popular JavaScript testing framework, along with JSDOM, a library that allows us to work with the Document Object Model (DOM) in Node.js. To install these tools, open your terminal and run the following commands:

```bash
npm install jest
npm install jsdom
```
You can run each test with it's number 
```bash
 npx jest -t '(number 1)'
 npx jest -t '(number 2)'
 npx jest -t '(number 3)'
 npx jest -t '(number 4)'
 npx jest -t '(number 5)'
```
Or run them all together with this command
```bash
npx jest testingFile.test.js
```

## Test 1: Page Title

### Create a Page Title

- Create a `<title>` element.
- Within the `<title>` element, set the text to "My First Web Page."

## Test 2: The Header

### Create the Header

- Create a `<div>` element with the class "header."
- Inside the "header" div, create an `<h1>` element.
- Inside the `<h1>` element, set the text to "Welcome to My Web Page."

## Test 3: The Navigation

### Create the Navigation

- Create a `<div>` element with the class "nav."
- Inside the "nav" div, create an unordered list (`<ul>`).
- Inside the unordered list, create three list items (`<li>` elements).

## Test 4: The Main Content

### Create the Main Content

- Create a `<div>` element with the class "main."
- Inside the "main" div, create an `<h2>` element for the main heading.
- Inside the "main" div, create a `<p>` element for text content.

## Test 5: Lists

### Create Lists

- Create a `<div>` element with the class "lists."
- Inside the "lists" div, create an ordered list (`<ol>`) with list items (`<li>` elements).
- Inside the "lists" div, create an unordered list (`<ul>`) with list items (`<li>` elements).

## HTML tags for reference

<!DOCTYPE>: This declaration defines the document type and version of HTML being used.

<html>: The root element that contains all other HTML elements on the page.

<head>: Contains meta-information about the document, such as the title and links to external resources.

<title>: Sets the title of the web page, which is displayed in the browser's title bar or tab.

<meta>: Provides metadata about the HTML document, such as character encoding and author information.

<link>: Used to link external resources, like CSS stylesheets, to the HTML document.

<style>: Defines inline CSS styles for specific elements on the page.

<script>: Used to include JavaScript code in the HTML document.

<body>: Contains the visible content of the web page, including text, images, and other elements.

<h1>, <h2>, <h3>, <h4>, <h5>, <h6>: Headings of decreasing importance, with <h1> being the most important and <h6> the least.

<p>: Represents a paragraph of text.

<a>: Creates hyperlinks to other web pages or resources.

<img>: Embeds images in the web page.

<ul>: Defines an unordered list, often used with <li> elements.

<ol>: Defines an ordered list, where list items are automatically numbered.

<li>: List item element, used within <ul> and <ol> to define individual list items.

<div>: A generic container element often used for grouping and styling content.

<span>: A generic inline container element for applying styles or scripting to a specific portion of text.

<br>: Inserts a line break, useful for breaking text onto the next line without starting a new paragraph.

<hr>: Creates a horizontal rule or line to separate content.

<table>: Defines a table, which can be populated with rows and cells.

<tr>: Represents a table row.

<th>: Defines a table header cell.

<td>: Represents a table data cell.

<form>: Used to create web forms for user input.

<input>: An input field within a form, used for text, checkboxes, radio buttons, etc.

<button>: A clickable button often used in forms.

<textarea>: A multiline text input field within a form.

<label>: Describes the purpose of an input element in a form.

<select>: Creates a dropdown list within a form.

That's it! Follow these steps to create your HTML code, and you'll pass all the tests. If you have any questions or need help, don't hesitate to ask. Happy coding!




