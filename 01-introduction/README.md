# Day 1 — Introduction to HTML

## What is HTML?

HTML stands for **HyperText Markup Language**.

HTML is the standard markup language used to create and structure content on web pages.

HTML is used to define elements such as:

* Headings
* Paragraphs
* Links
* Images
* Lists
* Tables
* Forms
* Buttons

HTML provides the basic structure of a webpage.

---

## Why is HTML Important?

HTML is one of the fundamental technologies of web development.

A typical website uses:

* **HTML** — Structure
* **CSS** — Styling and design
* **JavaScript** — Behavior and interaction

For example:

```text
HTML        → Structure
CSS         → Appearance
JavaScript  → Interaction
```

---

## Basic HTML Structure

A basic HTML document looks like this:

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My First HTML Page</title>
</head>

<body>

    <h1>Hello, HTML!</h1>
    <p>This is my first HTML document.</p>

</body>

</html>
```

---

## Understanding the Structure

### `<!DOCTYPE html>`

This declaration tells the browser that the document uses HTML5.

```html
<!DOCTYPE html>
```

It should normally be the first line of an HTML document.

---

### `<html>`

The `<html>` element is the root element of an HTML document.

```html
<html lang="en">
```

All other HTML elements are placed inside it.

---

### `<head>`

The `<head>` element contains information about the webpage that is generally not displayed directly as page content.

Example:

```html
<head>
    <meta charset="UTF-8">
    <title>My Website</title>
</head>
```

---

### `<title>`

The `<title>` element defines the title of the webpage.

```html
<title>My First HTML Page</title>
```

The title normally appears in the browser tab.

---

### `<body>`

The `<body>` element contains the visible content of the webpage.

```html
<body>

    <h1>Hello, HTML!</h1>
    <p>Welcome to my webpage.</p>

</body>
```

---

## First HTML Program

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First Page</title>
</head>

<body>

    <h1>Hello, World!</h1>
    <p>I am learning HTML.</p>

</body>
</html>
```

### Output

The browser will display:

**Hello, World!**

I am learning HTML.

---

## Key Points

* HTML means **HyperText Markup Language**.
* HTML creates the structure of webpages.
* HTML5 is the modern HTML standard.
* `<!DOCTYPE html>` declares the HTML document type.
* `<html>` is the root element.
* `<head>` contains document metadata and related information.
* `<title>` defines the browser page title.
* `<body>` contains the visible webpage content.

---

## Practice

Create a webpage containing:

1. Your name as a heading.
2. A paragraph introducing yourself.
3. A webpage title.
4. A second paragraph explaining why you are learning HTML.

Example:

html
<h1>My Name</h1>

<p>I am learning HTML to become a web developer.</p>

<p>HTML is the foundation of web development.</p>
```

---

## Day 1 Completed

**Topics covered:**

* HTML introduction
* Purpose of HTML
* HTML vs CSS vs JavaScript
* HTML5
* Basic document structure
* <!DOCTYPE html>
* <html>
* <head>
  <title>
* <body>
* First HTML webpage

