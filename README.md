# Mastering HTML

**Deep-Diving into HTML** and grasping the core concepts and functionalities of this powerful markup language. While HTML itself isn't that complex, we will explore both basic and advanced concepts to solidify our understanding.

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

---

### 🔹 **Forms**

Forms are sections of a document that contain interactive controls for submitting information. A form has two important attributes:

- `action`: Specifies the URL where the form data will be sent.
- `method`: Specifies the HTTP method (GET or POST) used to send form data.

---

### 🔹 **Label**

The `<label>` element associates text with a specific form control, improving accessibility by helping screen readers interpret form controls. It uses the `for` attribute to link with a specific form control.

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

### 🔹 **Select**

The `<select>`element is a dropdown list that allows users to choose one or more options where each option is represented by `<option>` tag, `multiple` attribute is used to select multiple options.

### 🔹 **Button**

The `<button>`element is used to create clikable buttons. It can be used to submit forms or trigger JavaScript actions. It uses `type` attribute to specifies the button function.

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
