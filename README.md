# 🗺️ STAK Digital

**English** · [Português](README.pt-BR.md)

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)]()
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)]()
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![Website](https://img.shields.io/badge/Live-stakdigital.com.br-185FA5?style=for-the-badge)](https://stakdigital.com.br)

Landing page for **STAK Digital**, a local SEO and Google Business Profile agency.
Live at [stakdigital.com.br](https://stakdigital.com.br).

## 🚀 Features

- Single-page site with services, target audience (local businesses and partner agencies),
  differentials and FAQ
- Free diagnosis form and WhatsApp call to action
- **AI search ready:** an `llms.txt` file describes the business for LLM-based search engines, and
  `robots.txt` allows crawling
- No build step and no dependencies besides Google Fonts and Font Awesome via CDN

## 🎨 Visual Identity

| Color | Value |
| --- | --- |
| Primary blue | `#185FA5` |
| Growth green | `#1D9E75` |
| Neutral graphite | `#2C2C2A` |
| Light blue (background) | `#E6F1FB` |
| WhatsApp green | `#25D366` |

## ⚙️ Running Locally

No server needed: open the file in the browser.

```bash
xdg-open index.html   # Linux
open index.html       # macOS
```

## 📂 Project Structure

```text
├── index.html        # the whole page (markup, styles and scripts)
├── images/           # logos and brand assets
├── faq-answers.md    # full FAQ answers
├── llms.txt          # business description for LLM-based search
└── robots.txt
```
