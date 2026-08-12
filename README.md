# Brightly — Landing Page

A simple, responsive landing page built with **plain HTML and CSS** — no frameworks, no JavaScript, no build tools. Created as a beginner-friendly project to practice layout fundamentals: sections, columns, headers/footers, spacing, and a consistent color palette.

---

## 📁 Project Structure

```
.
├── index.html      # Page markup — header, hero, features, about, contact, footer
└── style.css        # All styling
```

---

## ✨ Sections

- **Header** — logo and navigation links.
- **Hero** — main heading, subtext, and a call-to-action button.
- **Features** — three-column layout highlighting key selling points.
- **About** — two-column split (text + visual block).
- **Contact / CTA** — full-width call-to-action band.
- **Footer** — copyright and quick links.

---

## 🛠️ Tech Stack

- HTML5 (semantic sections)
- CSS3 (Flexbox for all layout, one `@media` breakpoint for mobile)

No dependencies, no npm install, no build step.

---

## 🚀 Getting Started

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```
2. Open `index.html` in your browser:
   ```bash
   # macOS
   open index.html
   # Windows
   start index.html
   # Linux
   xdg-open index.html
   ```

That's it — it's a static page, so there's nothing to install or run.

---

## ✏️ Customizing

| What to change | Where |
|---|---|
| Site name / logo text | `index.html` → `.logo` |
| Hero heading, subtext, button | `index.html` → `.hero` |
| Feature cards (titles, text) | `index.html` → `.feature-grid` |
| About section text | `index.html` → `.about-text` |
| CTA heading/button | `index.html` → `.contact` |
| Footer links | `index.html` → `.footer-links` |
| Accent color (used for logo, buttons, links, CTA band) | `style.css` → search and replace `#4a3fd6` |
| Fonts, spacing, borders | `style.css` |

---

## 📱 Responsive Behavior

The layout uses Flexbox throughout (`flex-wrap: wrap`), so the feature cards and footer links naturally stack on smaller screens. One `@media (max-width: 600px)` rule adjusts the nav and hero heading size for mobile.

---

## 📄 License

Feel free to fork and adapt this template for your own projects.
