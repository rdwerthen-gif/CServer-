# Server+ Study Desk (SK0-005)

A self-contained study companion for the CompTIA Server+ (SK0-005) exam. No
server, no build step, no dependencies — just open `index.html` in a browser.

## What's inside

```
server-plus-study-desk/
├── index.html        The site itself — open this file in any modern browser
├── manual.pdf         User manual (also downloadable from within the site's
│                        Settings page)
├── css/
│   └── styles.css     All styling: base theme tokens, 42 color themes,
│                        10 layout models, components
└── js/
    └── app.js         All application logic and data: 1,766 quiz questions,
                         200 performance-based exercises, 298 flashcards,
                         225 acronyms, dashboard/settings/quiz engine code
```

## Running it

Just double-click `index.html`, or open it from your browser's File menu.
Everything runs locally — no internet connection needed after the page loads,
and no installation of any kind is required.

If your browser blocks local file access for security reasons (some browsers
restrict `file://` pages from loading local scripts/styles), you can instead
serve the folder with any simple local web server, for example:

```bash
# Python 3
cd server-plus-study-desk
python3 -m http.server 8080
# then visit http://localhost:8080 in your browser
```

## Data & privacy

Your quiz progress, streaks, and settings are saved using your browser's
local storage, tied to this folder's `index.html` in that specific browser.
Nothing is ever sent to a server — there is no server. Clearing your
browser's site data, or opening the site in a different browser/device,
will not carry your progress over.

## Full documentation

See `manual.pdf` for a complete walkthrough of every feature: the dashboard,
practice quiz, flashcards, performance-based questions, the troubleshooting
methodology drill, the acronym glossary, study tips, and full settings/UI
customization (themes, layouts, custom colors, density, corners, motion,
and text size).

---

This is an independent study aid and is not affiliated with or endorsed by
CompTIA. For the official, authoritative exam objectives document, see
comptia.org/certifications/server.
