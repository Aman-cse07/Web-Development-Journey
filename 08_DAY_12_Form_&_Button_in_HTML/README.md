# HTML Forms - Submit Button, Reset Button & Search Forms

## 📖 Overview

In this project, I learned how to create HTML forms using different input fields and buttons. I also learned how to send user input directly to Google Search and YouTube Search using form actions and query parameters.

---

## 📚 Topics Covered

* HTML Form (`<form>`)
* Submit Button (`type="submit"`)
* Reset Button (`type="reset"`)
* Text Input (`type="text"`)
* Password Input (`type="password"`)
* Number Input (`type="number"`)
* Google Search Form
* YouTube Search Form
* Form Action Attribute
* Name Attribute

---

## 🏗️ Basic Form Example

```html id="ttv14c"
<form action="/action">

    <label for="username">Username:</label>
    <input type="text" id="username" placeholder="Enter Username">

    <label for="password">Password:</label>
    <input type="password" id="password" placeholder="Enter Password">

    <label for="age">Age:</label>
    <input type="number" id="age" placeholder="Enter Age">

    <button type="submit">Submit</button>
    <button type="reset">Reset</button>

</form>
```

---

# 🔹 Submit Button

The Submit button sends form data to the location specified in the `action` attribute of the form.

### Syntax

```html id="r57wpb"
<button type="submit">Submit</button>
```

### Purpose

* Sends user data
* Triggers form submission
* Executes the action defined in the form

---

# 🔹 Reset Button

The Reset button clears all entered form data and restores the default values.

### Syntax

```html id="hdbiv0"
<button type="reset">Reset</button>
```

### Purpose

* Clears input fields
* Restores default form values

---

# 🔹 Google Search Form

HTML forms can be used to perform searches directly on Google.

### Example

```html id="96m4kz"
<form action="https://www.google.com/search">
    <input type="text" name="q" placeholder="Search Here...">
    <button type="submit">Search Google</button>
</form>
```

### Explanation

| Attribute     | Purpose                         |
| ------------- | ------------------------------- |
| action        | Sends data to Google Search     |
| name="q"      | Google's search query parameter |
| submit button | Starts the search               |

### How It Works

If the user enters:

```text id="o89l4g"
HTML Forms
```

The browser opens:

```text id="mz19ch"
https://www.google.com/search?q=HTML+Forms
```

---

# 🔹 YouTube Search Form

HTML forms can also be used to search videos directly on YouTube.

### Example

```html id="j6x5y9"
<form action="https://www.youtube.com/results">
    <input type="text"
           name="search_query"
           placeholder="Search Here...">

    <button type="submit">
        Search YouTube
    </button>
</form>
```

### Explanation

| Attribute           | Purpose                    |
| ------------------- | -------------------------- |
| action              | Sends data to YouTube      |
| name="search_query" | YouTube's search parameter |
| submit button       | Starts the search          |

### How It Works

If the user enters:

```text id="j1d0d1"
Web Development Tutorial
```

The browser opens:

```text id="6epgpt"
https://www.youtube.com/results?search_query=Web+Development+Tutorial
```

---

# 🔹 Action Attribute

The `action` attribute specifies where the form data should be sent after submission.

### Example

```html id="w1ww8t"
<form action="https://www.google.com/search">
```

---

# 🔹 Name Attribute

The `name` attribute identifies form data when it is submitted.

### Examples

Google:

```html id="n4kncx"
<input type="text" name="q">
```

YouTube:

```html id="rmq4km"
<input type="text" name="search_query">
```

### Importance

Without the correct `name` attribute, Google and YouTube cannot understand what the user wants to search.

---

# 🎯 Learning Outcomes

After completing this project, I can:

✅ Create HTML forms

✅ Use Submit and Reset buttons

✅ Send user input to external websites

✅ Create a Google Search Form

✅ Create a YouTube Search Form

✅ Understand the use of `action` and `name` attributes

✅ Work with real-world form functionality

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)
Web Development Learning Journey 🚀

