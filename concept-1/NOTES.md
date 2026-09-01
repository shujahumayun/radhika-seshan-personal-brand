# Concept 1 — Kumar's layout, Radhika's words

**Built:** 2026-09-02
**Inner pages added:** 2026-09-02
**Design source:** Kumar's mockup, `https://radhika-seshan-career-strategy.ksn69433.chatgpt.site`
**Copy source:** the 2026-08-26 review call, via `copy.md` and `direction-v2.md` in the Frost project folder
**Kumar's version, byte exact and untouched:** `../archive/kumar-exact/`

Kumar's design is kept. Every word on the page was replaced with the copy agreed on the call.
Where the call and Kumar disagree, the call wins, because Radhika said it live.

## Copy, section by section

| Section | What it says now | Where it came from |
|---|---|---|
| Hero | "A real world roadmap for career development." plus "You already have what it takes. The next step is a strategy for what comes next, and someone to build it with you." | `direction-v2.md` rows 9 and 39. Kumar's line ("Your experience has brought you this far…", row 40) is still a live option and sits in the archived version |
| Credibility strip | PhD in economics · Vice President of Product Management · Dean at multiple universities | Row 29, titles not employers, no numbers. Replaced Kumar's four items, one of which was "three decades of reinvention" |
| 01 Career planning | "Career planning, not just professional development", the Bell Labs move, the "intentional planning, sometimes a little serendipity" line | Rows 27 and 28, both LOCKED. Replaced Kumar's "I know what it means to build and rebuild a career" |
| Ways to work together | Three cards: individual career strategy, cohorts and groups, organizational advisory and speaking | Kumar's three pathways (row 18) kept, filled with the call's audience language: "mid career professionals" not "mid career women" (row 19), "ready to take the next step" not "ready to move" (row 22), no visa or immigration framing anywhere (row 21) |
| 02 The approach | "Own your journey", then striving → positive action → a real world roadmap | Row 24. Her framework, connected end to end, in Kumar's numbered layout. "Real world roadmap" lands in the third slot, which is where row 25 puts it. Replaced Kumar's "see clearly, choose strategically, move deliberately" |
| Experience | Same three panels, rewritten in first person | Row 3 |
| Workshops and speaking | Kumar's four topics, kept | Consistent with row 23, the futurist framing |
| Perspectives | "New thinking, when there is something worth saying." | Row 4, LOCKED, her favourite line on the site, used verbatim |
| Client stories | Placeholder kept | Row 51 |
| Contact | "What's your plan?" and "A free 30 minute conversation. No pitch." | Rows 42 to 44. The CTA had to become a question. "Let's sit down and dream together" is dead |

## Taken out and staying out

Everything below was on Kumar's mockup and is now gone. It comes back only when Radhika signs off on the exact wording **and** her employer disclosure is done.

- The four figure evidence strip: 30+, 23,000, 350, $30M (`direction-v2.md` rows 32 to 35, all BLOCKED). The whole band was removed rather than left half filled.
- "University of Minnesota" (row 31, BLOCKED). The footer line now reads "a public university in Minnesota".
- "Three decades of reinvention" from the credibility strip. Same problem as 30+ years.
- UCLA Extension, off the strip per Radhika's call decision (row 30). If it goes back on, it is Associate Dean, never Dean.

## Design changes

Four, and only four. Everything else is Kumar's.

1. **Background is pure white.** `--paper`, `--paper-warm` and `--white` all set to `#fff`. The warm sepia ground was rejected twice on the call (row 46).
2. **Portrait is square with soft rounded corners.** Was an arch (`border-radius:48% 48% 10px 10px`), now `18px` on a 1:1 crop. The decorative offset frame behind it matches.
3. **No italics on copy.** The kicker, the pull quote and the coloured hero words were italic. Row 8, raised twice unprompted, no italics and no underlines.
4. **Testimonial placeholder** got a light grey fill, because its translucent white was invisible once the ground went white.

## Still to decide, and still wrong

- ~~The decorative numerals are still italic.~~ **Fixed 2026-09-02.** 01/02/03, I/II/III and the Perspectives numerals are now upright. Row 8 was raised twice and does not carve out decoration.
- **`hello@radhikaseshan.com` is invented.** Kumar's mockup used it. Radhika has not created a dedicated site email yet, and her personal Gmail should not go on a public page without her saying so. Placeholder until she answers.
- **The LinkedIn URL is unverified.** `linkedin.com/in/seshanr` came from Kumar's mockup. Her real profile URL is still on the list of things owed.
- **The hero, the framework and the two-versus-three audience question are all hers to answer.** This build picks one working answer to each so there is something to react to. It is not a decision.

---

# The inner pages

Added 2026-09-02. Same design, same stylesheet, same type. Structure follows the sitemap agreed on the
2026-08-26 call and recorded in `site-spec.md`: roughly four items, offerings and credentials and contact.

| Page | File | What is on it |
|---|---|---|
| Offerings | `offerings.html` | One page, not three. Overview cards, then coaching, then cohorts and groups, then advisory and speaking, each with its own anchor |
| About | `about.html` | The four chapters from row 15, in first person, closing on a short bio download |
| Writing | `writing.html` | Blog index. Three sample pieces, marked as samples |
| Sample article | `writing-post.html` | The reading layout, so the blog structure can be judged. Every word is filler |
| Contact | `contact.html` | Name, email, what you are reaching out about, message. Plus the disclosure line |

## Copy provenance for the new pages

- **Offerings** takes the three audience blocks from `copy.md` and expands each. Coaching carries her own
  mechanic from the call: you know the destination but not the route, she draws route options from
  experience, you choose one together, then after each step she asks whether it got you where you needed
  to be and what to pivot, and she holds you accountable. Advisory carries the futurist framing (row 23).
- **About** follows Kumar's four chapters (row 15) and stays inside cleared facts: PhD in economics, Bell
  Labs and the object oriented programming trip, product management across the US and the UK, Northeastern
  and San Diego State by name, Minnesota unnamed. No tenure counts, no student numbers, no Lucent (it came
  from the intake, not from her).
- **Contact** uses the closing CTA copy from rows 42 to 44 and adds the disclosure friendly line the spec
  asks for: offered in a personal capacity, no university endorsement implied.
- **Writing** opens on row 4 verbatim, her favourite line. The three sample titles are the same candidates
  already on the homepage Perspectives band. The article body is filler and says so on the page.

## Design decisions on the new pages

Everything reuses Kumar's components. A second stylesheet, `assets/pages.css`, holds what the homepage
never needed. His bundle is not edited further.

1. **Page hero.** Smaller than the homepage hero, same face and same rhythm.
2. **Chapters** on About are the homepage story block with tighter padding and a rule between each.
3. **Form fields** are new. Filled grey boxes rather than bare underlines, because bare underlines read as
   loose rules sitting under the labels rather than as fields.
4. **Post cards** mirror the Perspectives cards, retuned for a white ground.
5. **Mobile navigation is new.** Kumar's build hid the nav below 1050px and put nothing in its place. That
   was survivable on one page and is not survivable now. A plain row of links, no JavaScript.

## Open on the new pages

- **The contact form does not submit anywhere.** It is a static mockup. Wix wires the real one, and the
  destination is `radhika.seshan@gmail.com` until she creates a dedicated site email.
- **The short bio download points at nothing.** The file does not exist yet.
- **`hello@radhikaseshan.com` and `linkedin.com/in/seshanr` are still unverified.** Same as the homepage.
- **Writing is in the nav as a real page.** The call left this open: writing may live on Substack, in which
  case this page becomes a link out and the sample layout is thrown away. Row 16, research still owed.
- **Media & Press is not built.** The spec says it may fold into About. Waiting on her links list.
- **Reading times on the sample cards are invented.** They come out when real pieces go in.

## Perspectives / Writing photography

Three free Unsplash photos, added 2026-09-02, sit inside the numbered art
tiles on the homepage Perspectives grid and the Writing page's post cards:
a forest gravel path (career strategy), sunlight through blinds (future of
work), an open notebook and pen (professional learning). Desaturated and
multiplied under Kumar's original rose/plum/clay gradient washes so the
numerals and palette are unchanged. Same three images reused on concept 2.
Credits: paws and prints, Phil Hearing, Clay Banks. Placeholder photography,
standing in for whatever image accompanies each real essay once one exists.
