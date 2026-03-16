# Lhakpa-Sonam-Sherpa.github.io

Modern portfolio for Lhakpa Sonam Sherpa — full-stack developer focused on building scalable, performant web experiences.

## Folder structure
- `index.html` — primary one-page portfolio (hero, skills, projects, GitHub activity, contact)
- `style.css` — design system (colors, layout, glassmorphism, responsive rules)
- `case-studies/` — deep-dive pages (e.g., `ecommerce.html`)
- `resume.pdf` — downloadable resume placeholder
- `sitemap.xml` & `robots.txt` — SEO assets

## Running locally
No build step is required. Open `index.html` in your browser or serve the folder with a simple server:
```bash
python -m http.server 8000
# visit http://localhost:8000
```

## Customizing
- Update links to real project repos and live demos in the Projects & Case Studies sections.
- Replace `resume.pdf` with your actual resume while keeping the filename for the CTA.
- Swap the GitHub username in the GitHub stats image URLs if needed.
- Update the Formspree endpoint in the contact form (`action` attribute) to your own endpoint.

## Deployment (GitHub Pages)
The site is static. Deploy by pushing to the `main` branch (or enabling Pages in repo settings with the root folder). Pages will serve `index.html` automatically.
