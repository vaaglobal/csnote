# Customer Service Mastery — Training Guide

A practical, interactive single-page web application designed to train customer service professionals. Built with pure HTML, CSS, and vanilla JavaScript — no frameworks, no dependencies, no build step required.

---

## 🚀 Deployment

This project is a single HTML file ready to deploy on **Vercel**, Netlify, GitHub Pages, or any static hosting provider.

### Deploy on Vercel

1. Place `index.html` in the root of your project folder
2. Push to a GitHub/GitLab repository
3. Import the repository on [vercel.com](https://vercel.com)
4. Vercel will auto-detect it as a static site — click **Deploy**

> ⚠️ The file **must** be named `index.html` exactly. Any other name (e.g. `html_index.html`, `2-index.html`) will cause Vercel to return a 404 error.

### Deploy on Netlify

Drag and drop the `index.html` file directly onto the [Netlify dashboard](https://app.netlify.com/drop).

### Deploy on GitHub Pages

1. Push `index.html` to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to the branch containing your file
4. GitHub Pages will serve it at `https://yourusername.github.io/repo-name`

---

## 📁 Project Structure

```
/
└── index.html      # The entire application — HTML, CSS, and JS in one file
└── README.md       # This file
```

---

## 📚 Content Sections

| Section | Description |
|---|---|
| **Managing Complaints** | HEAT de-escalation framework, power phrases, phrases to avoid |
| **Real Scenarios** | Step-by-step dialogue walkthroughs for common CS situations |
| **Key Metrics** | CSAT, NPS, AHT, FCR — definitions, formulas, and benchmarks |
| **Collecting Feedback** | Channels, timing strategies, and survey best practices |
| **Professional Growth** | Career roadmap, PDP template, stress management techniques |

Each section includes an **interactive quiz** with immediate feedback and scoring.

---

## ✨ Features

- **Interactive quizzes** — Multiple choice with answer feedback and score display
- **Hamburger navigation** — Collapsible menu for mobile devices
- **Fully responsive** — Optimized for mobile, tablet, and desktop
- **No dependencies** — Runs entirely in the browser with no backend or npm install
- **Google Fonts** — Playfair Display, DM Sans, DM Mono (loaded via CDN)

---

## 🛠️ Customization

Since everything lives in one file, customization is straightforward:

**Colors** — Edit the CSS variables at the top of the `<style>` block:
```css
:root {
  --rust: #c94f2a;
  --teal: #1a6b6b;
  --gold: #c9972a;
}
```

**Content** — Edit the HTML directly. Each section is clearly commented, e.g. `<!-- SECTION 1 -->`.

**Quiz questions** — Each `.quiz-item` has a `data-correct` attribute (`a`, `b`, `c`, or `d`) that controls the answer. Update the option text and the `data-correct` value to change any question.

---

## 🌐 Browser Support

Works in all modern browsers — Chrome, Firefox, Safari, Edge. No polyfills needed.

---

## 📄 License

This training guide was created for educational purposes. All scenarios and examples are fictional.
