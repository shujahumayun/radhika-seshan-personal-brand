# Radhika Seshan Personal Brand — Homepage Concepts

Two working homepage concepts for **radhikaseshan.com**, built as static HTML for client review before the Wix build.

**Live review:** https://shujahumayun.github.io/radhika-seshan-personal-brand/

| | Concept One | Concept Two |
|---|---|---|
| Live | [/concept-one/](https://shujahumayun.github.io/radhika-seshan-personal-brand/concept-one/) | [/concept-two/](https://shujahumayun.github.io/radhika-seshan-personal-brand/concept-two/) |
| Structure reference | Corvairo / Tokomoo | Corvairo / Tokomoo |
| Display type | DM Serif Display | Inter Tight, DM Serif italic ×2 |
| Accent | Deep violet `#2E1B3D` | Plum `#5B2A46` |
| Hero | Headline left, 4:5 media card right | Full bleed photograph |
| Dark band | Iron gray `#3A3D42` | Deep violet `#2E1B3D` |

## Layout

```
index.html            landing page, links both concepts
concept-one/
  index.html          the concept
  preview.html        desktop + 390px mobile side by side
  NOTES.md            handover notes, tokens, assets needed
concept-two/
  index.html
  preview.html
  NOTES.md
  desktop.png         full page still
  mobile.png          390px still
```

## Shared design system

| Role | Value |
|---|---|
| Ink | `#111111` |
| Iron gray | `#3A3D42` |
| Body gray | `#5A5F66` |
| Hairline | `#E4E4E6` |
| Off white | `#FAFAFA` |
| White | `#FFFFFF` |

Locked on the 2026-07-27 call: black, white, and iron gray, with a single accent from the plum to violet family. Mustard, ochre, red white and blue, and sepia were all ruled out. Concept One carries deep violet, Concept Two carries plum, so the two options are also an accent test.

## Dependencies

No build step and no package manager. Open any `index.html` directly in a browser.

- **Fonts:** DM Serif Display, Inter, Inter Tight, loaded from Google Fonts. All three are free and all three exist in the Wix font library.
- **Images:** Unsplash placeholders loaded over HTTPS. **None of them are Radhika.** Photographer credits are in each file's header comment and in the per concept `NOTES.md`.
- **JavaScript:** vanilla only. An IntersectionObserver scroll reveal that respects `prefers-reduced-motion`, a mobile nav toggle, and client side newsletter form validation with no backend attached.

## Status

Draft copy from the 2026-07-27 content workshop, awaiting client sign off. Placeholder contact email and LinkedIn URL. Hero photograph needed from the client at 4:5, 1200 × 1500 px.

Concept One's accent moved from plum to deep violet on 2026-08-10, the second option named on the 2026-07-27 call.

## Rules held in both

- No testimonials, no invented numbers, no case studies, no logos, no pricing.
- Employer stays "a public university in Minnesota". No institution name anywhere.
- Zero em dashes and zero connector hyphens in copy.
