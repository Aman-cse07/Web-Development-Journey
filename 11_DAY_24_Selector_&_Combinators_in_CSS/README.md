# CSS Selectors

## 📖 Overview

CSS Selectors are one of the most fundamental concepts in CSS. They are used to **target HTML elements** so that styles can be applied to them.

Selectors tell the browser **which HTML element(s)** should receive a particular CSS rule.

Without selectors, CSS cannot determine which elements need styling.

In this project, I learned the following CSS selectors:

* Universal Selector (`*`)
* Element Selector
* ID Selector (`#`)
* Class Selector (`.`)
* Descendant Selector (Space)
* Child Combinator (`>`)
* Adjacent Sibling Combinator (`+`)
* Attribute Selector (`[]`)

Understanding selectors is essential for writing clean, reusable, and maintainable CSS.

---

# 🎯 Learning Objectives

* Understand the purpose of CSS selectors.
* Learn different ways to target HTML elements.
* Differentiate between basic and advanced selectors.
* Understand CSS selector priority.
* Write cleaner and more efficient CSS.

---

# 📚 Topics Covered

## Basic Selectors

* Universal Selector (`*`)
* Element Selector
* ID Selector (`#`)
* Class Selector (`.`)

## Advanced Selectors

* Descendant Selector
* Child Combinator (`>`)
* Adjacent Sibling Combinator (`+`)
* Attribute Selector (`[]`)

---

# 🧠 What is a CSS Selector?

A CSS selector tells the browser **which HTML element(s) should receive a particular style.**

## General Syntax

```css
selector{
    property: value;
}
```

Example

```css
h1{
    color: blue;
}
```

Every `<h1>` element becomes blue.

---

# 🌍 Universal Selector (`*`)

The Universal Selector selects **every HTML element** on the webpage.

## Syntax

```css
*{
    margin: 0;
    padding: 0;
}
```

## Example

```css
*{
    font-family: Arial, sans-serif;
}
```

### Uses

* Reset browser default styles
* Apply common fonts
* Set default margins and paddings

---

# 🏷️ Element Selector

The Element Selector targets every HTML element having the same tag.

## Syntax

```css
element{
    property: value;
}
```

## Example

```css
h1{
    color: red;
}

p{
    font-size:18px;
}
```

### Uses

* Styling headings
* Paragraphs
* Images
* Buttons
* Tables

---

# 🆔 ID Selector (`#`)

The ID Selector targets one unique HTML element.

## HTML

```html
<h1 id="title">Welcome</h1>
```

## CSS

```css
#title{
    color: blue;
}
```

### Rules

* One ID should belong to only one element.
* IDs should be unique.
* ID selectors have higher priority than class selectors.

---

# 🏷️ Class Selector (`.`)

The Class Selector targets one or more HTML elements sharing the same class.

## HTML

```html
<p class="intro">Hello</p>

<h2 class="intro">Learning CSS</h2>
```

## CSS

```css
.intro{
    color: green;
}
```

### Benefits

* Reusable
* Easy maintenance
* Recommended for styling multiple elements

---

# 🌳 Descendant Selector (Space)

The Descendant Selector selects elements that are **inside another element**, regardless of how deeply they are nested.

## Syntax

```css
ancestor descendant{
    property:value;
}
```

## Example

### HTML

```html
<div>
    <p>Hello World</p>
</div>
```

### CSS

```css
div p{
    color: blue;
}
```

### Explanation

Only the `<p>` elements inside a `<div>` will become blue.

### Uses

* Styling navigation links
* Nested lists
* Cards
* Sections

---

# 👨‍👩‍👦 Child Combinator (`>`)

The Child Combinator selects **only direct children** of an element.

## Syntax

```css
parent > child{
    property:value;
}
```

## Example

### HTML

```html
<div>

    <p>Paragraph 1</p>

    <section>

        <p>Paragraph 2</p>

    </section>

</div>
```

### CSS

```css
div > p{
    color:red;
}
```

### Output

Only **Paragraph 1** becomes red.

Paragraph 2 remains unchanged because it is not a direct child.

---

# ➕ Adjacent Sibling Combinator (`+`)

The Adjacent Sibling Combinator selects the **immediately next sibling**.

## Syntax

```css
element + sibling{
    property:value;
}
```

## Example

### HTML

```html
<h1>Heading</h1>

<p>Paragraph</p>

<div>Box</div>
```

### CSS

```css
h1 + p{
    color:green;
}
```

### Explanation

Only the first `<p>` immediately following the `<h1>` gets styled.

---

# 🏷️ Attribute Selector (`[]`)

The Attribute Selector selects elements based on their attributes.

## Syntax

```css
element[attribute]{
    property:value;
}
```

## Example

### HTML

```html
<input type="text">

<input type="password">
```

### CSS

```css
input[type="text"]{
    background-color: lightyellow;
}
```

### Explanation

Only the text input receives the background color.

---

## Another Example

```css
a[target]{
    color:red;
}
```

Only links having the `target` attribute will become red.

---

# 📊 Selector Comparison

| Selector         | Symbol | Targets                           | Reusable |
| ---------------- | ------ | --------------------------------- | -------- |
| Universal        | `*`    | Every element                     | ✅ Yes    |
| Element          | `h1`   | All same elements                 | ✅ Yes    |
| ID               | `#`    | One unique element                | ❌ No     |
| Class            | `.`    | Multiple elements                 | ✅ Yes    |
| Descendant       | Space  | Nested elements                   | ✅ Yes    |
| Child            | `>`    | Direct children                   | ✅ Yes    |
| Adjacent Sibling | `+`    | Immediate sibling                 | ✅ Yes    |
| Attribute        | `[]`   | Elements with specific attributes | ✅ Yes    |

---

# ⚖️ Selector Priority

When multiple selectors apply to the same element, CSS follows this priority:

| Priority                                  | Selector |
| ----------------------------------------- | -------- |
| 🥇 Inline CSS                             |          |
| 🥈 ID Selector                            |          |
| 🥉 Class Selector                         |          |
| 4️⃣ Attribute Selector                    |          |
| 5️⃣ Child / Descendant / Adjacent Sibling |          |
| 6️⃣ Element Selector                      |          |
| 7️⃣ Universal Selector                    |          |

---

# 🏗️ Complete Example

## HTML

```html
<div>

    <h1 id="title">CSS Selectors</h1>

    <p class="intro">Learning CSS</p>

    <input type="text">

</div>
```

## CSS

```css
*{
    font-family: Arial;
}

#title{
    color:blue;
}

.intro{
    color:green;
}

div p{
    font-size:20px;
}

div > input{
    border:2px solid blue;
}

input[type="text"]{
    background-color:lightyellow;
}
```

---

# 💡 Best Practices

* Use **Class Selectors** for reusable styles.
* Use **ID Selectors** only for unique elements.
* Avoid overusing the Universal Selector.
* Prefer Descendant and Child Selectors for structured layouts.
* Use Attribute Selectors for forms and links.
* Keep selectors simple for better readability and performance.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Style every element using the Universal Selector.

✅ Style HTML tags using the Element Selector.

✅ Target unique elements using the ID Selector.

✅ Reuse styles with the Class Selector.

✅ Style nested elements using the Descendant Selector.

✅ Target direct children using the Child Combinator.

✅ Style immediate sibling elements using the Adjacent Sibling Combinator.

✅ Target elements based on attributes using the Attribute Selector.

✅ Understand CSS selector priority and write maintainable CSS.

---

# 🚀 Next Topic

After learning CSS Selectors, the next topics are:

* Pseudo Classes (`:hover`, `:active`, `:focus`, `:checked`, `:nth-child()`)
* Pseudo Elements (`::before`, `::after`, `::first-letter`, `::first-line`)
* CSS Specificity
* Box Model
* Display Property

These concepts will help you build more interactive and responsive web pages.

---

## 📂 Project Structure

```text
Day_10_CSS_Selectors/
│
├── index.html
├── style.css
└── README.md
```

---

## 👨‍💻 Author

## **Aman Kumar**

**B.Tech CSE (AI & ML)**

**Web Development Learning Journey 🚀**
