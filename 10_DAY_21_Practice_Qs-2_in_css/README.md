# CSS Practice Project - Ozymandias Poem

## 📖 Overview

This project is a practice assignment that combines **HTML** and **CSS** to create a beautifully formatted webpage displaying the famous poem **"Ozymandias"** by **Percy Bysshe Shelley**.

The project demonstrates how HTML structures web content while CSS enhances its appearance using typography, colors, alignment, decorations, links, buttons, forms, and other styling techniques.

---

# 🎯 Objectives

* Create a structured HTML webpage.
* Display a famous poem using semantic HTML elements.
* Apply CSS typography and text styling.
* Style hyperlinks, buttons, and form controls.
* Practice combining multiple HTML and CSS concepts in one project.

---

# 📚 Topics Covered

## HTML

* HTML Boilerplate
* Headings (`<h1>`, `<h3>`, `<h4>`)
* Paragraph (`<p>`)
* Line Break (`<br>`)
* Horizontal Rule (`<hr>`)
* Hyperlink (`<a>`)
* Span (`<span>`)
* Div (`<div>`)
* Textarea (`<textarea>`)
* Button (`<button>`)
* External CSS Linking (`<link>`)

---

## CSS

* Text Color
* Background Color
* Text Alignment
* Font Family
* Font Size
* Line Height
* Text Decoration
* Text Decoration Color
* Hyperlink Styling
* Button Styling
* Textarea Styling
* Span Styling

---

# 📂 Project Structure

```text
Day_07_CSS_Practice_Project/
│
├── index.html
├── Practice_Qs_3.css
└── README.md
```

---

# 🏗️ HTML Structure

## 1️⃣ HTML Boilerplate

The webpage begins with the standard HTML5 boilerplate.

```html
<!DOCTYPE html>
<html lang="en">
```

This tells the browser that the document uses HTML5.

---

## 2️⃣ External CSS

The CSS file is connected using the `<link>` tag.

```html
<link rel="stylesheet" href="Practice_Qs_3.css">
```

This keeps HTML and CSS separate, following professional development practices.

---

## 3️⃣ Background Color

The webpage background is set using an inline style.

```html
<body style="background-color: wheat;">
```

Background Color:

* Wheat

---

## 4️⃣ Heading Elements

### Main Heading

```html
<h1>Ozymandias</h1>
```

Displays the poem title.

---

### Author Heading

```html
<h3>by Percy Bysshe Shelley</h3>
```

Displays the author's name.

---

### Information Heading

```html
<h4>
Read up more about the poem...
</h4>
```

Provides additional information.

---

## 5️⃣ Paragraph Element

The poem is written using the paragraph tag.

```html
<p>
...
</p>
```

This stores the main poem content.

---

## 6️⃣ Line Break (`<br>`)

```html
<br>
```

Used to display each line of the poem on a new line.

---

## 7️⃣ Span Element

```html
<span>Ozymandias</span>
```

The `<span>` element highlights only the word **"Ozymandias"** without affecting the rest of the paragraph.

---

## 8️⃣ Horizontal Rule

```html
<hr>
```

Creates a horizontal line that separates the poem from the remaining content.

---

## 9️⃣ Hyperlink

```html
<a href="https://en.wikipedia.org/wiki/Ozymandias">
Wikipedia...
</a>
```

Allows users to visit the Wikipedia page to learn more about the poem.

---

## 🔟 Div Element

```html
<div>
...
</div>
```

Groups the textarea and button together.

---

## 1️⃣1️⃣ Textarea

```html
<textarea
placeholder="Leave your comments here..."
rows="5"
cols="25">
</textarea>
```

Allows users to enter multiline comments.

---

## 1️⃣2️⃣ Button

```html
<button>Comment</button>
```

Creates a button for submitting comments.

---

# 🎨 CSS Styling

## Paragraph Styling

```css
p{
    color:red;
    text-align:center;
    line-height:30px;
}
```

### Properties Used

* Text Color
* Text Alignment
* Line Height

---

## Main Heading Styling

```css
h1{
    text-align:center;
    text-decoration:magenta underline;
    font-family:Georgia;
}
```

### Properties Used

* Center Alignment
* Underline Decoration
* Decoration Color
* Font Family

---

## Author Heading

```css
h3{
    color:black;
    text-align:center;
}
```

Centers the author's name.

---

## Information Heading

```css
h4{
    text-align:center;
}
```

Centers the information heading.

---

## Hyperlink Styling

```css
a{
    color:green;
    text-decoration:none;
}
```

### Explanation

* Changes link color to green.
* Removes the default underline.

---

## Button Styling

```css
button{
    color:blueviolet;
    background-color:white;
}
```

Changes:

* Text Color
* Background Color

---

## Textarea Styling

```css
textarea{
    color:#000000;
}
```

Changes the text color inside the textarea.

---

## Span Styling

```css
span{
    text-decoration:magenta underline;
}
```

Only the word **"Ozymandias"** receives a magenta underline.

---

# 🧠 HTML Elements Practiced

| Element      | Purpose                  |
| ------------ | ------------------------ |
| `<html>`     | Root element             |
| `<head>`     | Stores metadata          |
| `<title>`    | Browser tab title        |
| `<link>`     | Connects external CSS    |
| `<body>`     | Displays webpage content |
| `<h1>`       | Main heading             |
| `<h3>`       | Subheading               |
| `<h4>`       | Small heading            |
| `<p>`        | Paragraph                |
| `<br>`       | Line break               |
| `<hr>`       | Horizontal separator     |
| `<span>`     | Styles specific text     |
| `<a>`        | Hyperlink                |
| `<div>`      | Groups elements          |
| `<textarea>` | Multiline input          |
| `<button>`   | Clickable button         |

---

# 🎨 CSS Properties Practiced

| Property                      | Purpose                         |
| ----------------------------- | ------------------------------- |
| `color`                       | Changes text color              |
| `background-color`            | Changes background color        |
| `text-align`                  | Aligns text                     |
| `line-height`                 | Controls spacing between lines  |
| `font-family`                 | Changes font style              |
| `text-decoration`             | Adds or removes text decoration |
| `text-decoration-color`       | Changes decoration color        |
| `text-decoration-style`       | Changes decoration style        |
| `text-decoration-line`        | Specifies decoration type       |
| `text-decoration` (shorthand) | Combines line, style, and color |
| `text-decoration: none`       | Removes underline from links    |

---

# 💡 Key Learning Points

* HTML provides the **structure** of a webpage.
* CSS enhances the **appearance** of HTML elements.
* External CSS keeps the code clean and reusable.
* The `<span>` element is useful for styling specific words.
* The `<textarea>` element accepts multiline user input.
* Hyperlinks can be customized using CSS.
* Typography properties improve readability and design.

---

# 🎯 Learning Outcomes

After completing this project, I can:

✅ Create a complete HTML webpage.

✅ Link an external CSS file.

✅ Style headings and paragraphs.

✅ Use line breaks and horizontal rules.

✅ Create and style hyperlinks.

✅ Highlight specific words using `<span>`.

✅ Style buttons and textareas.

✅ Apply typography-related CSS properties.

✅ Combine HTML and CSS to build a visually appealing webpage.

---

# 🚀 Conclusion

This project helped me strengthen my understanding of HTML structure and CSS styling by combining multiple concepts into a single webpage. It demonstrates how typography, colors, links, forms, and layout work together to create a clean and attractive user interface.

As I continue my **Web Development Journey**, these foundational skills will help me build more advanced and responsive websites using CSS, JavaScript, and modern web technologies.

---

## 👨‍💻 Author

## **Aman Kumar**

**B.Tech CSE (AI & ML)**

**Web Development Learning Journey 🚀**
