# HTML Form Controls and Buttons

## 📖 Overview

In this project, I learned various HTML form controls that help collect user input in different ways. These controls make web forms interactive and user-friendly.

This project covers:

* Checkbox
* Radio Button
* Select Dropdown
* Range Slider
* Textarea
* Submit Button
* Reset Button

---

## 📚 Topics Covered

* Checkbox Input
* Radio Button Input
* Multiple Checkboxes
* Select Dropdown Menu
* Range Slider
* Textarea
* Submit Button
* Reset Button

---

# 🔹 Checkbox

Checkboxes allow users to select one or more options.

### Example

```html
<input type="checkbox" id="age">
<label for="age">I am 18+</label>
```

### Features

* Multiple checkboxes can be selected.
* Useful for agreements and multiple-choice selections.

---

# 🔹 Radio Button

Radio buttons allow users to select only one option from a group.

### Example

```html
<input type="radio" name="fruit" id="apple" value="apple">
<label for="apple">Apple</label>

<input type="radio" name="fruit" id="mango" value="mango">
<label for="mango">Mango</label>

<input type="radio" name="fruit" id="banana" value="banana">
<label for="banana">Banana</label>
```

### Features

* Only one option can be selected at a time.
* All radio buttons in a group must have the same `name` attribute.

---

# 🔹 Multiple Checkboxes

Used when users need to select multiple options.

### Example

```html
<input type="checkbox" name="subject" id="english">
<label for="english">English</label>

<input type="checkbox" name="subject" id="math">
<label for="math">Maths</label>
```

### Use Cases

* Subject Selection
* Skills Selection
* Interests Selection

---

# 🔹 Select Dropdown

The `<select>` element creates a dropdown menu.

### Example

```html
<select name="profession" id="profession">
    <option selected>Select your option</option>
    <option value="Stu">Student</option>
    <option value="Dev">Developer</option>
    <option value="Teacher">Teacher</option>
</select>
```

### Features

* Saves space on the page.
* Allows users to choose from predefined options.

---

# 🔹 Range Slider

The range input creates a slider that lets users select a value within a specified range.

### Example

```html
<input
    type="range"
    id="vol"
    min="0"
    max="100"
    step="5"
    value="70">
```

### Attributes

| Attribute | Description     |
| --------- | --------------- |
| min       | Minimum value   |
| max       | Maximum value   |
| step      | Increment value |
| value     | Default value   |

---

# 🔹 Textarea

The textarea element allows users to enter multiple lines of text.

### Example

```html
<textarea
    id="feedback"
    rows="5"
    cols="50"
    placeholder="Write your feedback here.....">
</textarea>
```

### Features

* Supports long text input.
* Commonly used for feedback and comments.

---

# 🔹 Submit Button

The submit button sends form data to the destination specified in the form action.

### Example

```html
<button type="submit">Submit</button>
```

### Purpose

* Submits form data
* Triggers form processing

---

# 🔹 Reset Button

The reset button clears all entered data and restores default values.

### Example

```html
<button type="reset">Reset</button>
```

### Purpose

* Clears form fields
* Resets form inputs

---

# 🎯 Learning Outcomes

After completing this project, I can:

✅ Create interactive HTML forms

✅ Use checkboxes and radio buttons

✅ Create dropdown menus

✅ Implement range sliders

✅ Collect multiline user input using textarea

✅ Submit and reset forms

✅ Build user-friendly web forms

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)

Web Development Learning Journey 🚀
