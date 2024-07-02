# Week 1: HTML & CSS Basics

## Day 1: Introduction to HTML, basic tags and structure.
### What is HTML?
HTML (HyperText Markup Language) is the standard markup language used to create web pages. It describes the structure of a web page and its content.

### Basic Structure of an HTML Document
An HTML document has a standard structure that includes the following elements:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>This is a Heading</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

*Explanation:*
- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html>`: Root element of the HTML document.
- `<head>`: Contains meta-information about the document (title, charset, styles, etc.).
- `<title>`: Sets the title of the document (displayed in the browser tab).
- `<body>`: Contains the content of the HTML document.

### Basic HTML Tags
Here are some of the most commonly used HTML tags:

#### Headings
HTML headings are defined with the `<h1>` to `<h6>` tags:

```
<h1>This is a Heading 1</h1>
<h2>This is a Heading 2</h2>
<h3>This is a Heading 3</h3>
<h4>This is a Heading 4</h4>
<h5>This is a Heading 5</h5>
<h6>This is a Heading 6</h6>
```
*Explanation:*\
`<h1>` to `<h6>` Define headings of different levels, with `<h1>` being the highest (most important) level and `<h6>` being the lowest.

#### Paragraphs
HTML paragraphs are defined with the `<p>` tag:

```<p>This is a paragraph.</p>```

*Explanation:*\
`<p>`: Defines a paragraph of text.

#### Links
HTML links are defined with the  `<a>` tag:

```<a href="https://www.example.com">This is a link</a>```

*Explanation:*
- `<a>`: Defines a hyperlink.
- `href`: Attribute specifies the URL of the page the link goes to.

#### Images
HTML images are defined with the `<img>` tag:
```<img src="image.jpg" alt="Description of Image">```

*Explanation:*
- `<img>`: Embeds an image in the HTML page.
- `src`: Attribute specifies the path to the image file.
- `alt`: Attribute provides alternative text for the image.

#### Lists:
HTML supports ordered (`<ol>`) and unordered (`<ul>`) lists:

```
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>

<ol>
    <li>First Item</li>
    <li>Second Item</li>
    <li>Third Item</li>
</ol>
```

*Explanation:*
- `<ul>`: Defines an unordered list.
- `<ol>`: Defines an ordered list.
- `<li>`: Defines a list item.

#### Tables:
HTML tables are defined with the `<table>` tag, along with `<tr>` for table rows, `<th>` for table headers, and `<td>` for table data cells:

```
<table>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>
```

*Explanation:*
- `<table>`: Defines a table.
- `<tr>`: Defines a table row.
- `<th>`: Defines a table header cell.
- `<td>`: Defines a table data cell.

#### Forms:
HTML forms are used to collect user input:

```
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
```

*Explanation:*
- `<form>`: Defines an HTML form for user input.
- `action`: Attribute specifies where to send the form data.
- `method`: Attribute specifies the HTTP method (GET or POST) to use when submitting the form.
- `<label>`: Defines a label for an input element.
- `<input>`: Defines an input field.

### Intermediate HTML Tags

#### Section:
`<section>`: Defines a section in a document

```
<section>
    <h2>Introduction</h2>
    <p>This section contains the introduction to the topic.</p>
</section>
```

#### Article:
`<article>`: Defines an independent, self-contained article

```
<article>
    <h2>Article Title</h2>
    <p>This is a self-contained article that can be distributed independently from the rest of the document.</p>
</article>
```

#### Aside:
`<aside>`: Defines content aside from the content it is placed in

```
<aside>
    <h2>Related Articles</h2>
    <p>Here are some related articles you might find interesting.</p>
</aside>
```
#### Nav:
`<nav>`: Defines navigation links

```
<nav>
    <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#services">Services</a></li>
        <li><a href="#contact">Contact</a></li>
    </ul>
</nav>
```

#### Header:
`<header>`: Defines a header for a document or section

```
<header>
    <h1>Website Title</h1>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>
```

#### Footer:
`<footer>`: Defines a footer for a document or section

```
<footer>
    <p>&copy; 2024 Your Company. All rights reserved.</p>
</footer>
```

#### Figure:
`<figure>`: Specifies self-contained content, like illustrations, diagrams, photos, code listings, etc.

```
<figure>
    <img src="image.jpg" alt="Description of Image">
    <figcaption>Figure 1: This is a description of the image.</figcaption>
</figure>
```

#### Figcaption:
`<figcaption>`: Defines a caption for a `<figure>` element

```
<figure>
    <img src="image.jpg" alt="Description of Image">
    <figcaption>Figure 1: This is a description of the image.</figcaption>
</figure>
```

### Advanced HTML Tags

#### Details:
`<details>`: Specifies additional details that the user can open and close on demand

```
<details>
    <summary>More Information</summary>
    <p>This is additional information that can be hidden or shown by clicking the summary.</p>
</details>
```

#### Summary:
`<summary>`: Defines a visible heading for a `<details>` element

```
<details>
    <summary>Click to see details</summary>
    <p>Here are the details that are revealed when you click the summary.</p>
</details>
```

#### Mark:
`<mark>`: Higlights text

```
<p>Here is a <mark>highlighted text</mark> within a paragraph.</p>
```

#### Time:
`<time>`: Defines a specific time (or datetime)

```
<p>The event starts at <time datetime="2024-07-01T19:30">7:30 PM on July 1, 2024</time>.</p>
```

#### Progress:
`<progress>`: Represents the progress of a task

```
<label for="file">File progress:</label>
<progress id="file" value="70" max="100">70%</progress>
```

#### Meter:
`<meter>`: Represents a scalar measurement within a known range

```
<label for="disk">Disk usage:</label>
<meter id="disk" value="2" min="0" max="10">2 out of 10</meter>
```

#### Template:
`<template>`: Defines a container for holding content that is not to be rendered when the page loads but can be instantiated later

```
<template id="my-template">
    <div class="alert">
        <strong>Warning!</strong> This is a warning message.
    </div>
</template>

<script>
    document.addEventListener('DOMContentLoaded', () => {
        const template = document.getElementById('my-template');
        const clone = template.content.cloneNode(true);
        document.body.appendChild(clone);
    });
</script>
```

## Additional Resources:
- [Mozilla Developer Network (MDN) Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3Schools - HTML Tutorial](https://www.w3schools.com/html/)



## Day 2: HTML5 semantic elements, forms, and tables.

###
## Day 3: Introduction to CSS, selectors, and properties.
## Day 4: CSS box model, display properties, and positioning.
## Day 5: Flexbox basics and layout techniques.
## Day 6: Grid layout basics and implementation.
## Day 7: Project work: Structure and basic styling of the portfolio website.
