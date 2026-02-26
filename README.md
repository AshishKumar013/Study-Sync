# 📚 StudySync — Educational Landing Page

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)

> A fully responsive educational landing page clone built to demonstrate advanced CSS layout techniques — Flexbox, CSS Grid, and media queries — with a clean, modern design.

**🔗 Live Demo:** [studysynccss.netlify.app](https://studysynccss.netlify.app/)

---

## 📸 Preview

The page features a modern, multi-section layout that gracefully adapts from desktop to mobile, including a responsive hamburger navigation, feature cards, testimonials, and a newsletter form.

---

## ✨ Features

- **Responsive Navigation Bar** — Sticky top nav with a hamburger menu toggle that activates at the 768px breakpoint for seamless mobile browsing.
- **Hero Section** — Eye-catching landing section with a clear call-to-action.
- **Feature Cards** — A CSS Grid-based card layout highlighting platform features with optimal visual alignment.
- **Testimonials Section** — Social proof section styled with Flexbox for consistent, clean layout.
- **Newsletter Form** — Clean subscription form section for user engagement.
- **4-Column Footer** — A complex footer grid that collapses gracefully into a single-column layout on smaller screens without any content overlap.

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling, layout, and animations |
| **Flexbox** | Component-level alignment (nav, cards, testimonials) |
| **CSS Grid** | Page-level layout (feature cards, footer) |
| **Media Queries** | Responsive breakpoints (6+ targeted queries) |
| **Netlify** | Deployment and hosting |

---

## 📐 Responsive Design

The project achieves 100% responsive accuracy across all device types through carefully crafted media queries:

- **Desktop (>1024px):** Full multi-column layout with all sections visible.
- **Tablet (768px–1024px):** Adjusted grid columns and spacing for medium screens.
- **Mobile (<768px):** Single-column layout; hamburger menu replaces the full nav; 4-column footer collapses to a single column.

**Breakpoints covered:** 6+ targeted media queries ensure no content overlap or layout breakage at any screen size.

---

## 📁 Project Structure

```
Study-Sync/
├── index.html       # Main HTML file with full page structure
├── style.css        # All styles: layout, components, and responsive rules
└── images/          # Image assets used throughout the page
```

---

## 🚀 Getting Started

### Run Locally

No build tools or dependencies required — it's pure HTML and CSS.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/AshishKumar013/Study-Sync.git
   ```

2. **Navigate into the project folder:**
   ```bash
   cd Study-Sync
   ```

3. **Open in your browser:**
   Simply open `index.html` in any modern web browser.
   ```bash
   # Or use Live Server in VS Code for hot reload
   ```

---

## 🌐 Deployment

This project is deployed on **Netlify** via drag-and-drop of the project folder.

To deploy your own version:
1. Go to [netlify.com](https://www.netlify.com/) and sign in.
2. Drag and drop the project folder onto the Netlify dashboard.
3. Your site will be live instantly with a generated URL.

---

## 🔑 Key Implementation Highlights

**Hamburger Menu:** The navigation system uses a CSS class toggle triggered by JavaScript to switch between the full nav and a mobile-friendly hamburger icon at the 768px breakpoint, significantly enhancing cross-browser compatibility.

**CSS Grid Footer:** The footer uses a `grid-template-columns: repeat(4, 1fr)` layout on desktop that collapses to `grid-template-columns: 1fr` on mobile, ensuring clean stacking without overlap.

**Flexbox Alignment:** Feature cards and testimonials use Flexbox with `align-items: center` and `justify-content: space-between` for consistent, gap-free alignment across all components.

---

## 👨‍💻 Author

**Ashish Kumar**
- GitHub: [@AshishKumar013](https://github.com/AshishKumar013)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with ❤️ using only HTML5 & CSS3 — no frameworks, no libraries.*
