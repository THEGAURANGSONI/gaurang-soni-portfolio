# Gaurang Soni — Personal Portfolio

A modern, single-file personal portfolio (`index.html`) built with HTML, Tailwind CSS (CDN) and vanilla JavaScript. No build step, no dependencies.

## Features
- Sections: Home, About, Education, Skills, Projects, Achievements, Contact
- Dark mode by default, light-mode toggle (saved in localStorage, respects system preference on first visit)
- Sticky glass navbar with active-section highlighting
- Accessible mobile menu (aria-expanded, closes on link click and Escape)
- Scroll-reveal animations, hover effects, animated blurred hero background
- Respects `prefers-reduced-motion`
- Skip link, semantic HTML, SEO + Open Graph tags, inline SVG favicon and icons

## Preview locally
- Double-click `index.html` to open it in your browser, **or**
- Run `npx serve .` in this folder and open the URL it prints.

## Deploy to Vercel
**a) Via GitHub**
1. Create a GitHub repo and push `index.html` and `README.md`.
2. Go to https://vercel.com/new and import the repo.
3. Framework Preset: **Other**. Leave Build Command and Output Directory empty.
4. Click **Deploy**.

**b) Via Vercel CLI**
```bash
npx vercel        # preview deployment
npx vercel --prod # production deployment
```

## Replace the placeholders
- **GitHub:** search `your-username` in `index.html` and replace it with your GitHub username (3 places).
- **Project links:** in the Projects section, replace each `href="#"` on "View Project" with your real project URL.
- **Achievements:** replace the "Add your achievement here" cards with your real achievements.
