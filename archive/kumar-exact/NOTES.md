> **Frozen reference.** This is Kumar's mockup reproduced byte for byte, kept so the working concept can be compared against it. Do not edit. The live concept is in `../../concept-1/`.

---

# Concept 1 — exact copy of Kumar's mockup

**This is not our design.** It is a byte-faithful static recreation of the AI built
mockup Radhika's husband Kumar produced and Radhika forwarded on 2026-08-26.

- **Source:** https://radhika-seshan-career-strategy.ksn69433.chatgpt.site
- **Captured:** 2026-09-02
- **Purpose:** hold Kumar's direction as concept 1 in our own tree, so concept 2 can be
  built against it as a like for like comparison instead of against a link on his account
  that may stop resolving.

## What the original was

A Vite RSC ("vinext") React app, server rendered. The HTML the server returns already
contains the complete markup; the JavaScript bundle only hydrated it.

## What we changed, and nothing else

| Change | Why |
|---|---|
| Removed all 11 `<script>` tags | RSC hydration payload (a duplicate of the markup), the module entry point, and a Cloudflare challenge script. None of them render anything. |
| Removed 5 `modulepreload` links | The JS they preloaded is gone. |
| Removed the `data-rsc-css-href` / `data-precedence` attributes | React RSC bookkeeping, no effect on rendering. |
| Rewrote `/assets/...` to `assets/...` | Absolute paths would break when served from a subdirectory. |
| `<meta charSet>` to `<meta charset>` | React's JSX casing is not valid HTML. |
| Dropped the 4 JS bundles from `assets/` | Unreferenced after the above. |

No markup, no text, no CSS, no image was altered. The stylesheet and the hero photograph
are the original files, unmodified.

Result: 36,045 bytes to 12,009 bytes of HTML; 8 files to 4; 280KB total.

## Verification

Rendered side by side against the live original in headless Chromium.
Full page screenshots are **byte identical** (matching MD5) at all three widths:

| Viewport | Result |
|---|---|
| 1440 x 9000 | identical |
| 1024 x 9000 | identical |
| 390 x 12000 | identical |

## Carried over from the original, deliberately not fixed

These conflict with the project's own constraints. They are left in place because this
folder is a faithful copy, not our recommendation. Fix them in concept 2, not here.

- **Uncleared metrics.** The evidence row shows `30+`, `23,000`, `350`, `$30M`.
  Every one of these is BLOCKED in `direction-v2.md` pending Radhika's sign off.
- **Institution names.** Named universities appear in the markup. Her current employer
  disclosure has not cleared (`01-brief.md`).
- **Copy rules from the 2026-08-26 call.** The original does not follow them: it uses
  italics, and its audience and framing language was not written against the call.

## Sections in the original

`hero` · `credential-strip` · `story#about` · `services#work` · `approach#approach` ·
`experience` · `topics` · `perspectives#perspectives` · `validation` · `contact#contact`
