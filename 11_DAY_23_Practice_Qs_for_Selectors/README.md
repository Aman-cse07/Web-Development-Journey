# CSS Practice Project - Facebook Login Interface

## 📖 Overview

This project is a simple **Facebook-inspired interface** created using **HTML** and **CSS**. It demonstrates the use of basic HTML elements along with CSS selectors such as the **Universal Selector (`*`)**, **Element Selector**, **Class Selector (`.`)**, and **ID Selector (`#`)**.

The project focuses on styling buttons, headings, input fields, and labels while understanding how different selectors work in CSS.

---

# 🎯 Objectives

- Build a simple webpage using HTML.
- Connect an external CSS file.
- Practice different CSS selectors.
- Style buttons using Class and ID selectors.
- Understand the difference between reusable and unique styles.
- Apply fonts and colors using CSS.

---

# 📚 Topics Covered

## HTML

- HTML Boilerplate
- Heading (`<h1>`)
- Division (`<div>`)
- Buttons (`<button>`)
- Horizontal Rule (`<hr>`)
- Label (`<label>`)
- Input Field (`<input>`)
- External CSS (`<link>`)

---

## CSS

- Universal Selector (`*`)
- Element Selector
- Class Selector (`.`)
- ID Selector (`#`)
- Font Family
- Text Color
- Background Color

---

# 📂 Project Structure

```text
Day_09_CSS_Selectors_Practice/
│
├── index.html
├── Practice_Qs_4.css
└── README.md
```

---

# 🏗️ HTML Structure

## 1️⃣ HTML Boilerplate

```html
<!DOCTYPE html>
<html lang="en">
```

Declares the document as an HTML5 webpage.

---

## 2️⃣ External CSS

```html
<link rel="stylesheet" href="Practice_Qs_4.css">
```

Connects the external CSS file with the HTML document.

---

## 3️⃣ Main Heading

```html
<h1>Facebook</h1>
```

Displays the title of the webpage.

---

## 4️⃣ Division (`<div>`)

```html
<div>
    <button class="a">Log in</button>
    <button class="a">Register</button>
</div>
```

The `<div>` groups the login and register buttons together.

---

## 5️⃣ Horizontal Rule

```html
<hr>
```

Creates a horizontal line to separate sections of the webpage.

---

## 6️⃣ Label

```html
<label for="search">Search</label>
```

The label describes the purpose of the input field.

Using the `for` attribute connects the label with the input element having the same `id`.

---

## 7️⃣ Input Field

```html
<input type="text" placeholder="search your friends" id="search">
```

Creates a text input box where users can type search queries.

### Attributes Used

| Attribute | Purpose |
|----------|---------|
| `type="text"` | Creates a text field |
| `placeholder` | Displays temporary hint text |
| `id="search"` | Gives a unique identity to the input |

---

## 8️⃣ Search Button

```html
<button id="b">Search</button>
```

Creates a button used for searching.

---

# 🎨 CSS Styling

## Universal Selector (`*`)

```css
*{
    font-family: 'Courier New';
}
```

### Explanation

The Universal Selector applies the font family to **every HTML element** on the webpage.

### Benefits

- Maintains consistent typography.
- Eliminates repetitive CSS code.
- Applies common styles globally.

---

## Element Selector

```css
h1{
    color: #1b74e4;
}
```

### Explanation

The Element Selector styles every `<h1>` element.

### Result

- Changes the heading color to Facebook Blue.

---

## Class Selector (`.a`)

```css
.a{
    color: black;
    background-color: aqua;
}
```

### Explanation

The class selector styles both **Log in** and **Register** buttons because they share the same class name.

### Why Use a Class?

- Reusable styling.
- Multiple elements can share the same design.
- Reduces duplicate CSS code.

---

## ID Selector (`#b`)

```css
#b{
    color: white;
    background-color: black;
}
```

### Explanation

The ID selector styles only the **Search** button because IDs are unique.

### Result

- White text
- Black background

---

# 📊 HTML Elements Practiced

| HTML Element | Purpose |
|--------------|---------|
| `<!DOCTYPE html>` | Declares HTML5 document |
| `<html>` | Root element |
| `<head>` | Contains metadata |
| `<title>` | Browser tab title |
| `<link>` | Links external CSS |
| `<body>` | Main webpage content |
| `<h1>` | Main heading |
| `<div>` | Groups related elements |
| `<button>` | Creates clickable buttons |
| `<hr>` | Horizontal separator |
| `<label>` | Describes an input field |
| `<input>` | Accepts user input |

---

# 📊 CSS Properties Practiced

| Property | Purpose |
|----------|---------|
| `font-family` | Changes the font style |
| `color` | Changes text color |
| `background-color` | Changes background color |

---

# 📚 CSS Selectors Practiced

| Selector | Symbol | Purpose |
|----------|--------|---------|
| Universal Selector | `*` | Styles every element |
| Element Selector | `h1` | Styles all `<h1>` elements |
| Class Selector | `.a` | Styles multiple elements sharing the same class |
| ID Selector | `#b` | Styles one unique element |

---

# ⚖️ Difference Between Class and ID

| Feature | Class | ID |
|---------|-------|----|
| Symbol | `.` | `#` |
| Used For | Multiple elements | One unique element |
| Reusable | ✅ Yes | ❌ No |
| Priority | Lower | Higher |

---

# 💡 Key Learning Points

- HTML provides the structure of a webpage.
- CSS controls the visual appearance.
- The Universal Selector is useful for applying common styles globally.
- Element Selectors style all elements of the same type.
- Class Selectors allow reusable styling across multiple elements.
- ID Selectors target a single unique element.
- External CSS keeps code organized and maintainable.

---

# 🎯 Learning Outcomes

After completing this project, I can:

✅ Create a structured HTML webpage.

✅ Link an external CSS stylesheet.

✅ Apply a common font using the Universal Selector.

✅ Style headings using the Element Selector.

✅ Style multiple buttons using the Class Selector.

✅ Style a unique button using the ID Selector.

✅ Understand the differences between Class and ID selectors.

✅ Write cleaner and more reusable CSS.

---

# 🚀 Conclusion

This practice project strengthened my understanding of **basic CSS selectors** by applying them to a simple Facebook-inspired interface. I learned how different selectors target HTML elements and how they help create clean, reusable, and maintainable styles.

Mastering these selectors is an important step toward building professional and responsive websites.

---

# 🌐 Learn More

To deepen your understanding of HTML and CSS, explore the official MDN Web Docs:

- **HTML Documentation:** https://developer.mozilla.org/en-US/docs/Web/HTML
- **CSS Documentation:** https://developer.mozilla.org/en-US/docs/Web/CSS

MDN is one of the best resources for learning modern web development and exploring advanced CSS concepts.

---

## 👨‍💻 Author

## **Aman Kumar**

**B.Tech CSE (AI & ML)**

**Web Development Learning Journey 🚀**
