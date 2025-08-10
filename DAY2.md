# 📚 Summary for First Session in ITI

This document summarizes the basic HTML structure, tags, and attributes introduced in the first ITI web development session.

---

## 🏗 Basic Structure Tags

| **Tag** | **Description** | **Example** |
|---------|----------------|-------------|
| `<!DOCTYPE html>` | Declares that the document is HTML5. No closing tag. | `<!DOCTYPE html>` |
| `<html></html>` | Root tag containing all HTML content. | `<html> ... </html>` |
| `<head></head>` | Contains metadata, title, styles, and links. | `<head> ... </head>` |
| `<title></title>` | Sets the page title (appears in the browser tab). | `<title>My Page</title>` |
| `<body></body>` | Contains the visible content of the page (text, images, etc.). | `<body> ... </body>` |

---

## 📝 Text and Formatting Tags

| **Tag** | **Purpose** | **Example** |
|---------|------------|-------------|
| `<h1>` → `<h6>` | Headings, `<h1>` is the highest priority (only one `<h1>` per page). | `<h1>Main Title</h1>` |
| `<p></p>` | Paragraph text. | `<p>Hello World</p>` |
| `<br>` | Line break (no closing tag). | `Line 1<br>Line 2` |
| `<a></a>` | Creates a clickable hyperlink. | `<a href="https://example.com">Click Me</a>` |
| `<img>` | Displays an image. No closing tag. | `<img src="image.jpg" alt="Description">` |
| `<hr>` | Horizontal rule/line. | `<hr>` |
| `<pre></pre>` | Preformatted text (keeps spaces & line breaks). | `<pre> Text    with    spaces </pre>` |
| `<b></b>` | Bold text. | `<b>Bold</b>` |
| `<strong></strong>` | Important text (SEO-friendly bold). | `<strong>Important</strong>` |
| `<i></i>` | Italic text. | `<i>Italic</i>` |
| `<em></em>` | Emphasized text. | `<em>Emphasis</em>` |
| `<ins></ins>` | Underlined text. | `<ins>Inserted</ins>` |
| `<del></del>` | Strikethrough text. | `<del>Deleted</del>` |
| `<sub></sub>` | Subscript text. | `H<sub>2</sub>O` |
| `<sup></sup>` | Superscript text. | `X<sup>2</sup>` |
| `<mark></mark>` | Highlighted text. | `<mark>Highlighted</mark>` |

---

## ⚙ Attributes

| **Attribute** | **Purpose** | **Example** |
|---------------|------------|-------------|
| `href` | Defines link destination (used with `<a>`). | `<a href="https://example.com">Link</a>` |
| `src` | File source (used with `<img>`, `<script>`, etc.). | `<img src="image.jpg">` |
| `width` | Width of an element (often in `<img>`). | `<img src="image.jpg" width="300">` |
| `height` | Height of an element (often in `<img>`). | `<img src="image.jpg" height="200">` |
| `alt` | Alternative text for images (SEO & accessibility). | `<img src="image.jpg" alt="A Cat">` |
| `style` | Inline CSS styling. | `<p style="color:red;">Red Text</p>` |

---

## 📌 Notes
- Always start with `<!DOCTYPE html>` for HTML5.
- Only one `<h1>` tag should be used per page for SEO.
- Attributes like `width` and `height` can use **px**, **%**, or other CSS units.
- The `style` attribute is for quick styling, but CSS files are preferred for larger projects.

---
