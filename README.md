# 💼 Personal Portfolio — bk0ss.github.io

> A fast, lightweight personal portfolio site built with vanilla web technologies — no build tools, no framework overhead, just clean code deployed via GitHub Pages.

🔗 **[Live Site → bk0ss.github.io](https://bk0ss.github.io/)**

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat-square&logo=javascript&logoColor=%23F7DF1E)

---

## 🧩 Problem → Solution

**Problem:** As a new grad entering the job market, a LinkedIn profile alone isn’t enough. Recruiters and hiring managers want to see a developer’s personality, projects, and skills in one place — and a polished online presence sets candidates apart from identical resumes.

**Solution:** Build a personal portfolio site that loads instantly, works on any device, and showcases projects, skills, and contact information — without the maintenance burden of a JavaScript framework. Deployed for free on GitHub Pages so it’s always live and always up to date.

---

## ✨ Features

- **Responsive Design:** Fully adaptive layout for mobile, tablet, and desktop
- **Dark / Light Mode:** Theme toggle persisted across page visits
- **Zero Dependencies:** No npm, no build step, no bundle — opens directly in any browser
- **Lightweight:** Fast initial load with no framework JavaScript overhead

---

## 🛠️ Tech Stack & Why

| Technology | Role | Why This Choice |
|---|---|---|
| **HTML5** | Page structure | Semantic HTML (header, main, section, article) improves accessibility and SEO with no extra tooling |
| **CSS3 (custom)** | Styling and layout | CSS custom properties (variables) make theming and dark/light mode trivial to implement and maintain |
| **fantaCSS** | Base CSS library | A minimal, classless CSS framework used as a styling baseline. Customized by overriding font family (Nunito), color variables, and spacing to match personal branding |
| **Vanilla JavaScript** | Interactivity & DOM | Theme toggle, smooth scroll, and dynamic content updates handled with native browser APIs — no jQuery or framework needed for this scope |
| **GitHub Pages** | Hosting | Free, zero-config static hosting that deploys automatically on every push to `main`. No server, no CI/CD pipeline, no cost |

---

## 📁 Project Structure

```text
├── index.html      # Main page structure
├── styles.css      # Custom styles and theme variables
├── fanta.css       # fantaCSS base library (customized)
└── public/         # Static assets (images, icons)
```

---

## ⚙️ Running Locally

No build step required. Simply clone and open:

```bash
git clone https://github.com/BK0SS/bk0ss.github.io.git
cd bk0ss.github.io
open index.html   # macOS
# or just double-click index.html in your file explorer
```

---

## 👤 Author

**Bogdan Kosulin**
- GitHub: [@BK0SS](https://github.com/BK0SS)
- LinkedIn: [bogdan-kosulin](https://www.linkedin.com/in/bogdan-kosulin/)
