# CSS Typography Practice

## 📖 Overview

This project demonstrates how to style text using various **CSS Typography** properties. It includes a simple HTML page with a heading and applies multiple CSS properties to enhance its appearance.

Typography is one of the most important aspects of web design because it improves readability, visual hierarchy, and the overall user experience.

---

# 🎯 Objectives

- Learn how to style text using CSS.
- Apply different typography properties.
- Understand the `text-transform` property.
- Improve webpage appearance using CSS.

---

# 📚 Topics Covered

- External CSS
- Font Family
- Text Color
- Text Alignment
- Font Size
- Font Weight
- Letter Spacing
- Line Height
- Text Decoration
- Text Transform

---

# 📂 Project Structure

```text
Day_06_CSS_Typography/
│
├── index.html
├── Practice_Qs_2.css
└── README.md
```

---

# 📝 HTML Code

The HTML file contains a single heading.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Typography Practice</title>

    <link rel="stylesheet" href="Practice_Qs_2.css">
</head>

<body>

    <h1>Hello <br> everyone</h1>

</body>
</html>
```

### Explanation

- `<!DOCTYPE html>` specifies the HTML5 document type.
- `<meta charset="UTF-8">` supports Unicode characters.
- `<meta name="viewport">` makes the webpage responsive.
- `<link>` connects the external CSS file.
- `<br>` inserts a line break, displaying **Hello** and **Everyone** on separate lines.

---

# 🎨 CSS Code

```css
h1 {
    font-family: 'Lucida Sans', 'Lucida Sans Regular',
                 'Lucida Grande', 'Lucida Sans Unicode',
                 Geneva, Verdana, sans-serif;

    color: #ffa511;

    text-align: center;

    font-size: 55px;

    font-weight: 900;

    letter-spacing: 2px;

    line-height: 1.5;

    text-decoration: rgb(3, 246, 246) double underline;

    text-transform: uppercase;
}
```

---

# 🔹 Font Family

The `font-family` property specifies the typeface used for text.

### Syntax

```css
font-family: Arial, Helvetica, sans-serif;
```

### In this project

```css
font-family: 'Lucida Sans', Geneva, Verdana, sans-serif;
```

### Purpose

- Improves readability.
- Provides fallback fonts if one font is unavailable.
- Creates a professional appearance.

---

# 🔹 Color

The `color` property changes the text color.

### Example

```css
color: #ffa511;
```

This gives the heading a bright orange color.

---

# 🔹 Text Align

The `text-align` property aligns text horizontally.

### Example

```css
text-align: center;
```

The heading appears in the center of the page.

---

# 🔹 Font Size

The `font-size` property changes the size of the text.

### Example

```css
font-size: 55px;
```

The heading becomes large and easy to read.

---

# 🔹 Font Weight

The `font-weight` property controls the thickness of text.

### Example

```css
font-weight: 900;
```

`900` is one of the boldest font weights available.

---

# 🔹 Letter Spacing

The `letter-spacing` property controls the spacing between characters.

### Example

```css
letter-spacing: 2px;
```

This creates extra space between letters, making the heading more attractive.

---

# 🔹 Line Height

The `line-height` property controls the vertical spacing between lines.

### Example

```css
line-height: 1.5;
```

Since the heading contains a `<br>` tag, this property adds appropriate spacing between **Hello** and **Everyone**.

---

# 🔹 Text Decoration

The `text-decoration` property adds decorative lines to text.

### Example

```css
text-decoration: rgb(3, 246, 246) double underline;
```

### Explanation

- `rgb(3, 246, 246)` → Underline color (cyan).
- `double` → Creates a double underline.
- `underline` → Adds an underline below the text.

---

# 🔹 Text Transform

The `text-transform` property changes the capitalization of text without modifying the original HTML content.

## Syntax

```css
text-transform: value;
```

## Common Values

| Value | Description |
|--------|-------------|
| `uppercase` | Converts all letters to uppercase. |
| `lowercase` | Converts all letters to lowercase. |
| `capitalize` | Capitalizes the first letter of each word. |
| `none` | Displays text exactly as written in HTML. |

---

## Examples

### Uppercase

```css
text-transform: uppercase;
```

Output:

```text
HELLO EVERYONE
```

---

### Lowercase

```css
text-transform: lowercase;
```

Output:

```text
hello everyone
```

---

### Capitalize

```css
text-transform: capitalize;
```

Output:

```text
Hello Everyone
```

---

### None

```css
text-transform: none;
```

Output remains exactly as written in the HTML document.

---

# 💡 Why Use `text-transform`?

Instead of changing the text directly in HTML, developers use CSS to control capitalization.

### Advantages

- Keeps HTML clean.
- Makes it easy to change text style later.
- Ensures consistent formatting across the website.
- Separates content (HTML) from presentation (CSS).

---

# 📊 Summary of CSS Properties

| Property | Purpose | Value Used |
|----------|---------|------------|
| `font-family` | Changes font style | Lucida Sans |
| `color` | Changes text color | `#ffa511` |
| `text-align` | Aligns text | `center` |
| `font-size` | Changes text size | `55px` |
| `font-weight` | Controls text thickness | `900` |
| `letter-spacing` | Adds spacing between letters | `2px` |
| `line-height` | Controls spacing between lines | `1.5` |
| `text-decoration` | Adds decoration to text | Double Underline |
| `text-transform` | Changes text capitalization | `uppercase` |

---

# 🎯 Learning Outcomes

After completing this project, I can:

✅ Link an external CSS file to an HTML document.

✅ Apply typography-related CSS properties.

✅ Change font family, size, weight, and color.

✅ Align text using `text-align`.

✅ Control spacing using `letter-spacing` and `line-height`.

✅ Decorate text using `text-decoration`.

✅ Transform text using `text-transform`.

✅ Create visually appealing headings with CSS.

---

# 🌟 Conclusion

This project strengthened my understanding of **CSS Typography** by applying multiple text styling properties to a simple HTML heading.

Mastering typography is an essential step in web development because it enhances readability, improves user experience, and gives websites a professional appearance.

---

## 👨‍💻 Author

## **Aman Kumar**

**B.Tech CSE (AI & ML)**

**Web Development Learning Journey 🚀**
