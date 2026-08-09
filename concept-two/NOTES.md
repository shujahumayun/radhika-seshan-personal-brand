# Radhika Seshan · Homepage Concept 2 — Handover Notes

**Built:** 2026-08-09
**File:** `index.html` (open directly in a browser)
**Stills:** `desktop.png`, `mobile.png`

Concept 2 takes the layout of the Corvairo / Tokomoo Webflow template (the reference screenshot) section for section, and fits Radhika's approved draft copy into it. Colour comes only from the client tokens in concept 1's `HANDOVER.md`. Concept 1 (`~/Downloads/radhika-landing-homepage-concept/index.html`) is untouched.

---

## Reference section → what it became

| Reference section | Concept 2 | Source |
|---|---|---|
| Sticky nav + pill CTA | Same, plum pill | copy.md nav |
| Full bleed hero, eyebrow + huge headline left, body + buttons right | Same | Hero |
| `1620+` stat block | **Dropped** | no invented numbers |
| Floating testimonial card | **Dropped** | no testimonials exist |
| About: centred headline + 3 bordered columns, `01 / 02 / 03` | Own your journey + the brand core triptych | Own your journey |
| Services: split header + rows of image / label + title / description / circle arrow | Two ways of working together, 2 rows | Two audiences |
| Case studies 2 × 2 grid | **Dropped** | no case studies |
| Why: split header + bento of alternating text and image cells | Her story, 2 cell bento | Career development, not professional development |
| Dark strip with one line + button | Background ribbon, 4 cells, type only | Credibility strip |
| Testimonials row | **Dropped** | none exist |
| Team row | **Dropped** | not applicable |
| Insights: 3 blog cards | **Dropped** | blog not live |
| Dark CTA band | Same, deep violet | CTA band |
| Newsletter: headline left, email field right | Same | Latest writing + newsletter |
| Footer with link columns | Same, iron gray fill | Footer |

Eight sections built. Six dropped for lack of content, per your instruction.

## Colour

Straight from `HANDOVER.md`, nothing added.

| Token | Value | Used for |
|---|---|---|
| Ink | `#111111` | wordmark on light |
| Iron gray | `#3A3D42` | all section headings, background ribbon fill, footer fill |
| Body gray | `#5A5F66` | body copy |
| Hairline | `#E4E4E6` | panel borders, row dividers, section rules |
| Off white | `#FAFAFA` | alternating section blocks, the accent bar inside the violet band |
| White | `#FFFFFF` | base |
| Accent plum | `#5B2A46` | primary CTA, links, numerals, the underline bar under every second tier headline |
| Deep violet | `#2E1B3D` | CTA band fill only |

The reference's cream page and light green accent are gone. Cream becomes off white, light green becomes plum. That is the single biggest visual difference from the screenshot, and it is deliberate.

One judgement call to flag: the reference puts a dark band where our credibility strip sits. Concept 1's rule was "dark moments only in the CTA band and the footer." I gave the strip **iron gray**, not violet, so deep violet still appears exactly once on the page.

## Type

The reference's whole rhythm is a tight grotesk with an italic second tier. Concept 1 ran DM Serif Display headlines. Concept 2 splits the difference:

- **Headlines:** Inter Tight, the two tier treatment with a plum bar under the italic tier.
- **DM Serif Display italic:** kept for exactly two words, `dream` in the hero and `together.` in the CTA band. That honours the brief's "two serif uses total" rule.
- **Body, nav, labels, buttons:** Inter.

All three are free Google Fonts and all three are in the Wix font library.

**To flip headlines back to the serif:** one line at the top of the file.
```css
--font-display: 'DM Serif Display', Georgia, serif;
--display-weight: 400;
```

## Copy

Everything is from `copy.md` > Home, still awaiting Radhika's sign off. Three changes worth naming.

**1. The brand core paragraphs were split, not rewritten.** The reference cell is `label → headline → body`, so each of her three paragraphs became a headline plus a body from her own sentence. Example: "Striving is trying without being attached to guaranteed results. It is playing the long game..." became headline "Trying, without being attached to guaranteed results." and body "It is playing the long game against a five year vision, not the next promotion." No new claims.

**2. Three designer stand in lines**, tagged `STAND IN` in the markup. The reference has an intro slot in each section header that her deck does not fill yet. Either get her a line for each, or delete them.

| Where | Line |
|---|---|
| Own your journey, centred intro | "Three ideas hold the whole roadmap together." |
| Two ways of working together, right column | "The same roadmap, delivered two ways. One person at a time, or one organization at a time." |
| Newsletter, support line | "No schedule and no filler. Occasional notes on career development, and nothing else." |

The section headline "Two ways of working together." is also mine. Her deck calls that section "Two audiences," which is an internal label, not a headline.

**3. Carried over unchanged from concept 1:** the employer stays "a public university in Minnesota," the consultation says 30 minutes (still unconfirmed against 20), no numbers, credentials, logos, or prices beyond what she said on a call, zero em dashes and zero connector hyphens.

## Photography

All four images are Unsplash placeholders under the free licence, chosen to match the crop each slot needs. Swap them for Radhika's own shots. Credits are in the file header comment.

| Slot | Photographer | Needs |
|---|---|---|
| Hero, full bleed | Vitaly Gariev | her speaking or leading a room, 2400 px wide or more, subject right of centre so the headline sits clear on the left |
| Her story bento cell | ThisisEngineering | her teaching or presenting, roughly 1200 × 900 |
| Coaching row | Amy Hirschi | a one to one working session, 4:3 |
| Speaking & Advisory row | Damaris Azocar | her at a podium or on stage, 4:3 |

## Build notes

- Plain grid and flexbox, 1280 px container. Everything maps to standard Wix sections. No exotic CSS.
- Sticky header goes transparent over the hero and blurs to white on scroll. Wix does the same.
- Motion is a fade with a small rise on scroll, gated by `prefers-reduced-motion`. Wix equivalent is the "fade in" scroll effect.
- Checked at 1440, 834 and 390. No horizontal overflow at any width.
- Below 640 the service row arrows hide and the text links carry the affordance.

## Open

- Radhika's sign off on the copy, especially the employer line.
- Her photographs.
- Real LinkedIn URL and contact email, currently `hello@radhikaseshan.com` and a bare linkedin.com link.
- Confirm 30 versus 20 minutes for the consultation.
- The three stand in lines above.
- Blog card row is a phase two swap into the newsletter section once posts exist.
