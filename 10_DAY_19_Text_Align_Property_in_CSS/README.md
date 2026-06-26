# CSS Text Properties

## 📖 Overview

Text properties in CSS are used to control the appearance and formatting of text on a web page. They help improve readability, alignment, spacing, and overall design.

In this project, I learned some of the most commonly used CSS text properties:

- `text-align`
- `font-weight`
- `text-decoration`
- `line-height`
- `letter-spacing`
- `font-size`

These properties are essential for designing attractive and user-friendly web pages.

---

# 🎯 Learning Objectives

- Understand different CSS text properties.
- Align text in different positions.
- Change text thickness.
- Add or remove text decorations.
- Control spacing between lines and letters.
- Change the font size of text.

---

# 📚 Topics Covered

- Text Alignment (`text-align`)
- Font Weight (`font-weight`)
- Text Decoration (`text-decoration`)
- Line Height (`line-height`)
- Letter Spacing (`letter-spacing`)
- Font Size (`font-size`)

---

# 🔹 Text Alignment (`text-align`)

The `text-align` property specifies the horizontal alignment of text inside an element.

## Syntax

```css
selector{
    text-align: value;
}
```

## Values

| Value | Description |
|--------|-------------|
| `left` | Aligns text to the left (default). |
| `right` | Aligns text to the right. |
| `center` | Centers the text. |
| `justify` | Stretches text so each line has equal width. |

## Example

```css
h1{
    text-align: center;
}

p{
    text-align: justify;
}
```

### Output

- Heading appears in the center.
- Paragraph is justified.

---

# 🔹 Font Weight (`font-weight`)

The `font-weight` property controls the thickness (boldness) of text.

## Syntax

```css
selector{
    font-weight: value;
}
```

## Common Values

| Value | Description |
|--------|-------------|
| `normal` | Default thickness |
| `bold` | Bold text |
| `lighter` | Lighter than parent |
| `bolder` | Bolder than parent |
| `100–900` | Numeric font weights |

## Example

```css
h1{
    font-weight: bold;
}

p{
    font-weight: 400;
}
```

---

# 🔹 Text Decoration (`text-decoration`)

The `text-decoration` property adds or removes decorative lines from text.

## Syntax

```css
selector{
    text-decoration: value;
}
```

## Common Values

| Value | Description |
|--------|-------------|
| `none` | Removes decoration |
| `underline` | Adds an underline |
| `overline` | Adds a line above text |
| `line-through` | Draws a line through text |

## Example

```css
a{
    text-decoration: none;
}

h2{
    text-decoration: underline;
}
```

### Use Case

Most websites remove the underline from navigation links using:

```css
a{
    text-decoration: none;
}
```

---

# 🔹 Line Height (`line-height`)

The `line-height` property controls the vertical spacing between lines of text.

## Syntax

```css
selector{
    line-height: value;
}
```

## Example

```css
p{
    line-height: 30px;
}
```

### Benefits

- Improves readability.
- Makes paragraphs easier to read.
- Creates clean layouts.

---

# 🔹 Letter Spacing (`letter-spacing`)

The `letter-spacing` property controls the space between characters.

## Syntax

```css
selector{
    letter-spacing: value;
}
```

## Example

```css
h1{
    letter-spacing: 4px;
}
```

### Use Cases

- Headings
- Logos
- Titles
- Stylish text

---

# 🔹 Font Size (`font-size`)

The `font-size` property changes the size of text.

## Syntax

```css
selector{
    font-size: value;
}
```

## Common Units

| Unit | Description |
|------|-------------|
| `px` | Pixels |
| `em` | Relative to parent |
| `rem` | Relative to root element |
| `%` | Percentage |

## Example

```css
h1{
    font-size: 40px;
}

p{
    font-size: 18px;
}
```

---

# 🏗️ Complete Example

## HTML (`index.html`)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Text Properties</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1>Welcome to CSS</h1>

    <p>
        CSS makes web pages beautiful and improves readability.
    </p>

    <a href="#">Visit Website</a>

</body>
</html>
```

---

## CSS (`style.css`)

```css
h1{
    text-align: center;
    font-size: 40px;
    font-weight: bold;
    letter-spacing: 3px;
}

p{
    line-height: 30px;
    font-size: 18px;
    text-align: justify;
}

a{
    text-decoration: none;
}
```

---

# 📊 Summary of Text Properties

| Property | Purpose | Example |
|----------|---------|---------|
| `text-align` | Aligns text | `center` |
| `font-weight` | Changes text thickness | `bold` |
| `text-decoration` | Adds or removes decoration | `underline` |
| `line-height` | Controls spacing between lines | `30px` |
| `letter-spacing` | Controls spacing between letters | `3px` |
| `font-size` | Changes text size | `20px` |

---

# 💡 Best Practices

- Use **`text-align: justify`** for long paragraphs to improve readability.
- Use **`font-weight: bold`** only for headings or important text.
- Remove underlines from navigation links using **`text-decoration: none`**.
- Use appropriate **`line-height`** (around `1.5` or `24px–32px`) for better readability.
- Avoid excessive **`letter-spacing`** on paragraphs.
- Prefer **`rem`** or **`em`** for responsive font sizes in larger projects.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Align text using `text-align`

✅ Change text thickness using `font-weight`

✅ Add or remove text decorations

✅ Control spacing between lines using `line-height`

✅ Adjust spacing between letters using `letter-spacing`

✅ Change text size using `font-size`

✅ Apply text properties to improve webpage design and readability

---

# 🚀 Next Topic

After learning CSS Text Properties, the next topics are:

- Font Family
- CSS Units (`px`, `%`, `em`, `rem`, `vh`, `vw`)
- Color and Background
- Box Model
- Display Property

---

## 📂 Project Structure

```text
Day_05_CSS_Text_Properties/
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
