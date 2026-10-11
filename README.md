# CCS — Design System

Part of the Cook Consulting Services, LLC brand family. Files: `tokens.json` (source of truth), `tokens.css` (CSS variables + font faces), the font files, logos, icons and images (all in the top level).

Cook Consulting Services, LLC (CCS) is a consulting practice led by its founder, CEO and principal consultant. Its identity is calm and editorial: a linen page, black ink, two blues, line-drawn florals and bold lowercase type. Three words steer every decision: **inclusive, modern, sophisticated**.

## Content fundamentals

- Write the way the brand looks: clear, warm and unhurried. Short sentences, plain words, no jargon for its own sake.
- **Inclusive**: speak to "you", invite rather than instruct, and write for readers who are new to the topic as well as experts.
- **Modern**: lowercase headings in League Spartan (`display`, `h1`, `h2`) — "this is your heading", not "This Is Your Heading".
- **Sophisticated**: restraint over hype. No exclamation-stacked claims, no emoji.
- Titles and roles are UPPERCASE and tracked in `label`: FOUNDER, CEO · PRINCIPAL CONSULTANT.
- Legal line: "© 2024 Cook Consulting Services, LLC" in `small`, `ink-muted`.

## Visual foundations

### Color

- Lead with `linen` as the page (`surface`) and `black` as the ink (`ink`). Most layouts are 80% linen, 15% black, 5% blue.
- `peacock-blue` is the signature accent: rules, links, buttons and the occasional emphasized word. It reads on linen at 5.4:1.
- `sky-blue` is a fill color — blocks, mats, graphics, and accents on black. Never body text on linen (2.6:1).
- Dark layouts: `black` ground, `linen` ink, `sky-blue` for accents (6.3:1). Peacock on black only at 24px+.
- Peacock and sky blue are close in hue; when they must be told apart (charts, status), rely on their lightness difference and a label, never hue alone.

### Type

- Headings: League Spartan Bold, lowercase, tight tracking (`display`, `h1`, `h2`). Sub-heads `h3` may be sentence case.
- Body: Quicksand Regular `body` at 16/1.6. Quicksand Medium for `small` and `label`.
- Wordmark sub-lines are lowercase and very widely tracked (`tracked`).
- Two families only. Do not add a third face to CCS layouts.

### Layout

- The brand book's frame is the layout: a `space-6` rail on each side holding a rotated UPPERCASE `label`, content between, and 1px `rule` lines (`border-hairline`) dividing rows and columns.
- Square corners everywhere (`radius-none`). Generous margins (`space-6`) and section gaps (`space-5`).
- No drop shadows. Separate with rules and color fields, not elevation.
- Focus: 2px solid `focus` ring, offset 2px.

### Photography

- Calm, editorial, daylight. Neutral stone, cream and white grounds with deep black accents, one subject per frame, generous negative space.
- Warm-neutral grade; no heavy filters, no saturated color casts. Black clothing, ceramics, glass and paper are on-brand props.
- Crop square-cornered (`radius-none`), set photos in a row with a `space-4` gutter, as in the brand book.
- People photos feel candid and confident, never stock-office.

### Elements

- The four line-drawn florals (magnolia, wildflower stems, ginkgo line, peony) are the only illustration. Use one or two per layout, in black ink on `linen`, never recolored to rainbow tones, never filled.
- Let them bleed off a corner or sit beside a heading; don't scatter them as confetti.

## Logos

- `ccs-logo.png` is the primary mark: bold lowercase "ccs" with "cook consulting services, llc" beneath. Black on linen.
- Keep clear space equal to the height of the "c" on all sides. Don't stretch, recolor, outline or add effects.
- The Family group holds the sibling brands' marks for joint materials; use each brand's own system for its own work.
- The current logo files are low-resolution PNGs from the brand book (about 350–400px). Request vector (SVG/PDF) originals from Canva before print use.

## Iconography

CCS has no icon set. Use words and the floral elements rather than icons. If a UI needs icons, use a thin-line set (1.5px stroke, square caps) in `ink`, and keep them small.

## The family

Cook Consulting Services, LLC is the house; each business below is its own brand with its own system, cut from the same cloth.

| Brand | Role | What it keeps from CCS | What it changes |
| --- | --- | --- | --- |
| CCS | Parent consultancy | — | — |
| The Collective Space | Community and gathering brand | Palette, League Spartan, Quicksand, florals | Leads on black; script word in the logo |
| Impact Advisory Group | Advisory practice | Palette, League Spartan, Quicksand, florals | Quietest of the set: ink and linen, one accent |
| Red Tape Academy | Education DBA | Linen, peacock blue, sky blue, black, Quicksand, League Spartan labels | Adds civic red; Libre Baskerville headings; no florals |
| Jules Studio | Handmade Etsy shop | Linen, black, Quicksand, League Spartan, line florals | Plum, rose and blush from the floral work |

Threads every brand keeps, so the family reads as one: the linen ground (`linen` #F1EFE7), black ink (`black` #101010), Quicksand for body copy, League Spartan somewhere in the hierarchy, wide-tracked lowercase or uppercase sub-lines (as in "a d v i s o r y   g r o u p"), square corners, and 1px hairline rules framing the page.

## Canva brand kit

Set up a Canva Brand Kit for this brand so designs stay consistent.

**Colors**

| Name | Hex | Role |
| --- | --- | --- |
| linen | `#F1EFE7` | Page background (shared family color) |
| sky-blue | `#4D9EC0` | Fills and graphics; accents on black |
| black | `#101010` | Text (shared family color) |
| peacock-blue | `#016795` | Lead accent: headings, links, buttons |

**Fonts** — all are Google Fonts; pick them from Canva's font menu. If one is missing, download it from fonts.google.com and upload the TTF to the Brand Kit (Canva Pro).

| Use | Font |
| --- | --- |
| Headings | League Spartan |
| Body text | Quicksand |

**Logos** to upload:
- `ccs-logo.png`

## Licenses

- Fonts: SIL Open Font License 1.1 — see `FONTS.md` and the `OFL-*.txt` files.
- Logos, icons and brand guidelines: © Cook Consulting Services, LLC. All rights reserved. Not licensed for reuse.
