# HTML Entities and Video Tag

## 📖 Introduction

This project demonstrates the use of HTML Entities and the HTML Video Tag. These elements help developers display reserved characters, special symbols, and multimedia content on web pages.

---

## 🎯 Objectives

* Learn how to use HTML Entities.
  
* Display special characters and symbols in HTML.
  
* Learn how to embed videos using the `<video>` tag.
  
* Understand common video attributes.
  
* Create interactive and multimedia-rich web pages.

---

## 📌 HTML Entities

HTML Entities are used to display reserved characters and special symbols that cannot be typed directly or may conflict with HTML syntax.

### Syntax

```html
&entity_name;
```

or

```html
&#entity_number;
```

---

### Common HTML Entities

| Entity     | Symbol | Description          |
| ---------- | ------ | -------------------- |
| `&lt;`     | <      | Less Than            |
| `&gt;`     | >      | Greater Than         |
| `&amp;`    | &      | Ampersand            |
| `&copy;`   | ©      | Copyright Symbol     |
| `&reg;`    | ®      | Registered Trademark |
| `&trade;`  | ™      | Trademark            |
| `&hearts;` | ♥      | Heart Symbol         |
| `&nbsp;`   | Space  | Non-Breaking Space   |

### Example

```html
<p>Made with &hearts; using HTML.</p>
<p>&copy; 2026 Aman Kumar</p>
```

### Output

Made with ♥ using HTML.

© 2026 Aman Kumar

---

## 📌 HTML Video Tag (`<video>`)

The `<video>` tag is used to embed video content directly into a webpage.

### Syntax

```html
<video src="video.mp4" controls>
</video>
```

---

### Example

```html
<video width="500" controls>
    <source src="sample-video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

---

### Common Attributes

| Attribute  | Description                               |
| ---------- | ----------------------------------------- |
| `controls` | Displays play, pause, and volume controls |
| `autoplay` | Starts video automatically                |
| `loop`     | Repeats the video continuously            |
| `muted`    | Mutes the video                           |
| `poster`   | Displays an image before video starts     |
| `width`    | Sets video width                          |
| `height`   | Sets video height                         |

---

## 💻 Complete Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>Entities and Video Tag</title>
</head>
<body>

    <h1>HTML Entities Example</h1>

    <p>Made with &hearts; by Aman Kumar</p>
    <p>&copy; 2026 All Rights Reserved</p>

    <hr>

    <h1>HTML Video Example</h1>

    <video width="500" controls>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>
```

---

## 🔍 Learn More About HTML Entities

For a complete list of HTML Entities, visit the official MDN documentation:

https://developer.mozilla.org/en-US/docs/Glossary/Entity

---

## ✨ Highlights

* Learned how to use HTML Entities.
  
* Displayed special symbols such as ©, ™, ®, and ♥.
  
* Embedded videos using the `<video>` tag.
  
* Explored video attributes like controls, autoplay, and loop.
  
* Built a multimedia webpage using HTML5.

---

## 🛠 Technologies Used

* HTML5

---

## 📚 Learning Outcomes

After completing this project, you will be able to:

* Display special characters using HTML Entities.
  
* Use reserved HTML characters safely.
  
* Embed and control video playback.
  
* Create engaging multimedia web pages.
  
* Improve webpage functionality using HTML5 features.

---

## 📂 Project Structure

```text
HTML-Entities-And-Video/
│
├── index.html
├── sample-video.mp4
└── README.md
```

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)

Web Development Learning Journey 🚀
