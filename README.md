# benjamindehant.com

The personal website of Benjamin Dehant: designer and maker across AI, food and
games. Fast, static, bilingual (English + French), and built to be findable by
both Google and AI assistants.

## What this is
- Pure static HTML/CSS/JS. No build step, no framework. Open `index.html` to view.
- English lives at `/` (`index.html`), French at `/fr/` (`fr/index.html`).
- Made to be hosted free on Cloudflare Pages, with the code backed up on GitHub.

## Where things live
```
index.html              English homepage
fr/index.html           French homepage (mirror of the English one)
assets/css/tokens.css   COLORS + FONTS only · edit this one file to re-skin
assets/css/styles.css   all other styling
assets/js/main.js       scroll reveals
assets/images/hero/     the portrait
assets/images/projects/ project thumbnails (real photos + hand-drawn SVGs)
assets/images/logos/    Le Konbini logo
assets/images/social-share/  the 1200x630 link-preview image
brand/brand.md          the brand sheet (colors, fonts, voice)
_source/                original files (portrait, logo, links doc) · not deployed
llms.txt, llms-full.txt what AI assistants read about Benjamin
sitemap.xml, robots.txt SEO
favicon.* , site.webmanifest  browser/app icons
```

## How to make common changes
- **Change a color or font:** edit only `assets/css/tokens.css`, then mirror it in
  `brand/brand.md`. Nothing else hard-codes colors.
- **Change wording:** edit both `index.html` (English) and `fr/index.html`
  (French) so the two languages stay in sync. Keep one main call to action
  (Connect on LinkedIn) and avoid em-dashes.
- **Swap the portrait:** drop the new photo in `_source/photos-original/`, export
  a square `.webp` to `assets/images/hero/benjamin-portrait.webp` (same name).
- **Add a project:** copy one of the `.proj` cards in the right group in both
  language files. Put its thumbnail in `assets/images/projects/` (a real image as
  `.webp`, or a hand-drawn SVG in the same style as the others).
- **Update the AI book:** when the title and cover are ready, replace the
  "Coming soon" book card in both language files and swap `projects/ai-book.svg`
  for the real cover.

## To request a change
Message everybodyknowsyou.com with what you want changed and we will update the
site and redeploy. If you want to edit and host it yourself, ask for the
Self-Sovereignty Pack, which hands you full ownership and a simple guide.

---
Website made with love by [everybodyknowsyou.com](https://everybodyknowsyou.com).
