# CSS Selectors

## 📖 Overview

CSS Selectors are used to target HTML elements so that styles can be applied to them. They are one of the most fundamental concepts in CSS because they determine **which HTML elements will receive specific styles**.

Without selectors, CSS would not know which elements to style.

In this project, I learned the four basic CSS selectors:

* Universal Selector (`*`)
* Element Selector
* ID Selector (`#`)
* Class Selector (`.`)

These selectors form the foundation for writing efficient and organized CSS.

---

# 🎯 Objectives

* Understand the purpose of CSS Selectors.
* Learn how different selectors target HTML elements.
* Apply styles using various selector types.
* Differentiate between Universal, Element, ID, and Class selectors.
* Follow best practices while styling web pages.

---

# 📚 Topics Covered

* Universal Selector (`*`)
* Element Selector
* ID Selector (`#`)
* Class Selector (`.`)

---

# 🧠 What is a CSS Selector?

A CSS selector tells the browser **which HTML element(s) should receive a particular style**.

### General Syntax

```css
selector {
    property: value;
}
```

### Example

```css
h1{
    color: blue;
}
```

This selector applies the color blue to all `<h1>` elements.

---

# 🌍 Universal Selector (`*`)

The Universal Selector selects **every HTML element** on the webpage.

## Syntax

```css
*{
    property: value;
}
```

## Example

```css
*{
    margin: 0;
    padding: 0;
}
```

### Explanation

This removes the default margin and padding from all HTML elements.

### Uses

* Reset browser default styles.
* Apply common styling to the entire webpage.
* Set default fonts or spacing.

---

# 🏷️ Element Selector

The Element Selector targets all elements with the same HTML tag.

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
    font-size: 18px;
}
```

### Explanation

* Every `<h1>` will appear in red.
* Every `<p>` will have a font size of 18px.

### Uses

* Styling headings.
* Formatting paragraphs.
* Applying common styles to buttons, images, links, etc.

---

# 🆔 ID Selector (`#`)

The ID Selector targets **one unique HTML element** using its `id` attribute.

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

### Explanation

Only the element with:

```html
id="title"
```

will receive the style.

### Rules

✅ An ID should be unique.

✅ One element should have only one ID.

❌ Avoid using the same ID on multiple elements.

---

# 🏷️ Class Selector (`.`)

The Class Selector targets one or more HTML elements using the `class` attribute.

## HTML

```html
<p class="intro">Hello World</p>

<h2 class="intro">Learning CSS</h2>
```

## CSS

```css
.intro{
    color: green;
}
```

### Explanation

Both elements with the class `intro` will become green.

### Uses

* Reuse the same style on multiple elements.
* Create consistent designs across the webpage.

---

# 📊 Difference Between ID and Class

| Feature       | ID Selector        | Class Selector    |
| ------------- | ------------------ | ----------------- |
| Symbol        | `#`                | `.`               |
| Used For      | One unique element | Multiple elements |
| Reusable      | ❌ No               | ✅ Yes             |
| Priority      | Higher             | Lower             |
| Best Practice | Unique components  | Reusable styles   |

---

# 🏗️ Complete Example

## HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Selectors</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1 id="title">Welcome</h1>

    <p class="intro">
        Learning CSS Selectors.
    </p>

    <p>
        This is another paragraph.
    </p>

</body>
</html>
```

---

## CSS (`style.css`)

```css
/* Universal Selector */
*{
    font-family: Arial, sans-serif;
}

/* Element Selector */
p{
    color: red;
}

/* ID Selector */
#title{
    color: blue;
    text-align: center;
}

/* Class Selector */
.intro{
    font-size: 22px;
    font-weight: bold;
}
```

---

# ⚖️ Selector Priority

When multiple selectors target the same element, CSS follows a priority order.

| Priority   | Selector                 |
| ---------- | ------------------------ |
| 🥇 Highest | Inline CSS               |
| 🥈         | ID Selector (`#`)        |
| 🥉         | Class Selector (`.`)     |
| 4          | Element Selector         |
| 5          | Universal Selector (`*`) |

### Example

```css
*{
    color: black;
}

p{
    color: blue;
}

.intro{
    color: green;
}

#message{
    color: red;
}
```

```html
<p id="message" class="intro">
    Hello World
</p>
```

**Output:** The text will be **red** because the **ID Selector** has the highest priority among these selectors.

---

# 💡 Best Practices

* Use the **Universal Selector** only when necessary.
* Use **Element Selectors** for common HTML elements.
* Use **Class Selectors** for reusable styles.
* Use **ID Selectors** only for unique elements.
* Avoid excessive use of IDs for styling; classes are more flexible and reusable.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Understand the purpose of CSS selectors.

✅ Style all elements using the Universal Selector.

✅ Target HTML tags using the Element Selector.

✅ Style unique elements using the ID Selector.

✅ Reuse styles using the Class Selector.

✅ Understand selector priority in CSS.

✅ Write cleaner and more maintainable CSS code.

---

# 🚀 Next Topic

After learning CSS Selectors, the next topics are:

* Descendant Selector
* Child Selector
* Adjacent Sibling Selector
* Attribute Selector
* Pseudo Classes (`:hover`, `:active`, `:focus`)
* Pseudo Elements (`::before`, `::after`, `::first-letter`)

These advanced selectors provide greater control over styling complex web pages.

---

## 📂 Project Structure

```text
Day_08_CSS_Selectors/
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
