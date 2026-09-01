# Concept 2 — build notes

Built 2026-09-02. One page only, by instruction. Concept 1 stays the five page build.

## What this is

A second design direction for the same words. Every line of copy on this page is
already approved copy from the 26 August review call, lifted from concept 1 without
change, so the only variable between the two concepts is the design.

## Type and palette

Carried over from the earlier concept two build that was scrapped on 2026-08-30, at
Shuja's instruction on 2026-09-02. Deliberately **not** concept 1's Georgia and
Avenir Next, so the two concepts read as genuinely different directions.

| Role | Face |
|---|---|
| Display and UI | Inter Tight, 400/500/600 |
| Body | Inter, 400/500/600 |
| Accent serif | DM Serif Display, 400 |

| Token | Value | Used for |
|---|---|---|
| `--ink` | `#111111` | headings, the name |
| `--iron` | `#3A3D42` | strong body |
| `--body` | `#5A5F66` | body text |
| `--soft` | `#83878E` | meta, captions |
| `--hairline` | `#E4E4E6` | rules |
| `--offwhite` | `#FAFAFA` | alternating bands |
| `--plum` | `#5B2A46` | the single accent |
| `--violet` | `#2E1B3D` | framework band |
| `--violet-deep` | `#241430` | contact and footer |

DM Serif Display is the closest face in that kit to the high contrast serif in the
reference image, so it carries the name, the pull quote and the closing question.
Everything else runs on Inter Tight.

## The hero

Built to the reference image Shuja supplied: full bleed portrait, the line set
centre of frame, the name running edge to edge along the bottom.

Three things had to be solved that the reference did not have to solve.

1. **The name lands edge to edge at every width.** It is SVG text with
   `textLength="1000" lengthAdjust="spacing"`, not a font size guessed per
   breakpoint. The browser measures the natural width and distributes the
   difference into the letter spacing, which is what a typesetter would do by hand.
2. **The subject is dark and sits right of centre.** The reference photograph is a
   pale wall throughout, so black type sits anywhere on it. Radhika's jacket is
   near black. The centred block is therefore held under roughly 20% of the frame
   width so it always clears her, and a wash plus a bottom fade lifts the whole
   image. The first pass had an intro paragraph and a second button in the hero;
   both ran across her jacket and became unreadable, so they were cut. The intro
   line moved down into the statement block. That also brings the hero closer to
   the reference, which carries only the line and the name.
3. **Fourteen characters on one line goes illegibly small on a phone.** Below 820px
   the name stacks to RADHIKA over SESHAN, each word still running edge to edge.

The photograph is desaturated with a very light violet multiply, which is what keeps
a colour photo from fighting the plum accent.

## Structure

Deliberately different from concept 1 at every point. No cards anywhere.

| # | Section | Device |
|---|---|---|
| 1 | Hero | full bleed portrait, centred line, name edge to edge |
| 2 | Statement | two column, then the credential row as titles only |
| 3 | Career planning | asymmetric editorial, ending on the Bell Labs pull quote set large |
| 4 | Ways to work together | full width numbered rows, four columns each, hover wash |
| 5 | Own your journey | violet band, outlined serif numerals |
| 6 | Experience | three columns with roman numerals |
| 7 | Speaking topics | a list, not a grid |
| 8 | Perspectives | a list, not a grid |
| 9 | Client stories | honest placeholder, kept from concept 1 |
| 10 | Contact | full bleed, the question set at hero scale |
| 11 | Footer | the name returns ghosted, as a bookend |

## Rules held

* **No italics and no underlines anywhere.** Row 8 of `direction-v2.md`, raised twice
  on the call. The scrapped concept two used italic underlined phrases as its
  signature move; they are gone. Link affordance is an arrow, not a rule.
* **No figures.** None of the four BLOCKED metrics appear.
* **No employer name.** "a public university in Minnesota", never the institution.
* **No tenure counts**, no "three decades of reinvention".
* Northeastern and San Diego State are named because the brief confirms them. UCLA
  is out by her decision.
* No dashes used as connectors in any copy.

## Open items, same as concept 1

* `hello@radhikaseshan.com` is a placeholder. The address does not exist.
* `linkedin.com/in/seshanr` came from Kumar's mockup and is unverified.
* Nav links are in page anchors, because this concept is a single page by
  instruction. If it wins, it gets the same five page sitemap concept 1 has.

## Writing row photography

Three free Unsplash photos, added 2026-09-02, grayscale to match the hero's
own desaturated treatment: a forest gravel path (career strategy), sunlight
through blinds (future of work), an open notebook and pen (professional
learning). Same three images used on concept 1. Credits: paws and prints,
Phil Hearing, Clay Banks. Placeholder photography, standing in for whatever
image accompanies each real essay once one exists.
