# cull-site

The website for CULL: home, formats, changelog, support, privacy policy,
license terms, terms of sale and the press kit. Static HTML, no framework,
served by GitHub Pages from `docs/` on `main`.

```
node build.mjs --sync   # copy CHANGELOG.md, legal/*.md, screenshots, fonts from ../cull, then build
node build.mjs          # build docs/ from content/ + pages/ + assets/
node serve.mjs          # look at docs/ on http://127.0.0.1:8188/
```

- `content/*.md` — text pages rendered by the small Markdown renderer in
  `build.mjs` (headings, paragraphs, lists, bold, links). `changelog.md`,
  `privacy.md` and `terms.md` are copies of the app's files: change them in
  the app repository and run `--sync`. `terms-of-sale.md` lives here.
- `pages/*.html` — page bodies written by hand (home, formats, support, press).
- `assets/` — the stylesheet (the app's tokens), fonts, icon, screenshots.
- `build.mjs` `config` — version shown on the download buttons, the
  downloads address, the support email (empty until one exists).

Downloads point at the public `cull-releases` repository. The app's source
is private.
