# HTML Tables

## Introduction

HTML tables are used to display data in rows and columns. They help organize information in a structured format, making it easy to read and understand.

Common uses of tables include:

* Student Records
  
* Product Lists
  
* Timetables
  
* Reports
  
* Employee Information

---

# Basic Table Structure

A table is created using the `<table>` element.

## Example

```html
<table>
    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Aman</td>
        <td>24</td>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>22</td>
    </tr>
</table>
```

### Output

| Name  | Age |
| ----- | --- |
| Aman  | 24  |
| Rahul | 22  |

---

# Important Table Tags

| Tag         | Description                 |
| ----------- | --------------------------- |
| `<table>`   | Creates a table             |
| `<tr>`      | Defines a table row         |
| `<th>`      | Defines a table header cell |
| `<td>`      | Defines a table data cell   |
| `<caption>` | Adds a title to the table   |
| `<thead>`   | Groups table header content |
| `<tbody>`   | Groups table body content   |
| `<tfoot>`   | Groups table footer content |

---

# Table with Caption

The `<caption>` element provides a title for the table.

```html
<table border="1">
    <caption>Student Information</caption>

    <tr>
        <th>Name</th>
        <th>Age</th>
    </tr>

    <tr>
        <td>Aman</td>
        <td>24</td>
    </tr>
</table>
```

---

# Table Border

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>

    <tr>
        <td>Aman</td>
        <td>CSE</td>
    </tr>
</table>
```

---

# Colspan Attribute

The `colspan` attribute allows a cell to span multiple columns.

```html
<table border="1">
    <tr>
        <th colspan="2">Student Details</th>
    </tr>

    <tr>
        <td>Name</td>
        <td>Aman</td>
    </tr>
</table>
```

### Result

The heading "Student Details" occupies two columns.

---

# Rowspan Attribute

The `rowspan` attribute allows a cell to span multiple rows.

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Subject</th>
    </tr>

    <tr>
        <td rowspan="2">Aman</td>
        <td>HTML</td>
    </tr>

    <tr>
        <td>CSS</td>
    </tr>
</table>
```

### Result

The name "Aman" occupies two rows.

---

# Semantic Table Structure

HTML provides semantic elements to organize table content into logical sections.

* `<thead>` → Table Header
* `<tbody>` → Table Body
* `<tfoot>` → Table Footer

These elements improve readability, accessibility, and maintainability.

---

# Table Header (`<thead>`)

The `<thead>` element contains the heading rows of a table.

## Example

```html
<thead>
    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Semester</th>
    </tr>
</thead>
```

### Purpose

* Defines column headings.
  
* Improves accessibility.
  
* Makes styling easier.
  
* Provides semantic meaning.

---

# Table Body (`<tbody>`)

The `<tbody>` element contains the main data of the table.

## Example

```html
<tbody>
    <tr>
        <td>Aman</td>
        <td>CSE</td>
        <td>3rd</td>
    </tr>

    <tr>
        <td>Rahul</td>
        <td>ECE</td>
        <td>2nd</td>
    </tr>
</tbody>
```

### Purpose

* Stores actual table data.
  
* Separates content from headers and footers.
  
* Improves code organization.

---

# Table Footer (`<tfoot>`)

The `<tfoot>` element contains summary information or footer content.

## Example

```html
<tfoot>
    <tr>
        <td colspan="3">Total Students: 2</td>
    </tr>
</tfoot>
```

### Purpose

* Displays totals and summaries.
  
* Useful in reports and statistics tables.
  
* Keeps summary information separate from data.

---

# Complete Example

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Tables</title>
</head>
<body>

<table border="1">

    <caption>Student Records</caption>

    <thead>
        <tr>
            <th>Name</th>
            <th>Course</th>
            <th>Semester</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Aman</td>
            <td>CSE</td>
            <td>3rd</td>
        </tr>

        <tr>
            <td>Rahul</td>
            <td>ECE</td>
            <td>2nd</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td colspan="3">Total Students: 2</td>
        </tr>
    </tfoot>

</table>

</body>
</html>
```

---

# Table Structure Visualization

```text
+--------------------------------+
|            THEAD               |
| Name | Course | Semester       |
+--------------------------------+
|            TBODY               |
| Aman | CSE    | 3rd            |
| Rahul| ECE    | 2nd            |
+--------------------------------+
|            TFOOT               |
| Total Students: 2              |
+--------------------------------+
```

---

# Best Practices

✅ Use tables only for tabular data.

✅ Use `<th>` for headings.

✅ Add `<caption>` for accessibility.

✅ Use `<thead>`, `<tbody>`, and `<tfoot>` for better structure.

✅ Keep table data organized and readable.

❌ Do not use tables for webpage layouts.

---

# Summary

HTML tables help organize data in rows and columns.

### Main Elements

* `<table>`
* `<tr>`
* `<th>`
* `<td>`
* `<caption>`
* `<thead>`
* `<tbody>`
* `<tfoot>`

### Attributes

* `colspan`
* `rowspan`

Using semantic table elements creates cleaner, more accessible, and professional HTML code.

---

## 👨‍💻 Author

## **Aman Kumar**

B.Tech CSE (AI & ML)

Web Development Learning Journey 🚀
