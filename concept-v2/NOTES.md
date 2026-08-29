# Radhika Seshan · Homepage · The concept — build notes

**Date:** 2026-08-30 · **For:** the Wix rebuild
**Source of truth:** `Frost/Projects/active/radhika-seshan-personal-brand/direction-v2.md`, `copy.md`, `design-direction.md`, `site-spec.md`

---

## What this is

The single homepage concept. Built to **Kumar Narayanan's forwarded blueprint** (2026-08-26 email, full text in `Shuja2/raw/gmail/2026-08-26-analysis-and-recommendation.md`), with the **2026-08-26 review call's copy rules** layered on top. It replaces Concept One and Concept Two as the working direction. Shuja's instruction on 2026-08-30: take Kumar's direction, combine it with Radhika's copy feedback, build one concept.

## Kumar's direction, built in

- **Hero line** is Kumar's, verbatim: "Your experience has brought you this far. Let us make it work harder for what comes next." Support line is his too. Radhika still picks the final version (her own draft and the call's line are the alternatives).
- **Credibility line** directly under the hero, three titles: PhD in economics / Technology and product executive / Dean and academic leader. Kumar's fourth part ("three decades...") moved down to Selected evidence so the strip carries no numbers.
- **Personal proposition**: first-person passage, "I know what it means to build, and rebuild, a career." Drawn from Kumar's draft narrative. Radhika supplies her own words.
- **Three service pathways** (Kumar's structure): Individual career strategy / Cohorts, groups and workshops / Organizational advisory and speaking. Each answers for whom, what problem, what result.
- **Signature framework**: Kumar's three verbs. Heading stays "Own your journey" (the call approved that heading). 01 See clearly / 02 Choose strategically / 03 Move deliberately, Kumar's connecting line, closing on "a real world roadmap, built together, the journey stays yours" (the call said keep "real world roadmap").
- **Experience that informs the work**: Kumar's three story-led panels (Reinventing across sectors / Developing people and possibilities / Leading through change).
- **Selected evidence**: qualitative only. Kumar wanted a four-point figures strip. See "Held out" below.
- **Perspectives**: three draft essay titles from Kumar's candidate list, marked as drafts.
- **Testimonials**: visible placeholder, "content pending client input".
- **CTA**: question headline (the call), Kumar's "Start a conversation" button and complimentary-first-conversation line.
- **Photography** away from the Roxie Nafousi wellness aesthetic (Kumar's caution). Roxie stays the layout and type reference only.
- **About page**: four-chapter structure (stubbed in `copy.md`).

## The call's copy rules, layered on

- No italics anywhere. No underlines anywhere (emphasis is weight and colour).
- Palette: iron gray and true neutral grays, plum `#5B2A46` on CTAs only. No sepia, pink, light brown.
- "mid career professionals" with women named inside, not "mid career women". "Indian professionals" out. No visa or immigration framing.
- "New thinking, when there is something worth saying" kept verbatim.
- "coach" not "mentor".
- Nav cut to four: Home / Ways to work / About / Contact.
- Cut text volume: short paragraphs, images between.
- Type: Fraunces (display) + Inter (body).

## Held out entirely (BLOCKED)

- Every number Kumar proposed (30+ years, ~23,000 learners, 350-person org, $30M revenue growth, $40M enterprise). The Selected evidence row is qualitative and carries a visible hold note.
- Every institution name (University of Minnesota, Northeastern, SDSU, UCLA Extension). The page carries no place names.
- Both need Radhika's explicit sign-off on exact wording and her completed employer disclosure.

## Still RADHIKA DECIDES (surfaced on the repo index page)

Hero version · framework (Kumar's vs her own) · two pathways or three · UCLA Extension in or out · Perspectives yes/no and will she write three · testimonial contacts · consultation length 30 vs 20.

## Assets

- Hero: `assets/radhika-hero.jpg`, her own portrait, client supplied 2026-08-26, 4:5 crop. A direct senior portrait, plus speaking/facilitating and small-group shots, are the preferred final assets.
- The "career planning" figure and the newsletter figure are marked grey placeholders, not stock.

## Engineering

- Single file, no build step. Google Fonts (Fraunces, Inter). Sticky header, mobile nav, IntersectionObserver reveals, `prefers-reduced-motion` respected, client-side newsletter validation.
- Breakpoints at 1024px and 560px. No horizontal overflow at 375px.
- `.site-nav a.nav-cta` is fully qualified so its white text is not overridden by `.site-nav a` (0,1,1 vs 0,1,0).
- `noindex, nofollow` while it is a review artifact.
