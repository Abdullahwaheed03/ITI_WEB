# 📚 HTML Basics – ITI Session 1 Summary

This document summarizes the **first ITI HTML session** covering the essential HTML tags, attributes, and their usage.  
It’s formatted for **GitHub README.md** so it’s clean, easy to read, and reference-friendly.

---

## 1️⃣ Basic HTML Structure

| Tag | Description | Notes |
|-----|-------------|-------|
| `<!DOCTYPE html>` | 📄 Declares that the document is HTML5. | No closing tag required. |
| `<html></html>` | 🌐 Root element of the HTML page. | Contains all page content. |
| `<head></head>` | 🧠 Contains metadata & page settings. | Not visible to the user. |
| `<title></title>` | 🏷 Page title (shown in browser tab). | Placed inside `<head>`. |
| `<body></body>` | 🖋 Contains all visible page content. | Text, images, audio, etc. |

---

## 2️⃣ Common Content Tags

| Tag | Purpose | Example |
|-----|---------|---------|
| `<h1>…</h1>` | 🏆 Main heading (h1-h6 levels). | `<h1>Main Title</h1>` |
| `<p>…</p>` | 📄 Paragraph of text. | `<p>This is text</p>` |
| `<br>` | ↩ Line break. | `<p>Line 1<br>Line 2</p>` |
| `<a href="">…</a>` | 🔗 Hyperlink. | `<a href="https://example.com">Visit</a>` |
| `<img src="">` | 🖼 Image. | `<img src="image.jpg" alt="Description">` |
| `<hr>` | ➖ Horizontal line. | `<hr>` |
| `<pre>…</pre>` | 📜 Preformatted text. | Preserves spaces & line breaks. |

---

## 3️⃣ Text Formatting Tags

| Tag | Purpose | Example |
|-----|---------|---------|
| `<b>…</b>` | 🔠 Bold text. | `<b>Bold</b>` |
| `<strong>…</strong>` | 📢 Important text (bold). | `<strong>Alert!</strong>` |
| `<i>…</i>` | ✏ Italic text. | `<i>Italic</i>` |
| `<em>…</em>` | 🎯 Emphasized text. | `<em>Focus</em>` |
| `<ins>…</ins>` | ✍ Underlined text. | `<ins>Underline</ins>` |
| `<del>…</del>` | ❌ Strikethrough. | `<del>Old</del>` |
| `<sub>…</sub>` | 🔽 Subscript. | `H<sub>2</sub>O` |
| `<sup>…</sup>` | 🔼 Superscript. | `x<sup>2</sup>` |
| `<mark>…</mark>` | 🖍 Highlight text. | `<mark>Important</mark>` |

---

## 4️⃣ HTML Attributes

| Attribute | Purpose | Example |
|-----------|---------|---------|
| `href` | 🔗 URL for links. | `<a href="link.html">Click</a>` |
| `src` | 📂 File path for media. | `<img src="image.jpg">` |
| `width` | 📏 Set width. | `<img width="300">` |
| `height` | 📏 Set height. | `<img height="200">` |
| `alt` | 🦯 Alternative text for accessibility. | `<img alt="Description">` |
| `style` | 🎨 Inline styling (CSS). | `<p style="color:red;">Text</p>` |

---

## 🛠 Notes
- **Basic Structure** = `<!DOCTYPE html>`, `<html>`, `<head>`, `<title>`, `<body>`.
- **Headings**: Use only **one `<h1>`** per page for SEO.
- **Accessibility**: Always add `alt` for images.
- **Separation of concerns**: Use CSS for styling instead of inline `style` when possible.

---

## 📌 Example HTML5 Page

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Page</title>
</head>
<body>
    <h1>Welcome to HTML</h1>
    <p>This is my first paragraph.</p>
    <a href="https://example.com">Visit Example</a>
    <br>
    <img src="image.jpg" alt="Sample Image" width="300">
</body>
</html>
