# Day 4 — HTML Text Formatting

HTML provides several elements for giving text different meanings or presentations.

## Text Formatting Elements

| Element    | Purpose                                        |
| ---------- | ---------------------------------------------- |
| `<b>`      | Stylistically bold/attention                   |
| `<strong>` | Indicates strong importance                    |
| `<i>`      | Represents alternate voice/mood or offset text |
| `<em>`     | Indicates stress emphasis                      |
| `<u>`      | Represents annotated/underlined text           |
| `<mark>`   | Highlights relevant text                       |
| `<small>`  | Represents side comments or small print        |
| `<del>`    | Represents deleted content                     |
| `<ins>`    | Represents inserted content                    |
| `<sub>`    | Displays subscript text                        |
| `<sup>`    | Displays superscript text                      |

---

## 1. Bold Text — `<b>`

```html
<p>This is <b>bold text</b>.</p>
```

The `<b>` element draws attention to text without adding strong semantic importance.

---

## 2. Important Text — `<strong>`

```html
<p>This is <strong>important text</strong>.</p>
```

`<strong>` indicates that the content has strong importance.

---

## 3. Italic Text — `<i>`

```html
<p>This is <i>italic text</i>.</p>
```

The `<i>` element is used for text in an alternate voice or mood, or other text that is conventionally offset from the surrounding content.

---

## 4. Emphasized Text — `<em>`

```html
<p>This is <em>emphasized text</em>.</p>
```

`<em>` represents stress emphasis.

---

## 5. Underlined Text — `<u>`

```html
<p>This is <u>underlined text</u>.</p>
```

The `<u>` element represents text with an annotation or other non-textual distinction.

---

## 6. Highlighted Text — `<mark>`

```html
<p>This is <mark>highlighted text</mark>.</p>
```

`<mark>` represents text that is highlighted because it is relevant to the current context.

---

## 7. Small Text — `<small>`

```html
<p>
    Main text
    <small>Additional information</small>
</p>
```

`<small>` represents side comments or small print.

---

## 8. Deleted Text — `<del>`

```html
<p>Old price: <del>$100</del></p>
```

`<del>` represents content that has been deleted from a document.

---

## 9. Inserted Text — `<ins>`

```html
<p>New price: <ins>$80</ins></p>
```

`<ins>` represents content that has been inserted into a document.

---

## 10. Subscript — `<sub>`

```html
<p>H<sub>2</sub>O</p>
```

Output:

```text
H₂O
```

Subscript is useful for chemical formulas and similar notation.

---

## 11. Superscript — `<sup>`

```html
<p>10<sup>2</sup> = 100</p>
```

Output:

```text
10² = 100
```

Superscript is useful for mathematical expressions, powers, and other notation.

---

# Semantic vs Visual Formatting

Some HTML elements communicate meaning, not just appearance.

For example:

```html
<strong>Important information</strong>
```

communicates importance.

While:

```html
<b>Bold text</b>
```

primarily draws visual attention.

Similarly:

```html
<em>Important emphasis</em>
```

communicates emphasis.

This is why choosing HTML elements based on their meaning is important when writing accessible and maintainable HTML.

---

# Complete Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>HTML Text Formatting</title>
</head>

<body>

    <h1>HTML Text Formatting</h1>

    <p>
        I am learning <strong>HTML</strong> every day.
    </p>

    <p>
        HTML is a <mark>markup language</mark>.
    </p>

    <p>
        Water: H<sub>2</sub>O
    </p>

    <p>
        10<sup>2</sup> = 100
    </p>

    <p>
        Old price: <del>$100</del>
    </p>

    <p>
        New price: <ins>$80</ins>
    </p>

</body>

</html>
```

---

# Key Points

* `<b>` makes text visually bold.
* `<strong>` indicates strong importance.
* `<i>` represents alternate voice/mood or offset text.
* `<em>` represents stress emphasis.
* `<u>` represents annotated text.
* `<mark>` highlights relevant text.
* `<small>` represents side comments or small print.
* `<del>` represents deleted content.
* `<ins>` represents inserted content.
* `<sub>` creates subscript text.
* `<sup>` creates superscript text.
* Use semantic elements when you need to communicate meaning.

---

# Practice Task

Create a webpage called **"My Favorite Technologies"**.

It must contain:

### 1. Bold text

```html
<b>HTML</b>
```

### 2. Strong text

```html
<strong>Important</strong>
```

### 3. Emphasized text

```html
<em>My favorite technology</em>
```

### 4. Highlighted text

```html
<mark>Web Development</mark>
```

### 5. Deleted and inserted text

```html
<del>Old information</del>
<ins>New information</ins>
```

### 6. Subscript

```html
H<sub>2</sub>O
```

### 7. Superscript

```html
x<sup>2</sup>
```

---

# Step 7 — Save Everything

In VS Code:

```text
Ctrl + S
```

Then test:

```text
04-text-formatting/index.html
```

in your browser.

---

# Step 8 — GitHub Commit

Open the VS Code terminal.

Run:

```bash
git status
```

Then:

```bash
git add .
```

Then:

```bash
git commit -m "docs: add HTML text formatting"
```

Finally:

```bash
git push
```

Refresh your GitHub repository.

You should now have:

```text
01-introduction/              ✅
02-elements-and-attributes/   ✅
03-headings-and-paragraphs/   ✅
04-text-formatting/           ✅
```

---

# Step 9 — Update Main README

Change your progress table to:

```markdown
| Day | Topic | Status |
|---|---|---|
| 01 | Introduction to HTML & Document Structure | ✅ |
| 02 | HTML Elements & Attributes | ✅ |
| 03 | Headings & Paragraphs | ✅ |
| 04 | Text Formatting | ✅ |
| 05 | Links | ⬜ |
```

Also update:

```text
Day 4 / 30–45 completed
```

---


Day 4/30–45 ✅

#HTML #HTML5 #WebDevelopment #FullStackWebDevelopment #GitHub #CodingJourney #LearningToCode

---

## 🎯 Day 5 Preview

Next topic:

**HTML Links**

You'll learn:

```html
<a>
href
target
title
mailto:
tel:
```

You'll also practice **internal links, external links, email links, telephone links, and opening links in a new tab**.
