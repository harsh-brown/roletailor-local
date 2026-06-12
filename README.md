# RoleTailor Local

> A free, zero-backend, local-first AI-powered resume tailoring app.

## What it does

RoleTailor Local helps you maintain one **Master CV** as a structured knowledge base, then tailors it to any job description (JD) you paste — automatically scoring, selecting, and rephrasing bullets for maximum relevance.

No backend. No subscriptions. No data leaves your browser.

---

## Features

| Screen | Description |
|---|---|
| 🏠 Home | Start a session, import/export JSON |
| 📄 Master CV | Edit your structured knowledge base (experiences, bullets, skills, education) |
| 🔍 JD Analyzer | Paste a job description — extracts keywords, role signals, domain, seniority |
| 🎯 Match Studio | Scores every bullet vs the JD, recommends must-include / good / drop |
| ✏️ Rewrite Review | Side-by-side original vs rewritten bullet with approve/reject |
| 📤 Export | ATS-friendly preview, PDF via browser print, JSON save |

---

## How to use

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge)
2. Edit the Master CV with your real experience
3. Paste a job description in the JD Analyzer
4. Go to Match Studio → review scored bullets
5. Go to Rewrite Review → approve/reject rewrites
6. Export → Print as PDF or save JSON

---

## Host on GitHub Pages

1. Fork this repo
2. Go to Settings → Pages
3. Set source to `main` branch, root folder
4. Access at `https://<your-username>.github.io/roletailor-local/`

---

## Tech stack

- Vanilla HTML/CSS/JS — no build tools, no npm
- [Tabler Icons](https://tabler.io/icons) via CDN
- JSON-based master CV data model
- Client-side PDF via browser print
- Zero backend, zero cookies, zero tracking

---

## Roadmap

- [ ] Optional AI rewrite via user-supplied Gemini/OpenAI API key
- [ ] PDF.js-based JD file upload
- [ ] Multiple tailored resume variants
- [ ] Cover letter generation
- [ ] Browser extension for LinkedIn JD capture
- [ ] Local Ollama support for fully offline AI rewrite

---

## Author

Built by [harsh-brown](https://github.com/harsh-brown)

---

## License

MIT
