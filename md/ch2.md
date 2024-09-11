---
title: "Introduction to HTML"
author: "Abdulla Ebrahim Subah"
institute: "University of Bahrain"
topic: "Introduction"
theme: "CambridgeUS"
colortheme: "beaver"
fonttheme: "professionalfonts"
fontsize: 8pt
linkstyle: bold
aspectratio: 169
dpi: 300
navigation: frame
# titlegraphic: 
# logo: 
date: \today{}
lang: en-US
section-titles: false
header-includes:
  - \usepackage{setspace}
  - \setstretch{1.5}
---
# Introduction to HTML

## What is HTML?

- **HTML** stands for **HyperText Markup Language**.
- It is the standard language for creating web pages.
- HTML describes the structure of a webpage.

## Basic Structure of an HTML Document

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

## Key Elements

- **`<!DOCTYPE html>`**: Defines the document type and version.
- **`<html>`**: The root element of an HTML page.
- **`<head>`**: Contains meta-information about the document.
- **`<title>`**: Sets the title of the webpage.
- **`<body>`**: Contains the content of the webpage.

## The `<head>` and `<body>` Tags

- **`<head>` Tag**:
  - Contains metadata and links to resources.
  - Includes elements like `<title>`, `<meta>`, `<link>`, and `<style>`.
  - Does not display content directly on the webpage.

- **`<body>` Tag**:
  - Contains the content of the webpage.
  - Includes text, images, links, and other media.
  - Everything inside is rendered in the browser window.

## HTML Tags, Elements, and Attributes

### Tags
- Tags are used to create elements.
- They usually come in pairs: an opening tag and a closing tag.
- Example: `<p>...</p>`

### Elements
- An element consists of a start tag, content, and an end tag.
- Example: `<h1>This is a heading</h1>`

### Attributes
- Attributes provide additional information about elements.
- They are always included in the opening tag.
- Example: `<a href="https://example.com">Visit Example</a>`

## HTML Syntax

- **Tags**: Enclosed in angle brackets, e.g., `<tagname>`.
- **Elements**: Consist of a start tag, content, and an end tag.
- **Nesting**: Elements can contain other elements.
- **Attributes**: Key-value pairs in the opening tag, e.g., `id="header"`.
- **Self-closing Tags**: Some tags don’t require a closing tag, e.g., `<br />`.
- **Case Sensitivity**: HTML tags and attributes are not case-sensitive, but lowercase is recommended.

## HTML Editors

- **Visual Studio Code**: Popular, extensible, and free.
- **Sublime Text**: Lightweight and fast with powerful features.
- **Notepad++**: Simple and efficient for Windows users.
- **Vim**: Highly configurable and powerful for advanced users.
- **Nano**: Simple, easy-to-use terminal-based editor.
- **Any Text Editor Will Work**

## HTML Standard and Resources

- **HTML Standard**: [WHATWG HTML Standard](https://html.spec.whatwg.org/)
- **HTML Tags List**: [W3Schools HTML Tags Reference](https://www.w3schools.com/tags/)

# Famous HTML Tags with Examples

### Headings
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
```

### Paragraphs
```html
<p>This is a paragraph.</p>
```

### Links
```html
<a href="https://example.com">Visit Example</a>
```

## Cont.
### Images
```html
<img src="image.jpg" alt="Description">
```

### Lists

- **Ordered List**
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

- **Unordered List**
```html
<ul>
  <li>First item</li>
  <li>Second item</li>
</ul>
```

## Cont.
### Div and Span

- **Div**
```html
<div>A block-level container.</div>
```

- **Span**
```html
<span>An inline-level container.</span>
```

### Forms
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <input type="submit" value="Submit">
</form>
```
