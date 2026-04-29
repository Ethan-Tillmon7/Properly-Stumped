# Properly Stumped LLC — Website

Marketing and booking site for **Properly Stumped LLC**, a stump grinding and removal company serving the Kansas City area.

Live site: [properlystumped.org](https://properlystumped.org)

---

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home | `index.html` | Hero, key benefits, and primary CTAs |
| Services & Scheduling | `services.html` | Four service tiers with individual booking links |
| About & FAQ | `about.html` | Why remove stumps, why hire a pro, and FAQ accordion |

---

## Tech Stack

- **Plain HTML/CSS** — no frameworks, no build step
- **Google Fonts** — Oswald (headings) + Lora (body)
- **Deployed on Netlify** — auto-deploys on push to `main`
- **Google Calendar** — booking links per service tier

---

## Project Structure

```text
/
├── index.html
├── services.html
├── about.html
├── styles.css
├── netlify.toml
└── images/
    ├── Logo.png
    ├── background.jpg
    ├── rowsoftrees.jpg
    ├── thinker.jpg
    └── truck.jpg
```

---

## Booking Links

Each service card links to its own Google Calendar appointment page:

| Service | Calendar |
| --- | --- |
| Stump Grinding | `calendar.app.google/VwF58x5UTuAnbGTj7` |
| Stump Grinding + Haul Away | `calendar.app.google/CfhbNPJgShLPuBYD9` |
| Grinding + Haul Away + Topsoil | `calendar.app.google/4xyDuTj3CzWywtJv9` |
| Properly Stumped? (Consultation) | `calendar.app.google/Nc1w7GPjbVHgtUui7` |

---

## Deployment

The site is deployed via Netlify with automatic deploys on every push to `main`. No build command is needed — Netlify serves the root directory directly.

`netlify.toml` handles:

- Clean URLs (`/services` → `/services.html`)
- Security headers (X-Frame-Options, CSP, etc.)
- Aggressive CSS caching

---

## Contact

- **Phone/Text:** (816) 237-8758
- **Email:** ericoconnor@properlystumped.org
