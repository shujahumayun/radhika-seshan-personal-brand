# Radhika Seshan · Homepage Concept 1 — Handover Notes

**For:** Shuja (Wix build) · **Brief codename:** Hermes · **Date:** 2026-08-09 · **Accent updated:** 2026-08-10

---

## 1. What this concept is

The lead homepage concept. It follows the Corvairo reference structure (the second site shortlisted on the 2026-08-09 call), with the agreed copy deck and the client design system: iron gray plus a single deep violet accent, DM Serif Display and Inter.

**Accent change 2026-08-10:** the accent moved from plum `#5B2A46` to deep violet `#2E1B3D`, the second option Radhika named on the 2026-07-27 call ("Something I love violet. Very dark violet. Almost black."). One accent only, as agreed.

Open `preview.html` for a side by side desktop (full page) and 390px mobile review.

---

## 2. Structure map: Corvairo reference → this page

The client reference screenshot was reviewed section by section. Everything that does not have client copy, or is ruled out by the brief, was dropped deliberately.

| Corvairo section | What we did | Why |
|---|---|---|
| Header: logo + nav + CTA button | Kept: wordmark, 6 nav items, one CTA button | Matches the agreed working nav |
| Hero: eyebrow + two line serif headline + subhead + two CTAs + media card on the right | Kept, media card holds the photograph | Hero pattern from the reference |
| Hero boast stat ("1620+") | Dropped | No invented numbers allowed |
| About (centered statement) | Maps to "Own your journey." | Philosophical centre, violet rule accent |
| Numbered pillars 01/02/03 | Dropped | Would read as a framework. Brand core is already the three paragraphs |
| Services (title left, description right rows) | Maps to the Two Audiences rows | Clean B2C / B2B routing without merged pitch |
| Case studies grid | Dropped | No cases, no testimonials cleared |
| Why us numbered pillars | Dropped | No invented claims |
| Testimonials wall + ratings | Dropped | Client rule: no testimonial walls, no numbers to claim |
| Our team roster | Dropped | Multi consultant framing not wanted |
| Insights (blog posts) | Dropped for now | No post copy. Newsletter only at launch |
| CTA "The work begins with a Single Question" | Maps to the CTA band | Same centred dark band pattern |
| Newsletter pre-footer | Maps to the newsletter section | Launch state: signup only |

---

## 3. Design tokens

| Role | Value | Use on this page |
|---|---|---|
| Ink | `#111111` | Wordmark, hero headline, card headlines |
| Iron gray | `#3A3D42` | Section headlines, CTA band fill, credibility type |
| Body gray | `#5A5F66` | Body copy |
| Hairline | `#E4E4E6` | Row rules, borders, dividers |
| Off white | `#FAFAFA` | Alternating sections (journey, audiences, footer) |
| White | `#FFFFFF` | Base background |
| Accent deep violet | `#2E1B3D` | Eyebrows, hero CTA, links, journey rule, input focus |
| Accent pressed state | `#1F1229` | Hover and active on violet buttons |
| Plum | `#5B2A46` | Retired from this concept on 2026-08-10. Concept 2 still carries it |

**Accent discipline:** deep violet appears only as small marks: eyebrows, the hero CTA, the journey rule, links, input focus. The CTA band is `#3A3D42` iron gray with a white button, so her favourite colour still carries the close of the page.

**One note to watch on screen:** `#2E1B3D` is deliberately near black, so against `#111111` ink the violet reads as depth rather than as colour. It is clearest on the filled hero button and the journey rule, quietest on inline links. If Radhika wants the accent to register more, lifting it a step to roughly `#3D2450` keeps it inside the family she approved. Ask on the call before changing it.

## 4. Typography

- **DM Serif Display** for display headlines and the credibility statement. Two italic accent words only: "dream" in the hero, "together" in the CTA band.
- **Inter** for body, nav, labels, buttons.
- Both free Google Fonts, both in the Wix font library. Two typefaces total.

## 5. Imagery (Unsplash)

All three images are real, verified Unsplash URLs. **None of them are Radhika.** They are stand-ins for layout, crop, and tone.

| Placement | Current image (source) | Final asset needed |
|---|---|---|
| Hero, 4:5 card, right column | Professional woman, neutral tones — `photo-1573496359142-b8d87734a5a2` | Radhika speaking context photo, 4:5 crop, 1200 × 1500 px |
| Origin story, 3:2, left of text | Woman speaking at a conference — `photo-1531482615713-2afd69097998` | Optional editorial image (conference, lecture) |
| Newsletter, 4:5, right column | Stack of books — `photo-1456513080510-7bf3a84b82f8` | Optional editorial image |

**Crop specs to give the client:** hero is the critical one: 4:5, 1200 × 1500 px, subject framing the space you need on the left where the text column sits. The two smaller images are optional and can be swapped or dropped in Wix without touching the layout.

## 6. Wix rebuild notes

- Standard 12 column feel via grids: hero and origin use a 55/45 split, audience rows use 40/60. All rebuildable as Wix column layouts.
- Radii: buttons pill (999px), image frames 18px, inputs 12px. One system, keep it.
- Fonts: DM Serif Display + Inter via the Wix font library.
- Motion: only fade + 10px rise on first scroll, plus hover states. IntersectionObserver based, respects reduced motion. Wix scroll animation with the same settings is fine.
- The newsletter form has a client side validation and a success / error line. At launch, wire it to the email marketing service of choice. Phase two: replace the signup with a three post card row once the blog has content.
- Headers / counters / stats: none on this page. Do not add any.

## 7. Copy flags

Everything on the page is the client's draft copy deck except two designer stand-in lines, flagged for sign off:

1. Newsletter body: "Notes arrive occasionally, only when there is something worth saying. No schedule, no noise."
2. Footer disclosure: "This is a personal site and is not affiliated with or endorsed by any institution."

Also open items carried from the brief: email address and LinkedIn link are placeholders; consultation copy says 30 minutes (easy to change to 20); "Speaking & Advisory" may split into two nav items; the blog stays in launch state.

## 8. Hard rules held

- Zero em dashes, zero hyphen connectors in copy.
- No employer name. "A public university in Minnesota" everywhere.
- No invented facts, numbers, testimonials, prices, or logos. Credibility is type only.
- No pricing anywhere. No urgency, no countdowns, no "limited spots".