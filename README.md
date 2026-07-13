# Busy For You — book mockup

Interactive HTML flipbook for the photobook *Busy For You* by Louis Royer.
Static single-file site (no build step), hosted on GitHub Pages.

## Structure

- `index.html` — the flipbook. `Busy For You - book mockup.html` is an identical
  twin; any edit must be applied to both.
- `pages/` — web-res images (lowercase filenames; hosting is case-sensitive).
- `captions.js` — notes-page text (`window.CAPTIONS`), edited in-app via
  ✎ EDIT NOTES → SAVE CAPTIONS FILE.
- `.nojekyll` — tells GitHub Pages to serve files as-is (no Jekyll processing).
- `robots.txt` + a `noindex` meta tag — site is deliberately hidden from crawlers.

## Deploy

Pushing to the default branch auto-publishes via GitHub Pages
(Settings → Pages → Source: deploy from branch, root).
