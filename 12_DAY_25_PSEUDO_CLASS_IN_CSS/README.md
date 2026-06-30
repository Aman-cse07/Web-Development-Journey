# CSS Pseudo Classes

## 📖 Overview

CSS **Pseudo Classes** are special keywords added to selectors that define the **special state of an HTML element**. They allow developers to style elements based on user interaction or their position in the document without using JavaScript.

Pseudo classes begin with a **single colon (`:`)**.

For example, you can change the appearance of a button when a user hovers over it, clicks it, or focuses on it.

---

# 🎯 Learning Objectives

* Understand what CSS pseudo classes are.
* Learn how to style elements based on different states.
* Apply interactive effects without JavaScript.
* Improve user experience using CSS.
* Understand commonly used pseudo classes.

---

# 📚 Topics Covered

* What are Pseudo Classes?
* `:hover`
* `:active`
* `:focus`
* `:checked`
* `:nth-child()`
* `:first-child`
* `:last-child`
* `:disabled`
* `:enabled`

---

# 🧠 What are CSS Pseudo Classes?

A **Pseudo Class** is a keyword added to a selector that specifies a **special state** of an element.

They allow CSS to style elements when:

* The mouse is over an element.
* A user clicks an element.
* An input field receives focus.
* A checkbox is checked.
* A specific child element is selected.
* An input is disabled or enabled.

---

## Syntax

```css
selector:pseudo-class{
    property: value;
}
```

### Example

```css
button:hover{
    background-color: blue;
}
```

When the mouse pointer moves over the button, its background becomes blue.

---

# 🔹 `:hover`

The `:hover` pseudo class styles an element when the user places the mouse pointer over it.

## Syntax

```css
selector:hover{
    property: value;
}
```

### Example

```css
button:hover{
    background-color: blue;
    color: white;
}
```

### Uses

* Buttons
* Navigation menus
* Images
* Cards
* Links

---

# 🔹 `:active`

The `:active` pseudo class styles an element while it is being clicked.

## Syntax

```css
selector:active{
    property: value;
}
```

### Example

```css
button:active{
    background-color: red;
}
```

### Uses

* Buttons
* Links
* Interactive components

---

# 🔹 `:focus`

The `:focus` pseudo class styles an element when it receives keyboard or mouse focus.

Mostly used with form elements.

### Example

```css
input:focus{
    border: 2px solid blue;
}
```

### Uses

* Input fields
* Textareas
* Select boxes

---

# 🔹 `:checked`

The `:checked` pseudo class targets checked radio buttons and checkboxes.

### HTML

```html
<input type="checkbox">
```

### CSS

```css
input:checked{
    accent-color: green;
}
```

### Uses

* Checkboxes
* Radio buttons
* Toggle switches

---

# 🔹 `:nth-child()`

The `:nth-child()` pseudo class selects elements based on their position inside the parent element.

## Syntax

```css
selector:nth-child(number){
    property: value;
}
```

### Example

```css
li:nth-child(2){
    color: red;
}
```

Only the second list item becomes red.

---

## Odd Children

```css
li:nth-child(odd){
    background-color: lightgray;
}
```

---

## Even Children

```css
li:nth-child(even){
    background-color: lightblue;
}
```

---

# 🔹 `:first-child`

Selects the first child element inside a parent.

### Example

```css
p:first-child{
    color: blue;
}
```

---

# 🔹 `:last-child`

Selects the last child element inside a parent.

### Example

```css
p:last-child{
    color: green;
}
```

---

# 🔹 `:disabled`

Targets disabled form elements.

### HTML

```html
<input type="text" disabled>
```

### CSS

```css
input:disabled{
    background-color: lightgray;
}
```

---

# 🔹 `:enabled`

Targets enabled form elements.

### Example

```css
input:enabled{
    border: 2px solid green;
}
```

---

# 🏗️ Complete Example

## HTML

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>Pseudo Classes</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <button>Click Me</button>

    <br><br>

    <input type="text" placeholder="Enter your name">

    <br><br>

    <input type="checkbox">

    <ul>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>

</body>

</html>
```

---

## CSS

```css
button:hover{
    background-color: blue;
    color: white;
}

button:active{
    background-color: red;
}

input:focus{
    border:2px solid green;
}

input:checked{
    accent-color: blue;
}

li:nth-child(odd){
    background-color: lightgray;
}
```

---

# 📊 Common Pseudo Classes

| Pseudo Class   | Description                                         |
| -------------- | --------------------------------------------------- |
| `:hover`       | Styles an element when the mouse pointer is over it |
| `:active`      | Styles an element while it is being clicked         |
| `:focus`       | Styles an element when it receives focus            |
| `:checked`     | Styles checked radio buttons and checkboxes         |
| `:nth-child()` | Selects elements based on their position            |
| `:first-child` | Selects the first child element                     |
| `:last-child`  | Selects the last child element                      |
| `:disabled`    | Styles disabled form elements                       |
| `:enabled`     | Styles enabled form elements                        |

---

# 💡 Best Practices

* Use `:hover` to provide visual feedback for interactive elements.
* Use `:focus` to improve keyboard accessibility.
* Use `:active` for click effects on buttons and links.
* Use `:checked` for custom checkbox and radio button styling.
* Use `:nth-child()` to create zebra-striped tables and lists.
* Keep hover and focus styles consistent for a better user experience.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Understand the purpose of CSS pseudo classes.

✅ Style elements during user interaction.

✅ Create hover and click effects.

✅ Style focused input fields.

✅ Customize checkboxes and radio buttons.

✅ Select elements based on their position.

✅ Improve webpage interactivity using only CSS.

---

# 🚀 Next Topic

After learning CSS Pseudo Classes, the next topics are:

* CSS Pseudo Elements (`::before`, `::after`, `::first-letter`, `::first-line`, `::selection`)
* CSS Specificity
* Box Model
* Display Property
* Position Property

These concepts will help you create more advanced, interactive, and visually appealing web pages.

---

## 📂 Project Structure

```text
Day_11_CSS_Pseudo_Classes/
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
