Fintech UI Redesign — Mawushe Digital Solutions

Summary:
- Replaced homepage with a clean fintech-style layout.
- Added `assets/css/fintech.css` implementing color system, typography, responsive rules, cards, and buttons.
- Removed glassmorphism and heavy blur effects for improved readability.
- Updated secondary pages (`pages/about.html`, `pages/contact.html`, `pages/services.html`) to use the new header and stylesheet.

Files changed:
- index.html
- assets/css/fintech.css
- pages/about.html
- pages/contact.html
- pages/services.html

How to preview:
- Open `index.html` in your browser or serve the folder with a static server.

Quick static server (Python):

```bash
# from inside the project folder
# Python 3
python -m http.server 8000
# then open http://localhost:8000/
```

Notes & next steps:
- I tightened mobile spacing and touch targets; further visual polishing can be done on request.
- If you want, I can: (A) standardize other pages, (B) extract header/footer into includes for templating, (C) add accessible focus styles.

Contact me with which next step you'd like.
