# Radhika Seshan · Homepage · Consolidated concept (v2) — build notes

**Date:** 2026-08-28 · **For:** the Wix rebuild
**Source of truth:** `Frost/Projects/active/radhika-seshan-personal-brand/direction-v2.md`, `copy.md`, `design-direction.md`, `site-spec.md`

---

## What this is

The single homepage concept, built from the 2026-08-26 review call and Kumar Narayanan's forwarded AI analysis of the same evening. It replaces Concept One and Concept Two as the working direction. Concept One's calm, person-first editorial layout is the base; the numbered blocks, card structure and stronger section rhythm come from Concept Two.

## Decisions built in (LOCKED in direction-v2.md)

- Tone: supportive partner, not confident expert. No motivational-coach or guru register.
- Hero: name set large, portrait beside it, "A real world roadmap for career development" as the enlarged tagline, "you already have what it takes" reduced to a supporting line, one question ("What's your plan?") plus one plum button. No dual CTA, no duplicate name beyond the wordmark.
- Credibility line directly under the hero: titles only, no employer names, no numbers.
- "Own your journey" as three connected numbered blocks (01 Striving, 02 Positive action, 03 A real world roadmap), closing on "the roadmap is what we develop together, the journey stays yours".
- "Career planning, not just professional development" reframe, with the Bell Labs just-in-time-training story.
- Who she helps: three cards side by side (coaching, cohorts/workshops, speaking/advisory). Audience language is "mid career professionals" with women named inside, relocated professionals not "Indian professionals", no visa or immigration framing, futurist angle for organizations.
- "Experience that informs the work": three story-led panels, no metrics.
- Testimonials: visible placeholder block, marked "content pending client input".
- CTA band: a question ("What's your plan?"), the one dark band, plum on the button only.
- "New thinking, when there is something worth saying" kept verbatim.
- Palette: iron gray and true neutral grays (`--mist:#F3F3F4`, corrects the old brownish cast), plum `#5B2A46` on CTAs only. No sepia, pink, light brown.
- Type: Fraunces (display) + Inter (body). No italics anywhere. No underlines anywhere (emphasis is weight and colour).
- Nav: four items, Home / Offerings / Credentials / Contact.

## Where it takes the call's side, pending Radhika (RADHIKA DECIDES)

- Hero wording uses the call's direction, not Kumar's "brought you this far" line.
- Framework keeps her three (striving / positive action / real world roadmap), not Kumar's "see clearly / choose strategically / move deliberately".
- Three service cards, not two (Kumar's cohorts pathway is included).
- Credentials line carries no institution names at all, which sidesteps the UCLA in/out question. UCLA was an Associate Dean role, not a deanship, either way.
- Consultation reads 30 minutes.

## Held out entirely (BLOCKED)

- Every number Kumar proposed (learners served, org size, revenue growth, enterprise size).
- The employer / institution name. "A public university in Minnesota" is not even used here; the page carries no place names.
- Both need Radhika's explicit sign-off on exact wording and her completed employer disclosure.

## Assets

- Hero: `assets/radhika-hero.jpg`, her own portrait, client supplied 2026-08-26, 4:5 crop. A speaking or facilitating photograph is the preferred final asset.
- The "career planning" figure and the newsletter figure are marked grey placeholders, not stock. Kumar's caution: authentic Radhika photography only, steer away from the wellness-influencer aesthetic. Roxie Nafousi is the layout and type reference, not the photo mood.

## Engineering

- Single file, no build step. Google Fonts (Fraunces, Inter). Sticky header, mobile nav, IntersectionObserver reveals, `prefers-reduced-motion` respected, client-side newsletter validation.
- Breakpoints at 1024px and 560px. Hero, name and single CTA survive small screens.
- `noindex, nofollow` while it is a review artifact.
