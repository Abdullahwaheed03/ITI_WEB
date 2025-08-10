# 📚 ITI – First Session Summary: HTML Basics

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

---

## ✅ 1. HTML Tags

### 🏗 Basic Structure Tags
| Tag | Description |
|-----|-------------|
| `<!DOCTYPE html>` | ✅ First tag in the document. Declares HTML5 and has no closing tag. |
| `<html> ... </html>` | ✅ Root element containing all content. |
| `<head> ... </head>` | ✅ Contains page metadata, title, styles, and scripts. |
| `<title> ... </title>` | ✅ Page title shown in the browser tab (**inside `<head>`**). |
| `<body> ... </body>` | ✅ Contains all visible page content (text, images, videos, etc.). |

---

### 📄 Headings & Text
| Tag | Description |
|-----|-------------|
| `<h1> ... </h1>` | ✅ Main heading of the page (**only one `<h1>` allowed per page** ❌ duplicate). Subheadings: `<h2>` → `<h6>`. |
| `<p> ... </p>` | ✅ Paragraph of text (inside `<body>`). |
| `<br>` | ✅ Line break (no closing tag). |
| `<hr>` | ✅ Horizontal rule separator (no closing tag). |
| `<pre> ... </pre>` | ✅ Preformatted text (preserves spaces and line breaks). |
| `<b> ... </b>` | ✅ Bold text (visual only). |
| `<strong> ... </strong>` | ✅ Important text (semantic + bold). |
| `<i> ... </i>` | ✅ Italic text (visual only). |
| `<em> ... </em>` | ✅ Emphasized text (semantic + italic). |
| `<ins> ... </ins>` | ✅ Underlined inserted text. |
| `<del> ... </del>` | ✅ Strikethrough deleted text. |
| `<sub> ... </sub>` | ✅ Subscript text (e.g., `H₂O`). |
| `<sup> ... </sup>` | ✅ Superscript text (e.g., `x²`). |

---

### 🔗 Links & Media
| Tag | Description |
|-----|-------------|
| `<a href="..."> ... </a>` | ✅ Anchor tag – clickable link. |
| `<img src="..." alt="...">` | ✅ Displays an image. |

---

## ⚙ 2. HTML Attributes

| Attribute | Used With | Description |
|-----------|-----------|-------------|
| `href` | `<a>` | ✅ Link destination URL. |
| `src` | `<img>`, `<script>`, `<audio>`, `<video>` | ✅ File source path. |
| `width` | `<img>`, `<video>` | ✅ Width in pixels or %. |
| `height` | `<img>`, `<video>` | ✅ Height in pixels or %. |
| `alt` | `<img>` | ✅ Alternative text (for accessibility & SEO). |

---

## 💻 Example Basic HTML Page

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is my first paragraph.</p>

    <img src="image.jpg" alt="Sample Image" width="300" height="200">
    <br>
    
    <a href="https://example.com">Visit Example</a>
    <hr>
    
    <p>H<sub>2</sub>O is water, and E = mc<sup>2</sup> is Einstein's equation.</p>
</body>
</html>
