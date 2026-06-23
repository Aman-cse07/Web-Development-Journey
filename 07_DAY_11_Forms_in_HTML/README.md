# HTML Forms - Basic Input Fields

This repository is a part of my Web Development learning journey where I document my daily progress, practice exercises, and achievements while learning modern web technologies.

---

# 📖 Introduction to HTML Forms

HTML forms are used to collect information from users. They provide various input fields that allow users to enter data such as names, passwords, numbers, dates, and more.

Forms are an essential part of web development and are commonly used in:

* Registration Forms
  
* Login Forms
  
* Contact Forms
  
* Survey Forms
  
* Booking Forms

---

# 📚 Topics Covered

* Form Tag (`<form>`)
  
* Text Input (`type="text"`)
  
* Password Input (`type="password"`)
  
* Number Input (`type="number"`)
  
* Date Input (`type="date"`)
  
* Date & Time Input (`type="datetime-local"`)
  
* Label Tag (`<label>`)
  
* Div Tag (`<div>`)
  
* Placeholder Attribute
  
* Name Attribute
  
* ID Attribute
  
* For Attribute

---

# 🏗️ Complete Example

```html
<form>

    <div>
        <label for="name">Full Name:</label>
        <input
            type="text"
            id="name"
            name="fullname"
            placeholder="Enter your full name">
    </div>

    <br>

    <div>
        <label for="password">Password:</label>
        <input
            type="password"
            id="password"
            name="password"
            placeholder="Enter your password">
    </div>

    <br>

    <div>
        <label for="age">Age:</label>
        <input
            type="number"
            id="age"
            name="age"
            placeholder="Enter your age">
    </div>

    <br>

    <div>
        <label for="dob">Date of Birth:</label>
        <input
            type="date"
            id="dob"
            name="dob">
    </div>

    <br>

    <div>
        <label for="meeting">Meeting Time:</label>
        <input
            type="datetime-local"
            id="meeting"
            name="meeting">
    </div>

</form>
```

---

# 🔹 Text Input

Used to receive text-based information from users.

```html
<input type="text">
```

### Example

```html
<input type="text" placeholder="Enter your name">
```

---

# 🔹 Password Input

Used to enter passwords securely. Characters are hidden while typing.

```html
<input type="password">
```

---

# 🔹 Number Input

Accepts only numeric values.

```html
<input type="number">
```

---

# 🔹 Date Input

Allows users to select a date using a calendar picker.

```html
<input type="date">
```

---

# 🔹 Date and Time Input

Allows users to select both date and time.

```html
<input type="datetime-local">
```

---

# 🔹 Div Tag

The `<div>` tag is used to group related elements together.

### Example

```html
<div>
    <label>Name:</label>
    <input type="text">
</div>
```

### Benefits

* Better organization
  
* Easy CSS styling
  
* Improved readability

---

# 🔹 Label Tag

The `<label>` tag provides a description for an input field.

### Example

```html
<label>Name:</label>
<input type="text">
```

### Benefits

* Improves accessibility
  
* Makes forms more user-friendly

---

# 🔹 Placeholder Attribute

Displays a hint inside the input field.

### Example

```html
<input type="text" placeholder="Enter your full name">
```

---

# 🔹 Name Attribute

The `name` attribute identifies form data when submitted.

### Example

```html
<input type="text" name="fullname">
```

### Purpose

* Sends data to the server
  
* Identifies form fields

---

# 🔹 ID Attribute

The `id` attribute uniquely identifies an HTML element.

### Example

```html
<input type="text" id="name">
```

### Purpose

* Used in CSS
  
* Used in JavaScript
  
* Connects labels with input fields

---

# 🔹 For Attribute

The `for` attribute is used inside a label and should match the input's `id`.

### Example

```html
<label for="name">Full Name</label>
<input type="text" id="name">
```

### Benefit

Clicking on the label automatically focuses the corresponding input field.

---

# 🎯 Learning Outcomes

After completing this topic, I can:

✅ Create HTML forms

✅ Use text, password, number, date, and datetime inputs

✅ Connect labels with input fields

✅ Use placeholder text effectively

✅ Understand the purpose of `name`, `id`, and `for` attributes

✅ Organize form elements using `<div>`

---

# 🚀 Web Development Journey

This repository contains my daily achievements and progress in Web Development. My goal is to learn Web Development from beginner to advanced level and build real-world projects while documenting my learning journey on GitHub.

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)
Web Development Learning Journey 🚀
