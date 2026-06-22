# HTML Video Tag

## 📖 Introduction

This project demonstrates the use of the HTML5 `<video>` tag. The video tag allows developers to embed videos directly into web pages without using external plugins.

It provides several built-in attributes to control video playback, including `controls`, `autoplay`, `loop`, and `muted`.

---

## 🎯 Objectives

* Learn how to embed videos in HTML.
  
* Understand the structure of the `<video>` tag.
  
* Learn about the `controls` attribute.
  
* Learn about the `autoplay` attribute.
  
* Create a webpage with playable video content.

---

## 📌 HTML Video Tag

The `<video>` tag is used to display video files on a webpage.

### Basic Syntax

```html
<video src="video.mp4"></video>
```

### Recommended Syntax

```html
<video width="600" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

---

## 📌 Controls Attribute

The `controls` attribute displays built-in video controls to the user.

### Example

```html
<video width="600" controls>
    <source src="video.mp4" type="video/mp4">
</video>
```

### Features Provided by Controls

* ▶️ Play Button
  
* ⏸️ Pause Button
  
* 🔊 Volume Control
  
* ⏩ Seek/Progress Bar
  
* ⚙️ Playback Options
  
* ⛶ Fullscreen Mode

### Purpose

Without the `controls` attribute, users cannot easily play, pause, or adjust the video.

---

## 📌 Autoplay Attribute

The `autoplay` attribute starts the video automatically when the webpage loads.

### Example

```html
<video width="600" autoplay>
    <source src="video.mp4" type="video/mp4">
</video>
```

### Purpose

* Automatically starts video playback.
  
* Useful for banners, advertisements, and presentations.

### Important Note

Most modern browsers block autoplay videos with sound for a better user experience.

To ensure autoplay works, use:

```html
<video width="600" autoplay muted>
    <source src="video.mp4" type="video/mp4">
</video>
```

The `muted` attribute allows the browser to autoplay the video without sound.

---

## 📌 Controls + Autoplay Example

```html
<video width="600" controls autoplay muted>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
```

This video:

* Starts automatically.
  
* Shows playback controls.
  
* Plays without sound initially.

---

## 💻 Complete Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>HTML Video Tag</title>
</head>
<body>

    <h1>Learning HTML Video Tag</h1>

    <video width="600" controls autoplay muted>
        <source src="sample-video.mp4" type="video/mp4">
        Your browser does not support the video tag.
    </video>

</body>
</html>
```

---

## ✨ Highlights

* Learned how to embed videos using the `<video>` tag.
  
* Used the `<source>` tag to specify video files.
  
* Explored the `controls` attribute for user interaction.
  
* Explored the `autoplay` attribute for automatic playback.
  
* Learned why `muted` is often required with autoplay.
  
* Built a multimedia webpage using HTML5.

---

## 🛠 Technologies Used

* HTML5

---

## 📚 Learning Outcomes

After completing this project, you will be able to:

* Add videos to webpages.
  
* Control video playback using HTML attributes.
  
* Understand browser autoplay restrictions.
  
* Create interactive multimedia content.
  
* Improve user experience with video elements.

---

## 📂 Project Structure

```text
HTML-Video-Tag/
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
