# Internal CSS (Style Tag in HTML)

## 📖 Overview

Internal CSS is a method of adding CSS styles directly inside an HTML document using the `<style>` tag. The style rules are written within the `<head>` section of the webpage.

Internal CSS is useful for small projects, testing, and single-page websites. However, it is generally not recommended for large-scale professional web development because it makes maintenance and reusability more difficult.

---

## 🎯 What is Internal CSS?

Internal CSS allows developers to define CSS rules inside the same HTML file using the `<style>` tag.

### Syntax

```html
<head>
    <style>
        selector {
            property: value;
        }
    </style>
</head>
```

---

## 🏗️ Example of Internal CSS

```html
<!DOCTYPE html>
<html>
<head>
    <title>Internal CSS Example</title>

    <style>
        h1 {
            color: blue;
            text-align: center;
        }

        p {
            color: green;
            font-size: 18px;
        }
    </style>

</head>

<body>

    <h1>Welcome to CSS</h1>
    <p>This is a paragraph.</p>

</body>
</html>
```

---

## 🔹 How Internal CSS Works

1. CSS rules are written inside the `<style>` tag.
2. The browser reads these rules when loading the page.
3. The styles are applied to matching HTML elements.

### Example

```html
<style>
    h1 {
        color: red;
    }
</style>
```

All `<h1>` elements will appear in red color.

---

## ✅ Advantages of Internal CSS

### 1. Better Than Inline CSS

Styles are separated from HTML elements.

```html
<style>
    h1 {
        color: blue;
    }
</style>
```

The HTML remains cleaner compared to inline CSS.

---

### 2. Easy for Small Projects

Suitable for:

* Practice projects
* Single-page websites
* Learning CSS

---

### 3. No Additional CSS File Required

Everything is contained within one HTML file.

---

### 4. Faster Setup

No need to create and link a separate CSS file.

---

## ❌ Disadvantages of Internal CSS

### 1. Not Reusable

The styles only work for the current HTML page.

If your website contains:

```text
Home Page
About Page
Contact Page
```

You must copy the same CSS into each page.

---

### 2. Difficult to Maintain

Suppose your website has 20 pages.

Changing one style means updating all pages individually.

This wastes time and increases the chance of mistakes.

---

### 3. Larger HTML Files

Both HTML and CSS are stored in the same file.

As the project grows, files become lengthy and harder to manage.

---

### 4. Poor Scalability

Internal CSS works well for small projects but becomes difficult to manage in large applications.

---

### 5. Team Collaboration Issues

Professional projects often involve multiple developers.

Keeping CSS inside HTML files makes collaboration less efficient.

---

### 6. No Shared Styling

Different pages cannot share the same CSS rules easily.

This leads to code duplication.

---

## 🔥 Why Internal CSS Is Rarely Used in Professional Development

Professional developers usually avoid Internal CSS because:

### ❌ Difficult Maintenance

Large projects may contain hundreds of pages.

Updating styles across multiple pages becomes time-consuming.

---

### ❌ Repetition of Code

The same CSS must be written repeatedly in different files.

---

### ❌ Poor Project Organization

Best Practice:

```text
HTML  → Structure
CSS   → Styling
JavaScript → Functionality
```

Internal CSS partially mixes structure and styling.

---

### ❌ Not Suitable for Large Websites

Modern websites often contain:

* Hundreds of pages
* Thousands of style rules
* Multiple developers

Internal CSS cannot efficiently handle such requirements.

---

## ✅ Professional Solution: External CSS

Instead of writing CSS inside HTML, developers create a separate CSS file.

### HTML File

```html
<link rel="stylesheet" href="style.css">
```

### CSS File

```css
h1 {
    color: blue;
}

p {
    color: green;
}
```

### Benefits

✅ Reusable

✅ Easy Maintenance

✅ Better Organization

✅ Faster Development

✅ Industry Standard

---

## 📊 Internal CSS vs External CSS

| Feature                     | Internal CSS | External CSS |
| --------------------------- | ------------ | ------------ |
| Reusable                    | ❌ No         | ✅ Yes        |
| Maintainability             | ❌ Difficult  | ✅ Easy       |
| Suitable for Large Projects | ❌ No         | ✅ Yes        |
| Team Collaboration          | ❌ Poor       | ✅ Better     |
| Industry Usage              | ⚠️ Limited   | ✅ Standard   |

---

## 🎯 Learning Outcomes

After completing this topic, I can:

✅ Understand Internal CSS

✅ Use the `<style>` tag inside the `<head>` section

✅ Apply styles to multiple elements

✅ Explain the advantages of Internal CSS

✅ Identify its limitations

✅ Understand why professional developers prefer External CSS

---

## 🚀 Next Topic

After Internal CSS, the next topic is:

* External CSS
* CSS Selectors
* Colors and Backgrounds

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)

Web Development Learning Journey 🚀

