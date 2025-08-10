# 📚 Summary for Content of First Session in ITI — Web Development

This document summarizes the **basic HTML structure**, common tags, and attributes introduced in the **first session** of ITI Web Development.

---

## 1️⃣ **Basic HTML Tags**

| **Tag** | **Description** |
|---------|-----------------|
| `<!DOCTYPE html>` | 📝 *Informs the browser that you’re using **HTML5**. No closing tag is required.* |
| `<html></html>` | 🌐 **Root tag** of your project. Contains all content. |
| `<head></head>` | 📄 **Header section** of the page. |
| `<title></title>` | 🏷️ First tag inside `<head>`. Sets the **page title**. |
| `<body></body>` | 📦 Main container for all visible content (**text, images, audio, etc.**). |
| `<h1></h1>` → `<h6></h6>` | 🔠 Headings. `<h1>` is the highest priority. **Only one `<h1>` per page.** |
| `<p></p>` | 📃 Paragraph tag — displays text inside `<body>`. |
| `<br>` | ↩ Line break — moves content to a new line. |
| `<a></a>` | 🔗 Anchor tag — creates clickable links. |
| `<img>` | 🖼️ Displays images. |
| `<hr>` | ➖ Horizontal line separator. |
| `<pre></pre>` | ✍ Preformatted text — preserves spaces & line breaks. |
| `<b></b>` | **Bold** text. |
| `<strong></strong>` | **Important** text — adds semantic meaning. |
| `<i></i>` | *Italic* text. |
| `<em></em>` | *Emphasized* text — also semantic. |
| `<ins></ins>` | Underlined text. |
| `<del></del>` | ~~Crossed-out text~~. |
| `<sub></sub>` | Subscript text (e.g., `H₂O`). |
| `<sup></sup>` | Superscript text (e.g., `x²`). |
| `<mark></mark>` | <mark>Highlighted text</mark>. |

---

## 2️⃣ **HTML Attributes**

| **Attribute** | **Description** |
|---------------|-----------------|
| `href` | 🔗 Adds a link to an element (commonly used with `<a>`). |
| `src` | 📂 Specifies the source of a file (e.g., for `<img>`). |
| `width` | 📏 Defines image width. |
| `height` | 📏 Defines image height. |
| `alt` | 🆘 Alternative text for images — helps with SEO & accessibility. |
| `style` | 🎨 Inline CSS styling (color, background, margin, etc.). |

---

## 📌 **Notes**
- The above tags form the **basic structure** of any HTML page.
- Some tags add **semantic meaning** (`<strong>`, `<em>`), which improves **SEO** and accessibility.
- Attributes can **customize behavior** or **style** of elements.
- Use `<style>` attribute for quick inline changes, but for larger projects prefer **CSS files**.

---

## 📜 **Example Basic HTML Structure**

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Webpage</title>
</head>
<body>
  <h1>Hello, ITI!</h1>
  <p>This is my first webpage.</p>
  <a href="https://iti.gov.eg">Visit ITI</a>
  <br>
  <img src="image.jpg" alt="Sample Image" width="200" height="150">
</body>
</html>
