# lowtide-locks-site

Landing page, support and privacy pages for **Lowtide Locks**, a calm isometric puzzle game for iPhone
where the still water is a mirror and the reflection is a second path.

Live: https://nguyenvanlamm.github.io/lowtide-locks-site/ · [support](https://nguyenvanlamm.github.io/lowtide-locks-site/support.html) · [privacy](https://nguyenvanlamm.github.io/lowtide-locks-site/privacy.html)

Plain static HTML/CSS, no build step and no JavaScript. GitHub Pages serves the `main` branch root
directly (no GitHub Actions). Fonts are self-hosted (Rokkitt, Atkinson Hyperlegible Next — SIL OFL 1.1,
licences in `assets/fonts/`), so the site makes no third-party requests.

Preview locally: `python3 -m http.server 8000` and open http://127.0.0.1:8000/.
