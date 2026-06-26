# CSS Color System (RGB & Hexadecimal Colors)

## 📖 Overview

Colors play a vital role in web design by improving the appearance and user experience of a website. CSS provides several ways to define colors, with **RGB (Red, Green, Blue)** and **Hexadecimal (Hex)** being the most commonly used color systems.

In this project, I learned how to apply colors using both RGB and Hexadecimal values.

---

## 🎯 What is the CSS Color System?

The CSS Color System allows developers to change the color of text, backgrounds, borders, and many other elements.

Some common ways to define colors in CSS are:

* Color Names (e.g., `red`, `blue`, `green`)
* RGB Color System
* RGBA Color System
* Hexadecimal Colors
* HSL & HSLA Colors

In this topic, we focus on **RGB** and **Hexadecimal** colors.

---

# 🌈 RGB Color System

RGB stands for:

* **R** → Red
* **G** → Green
* **B** → Blue

Each color component can have a value from **0 to 255**.

### Syntax

```css
color: rgb(red, green, blue);
```

### Example

```css
h1 {
    color: rgb(255, 0, 0);
}
```

The above code displays the heading in **Red**.

---

## 🎨 RGB Examples

```css
h1 {
    color: rgb(255, 0, 0);
}
```

🔴 Red

```css
h2 {
    color: rgb(0, 255, 0);
}
```

🟢 Green

```css
h3 {
    color: rgb(0, 0, 255);
}
```

🔵 Blue

```css
p {
    color: rgb(255, 255, 0);
}
```

🟡 Yellow

```css
body {
    background-color: rgb(240, 240, 240);
}
```

⚪ Light Gray Background

---

## 📊 Understanding RGB Values

| Color   | RGB Value            |
| ------- | -------------------- |
| Red     | `rgb(255, 0, 0)`     |
| Green   | `rgb(0, 255, 0)`     |
| Blue    | `rgb(0, 0, 255)`     |
| White   | `rgb(255, 255, 255)` |
| Black   | `rgb(0, 0, 0)`       |
| Yellow  | `rgb(255, 255, 0)`   |
| Cyan    | `rgb(0, 255, 255)`   |
| Magenta | `rgb(255, 0, 255)`   |

---

# 🎨 Hexadecimal Color System

Hexadecimal colors are represented using a **#** symbol followed by six hexadecimal characters.

Each pair represents:

* Red
* Green
* Blue

### Syntax

```css
color: #RRGGBB;
```

Each pair ranges from:

```text
00 → Minimum
FF → Maximum
```

---

## 🎨 Hexadecimal Examples

```css
h1 {
    color: #ff0000;
}
```

🔴 Red

```css
h2 {
    color: #00ff00;
}
```

🟢 Green

```css
h3 {
    color: #0000ff;
}
```

🔵 Blue

```css
p {
    color: #ff00ff;
}
```

🟣 Magenta

```css
body {
    background-color: #f5f5f5;
}
```

⚪ Light Gray

---

## 📊 Common Hexadecimal Colors

| Color   | Hex Value |
| ------- | --------- |
| Red     | `#ff0000` |
| Green   | `#00ff00` |
| Blue    | `#0000ff` |
| White   | `#ffffff` |
| Black   | `#000000` |
| Yellow  | `#ffff00` |
| Cyan    | `#00ffff` |
| Magenta | `#ff00ff` |

---

# 🏗️ Complete Example

## HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>CSS Colors</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>RGB Color</h1>

    <h2>Hexadecimal Color</h2>

</body>
</html>
```

---

## CSS (style.css)

```css
h1{
    color: rgb(0,0,255);
}

h2{
    color: #ff00ff;
}
```

---

# ⚖️ RGB vs Hexadecimal

| Feature             | RGB            | Hexadecimal |
| ------------------- | -------------- | ----------- |
| Syntax              | `rgb(255,0,0)` | `#ff0000`   |
| Readability         | Easy           | Compact     |
| Uses Decimal Values | ✅ Yes          | ❌ No        |
| Uses Hex Values     | ❌ No           | ✅ Yes       |
| Popularity          | High           | Very High   |

---

# 💡 Which One Should You Use?

### Use RGB When:

* Adjusting individual Red, Green, and Blue values.
* Learning color combinations.
* Working with `rgba()` for transparency.

### Use Hexadecimal When:

* Writing cleaner and shorter CSS.
* Following professional web development practices.
* Using design tools like Figma or Adobe XD, where colors are often provided in Hex format.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Understand the CSS Color System.

✅ Apply colors using RGB values.

✅ Apply colors using Hexadecimal values.

✅ Differentiate between RGB and Hex colors.

✅ Choose the appropriate color format for different situations.

---

# 🚀 Next Topic

After learning CSS Colors, the next topics are:

* Background Color
* Opacity
* CSS Units (`px`, `%`, `em`, `rem`)
* Text Properties
* Font Properties

---

## 📂 Project Structure

```text
Day_04_CSS_Colors/
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

