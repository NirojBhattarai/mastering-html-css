# Mastering HTML and CSS

**Deep-Diving into HTML and CSS** and grasping the core concepts and functionalities of this powerful markup language and Style Sheet Language. While HTML and CSS itself isn't that complex, we will explore both basic and advanced concepts to solidify our understanding.

## HTML: HyperText Markup Language

HTML is the backbone of the web, structuring content for web browsers to interpret. This repository will serve as a log of my learning process, from foundational concepts to advanced features.

---

## Key Concepts

### 🔹 **Metadata**

Metadata is a set of data that describes and provides information about other data. In HTML, it plays an important role in the SEO (Search Engine Optimization) of a website. It tells search engines about the data on a website, which ultimately helps to rank our content on Google or other similar search engines.

- Metadata is always placed inside the `<head>` element of an HTML page.
- Typically used for specifying:
  - Character set
  - Page description
  - Keywords
  - Author of the document
  - Viewport settings

---

### 🔹 **What is Emmet?**

Emmet is a toolkit for text editors that allows high-speed coding and editing through abbreviations and shortcuts. It is supported in most modern code editors such as Visual Studio Code, Sublime Text, Atom, etc.

#### Use Cases of Emmet:

- **Creation of boilerplate code:**

  > Example: Typing `html:5` generates boilerplate code for HTML version 5.

- **Generation of nested elements:**

  > Example: Typing `div>ul>li*3` creates a `div` consisting of an unordered list with three list items.

- **Adding IDs and Classes:**

  > Example: Typing `div#container>header.page-header` creates a `div` with the `id="container"`, holding a `header` element with the class `page-header`.

- **Creating Multiple Instances of the Same Element:**

  > Example: Typing `ul>li.item$*3` creates an unordered list with three list items, having classes respectively named `item1`, `item2`, and `item3`.

---

### 🔹 **What are Plug-ins?**

A plug-in is software that adds extra features or functions to a host program without altering the host program itself.

---

### 🔹 **Heading**

HTML defines six levels of headings: `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, and `<h6>`. Headings are ranked in order of importance, with `<h1>` considered the most important (usually the title).

- Best practice: Only one `<h1>` per HTML document, as multiple `<h1>` tags can confuse search engines and screen readers. They rely on the hierarchy of headings to determine the structure of the page.

---

### 🔹 **Inline Element**

An inline element displays inline, meaning it does not force text or elements after it to start on a new line.

#### Common Inline Elements:

- `<img>`
- `<a>` (anchor tag)
- `<strong>`
- `<em>`
- `<b>`
- `<span>`

---

### 🔹 **Block Element**

A block element takes up the full width available and starts on a new line by default, stacking vertically down the page.

#### Common Block Elements:

- `<p>`
- `<ol>`
- `<ul>`
- `<dl>`
- All heading tags (`<h1>` to `<h6>`)
- `<div>`
- `<article>`
- `<section>`

> **Note:** HTML5 introduces an exception where block-level elements can now be wrapped inside a link.

---

### 🔹 **Tables**

Table elements represent tabular data, which is two-dimensional, consisting of rows and columns of cells. The table is defined using the `<table>` tag. Rows are defined with `<tr>`, and columns are defined using `<th>` for headers and `<td>` for data cells. The main body of the table is enclosed within the `<tbody>` element, which helps the browser create the intended table structure.

Example:

```html
<table>
  <thead>
    <tr>
      <th>Header 1</th>
      <th>Header 2</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Data 1</td>
      <td>Data 2</td>
    </tr>
    <tr>
      <td>Data 3</td>
      <td>Data 4</td>
    </tr>
  </tbody>
</table>
```

---

### 🔹 **Forms**

Forms are sections of a document that contain interactive controls for submitting information. A form has two important attributes:

- `action`: Specifies the URL where the form data will be sent.
- `method`: Specifies the HTTP method (GET or POST) used to send form data.

Example:

```html
<form action="/submit" method="POST">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" />
  <input type="submit" value="Submit" />
</form>
```

---

### 🔹 **Label**

The `<label>` element associates text with a specific form control, improving accessibility by helping screen readers interpret form controls. It uses the `for` attribute to link with a specific form control.

Example:

```html
<label for="email">Email:</label> <input type="email" id="email" name="email" />
```

---

### 🔹 **Input**

The `<input>` element allows users to enter data in various ways, depending on the `type` attribute.

#### Common Input Types:

- `text`: Allows single-line text input.
- `password`: Allows text input with masked characters.
- `email`: Input field for email addresses.
- `checkbox`: Allows selection of multiple options.
- `radio`: Allows selection of one option from a group.
- `submit`: Allows submission of the form data.

Example:

```html
<input type="text" placeholder="Enter your name" />
<input type="checkbox" id="subscribe" name="subscribe" />
<label for="subscribe">Subscribe to newsletter</label>
```

---

### 🔹 **Select**

The `<select>`element is a dropdown list that allows users to choose one or more options where each option is represented by `<option>` tag, `multiple` attribute is used to select multiple options.

Example:

```html
<select multiple>
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
</select>
```

---

### 🔹 **Button**

The `<button>`element is used to create clikable buttons. It can be used to submit forms or trigger JavaScript actions. It uses `type` attribute to specifies the button function.

Example:

```html
<button type="button">Click Me</button>
```

---

### 🔹 **Semantic Tags**

HTML Semantic Tags are elements that give both the browser and developers better insight into the structure and content of web page.

#### Common HTML Semantic Tags:

- `<header>`: Represents introductory part and usually contains navigation links or headings.
- `<nav>`: Defines section of navigation links.
- `<section>`: Represent distinct group of contents usually with heading.
- `<article>`: Contains independent, self-contained content like blog post or news article.
- `<aside>`: Used for content that is related to the main content but placed in a sidebar or as a extra content.
- `<footer>`: Defines the footer for a page or section, typically containing metadata, trademark logo, copyright info, or links.
- `<figure>` and `<figurecaption>`: Used for a figure with a caption.
- `<address>`: Contains information related to location or address.
- `<time>`: Represent a specific time or date.

---

### 🔹 **Multimedia Element**

Multimedia elements in HTML are elements used to include and handle different types of media, such as `<audio>`, `<video>`, and `<img>`, within web pages. These elements enhance the user experience by allowing content creators to embed rich media like pictures, music, and videos.

#### Types of Multimedia Elements in HTML:

- `<img>`: Embeds an image into the web page.
- `<audio>`: Embeds an audio file with controls like play, pause, etc.
- `<video>`: Embeds a video file with optional controls.
- `<canvas>`: A drawable region, useful for rendering shapes, graphs, or animations.
- `<svg>`: Embeds SVG graphics within an HTML document.
- `<embed>`: Used for embedding external content (like Flash, PDFs, etc.) into a webpage.
- `<object>`: Embeds external objects (including multimedia and other documents).
- `<iframe>`: Used to embed external web content such as videos or other pages.

---

### 🔹 **ARIA Elements**

ARIA (Accessible Rich Internet Applications) elements in HTML are attributes that help improve the accessibility of web content, especially for users who rely on assistive technologies such as screen readers. These attributes provide additional information about the structure, behavior, and functionality of web elements that might not be easily understood by such tools.

#### **ARIA Roles**

ARIA Roles defines what an element is or how it behaves. For example button, alert, navigation, etc. The role helps assistive technologies understand the purpose of the element.

##### Common ARIA Roles:

- `role="button"`: It indicates that an elementb behaves like a button.
- `role="alert"`: Marks an element as an important alert that needs immediate attention.
- `role="main"`: Defines the main content of a document.
- `role="navigation"`: Defines a group of navigational links.

Example:

```html
<div role="alert">Your session is about to expire!</div>
```

---

## CSS: Cascading Style Sheet

Cascading Style Sheets is a style sheet language used for specifying the presentation and styling of a document written in a markup language such as HTML or XML.

--

## Key Concepts

### 🔹 **CSS Selectors**

CSS Selectors are used to target the HTML elements on our webpages that we want to style.

#### Common Type of CSS Selectors:

**Universal Selector:**

Universal Selector selects all elements.

Example:

```css
* {
  margin: 0;
  padding: 0;
}
```

---

**Type Selectors:**

The CSS type selector matches elements by node name. In other words, it selects all elements of the given type within a document.

Example:

```css
p {
  font-size: 16px;
}
```

---

**Class Selector:**

Selects a name with specified class.

Example:

```css
.btn {
  background-color: blue;
  color: white;
}
```

---

**Id Selector:**

Selects a single element with a specified ID.

Example:

```css
#header {
  background-color: gray;
}
```

---

**Atribute Selector:**

Attribute selectors allows us to select elements based on their attributes.

Example:

```css
input[type="text"] {
  border: 1px solid black;
}
```

---

**Descendant Selector:**

Selects all elements that are descendants of a specified element.

Example:

```css
div p {
  color: red;
}
```

---

**Child Selector**

Selects all elements that are direct children of a specified element.

Example:

```css
ul > li {
  list-style-type: square;
}
```

---

**Adjacent Sibling Selector**

Selects an element that is immediately preceded by a specified element.

Example:

```css
h1 + p {
  margin-top: 0;
}
```

---

**General Sibling Selector**

Selects all elements that are siblings of a specified element.

Example:

```css
h1 ~ p {
  color: green;
}
```

---

**Pseudo-Classes**

Pseudo-classes are used to define the special state of an element.

Example:

```css
a:hover {
  color: red;
}
```

---

**Pseudo-Elements**

Pseudo-elements are used to style a specific part of an element.

Example:

```css
p::first-line {
  font-weight: bold;
}
```

---
