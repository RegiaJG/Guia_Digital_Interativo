# Genesis Protocol — Interactive Digital Guide
> From static e-book to navigable reading experience, directly in the browser.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/RegiaJG/Guia_Digital_Interativo)

---

## About the Project

The **Genesis Protocol** is a technical-executive guide for Artificial Intelligence agent architecture — originally developed as a PDF e-book. This repository presents its version as an **Interactive Digital Guide**: a self-contained HTML file that runs directly in the browser, with no installation, no external dependencies and no PDF reader required.

The content remains entirely the same. The reading experience is completely different.

---

## Features

- **Side navigation** with full module index — access any page directly
- **Previous / Next buttons** on all 34 pages
- **Reading progress bar** at the top
- **Keyboard navigation** — right/left or up/down arrow keys
- **Swipe support** on touch devices
- **Zero dependencies** — a single self-contained `.html` file
- **Responsive design** — works on desktop and mobile

---

## Content Structure

| Module | Topic | Pages |
|--------|-------|-------|
| 01 | The Introduction — The End of Generic Prompting | 04 – 09 |
| 02 | The Operational Soul — System Prompt Engineering | 10 – 13 |
| 03 | The Library — RAG and the Hierarchy of Truth | 14 – 16 |
| 04 | Memory & Cost — Tokens and Context Window | 17 – 19 |
| 05 | The Tools — From Reasoning to Execution | 20 – 23 |
| 06 | The First Agent — Practical Tutorial | 24 – 29 |
| — | Closing — The New Standard | 30 – 34 |

---

## Deploy

### Vercel (recommended)

Click the button above or follow these steps:

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy from the project directory
vercel
```

Vercel will automatically detect the static site and serve `protocolo-genese-executivo.html` at the root URL. No build step required.

### Other static hosts

This project works on any static hosting platform (Netlify, GitHub Pages, Cloudflare Pages). Just upload the files — `protocolo-genese-executivo.html` and `vercel.json` (if applicable) — and configure the root redirect if needed.

---

## How to Use

**Online:** Access the deployed URL directly in any modern browser.

**Local:**

```bash
# Clone the repository
git clone https://github.com/RegiaJG/Guia_Digital_Interativo.git

# Open the file in your browser
open protocolo-genese-executivo.html
```

Or simply download the `.html` file and open it with any modern browser.

---

## Technologies

This project is intentionally minimalist — built with web fundamentals, no frameworks, no build step.

- **HTML5** — structure and content
- **CSS3** — layout, typography and animations
- **Vanilla JavaScript** — navigation, swipe and state logic
- **Google Fonts** — Cormorant Garamond, Outfit, DM Mono

---

## Design Decision

The format was migrated from PDF to HTML for practical and strategic reasons:

- PDF depends on an external reader; HTML opens on any device with a single click
- PDF has no state — HTML maintains progress, animations and interactivity
- PDF is a download — HTML can be hosted and accessed via direct link
- PDF is static — HTML allows future improvements without generating a new file version

---

## Author

Developed by **[Lucas Costa Nogueira](https://github.com/RegiaJG)**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Lucas%20Costa%20Nogueira-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucas-nogueira-017b12191)
[![GitHub](https://img.shields.io/badge/GitHub-RegiaJG-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RegiaJG)

---

## License

© 2025 · Genesis Protocol · All rights reserved.

This material is protected against reproduction, transmission or sharing without express authorization. See the full legal notice on page 02 of the guide.
