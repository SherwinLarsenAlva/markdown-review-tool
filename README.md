# 📝 Markdown Review Tool

A standalone, zero-dependency web-based tool for reviewing and annotating Markdown documents. Built as a single HTML file — just open it in your browser.

![Markdown Review Tool](screenshot.png)

## ✨ Features

| Feature | Details |
|---|---|
| **File Loading** | Drag-and-drop or browse for `.md` files |
| **6 Comment Types** | 💬 Comment · 📋 Todo · ✨ Improve · ❓ Clarify · 🔍 Check · 🔀 Restructure |
| **Section Guide** | Toggle-able banners showing what each academic section should contain |
| **Comment Sidebar** | Filter by type, click to jump, edit, delete |
| **Export** | Save annotated `.md` with embedded comment tags via native Save dialog |
| **Import** | Re-import annotated files to restore comments |
| **Keyboard** | `Ctrl+Enter` to submit comments |

## 🚀 Quick Start

1. Download or clone this repository
2. Open `index.html` in your browser (Chrome recommended)
3. Load any `.md` file
4. Click on sections to add review comments
5. Export the annotated file when done

## 📐 Section Guide

The built-in Section Guide recognizes 30+ academic section types (Abstract, Introduction, Methodology, Related Work, Evaluation, Conclusion, etc.) and displays:
- **Purpose** — what the section should accomplish
- **Checklist** — specific items to include

Toggle it with the **📐 Section Guide** button in the toolbar.

## 📤 Export Format

Comments are embedded as HTML comments above annotated sections:

```markdown
<!-- [TODO: Add citations for NIST CSF 2.0] -->
# ABSTRACT

<!-- [IMPROVE: Use more formal academic language] -->
The system processes data...

<!-- [CHECK: Verify this claim is accurate] -->
CVSS scores are commonly used...
```

## 🛠️ Technology

- **Zero dependencies** — pure HTML, CSS, and JavaScript
- **No build step** — single file, works offline
- **File System Access API** — native Save As dialog in Chrome
- **Dark glassmorphism design** — premium aesthetic with Inter font

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.
