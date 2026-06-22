# Semantic Markup in HTML

## Introduction

Semantic HTML uses elements that clearly describe their meaning and purpose to both browsers and developers. These elements help create a well-structured, accessible, and SEO-friendly webpage.

---

## What is Semantic Markup?

Semantic markup refers to the use of HTML tags that convey the meaning of the content they contain.

### Example

```html
<header>
    <h1>My Website</h1>
</header>
```

The `<header>` tag clearly indicates that the content inside it is the header section of the webpage.

---

## Benefits of Semantic HTML

* Improves code readability
  
* Enhances website accessibility
  
* Helps search engines understand page structure
  
* Improves SEO (Search Engine Optimization)
  
* Makes maintenance easier
  
* Provides better user experience

---

## Common Semantic Elements

| Element        | Description                               |
| -------------- | ----------------------------------------- |
| `<header>`     | Defines the header of a page or section   |
| `<nav>`        | Contains navigation links                 |
| `<main>`       | Represents the main content               |
| `<section>`    | Groups related content                    |
| `<article>`    | Represents independent content            |
| `<aside>`      | Contains sidebar or supplementary content |
| `<footer>`     | Defines the footer section                |
| `<figure>`     | Represents media content                  |
| `<figcaption>` | Provides a caption for a figure           |
| `<details>`    | Creates expandable content                |
| `<summary>`    | Defines a heading for details             |

---

## Example of Semantic HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Semantic HTML Example</title>
</head>
<body>

    <header>
        <h1>My Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Contact</a>
    </nav>

    <main>
        <section>
            <h2>About Us</h2>
            <p>Welcome to our website.</p>
        </section>

        <article>
            <h2>Blog Post</h2>
            <p>This is an article.</p>
        </article>
    </main>

    <footer>
        <p>&copy; 2026 My Website</p>
    </footer>

</body>
</html>
```

---

# Semantic vs Non-Semantic Elements

## Semantic Elements

Semantic elements clearly define the purpose of their content.

### Examples

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

### Advantages

* Meaningful structure
  
* Better accessibility
  
* Improved SEO(SEARCH ENGINE OPTIMIZATION)
  
* Easy to understand

---

## Non-Semantic Elements

Non-semantic elements do not describe the content they contain.

### Examples

```html
<div>
<span>
```

These tags are mainly used for styling and layout purposes.

### Example

```html
<div class="header">
    <h1>My Website</h1>
</div>
```

The browser cannot determine that this `div` represents a header section.

---

## Comparison Table

| Semantic Elements                         | Non-Semantic Elements           |
| ----------------------------------------- | ------------------------------- |
| Describe content meaning                  | Do not describe content meaning |
| Better for SEO                            | Limited SEO benefits            |
| Improve accessibility                     | Less accessible                 |
| Easier to understand                      | Require additional context      |
| Examples: `<header>`, `<nav>`, `<footer>` | Examples: `<div>`, `<span>`     |

---

## Best Practice

Use semantic elements whenever possible and use non-semantic elements (`div`, `span`) only when no suitable semantic tag exists.

---

## Conclusion

Semantic HTML helps create structured, accessible, and search-engine-friendly web pages. Understanding the difference between semantic and non-semantic elements is essential for modern web development.
