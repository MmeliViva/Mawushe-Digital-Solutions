Mawushe Digital Solutions — Frontend prototype

Overview

This workspace contains a fintech-grade marketing website prototype for Mawushe Digital Solutions. It's built using static HTML, Tailwind (Play CDN), and small custom CSS/JS for layout and interactions.

Quick preview (local)

From the project root, run a simple static server (Python):

```powershell
# Windows (PowerShell)
python -m http.server 8000
# Then open http://localhost:8000/ in your browser
```

Or use Node's http-server if installed:

```bash
npx http-server -c-1 .
```

Deployment

- Vercel: recommended for zero-config static deploys. Connect repo and deploy (auto-build).
- Netlify: drag-and-drop or connect repo with default settings.

Key files

- `index.html` — Main landing page (Tailwind-first, fintech-style)
- `pages/` — Services, About, Contact pages
- `assets/css/base.css` — Small shared token + accessibility CSS
- `assets/js/` — UI scripts (header, loader, AOS init)

Accessibility & Responsive QA checklist

- Skip link present (`<a class="skip-link" ...>`)
- Keyboard focus-visible outlines applied
- Forms include labels and `required` where relevant
- Mobile menu overlay with correct aria attributes
- Contrast: primary content uses high-contrast text colors

Next steps

- Add automated linting (HTML validator, a11y checks)
- Hook up a contact form backend or use a serverless form provider
- Replace placeholder images and logos with production assets

If you want, I can:
- Run a deeper accessibility audit and produce a short report
- Wire up Netlify/Vercel deployment config (optional)
