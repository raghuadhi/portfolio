# Raghu Adhithya B — Portfolio Website

A fast, self-contained personal portfolio for **Raghu Adhithya B** — Database Administrator & Cloud Specialist (SQL Server, AWS, Azure, FinOps, Automation).

Built with plain **HTML, CSS, and vanilla JavaScript** — no build step, no frameworks, no dependencies to install. Just open it and go.

## Files

| File         | Purpose                                              |
|--------------|------------------------------------------------------|
| `index.html` | Page structure and all content                       |
| `styles.css` | Styling, responsive layout, dark/light theme         |
| `script.js`  | Theme toggle, mobile nav, scroll animations, counters|

## Sections

- **Hero** — name, title, headline, quick contact links, animated SQL "status" card
- **About** — professional summary with animated stat counters
- **Experience** — timeline of your role at Codincity Digital Technologies
- **Skills** — Databases, Programming, ERP, Cloud, Monitoring/DevOps, Reporting
- **Projects** — six project cards from your resume
- **Certifications & Education** — certs, degree, and soft skills
- **Contact** — email, phone, location, languages, and a direct email CTA

## How to view it

**Option 1 — Just open it**
Double-click `index.html`, or right-click → Open with → your browser.

**Option 2 — Run a local server** (recommended; avoids any browser file restrictions)

```powershell
# Python
python -m http.server 8000

# or Node (if installed)
npx serve .
```

Then visit `http://localhost:8000`.

## How to put it online (free)

**GitHub Pages**
1. Create a repo and push these three files (plus this README).
2. Repo → Settings → Pages → Source: `main` branch, `/root`.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

**Netlify / Vercel**
- Drag-and-drop the folder onto the Netlify dashboard, or import the repo in Vercel. No build command needed — it's a static site.

## Customizing

- **Text/content** — edit `index.html` directly; everything is readable, labeled HTML.
- **Colors/theme** — edit the CSS variables at the top of `styles.css` (`:root` for dark, `[data-theme="light"]` for light).
- **Stats** — change `data-count` / `data-suffix` on the `.stat__num` elements in `index.html`.
- **Add a LinkedIn/GitHub link** — add an anchor in the `.hero__meta` block or the contact section.

## Notes

- Theme preference is remembered in the browser (`localStorage`).
- The design is responsive down to mobile and respects `prefers-reduced-motion`.
- Fonts load from Google Fonts over the internet; the rest works fully offline.
