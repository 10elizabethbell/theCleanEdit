---
name: The Clean Edit • Home + Closet
description: Cleaning and home organization by Jen, Sparta NJ. One page that ends in a text to Jen.
colors:
  linen: "#F3EFE8"
  linen-2: "#ECE5D9"
  mist: "#E5E7DA"
  ring: "#DCD2C4"
  sage: "#7B8A69"
  sage-deep: "#4E5D43"
  forest: "#2F3B2D"
  ink: "#262B23"
  ink-soft: "#545A4E"
  brass: "#A57A44"
  field-edge: "#958977"
  field-fill: "#FBF9F5"
  error: "#9A3B26"
typography:
  display:
    fontFamily: "Cormorant Garamond, Iowan Old Style, Palatino Linotype, Palatino, Georgia, serif"
    fontSize: "clamp(46px, min(13.4vw, 15svh), 104px)"
    fontWeight: 600
    lineHeight: 0.94
    letterSpacing: "0.035em"
  headline:
    fontFamily: "Cormorant Garamond, Iowan Old Style, Palatino Linotype, Palatino, Georgia, serif"
    fontSize: "clamp(32px, 8.4vw, 54px)"
    fontWeight: 600
    lineHeight: 1.02
    letterSpacing: "0.05em"
  title:
    fontFamily: "Cormorant Garamond, Iowan Old Style, Palatino Linotype, Palatino, Georgia, serif"
    fontSize: "clamp(25px, 6.6vw, 34px)"
    fontWeight: 600
    lineHeight: 1.1
    letterSpacing: "0.03em"
  voice:
    fontFamily: "Cormorant Garamond, Iowan Old Style, Palatino Linotype, Palatino, Georgia, serif"
    fontSize: "clamp(30px, 8vw, 44px)"
    fontWeight: 600
    lineHeight: 1.15
    letterSpacing: "normal"
  voice-small:
    fontFamily: "Cormorant Garamond, Iowan Old Style, Palatino Linotype, Palatino, Georgia, serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.02em"
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.6
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 600
    lineHeight: 1.2
rounded:
  check: "5px"
  field: "14px"
  card: "22px"
  pill: "999px"
  circle: "50%"
spacing:
  gutter: "20px"
  gutter-desk: "40px"
  seam: "26px"
  seam-desk: "38px"
  field-gap: "20px"
  band-top: "64px"
  band-bottom: "76px"
  band-top-desk: "96px"
  band-bottom-desk: "108px"
  container: "1160px"
components:
  button-primary:
    backgroundColor: "{colors.sage-deep}"
    textColor: "{colors.linen}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "58px"
  button-primary-hover:
    backgroundColor: "#43513A"
  button-secondary:
    backgroundColor: "transparent"
    textColor: "{colors.sage-deep}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "58px"
  button-on-forest:
    backgroundColor: "{colors.linen}"
    textColor: "{colors.forest}"
    rounded: "{rounded.pill}"
    height: "58px"
  service-arrow:
    backgroundColor: "transparent"
    textColor: "{colors.sage-deep}"
    rounded: "{rounded.circle}"
    size: "46px"
  service-arrow-hover:
    backgroundColor: "{colors.sage-deep}"
    textColor: "{colors.linen}"
  knot:
    backgroundColor: "{colors.linen}"
    textColor: "{colors.sage-deep}"
    rounded: "{rounded.circle}"
    size: "44px"
  facebook-card:
    backgroundColor: "{colors.linen}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "18px 20px"
  input:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "13px 16px"
    height: "54px"
  chip:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 14px"
    height: "48px"
  chip-checked:
    backgroundColor: "{colors.sage-deep}"
    textColor: "{colors.linen}"
---

# Design System: The Clean Edit • Home + Closet

## Overview

**Creative North Star: "The Freshly Made Bed"**

The page is undyed linen. A faint warp-and-weft weave sits over every ground, under every word. Sections are lengths of cloth sewn together: each band meets the one above along a slowly breathing wavy edge, with a turned-under hem strip and a running stitch. The hero's lower half is a rumpled sheet that the visitor smooths flat with a finger or mouse. Left alone, it smooths itself. Everything else stays still and tidy, because the product is a room that has just been put right.

The world comes from Jen's own logo: a cream round seal, a pale taupe ring, a sage olive sprig, high-contrast serif capitals and a small four-point sparkle. The cream becomes the ground, the ring becomes every hairline, the sprig's green is the single accent, and Cormorant Garamond capitals echo the lettering. Density is low. There is one column of copy, generous bands and very little chrome. The contact system is a text message: every primary control opens a pre-filled `sms:` to Jen.

The world rejects the stock sparkling-kitchen photo and the checkmark-list cleaning template (direction contract THESIS).

**Key Characteristics:**
- Linen ground with a woven slub texture (`body::before`, multiply, opacity .07) over the whole page.
- One accent, sage-deep, for buttons, hover arrows, knots and focus rings. Brass is reserved for form controls.
- Cormorant Garamond 600 in uppercase for names and headings, Cormorant italic for Jen's own voice, and the system sans for reading.
- Sections joined by sewn hems instead of rules or straight edges.
- One interactive signature (the sheet). Motion is ambient, cloth-like, and runs on one shared scheduler.
- The page ends on a forest-green close carrying the full logo seal.

## Colors

The palette is warm undyed textile with one green thread through it. It is low-chroma throughout, and the accent earns its weight by being the only saturated thing on screen.

### Primary
- **Sprig Sage** (sage-deep): the one accent. It fills the primary button, fills a service row's arrow on hover, colours the knot numerals, the phone glyph, the italic voice lines and the default `:focus-visible` ring (3px, 3px offset), and sets the page's `accent-color`.
- **Leaf Sage** (sage): a lighter step used only for small marks: the hero sparkle and the chip checkbox outline.

### Secondary
- **Brass Thread** (brass): the form's outline accent. Inputs, chips, the send button and the copy button turn brass on hover and focus. It is deliberately not the button fill (finishing rule: one accent for form outlines that stands out from the fill).

### Neutral
- **Undyed Linen** (linen): page ground, hero, How it works and the form band. It is also the sheet's exact flat colour, so smoothed cloth disappears into the page. Text on forest.
- **Pressed Linen** (linen-2): the Meet Jen band and the "text is ready" panel. One step darker, like a second sheet.
- **Sage Mist** (mist): the services band. The palest green wash.
- **Seal Ring** (ring): hairlines. It rings the brand mark, outlines the knots and borders the sent panel.
- **Forest** (forest): the close and footer ground, and the text colour of the inverted button on it.
- **Ink** (ink): headings and body text.
- **Soft Ink** (ink-soft): ledes, step copy, notes and secondary text.
- **Field Edge** (field-edge) and **Field Fill** (field-fill): the resting border and fill of every form control. These are hard-coded in the build rather than declared on `:root`, but are used consistently across inputs, chips and the sent textarea.
- **Error Rust** (error): error message text only. Invalid inputs take a lighter rust border (#B5583F).

### Named Rules
**The One Thread Rule.** Sage-deep is the only accent outside the form. Rows, cards and labels stay neutral at rest. The accent appears on hover, press or selection, never by default on something the visitor hasn't touched.

**The Brass-Is-For-Forms Rule.** Brass appears only as the hover/focus outline of controls inside the estimate form. It never fills anything and never appears outside the form.

**The Flat-Sheet Rule.** The hero canvas shades toward HI rgb(254,252,248) and LO rgb(182,172,154) around a base of exactly linen. Flat cloth must render as the page ground, pixel for pixel, so there is never a visible canvas edge.

## Typography

**Display Font:** Cormorant Garamond 600, roman and italic, subset and embedded as woff2 (with Iowan Old Style, Palatino, Georgia)
**Body Font:** System sans stack (-apple-system, Segoe UI, Roboto, Helvetica Neue, Arial)

**Character:** High-contrast bookish capitals, taken from the logo, sit over a plain native sans that reads instantly on a phone. Cormorant italic is the handwritten-note voice for Jen's own lines.

### Hierarchy
- **Display** (600, clamp(46px, min(13.4vw, 15svh), 104px), 0.94): the hero headline only, uppercase, 0.035em tracking. The svh term keeps it from crowding the phone's first screen.
- **Headline** (600, clamp(32px, 8.4vw, 54px), 1.02): section h2, uppercase, 0.05em, balanced wrap. On desktop the services, how and ask headings tighten to clamp(40px, 4.4vw, 52px).
- **Title** (600, clamp(25px, 6.6vw, 34px), 1.1): service row names and step titles (steps cap at 32px), uppercase, 0.03 to 0.04em.
- **Voice** (italic 600, clamp(30px, 8vw, 44px), 1.15): "Hi! My name is Jen." Jen's own words, sentence case.
- **Voice small** (italic 600, 17 to 19px, 1.2 to 1.3, 0.02em): the October special line and row tags, in sage-deep.
- **Lede** (400, clamp(17px, 4.7vw, 20px), 1.55): the hero promise, max 30em, in soft ink.
- **Body** (400, 17px, 1.6): reading text. Meet Jen paragraphs are 18px. Step copy is max 34em.
- **Label** (600, 16px): form labels, the tel link and knot numerals (17px). Optional markers are 400 in soft ink. Notes are 15px.
- **Wordmark** (600, 22px, 0.06em, uppercase display): header brand and footer name. On narrow phones it steps down to 18, 16 and 15px.

### Named Rules
**The Logo Capitals Rule.** Every display-face heading is uppercase with positive tracking (0.03 to 0.06em). Sentence case in the display face is reserved for italic, which means Jen speaking.

**The Native Reading Rule.** Paragraphs, labels, buttons and form text use the system sans. The serif never sets running text.

## Layout

The layout is a single centred container (max 1160px) with a side gutter of 20px on phones and 40px from 960px up. Each section is a full-bleed band with its own ground colour. Band padding is 64px top and 76px bottom, rising to 96px and 108px on desktop.

- **Hero:** fills the first screen (min-height calc(100svh - 60px)). It is one column on phones: copy on top, with the sheet zone filling the remaining height (min 200px). At 960px and up it becomes a row: a 560px copy column beside the sheet zone, capped at min(100svh - 64px, 860px). The hero buttons stack below 600px and sit side by side above it.
- **Two-column bands (≥960px):** Services, Meet Jen and the form use a 5fr / 7fr grid with a 64px gap. The left column ("side") holds the heading and is sticky at top 40px.
- **How it works:** a vertical list on phones. From 960px it becomes three equal columns with a 48px gap, and the thread turns horizontal.
- **Form:** fields use a 20px gap. Paired fields go side by side from 1024px. Chips form a 2-column grid on phones and a wrapping row from 600px.
- **Close:** centred column, and the footer sits inside the forest band.
- **Tap targets:** at least 44px everywhere (header links 48, buttons 58, rows 72, chips 48, footer links 44).

## Elevation & Depth

Depth comes from cloth: the weave texture, the hem's soft shadow and the sheet's lit folds, not from floating panels. Surfaces are flat. Only four soft, low, warm-tinted shadows exist, and none are hard-offset.

### Shadow Vocabulary
- **Hem lift** (`filter: drop-shadow(0 -2px 2.5px rgba(70,58,38,.12))`): every seam. The upper cloth casts a hair of shadow onto the band below.
- **Button press** (`box-shadow: 0 6px 12px -8px rgba(47,59,45,.6)`): the filled sage button only.
- **Card rest** (`box-shadow: 0 14px 30px -16px rgba(60,50,30,.42)`): the Facebook card, the one raised object on the page.
- **Seal** (`box-shadow: 0 18px 40px -16px rgba(0,0,0,.55)`): the logo seal on forest.

### Named Rules
**The Cloth-Not-Cards Rule.** New content goes on a band, joined by a sewn hem, not in a floating card. A card shadow is reserved for something the visitor taps that leaves the page (the Facebook card).

## Shapes

The form language is round and soft, like the logo seal. Buttons and chips are full pills (999px). Arrows, knots, the brand mark, the Facebook glyph and the seal are perfect circles. Inputs use 14px corners, the Facebook card 22px, and the sent panel 18px. Chip checkboxes are rounded squares (16px, 5px radius) so a multi-select reads as a checkbox, not a radio. Borders are 1.5px everywhere a control has one. Hairline dividers are 1px sage at 22% alpha.

Section edges are never straight. Each band's top is a live wavy cloth edge with an 11px hem strip and a 2px dashed running stitch (6/5 dash, round caps). Dashed stitches are native to this world: they draw the hem and the How it works thread.

## Components

### Header
The header is quiet and organized. On the left is the brand: a 42px circular logo mark with a 1.5px ring halo and the wordmark in display caps. On the right is the phone number as plain tabular-numeral text, a `tel:` link with a sage phone glyph (the glyph is hidden below 520px). It is not sticky and not a button. Hover turns the number sage-deep.

### Buttons
- **Shape:** full pill (999px), 58px min height, 26px side padding, 1.5px sage-deep border, 600 17px system sans, optional 20px leading icon.
- **Primary (filled):** sage-deep fill, linen text, button-press shadow. Hover darkens the fill to #43513A. Press moves it down 1px.
- **Secondary (outlined):** transparent with sage-deep text and border. Hover adds an 8% sage tint.
- **On forest:** the primary inverts to a linen fill with forest text (hover white), min width min(100%, 320px). The focus ring there is linen.
- **Form send:** the primary button, but hover adds a 3px brass halo and focus uses a brass outline (it follows the form rule).
- **Hero:** two buttons at most: filled "Text me for an estimate" (sms) and outlined "Tell me about your home" (anchor to the form).

### Service Rows
These are the tappable list. Each row is a full-width link (72px min) between 1px sage hairlines, holding an uppercase title (with an optional italic sage tag such as "October special") and a 46px circular arrow at the right. At rest the arrow has a 35% sage outline and a sage glyph. On hover, focus or press **only the arrow changes**: it fills sage-deep with a linen glyph. Keyboard focus puts the 3px ring around the arrow, never the row. The row itself never gets an outline, background or shadow. Each row opens a service-specific pre-filled text.

### How It Works Thread
Three numbered steps hang on a 2px dashed sage thread (60% alpha). Each step starts at a "knot": a 44px linen circle with a ring border and a sage-deep numeral. The thread runs vertically on phones (left 21px) and horizontally between the knots on desktop. The knots are decorative (`aria-hidden`) and have no hover state, because they are not controls.

### Meet Jen + Facebook Card
Jen's line is in the italic voice. Her body copy is 18px soft ink. Under it is the one raised object: a linen card (22px radius, card-rest shadow) with a 52px circular Facebook glyph, "See my work / on Facebook", and the standard row arrow. Hover changes only the arrow, matching the rows. The Facebook link sits here, where proof would be, and again in the footer.

### Inputs / Fields
- **Style:** field-fill background, 1.5px field-edge border, 14px radius, 54px min height (textarea 110px, no resize), 17px text, sage caret, placeholder #6B6E63.
- **Hover:** brass border plus a 1px brass ring.
- **Focus:** brass border plus a 3px brass glow at 28% (rgba(165,122,68,.28)). The native outline is removed.
- **Error:** rust border (#B5583F) and a 15px 600 rust message under the field. The first invalid field takes focus.
- **Labels:** 600 16px above the field. Optional fields say "(optional)" in soft ink.

### Chips (multi-select)
Chips are pill checkboxes (48px min, 14px padding) with field fill and field edge at rest, and a 16px rounded-square checkbox (5px radius, sage border) leading the label. Hover gives a brass border and ring. Keyboard focus gives a brass glow. Checked chips fill sage-deep with linen text, and the box turns linen with a sage tick. Checked plus hover keeps the brass border. They are only used for real choices inside the form.

### Sent Panel
After submit, the form opens the messages app and reveals a pressed-linen panel (18px radius, ring border) with the composed message in a read-only textarea and an outlined pill "Copy message" button (brass halo on hover and focus).

### Close + Footer
The close is a forest band with a linen stitch. It is centred: the full logo seal (150px circle, seal shadow), Jen's own line as a linen headline, and the inverted primary button. The footer sits inside it behind an 18%-linen hairline: the wordmark name, "Cleaning & home organization · Sparta, NJ", then the phone number and a Facebook link (44px targets, linen). Any future email goes here and nowhere else.

### The Sheet (signature)
The sheet is a canvas heightfield of rumpled linen behind the hero's lower half. It is lit from the upper left, valleys sit in their own shade, and folds cast short shadows beside them. It is flat (exact linen) behind the copy, with a soft wobbling edge so no fold runs through text.
- **Input:** a mouse anywhere in the hero, or a finger in the sheet zone (`touch-action: none` there only, so the page still scrolls from the copy). The hero position is re-read every frame. A stroke flattens folds within its brush and pushes a soft ridge of fabric ahead of the hand. Folds then settle back.
- **Self-smoothing ghost:** after 5s with no touch, an invisible hand traces a slow Lissajous path (x speed 0.7, y speed 1.4) through the sheet zone at 0.6 strength.
- **Tunables (`SHEET`):** `CELL_PHONE/DESK` 3/4 (sim px per cell), `CREASES_PHONE/DESK` 22/26 (broad drapes), `FINE_PHONE/DESK` 26/40 (small crisp wrinkles), `FOLD_HEIGHT` 15 and `FOLD_WIDTH` 22 px, `BRUSH` 58 (smoothing radius px), `SMOOTH` 0.8 (how fast a stroke flattens), `REGROW` 0.0032 (per-frame settle-back), `GHOST` 0.6 (ghost hand's gentleness), `BUNCH` 2.2 / `BUNCH_DECAY` 0.93 (ridge pushed ahead of the hand), `BREEZE` 1.5 / `BREEZE_AMP` 4.2 (slow billow speed and px), `COPY_PAD` 18 / `FADE` 200 / `FADE_PHONE` 80 (flat clearance and fade distance around the copy), `IDLE_RESUME` 5000 ms (wait before the ghost starts), `MAX_DPR` 2. The seeded RNG (20261019) makes the rumple identical on every load.
- **Economy:** only cells that are visible get simulated (the mask's bounding box). The loop pauses when the hero is off screen. An address-bar resize keeps what the visitor did. The mask re-measures after the display font loads.

### Sewn Hem (signature)
An SVG at the top of each band, `--seam` tall (26px, 38px on desktop), with three paths: **cloth** (filled in the band's `--bg`, the wavy edge), **fold** (an 11px hem strip, the band colour mixed 10% toward #8a7a60) and **stitch** (a dashed line along the hem's middle, coloured from `--stitch`: sage by default, warm brown on Jen's band, linen on forest).
- **Tunables (`SEAM`):** `STEP` 14 (px between points), `A1` 3.2 / `A2` 1.6 / `A3` 2.4 (amplitudes of the three sine layers), `SPEED` 1 (time scale), `HEM` 11 (hem strip depth), `PUSH` 7 / `PUSH_R` 90 (how far and how wide the cloth lifts when the pointer comes near), `FLUTTER` 1.6 / `FLUTTER_DECAY` 0.94 (extra wave amplitude after a fast scroll, and how fast it calms). Each seam is phase-offset by index.

### Motion system
- **One scheduler.** `Loop` is a single shared requestAnimationFrame. Jobs return true to keep running, and the loop stops itself when every job is idle. Input and IntersectionObservers `kick()` it back on. New motion must register as a Loop job, never a second rAF.
- **Reduced motion:** the page scrolls smoothly only without the preference. With `prefers-reduced-motion: reduce`, the breeze is frozen, the ghost never runs, and the sheet loop runs only for 4s after the visitor's own stroke. Seams draw once (redrawn on resize) with no breathing, flutter or pointer lift. The form's scroll-to-result is instant.
- **UI transitions:** 0.2 to 0.25s colour, border and shadow transitions. The button press is a 0.15s 1px translate. Nothing enters on scroll.

## Do's and Don'ts

### Do:
- **Do** put the phone number in the header's top-right as a `tel:` text link, and nowhere else on the first screen. The footer may repeat it.
- **Do** keep the hero to a short display headline, Jen's promise, and at most two buttons (filled text, outlined secondary).
- **Do** make every primary action an `sms:` to Jen with a pre-filled body, and let the form hand off by text.
- **Do** put the Facebook link where proof lives (under work photos once they exist, the Meet Jen card today) and in the footer.
- **Do** change only the arrow on row hover, focus and press: neutral circle at rest, sage-deep fill when engaged, focus ring on the arrow.
- **Do** outline every form control (fields, chips, send, copy) in brass on hover and focus, and only form controls.
- **Do** join new sections with a sewn hem and set the band's `--bg` (and `--stitch` when the ground needs a different thread).
- **Do** keep the sheet flat behind any text it sits under, and keep it rendering exact linen when smooth.
- **Do** run new motion through `Loop`, pause it off-screen, and give it a reduced-motion state that only moves under the visitor's own input.
- **Do** use only Jen's facts. Gaps (photos, towns, prices, reviews, email) stay gaps. Time-limited offers carry `data-until` so they disappear on their own.
- **Do** keep raster provenance with the files: the logo, favicon (`assets/favicon-64.png`) and touch icon (`assets/apple-touch-icon.png`) come from the business's Facebook profile image (fetched 2026-10-19). `assets/og.png` was composed in Chromium from the page's own type and logo.

### Don't:
- **Don't** add a sticky bottom bar or a fixed contact banner.
- **Don't** put a Call button under the hero title, or show the number twice on one screen.
- **Don't** add email buttons, links or prompts. An email, if Jen supplies one, goes in the footer only.
- **Don't** outline, tint or shadow a service row (or any arrow row) on hover.
- **Don't** style non-interactive labels (row tags, knots, the special line, any future town list) as pills, chips or buttons. Town names are plain text.
- **Don't** introduce a second accent outside the form, or use brass as a fill.
- **Don't** invent facts: no prices, discount amounts, reviews, towns, years, insurance or "free estimate" claims Jen hasn't made.
- **Don't** let pattern, fold or stitch lines run through text.
- **Don't** set running text in Cormorant, or set the display face in sentence-case roman.
