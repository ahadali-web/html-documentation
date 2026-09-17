# Day 2 — HTML Elements and Attributes

## 1. What is an HTML Element?

An HTML element is a complete part of an HTML document.

Most HTML elements consist of:

* Opening tag
* Content
* Closing tag

Example:

```html
<p>Hello World!</p>
```

Here:

```text
<p>          → Opening tag
Hello World! → Content
</p>         → Closing tag
```

Together, they form an HTML element.

---

## 2. HTML Tags

HTML tags are used to define the structure and meaning of webpage content.

Example:

```html
<h1>My Heading</h1>
```

The tags are:

```text
<h1>  → Opening tag
</h1> → Closing tag
```

Some common HTML tags are:

```html
<h1>Heading</h1>
<p>Paragraph</p>
<a>Link</a>
<img>
<div>Content</div>
```

---

## 3. Opening and Closing Tags

Most HTML elements have both an opening tag and a closing tag.

Example:

```html
<p>This is a paragraph.</p>
```

The opening tag:

```html
<p>
```

The closing tag:

```html
</p>
```

The closing tag contains a `/` before the tag name.

---

## 4. Nested HTML Elements

HTML elements can be placed inside other HTML elements.

This is called **nesting**.

Example:

```html
<div>
    <h1>My Website</h1>
    <p>Welcome to my website.</p>
</div>
```

Here, the `<h1>` and `<p>` elements are inside the `<div>` element.

Good indentation makes nested HTML easier to read.

---

## 5. What are HTML Attributes?

HTML attributes provide additional information about an HTML element.

Attributes are normally written inside the opening tag.

Example:

```html
<a href="https://www.google.com">Google</a>
```

Here:

```text
<a>      → HTML element
href     → Attribute
URL      → Attribute value
```

The general syntax is:

```html
<tag attribute="value">
```

---

## 6. The `href` Attribute

The `href` attribute specifies the destination of a link.

Example:

```html
<a href="https://www.google.com">Visit Google</a>
```

The browser uses the `href` value to know where the link should go.

---

## 7. The `src` Attribute

The `src` attribute specifies the source of an external resource, such as an image.

Example:

```html
<img src="image.jpg">
```

Here:

```text
src       → Attribute
image.jpg → Attribute value
```

---

## 8. The `alt` Attribute

The `alt` attribute provides alternative text for an image.

Example:

```html
<img src="image.jpg" alt="A beautiful landscape">
```

The alternative text can help describe the image when it cannot be displayed and is also important for accessibility.

---

## 9. The `class` Attribute

The `class` attribute assigns a class name to an element.

Example:

```html
<p class="intro">Welcome to my website.</p>
```

Classes are commonly used with CSS and JavaScript.

---

## 10. The `id` Attribute

The `id` attribute gives an element a unique identifier within a page.

Example:

```html
<h1 id="main-title">My Website</h1>
```

An `id` can be used by CSS, JavaScript, and links that target a specific part of a page.

---

## 11. Multiple Attributes

An HTML element can have multiple attributes.

Example:

```html
<img 
    src="image.jpg" 
    alt="Example image" 
    width="300"
>
```

This image has three attributes:

* `src`
* `alt`
* `width`

---

## 12. Boolean Attributes

Some HTML attributes do not require a value.

These are called **boolean attributes**.

Example:

```html
<input type="text" disabled>
```

The presence of `disabled` means the input is disabled.

Other examples include:

```html
<input type="checkbox" checked>
<input type="text" required>
```

---

## 13. Comments in HTML

HTML comments are not displayed as normal webpage content.

Syntax:

```html
<!-- This is a comment -->
```

Example:

```html
<h1>Hello World</h1>

<!-- This paragraph explains the website -->
<p>Welcome to my website.</p>
```

Comments are useful for explaining code.

---

# Complete Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Elements and Attributes</title>
</head>

<body>

    <h1 id="main-title">My Website</h1>

    <p class="intro">
        Welcome to my first website.
    </p>

    <a href="https://www.google.com">
        Visit Google
    </a>

    <br><br>

    <img 
        src="image.jpg" 
        alt="Example image" 
        width="300"
    >

</body>

</html>
```

---

# Key Points

* An HTML element usually contains an opening tag, content, and closing tag.
* HTML tags define elements.
* HTML elements can be nested inside other elements.
* Attributes provide additional information about elements.
* Attributes are normally placed inside opening tags.
* `href` defines a link destination.
* `src` defines the source of an external resource.
* `alt` provides alternative text for images.
* `class` identifies an element as belonging to a class.
* `id` identifies a specific element.
* Boolean attributes can work through their presence alone.
* HTML comments use `<!-- -->`.

---

# Practice Task

Create a webpage containing:

1. A heading with an `id`.
2. A paragraph with a `class`.
3. A link using `href`.
4. An image using `src` and `alt`.
5. A disabled input.
6. At least one HTML comment.

Example:

```html
<h1 id="title">My Profile</h1>

<p class="description">
    I am learning HTML.
</p>

<a href="https://github.com">
    My GitHub
</a>

<img src="profile.jpg" alt="My profile image">

<input type="text" disabled>

<!-- This is my practice webpage -->
```

---

## Day 2 Completed ✅

**Topics covered:**

* HTML elements
* HTML tags
* Opening tags
* Closing tags
* Nested elements
* HTML attributes
* `href`
* `src`
* `alt`
* `class`
* `id`
* Boolean attributes
* HTML comments

