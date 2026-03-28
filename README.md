# wholecricket.github.io

Static one-page landing site for **wholecricket**, tuned for [GitHub Pages](https://pages.github.com/) (no build step).

## Files

| File | Role |
|------|------|
| `index.html` | Structure and copy |
| `style.css` | Theme (black / neon green, layout, motion) |
| `assets/` | Optional: favicon, images, fonts |

## Quick edits

1. **Social links** — In `index.html`, update each `<a class="link">` (X, GitHub, Bluesky, Mastodon): `href`, link text, and the matching inline `<svg>` if you swap networks.

2. **Copy** — Change the hero title, tagline, bio, or footer inside `index.html` (search for `hero-title`, `hero-tagline`, `hero-bio`, `site-footer`).

3. **Colors / glow** — At the top of `style.css`, edit the `:root` custom properties (`--green`, `--bg`, `--glow-soft`, etc.).

4. **Terminal intro** — Adjust the fake prompt in `index.html` inside `.terminal-line` (e.g. change `whoami` or the `user@build` label).

5. **Favicon** — Add `favicon.ico` (or `.png`) under `assets/`, then in `index.html` `<head>` add:

   ```html
   <link rel="icon" href="assets/favicon.ico" type="image/x-icon" />
   ```

## Local preview

Open `index.html` in a browser, or from the repo folder run a static server if you prefer (e.g. `npx serve .` — optional; not required for the site itself).
