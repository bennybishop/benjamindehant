# Benjamin Dehant · Brand sheet

Human-readable companion to `assets/css/tokens.css`. If you change a value here,
change it there too (that file is what the site actually reads).

## Personality
Playful, curious, warm, hand-drawn. A creative thinker who moves between AI,
food and games. The site should feel like a friendly sketchbook, not a corporate
resume. Chunky outlines, rounded shapes, soft bounce, blue and yellow.

## Colors
| Token | Hex | Use |
|---|---|---|
| `--bg` | `#FCFAF2` | Warm paper background |
| `--ink` | `#1B2432` | Main text, outlines, hard shadows |
| `--muted` | `#59647A` | Secondary text |
| `--surface` | `#FFFFFF` | Cards |
| `--surface-2` | `#F3EFE0` | Cream alt sections |
| `--blue` | `#1E9BE9` | Primary accent, buttons, links (his signature blue) |
| `--blue-deep` | `#0B5FA5` | Darker blue, headings, hovers |
| `--blue-soft` | `#DCEEFB` | Pale blue washes |
| `--yellow` | `#FFCB2E` | Secondary accent, highlighter, stickers, stars |
| `--yellow-soft` | `#FFF1C2` | Pale yellow washes |
| `--coral` | `#FF7A59` | Playful tertiary (tags, art) |
| `--mint` | `#4FC2A6` | Playful tertiary (tags, art) |
| `--grape` | `#8A6FE8` | Playful tertiary (tags, art) |
| `--footer-bg` | `#12202F` | Footer background |
| `--footer-fg` | `#FCFAF2` | Footer text |

Blue and yellow are the core pair (from Benjamin's own profile branding).
Coral, mint and grape are accents only, used lightly in tags and illustrations.

## Fonts
- Display / headings: **Fredoka** (rounded, curvy, friendly) · weights 400 to 700.
- Body: **Nunito** (rounded, readable) · weights 400 to 800.
- Both loaded from Google Fonts, async. Both include French accents.

## Signature look
- Chunky 2.5px ink outlines and hard offset shadows (`box-shadow: 7px 7px 0 ink`).
- Slightly irregular border-radius on cards (feels hand-drawn).
- Yellow highlighter marks behind key words.
- Squiggle dividers, organic blob behind the portrait, floating sticker tags.
- Gentle motion: scroll reveals, soft hovers, a slow bob on stickers.

## Voice and copy rules
- First person, warm, plain. Benjamin's real phrasing: "discover, learn, share."
- No em-dashes anywhere in visible copy (commas, colons or parentheses instead).
- English at `/`, French at `/fr/`. French must keep correct accents.
- One primary call to action everywhere: Connect on LinkedIn.

## Do / don't
- Do keep it playful and colorful. Do keep blue + yellow dominant.
- Do keep exactly one main CTA (LinkedIn).
- Don't add stock-corporate language or a long timeline/resume.
- Don't introduce new brand colors without updating tokens.css and this sheet.
