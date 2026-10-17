# Calisthenia website

Static site for GitHub Pages. Plain HTML and CSS, no JS, no trackers.

- `index.html`: landing page (text only for now; game media is intentionally not published before the app is live)
- `privacy/index.html`: privacy policy, linked from Google Play. Keep the URL `/privacy/` stable.
- `assets/style.css`: shared styles

## Run locally

    python3 -m http.server 8000

Then open http://localhost:8000. Note: `404.html` uses root-absolute paths, which assume the site is served at a domain root.

## Play Store URL

Not live yet. It is in a comment in `index.html` next to the "Coming soon to Google Play" badge:
`https://play.google.com/store/apps/details?id=com.sahandrez.calisthenia`

## Media

`media/` and `WEBSITE_BRIEF.md` are git-ignored. Remove them from `.gitignore` when ready to publish the full showcase.
