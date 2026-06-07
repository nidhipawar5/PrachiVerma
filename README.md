# Prachi Verma — Portfolio Website

A professional portfolio site for **Prachi Verma** — Social Media Manager, Content Strategist & HR Communications Professional.

## 🚀 Deploying to GitHub Pages

1. **Create a new GitHub repository** (e.g. `prachi-portfolio` or `prachiverma.github.io`)

2. **Upload all files** maintaining this exact folder structure:
   ```
   /
   ├── index.html
   ├── assets/
   │   ├── css/
   │   │   └── style.css
   │   └── js/
   │       └── main.js
   └── README.md
   ```

3. **Go to repository Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`
   - Click **Save**

4. Your site will be live at:
   `https://yourusername.github.io/prachi-portfolio/`
   or
   `https://prachiverma.github.io/` (if repo named `yourusername.github.io`)

---

## ✏️ What to Update

Search for `#placeholder` in `index.html` and replace with real links:

| Placeholder | Replace with |
|---|---|
| `#placeholder-linkedin` | Your LinkedIn URL |
| `#placeholder-instagram` | Your Instagram URL |
| `#placeholder-twitter` | Your Twitter/X URL |
| `#placeholder-case-study-1` | Link to first project |
| `#placeholder-case-study-2` | Link to second project |
| `#placeholder-case-study-3` | Link to third project |
| `#placeholder-case-study-4` | Link to fourth project |
| `#placeholder-portfolio-link` | Full portfolio / Notion / Behance |

### Resume Download
- Add your resume PDF as `Prachi_Verma_Resume.pdf` in the root folder
- The download button in the About section is already linked to it

### Contact Form
- The form currently simulates a send
- To make it functional, integrate with **[Formspree](https://formspree.io)** (free):
  - Replace `<form class="contact-form" id="contactForm">` with:
  - `<form class="contact-form" id="contactForm" action="https://formspree.io/f/YOUR_ID" method="POST">`
  - Remove the JS form handler from `main.js`

---

## 🎨 Design System

- **Aesthetic:** Dark Luxury Editorial with Gold Accents
- **Fonts:** Cormorant Garamond (display) · DM Sans (body) · Playfair Display (italic accent)
- **Accent Color:** `#D4AF37` (classic gold)
- **Background:** Deep navy-indigo dark (`#07050f`)

---

Built with pure HTML, CSS & vanilla JavaScript. No frameworks. No dependencies. No build step required.
