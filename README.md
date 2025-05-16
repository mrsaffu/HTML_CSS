# HTML & CSS Learning Practice Repository

Welcome to the **HTML & CSS Learning Practice** repository!  
This repo is a collection of mini-projects, exercises, and reference materials to help you understand and master the fundamentals of web development using **HTML** and **CSS**.

---

## 📘 What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to create and structure content on the web. It provides the basic building blocks of a web page such as headings, paragraphs, images, links, and more.

### 🔑 Important HTML Tags

| Tag           | Description                          |
|---------------|--------------------------------------|
| `<html>`      | Root of an HTML document             |
| `<head>`      | Contains metadata, links, and title  |
| `<title>`     | Sets the title of the page           |
| `<body>`      | Contains visible page content        |
| `<h1>`-`<h6>` | Headings from largest to smallest    |
| `<p>`         | Paragraph                            |
| `<a>`         | Anchor (links)                       |
| `<img>`       | Embeds images                        |
| `<div>`       | Generic container                    |
| `<span>`      | Inline container                     |
| `<ul>`        | Unordered list                       |
| `<ol>`        | Ordered list                         |
| `<li>`        | List item                            |
| `<table>`     | Table                                |
| `<tr>`        | Table row                            |
| `<td>`        | Table data cell                      |
| `<th>`        | Table header cell                    |
| `<form>`      | HTML form                            |
| `<input>`     | Input field                          |
| `<button>`    | Clickable button                     |

---

## 🏷️ Meta Tags

Meta tags are used inside the `<head>` tag to provide metadata about the web page.

```html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Learning HTML and CSS">


## 🧾 What is DOCTYPE in HTML?

The `<!DOCTYPE html>` declaration is used to tell the web browser what version of HTML the document is written in. It must be the **very first line** in an HTML document, before the `<html>` tag.

### ✅ Example:
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Document Title</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
</html>


---

### `4-semantic-tags.md`

```markdown
# 📄 Semantic HTML Tags

Semantic HTML tags clearly describe their meaning in a human- and machine-readable way.

| Tag         | Purpose                                |
|-------------|----------------------------------------|
| `<header>`  | Header section                         |
| `<nav>`     | Navigation links                       |
| `<main>`    | Main content of the document           |
| `<section>` | A section of content                   |
| `<article>` | Self-contained content (e.g., blog)    |
| `<aside>`   | Side content like a sidebar            |
| `<footer>`  | Footer section                         |


# ✏️ HTML Forms

HTML forms are used to collect user input.

```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>


<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>



---

### `7-tables.md`

```markdown
# 📊 HTML Tables

```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
  </tr>
</table>



---

### `8-css.md`

```markdown
# 🎨 What is CSS?

**CSS (Cascading Style Sheets)** is used to style and layout HTML elements — controlling color, spacing, fonts, positioning, and much more.

# 🔍 CSS Selectors

| Selector        | Description                        |
|-----------------|------------------------------------|
| `*`             | Universal selector                 |
| `p`             | All `<p>` tags                     |
| `.class`        | Elements with a specific class     |
| `#id`           | Element with a specific ID         |
| `div > p`       | Direct child selectors             |
| `div p`         | Descendant selectors               |
| `p:hover`       | Pseudo-class                       |


# 🧭 CSS Positioning

| Position   | Description                              |
|------------|------------------------------------------|
| `static`   | Default position                         |
| `relative` | Relative to its normal position          |
| `absolute` | Relative to nearest positioned ancestor  |
| `fixed`    | Fixed relative to the viewport           |
| `sticky`   | Sticky based on scroll position          |
 

 # 🧱 CSS Display

| Value           | Usage                                      |
|-----------------|--------------------------------------------|
| `block`         | Takes full width                           |
| `inline`        | Takes only content width                   |
| `inline-block`  | Like inline, but allows block features     |
| `none`          | Hides the element                          |
| `flex`          | Flexbox layout                             |
| `grid`          | Grid layout                                |


# 🧩 CSS Flexbox

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}



---

### `13-grid.md`

```markdown
# 🧮 CSS Grid

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 10px;
}



---

### `14-colors.md`

```markdown
# 🌈 CSS Colors & Properties

Common CSS properties:

- `color`
- `background-color`
- `border`
- `border-radius`
- `opacity`
- `box-shadow`
- `text-align`
- `font-size`
- `font-family`

Example:

```css
button {
  background-color: #3498db;
  color: white;
  border: none;
  border-radius: 5px;
  padding: 10px 20px;
}



---

### `15-animation.md`

```markdown
# ✨ CSS Animations

## Keyframes

```css
@keyframes fadeIn {
  from { opacity: 0; }
  to { opacity: 1; }
}

.fade {
  animation: fadeIn 2s ease-in;
}


button {
  transition: background-color 0.3s ease;
}



---

### `16-resources.md`

```markdown
# 📌 Useful Resources .

- [MDN Web Docs - HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs - CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [W3Schools](https://www.w3schools.com/)
- [CSS Tricks](https://css-tricks.com/)
- [Flexbox Froggy](https://flexboxfroggy.com/)
- [CSS Grid Garden](https://cssgridgarden.com/)


<!-- readme -->