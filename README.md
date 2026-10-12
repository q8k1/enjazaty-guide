# enjazaty-guide
Interactive step-by-step guide for Enjazaty (نظام إنجازاتي)

Start with the [multi-page guide hub](multipage/index.html):

1. [Home](multipage/01-home.html)
2. [Add Task](multipage/02-add-task.html)
3. [Calendar](multipage/03-calendar.html)
4. [View Enjazaty](multipage/04-view-enjazaty.html)

Open the hub directly in a browser, or serve this directory with
`python3 -m http.server 8000` and visit `/multipage/`. No build or dependencies
are required. Each guide includes its own original Arabic/English tutorial.
When a guide page opens, press **ابدأ** to start the tutorial immediately; use
**Back/Next** or arrow keys to navigate, **End** on the last step or **Escape**
to close it, and the glowing **?** button to reopen it. The calendar uses the original October 2026 demo data.
These are illustrative guide screens, not a backend for saving achievements.

The root `index.html` redirects to `multipage/` so the GitHub Pages site
(https://q8k1.github.io/enjazaty-guide/) opens the guide hub.
