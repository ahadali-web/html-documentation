# Day 3 — HTML Headings & Paragraphs

## 1. HTML Headings

HTML provides six levels of headings.

They range from `<h1>` to `<h6>`.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

The `<h1>` element represents the highest-level heading, while `<h6>` represents the lowest-level heading.

---

## 2. `<h1>` — Main Heading

`<h1>` is normally used for the main heading of a page or major content section.

Example:

```html
<h1>My Website</h1>
```

---

## 3. `<h2>` — Second-Level Heading

`<h2>` is commonly used for major sections under the main heading.

Example:

```html
<h2>About Me</h2>
```

---

## 4. `<h3>` to `<h6>`

The remaining heading levels provide deeper levels of structure.

```html
<h3>Web Development</h3>

<h4>Frontend Development</h4>

<h5>HTML</h5>

<h6>HTML Elements</h6>
```

The heading levels create a hierarchy of content.

---

## 5. Heading Hierarchy

A simple webpage might have this structure:

```text
h1 → Main page heading
 ├── h2 → Section
 │    ├── h3 → Subsection
 │    └── h3 → Subsection
 └── h2 → Another section
```

Example:

```html
<h1>Web Development</h1>

<h2>Frontend Development</h2>

<h3>HTML</h3>

<h3>CSS</h3>

<h2>Backend Development</h2>

<h3>Node.js</h3>
```

Using headings in a logical hierarchy makes a document easier to understand.

---

# 6. HTML Paragraphs

The `<p>` element is used to define a paragraph.

Example:

```html
<p>
    HTML is the standard markup language for creating web pages.
</p>
```

The browser normally displays paragraphs as separate blocks of text.

---

## 7. Multiple Paragraphs

You can create multiple paragraphs using multiple `<p>` elements.

```html
<p>This is the first paragraph.</p>

<p>This is the second paragraph.</p>

<p>This is the third paragraph.</p>
```

Each paragraph is treated as a separate block.

---

# 8. Line Break — `<br>`

The `<br>` element creates a line break.

Example:

```html
<p>
    Hello!<br>
    Welcome to my website.
</p>
```

The text after `<br>` starts on a new line.

`<br>` is a void element, so it does not have a closing tag.

Correct:

```html
<br>
```

Not:

```html
</br>
```

---

# 9. Horizontal Rule — `<hr>`

The `<hr>` element represents a thematic break between sections of content.

Example:

```html
<h2>About HTML</h2>

<p>
    HTML provides the structure of a webpage.
</p>

<hr>

<h2>About CSS</h2>

<p>
    CSS is used to style webpages.
</p>
```

The browser normally displays a horizontal line.

Like `<br>`, `<hr>` is a void element.

---

# 10. Whitespace in HTML

Multiple spaces and line breaks in normal HTML text are generally collapsed into a single space when rendered.

For example:

```html
<p>Hello       World</p>
```

will normally appear approximately as:

```text
Hello World
```

If you need a new line, use an appropriate HTML element such as `<br>` or structure the content using separate elements.

---

# 11. Complete Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>My Web Development Journey</title>
</head>

<body>

    <h1>My Web Development Journey</h1>

    <p>
        I am learning web development step by step.
    </p>

    <h2>HTML</h2>

    <p>
        HTML provides the structure of webpages.
    </p>

    <h3>Why I Am Learning HTML</h3>

    <p>
        HTML is an important foundation for web development.
    </p>

    <hr>

    <h2>My Goal</h2>

    <p>
        My goal is to become a professional web developer.
    </p>

</body>

</html>
```

---

# 12. Important Rules

### Rule 1 — Use headings for structure

Don't choose `<h1>` just because it looks bigger.

Headings should represent the structure and hierarchy of your content.

### Rule 2 — Don't use headings for normal text

Use:

```html
<p>This is normal text.</p>
```

instead of:

```html
<h6>This is normal text.</h6>
```

### Rule 3 — Don't use `<br>` just to create large spacing

Use CSS for visual spacing.

`<br>` is mainly for an intentional line break within content.

### Rule 4 — Use logical heading levels

Prefer:

```text
h1
 ├── h2
 │    ├── h3
 │    └── h3
 └── h2
```

rather than randomly jumping between heading levels.

---

# 13. Key Points

* HTML has six heading levels: `<h1>` through `<h6>`.
* `<h1>` represents the highest-level heading.
* `<h6>` represents the lowest-level heading.
* `<p>` defines a paragraph.
* `<br>` creates a line break.
* `<hr>` represents a thematic break.
* `<br>` and `<hr>` are void elements.
* Headings should create a logical content hierarchy.
* CSS should be used for visual styling and spacing.

---

# 14. Practice Task

Create a personal profile webpage.

Your page should contain:

* One `<h1>`
* At least two `<h2>` elements
* At least one `<h3>`
* At least three paragraphs
* One `<br>`
* One `<hr>`

Example:

```html
<h1>About Me</h1>

<p>
    My name is Ahad.
</p>

<h2>Education</h2>

<p>
    I am studying Computer Science and Engineering.
</p>

<h2>Career Goal</h2>

<p>
    I want to become a professional web developer.
</p>

<h3>My Learning</h3>

<p>
    I am currently learning HTML and web development.
</p>

<hr>

<p>
    My learning journey continues every day.
</p>
```

---

# Day 3 Completed ✅

### Topics covered

* `<h1>`
* `<h2>`
* `<h3>`
* `<h4>`
* `<h5>`
* `<h6>`
* Heading hierarchy
* `<p>`
* `<br>`
* `<hr>`
* HTML whitespace
* Heading best practices
