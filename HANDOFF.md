# The Clean Edit • Home + Closet — handoff at ~60%

**Live:** https://10elizabethbell.github.io/theCleanEdit/ · **Repo:** https://github.com/10elizabethbell/theCleanEdit · **Built:** 2026-10-19 from Muse brief (run 2026-10-19, found via a "Morris County Business Network" group post)

## What's built
- One page, `index.html` (single file, ~98KB with two font subsets and the logo embedded; no photos exist yet).
- **World: a freshly made bed.** Undyed-linen ground (#F3EFE8, from Jen's cream logo) with a faint warp/weft weave over the whole page, sage accent from the logo's leaf, Cormorant Garamond capitals and italics to echo the logo lettering, sections joined by "sewn hems" (a breathing wavy cloth edge, a turned-under hem strip and a running stitch) that flutter when you flick the page.
- **Signature element:** the hero's lower half is a rumpled linen sheet (canvas cloth heightfield). Mouse or finger smooths the folds flat and pushes a soft ridge of fabric ahead of the hand; the folds settle back over a few seconds. When nobody touches it for 5s, an invisible hand smooths it by itself. Reduced motion: still picture that only moves under the visitor's own finger. All tunables are the `SHEET` / `SEAM` constants at the top of each script block; one shared animation loop. Behind the text the sheet is pulled flat so nothing runs through the words. Phone drag works in all directions (touch-action none on the sheet area only, so the page still scrolls from the text area).
- Sections: header (sprig mark + wordmark, 908-414-1740 top right) → hero ("Your home, edited.", Jen's promise, Text / Tell me about your home, October specials line) → What I do (6 rows, each opens a pre-filled text) → How it works (3 steps on a stitched thread) → Meet Jen ("Hi! My name is Jen." + "See my work on Facebook" card + "Based in Sparta, NJ") → estimate form (turns into a text, with copy fallback) → forest-green close with the full logo seal, "Creating spaces that feel like home." (her own page line) + footer.
- Impeccable: every mode except live run (critique, audit, harden, optimize, polish, layout, typeset, adapt, clarify, bolder, quieter, distill, colorize, animate, delight, overdrive, finish review); fixes applied, finishing-rules checklist re-checked. Detector ignores recorded in `.impeccable/config.json` (cream ground = her logo; Roboto = system stack; short caps names; two false positives).
- **October special auto-hides after 2026-10-31** (`data-until` attributes; one date in the HTML).
- Contact: every button is `sms:+19084141740` with a pre-filled body; the number in the header and footer is `tel:`. No email anywhere (none exists).
- Favicon / home-screen icon: the sprig from her logo. Facebook preview card: `assets/og.png`.

## Assumptions I made
- **Location Sparta, NJ** comes from her Facebook page title ("The Clean Edit • Home + Closet | Sparta NJ"), not the brief. The brief said don't infer Morris County from the group; I didn't, and I list no towns.
- **Services** = post (deep, standard cleaning) + Facebook page description ("Professional home & closet organization, decluttering, & residential/commercial…", cut off there) + logo subtitle "Cleaning & Home Organization". "Commercial cleaning" is inferred from the truncated "residential/commercial…"; confirm with Jen.
- Colors and type from the logo (cream, taupe ring, sage leaf, high-contrast serif caps, four-point sparkle).
- One-person business → first person "I/my" throughout.
- Copy I wrote in her voice (hers to approve): headline "Your home, edited.", the promise ("I'm Jen. I clean and organize homes, and I treat yours like it's my own, right down to the back of the closet"), the Meet Jen paragraphs, How it works steps. Verbatim from her: "Hi! My name is Jen." and "Creating spaces that feel like home."
- The hero's October line names deep and standard cleaning. I read it as the offer, not a services list (finishing rule), but it's your call; it disappears Nov 1 anyway.
- Facebook link says "See my work / on Facebook" instead of "Click to see more of my work.": there are no photos on the page yet, and "click" is wrong on phones.
- I don't say estimates are free (she never said so).
- Audience treated as general homeowners (age not stated), so the signature motion is on. If Jen's customers skew 40+, switch to the still-picture rules in `older-audience.md`.

## Placeholders and gaps
- **No photos of her work** (the ad was text-only). The proof section is the Facebook link only. Top ask at outreach: 3–6 work photos, before/afters if she has them (closets especially).
- No reviews, prices, hours, email, last name, years in business, insurance.
- October special has no amounts; the page just says "October specials on deep and standard cleaning" until Oct 31.

## Questions for the owner
1. Photos: can you send a few jobs, especially before/after closets?
2. Which towns do you travel to around Sparta?
3. Is commercial cleaning something you offer?
4. Any reviews from customers (Facebook recommendations, texts you can share)?
5. Email address for the footer?
6. What's the next special after October (holidays)? The hero line can swap to it.
7. Is "Home organizing" / "Closet organizing" how you'd name those, or something else?

## Ideas not built (yours to pick)
- **Runner-up world:** a steamed bathroom mirror you wipe clear with a cloth (fog + droplets regrowing). Other candidates: rising soap suds, folded linen closet shelves, sage sprig that sways, sunlit dust motes, an editor's proof page ("edit" pun).
- Once photos exist: before/after sliders (closets are perfect for this) framed as folded linen; photo cards that "unfold" like a turned-down sheet.
- A holiday-cleaning special block that swaps in on Nov 1 (same `data-until` mechanism, add `data-from`).
- Weave strength: `body::before` opacity .07. Raise for more linen, drop to 0 if it ever reads as a film.
- A `book.html` with the same form at full page, if Jen wants a link to share in group posts.

## Not verified
- Real-device touch on iPhone/Android inside Facebook's in-app browser (tested headless Chromium + WebKit with simulated touch and mouse).
- That the `sms:` body actually pre-fills on iOS and Android messaging apps.
- Frame rate on old phones (sim runs ~20k cells/frame on phones).
