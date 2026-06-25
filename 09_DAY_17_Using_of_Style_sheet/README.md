# External CSS (Separate Stylesheet)

## 📖 Overview

External CSS is the most commonly used and recommended method for styling web pages. In this approach, all CSS code is written in a separate `.css` file and linked to the HTML document.

This method keeps HTML and CSS separate, making projects cleaner, easier to maintain, and more scalable.

External CSS is the industry-standard approach used by professional web developers.

---

## 🎯 What is External CSS?

External CSS means writing all styling rules in a separate CSS file and connecting that file to an HTML document using the `<link>` tag.

### Example Files

```text
Project/
│
├── index.html
└── style.css
```

---

# 🔗 Linking CSS with HTML

To connect a CSS file with an HTML file, use the `<link>` tag inside the `<head>` section.

### Syntax

```html
<link rel="stylesheet" href="style.css">
```

### Explanation

| Attribute        | Purpose                                        |
| ---------------- | ---------------------------------------------- |
| rel="stylesheet" | Specifies that the linked file is a stylesheet |
| href="style.css" | Path of the CSS file                           |

---

# 🏗️ Complete Example

## HTML File (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>External CSS Example</title>

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1>Welcome to CSS</h1>

    <p>This is an External CSS example.</p>

</body>
</html>
```

---

## CSS File (style.css)

```css
h1 {
    color: blue;
    text-align: center;
}

p {
    color: green;
    font-size: 20px;
}
```

---

# 🔹 How External CSS Works

### Step 1

Create an HTML file.

```html
index.html
```

### Step 2

Create a CSS file.

```css
style.css
```

### Step 3

Link the CSS file inside the HTML `<head>` section.

```html
<link rel="stylesheet" href="style.css">
```

### Step 4

Write CSS rules inside the CSS file.

```css
h1 {
    color: red;
}
```

The browser automatically applies these styles to matching HTML elements.

---

# ✅ Advantages of External CSS

## 1. Clean Code Structure

HTML and CSS remain separate.

```text
HTML → Structure
CSS → Styling
```

This makes code easier to read.

---

## 2. Reusable Styles

One CSS file can style multiple HTML pages.

```text
index.html
about.html
contact.html

↓

style.css
```

All pages can share the same stylesheet.

---

## 3. Easy Maintenance

Suppose your website has 100 pages.

If you want to change:

```css
color: blue;
```

You only need to update the CSS file once.

---

## 4. Faster Development

Developers can focus separately on:

* HTML Structure
* CSS Design

This improves productivity.

---

## 5. Better Team Collaboration

Different developers can work on:

* HTML
* CSS
* JavaScript

without interfering with each other's code.

---

## 6. Industry Standard

Almost all professional websites use External CSS.

Examples:

* E-commerce Websites
* Portfolio Websites
* Blogs
* Social Media Platforms

---

# 🔥 Why Developers Prefer External CSS

Professional developers prefer External CSS because:

✅ Cleaner Code

✅ Easy Reusability

✅ Better Performance

✅ Easier Debugging

✅ Better Organization

✅ Suitable for Large Projects

---

# ❌ Problems with Inline and Internal CSS

### Inline CSS

```html
<h1 style="color:red;">
    Welcome
</h1>
```

Problems:

* Repeated code
* Difficult maintenance
* Poor readability

---

### Internal CSS

```html
<style>
h1{
    color:red;
}
</style>
```

Problems:

* Only works for one page
* Difficult to manage in large projects

---

### External CSS Solution

```html
<link rel="stylesheet" href="style.css">
```

```css
h1{
    color:red;
}
```

Much cleaner and reusable.

---

# 📊 Comparison of CSS Methods

| Feature                     | Inline CSS  | Internal CSS | External CSS |
| --------------------------- | ----------- | ------------ | ------------ |
| Reusable                    | ❌ No        | ❌ Limited    | ✅ Yes        |
| Readability                 | ❌ Poor      | ⚠️ Medium    | ✅ Excellent  |
| Maintainability             | ❌ Difficult | ⚠️ Medium    | ✅ Easy       |
| Suitable for Large Projects | ❌ No        | ❌ No         | ✅ Yes        |
| Industry Usage              | ❌ Rare      | ⚠️ Limited   | ✅ Standard   |

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Create separate CSS files

✅ Link CSS with HTML using the `<link>` tag

✅ Understand how External CSS works

✅ Reuse styles across multiple pages

✅ Explain why External CSS is preferred in professional development

✅ Follow industry-standard CSS practices

---

# 🚀 Next Topic

After External CSS, the next topic is:

* CSS Selectors
* Element Selector
* Class Selector
* ID Selector
* Universal Selector

These selectors help target and style HTML elements efficiently.

---

## 📂 Project Structure

```text
Day_03_External_CSS/
│
├── index.html
├── style.css
└── README.md
```

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)

Web Development Learning Journey 🚀
