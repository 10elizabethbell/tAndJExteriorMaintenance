---
name: T&J Exterior Maintenance
description: Dusk on a Jersey Shore street; a phone-first pitch site where the visitor pressure-washes a dirty house and driveway under a fall tree that drops its leaves.
colors:
  navy: "#16263a"
  navy-2: "#1d3149"
  navy-3: "#0f1c2b"
  ink: "#16263a"
  cream: "#f3eee5"
  cream-2: "#e7e0d3"
  orange: "#e8892b"
  orange-hi: "#f29a3f"
  rust: "#b5502a"
  gold: "#e6b44a"
  mist: "#cfe3f0"
  text-on-dark: "#f3eee5"
  muted-on-dark: "#b7c3d1"
  muted-on-light: "#4f5b69"
  field-line: "#8f8676"
  field-fill: "#fffdf8"
  error: "#a3361b"
  error-line: "#c4502a"
  rust-text: "#9c3f1d"
  placeholder: "#6d7480"
  dusk-sky: "#24405f"
  dusk-floor: "#223c5a"
  pitch-on-scene: "#d6dee8"
  scene-shadow: "rgba(10,18,30,.6)"
  panel-text: "#3a4552"
  ticket-line: "#cfc7b8"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.35rem, 10.6vw, 5.4rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 8.4vw, 3.8rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  pitch:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(16px, 4.5vw, 20px)"
    fontWeight: 400
    lineHeight: 1.4
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 800
    lineHeight: 1.55
  button:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
  display-close:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.3rem, 10vw, 5rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  display-desktop-hero:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(3.2rem, 4.6vw, 4.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  promise-quote:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.5rem, 6.2vw, 2.4rem)"
    fontWeight: 900
    lineHeight: 1.08
    letterSpacing: "-0.02em"
  card-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "24px"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  promise-title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "19px"
    fontWeight: 900
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 500
    lineHeight: 1.5
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 800
    lineHeight: 1.1
    letterSpacing: "0.06em"
  hint:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 700
    lineHeight: 1.55
  tag:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "0.04em"
rounded:
  focus: "10px"
  pill: "999px"
  card: "24px"
  field: "14px"
  circle: "50%"
spacing:
  gutter: "20px"
  chip-gap: "10px"
  stack: "14px"
  section-top: "64px"
  section-bottom: "72px"
  column-gap: "64px"
  container: "1180px"
  button-height: "56px"
components:
  button-primary:
    backgroundColor: "{colors.orange}"
    textColor: "{colors.navy}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "{spacing.button-height}"
  button-primary-hover:
    backgroundColor: "{colors.orange-hi}"
    textColor: "{colors.navy}"
  button-ghost:
    backgroundColor: "rgba(22,38,58,.55)"
    textColor: "{colors.text-on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 22px"
    height: "{spacing.button-height}"
  button-ghost-on-light:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    height: "{spacing.button-height}"
  chip:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 16px"
    height: "46px"
  chip-selected:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.cream}"
  input:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "12px 14px"
    height: "52px"
  quote-card:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.ink}"
    rounded: "{rounded.card}"
    padding: "22px 18px 24px"
  service-row-cue:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.cream}"
    rounded: "{rounded.circle}"
    size: "44px"
  service-row-cue-fall:
    backgroundColor: "{colors.orange}"
    textColor: "{colors.navy}"
  hero-hint:
    backgroundColor: "rgba(22,38,58,.78)"
    textColor: "{colors.text-on-dark}"
    typography: "{typography.hint}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
  town-pill:
    backgroundColor: "{colors.field-fill}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "8px 14px"
---

# Design System: T&J Exterior Maintenance

## Overview

**Creative North Star: "Dusk on a Jersey Shore Driveway"**

The whole system is one evening scene. Dark sections are the navy dusk T&J's own site already uses; light sections are clean concrete in daylight; orange is both T&J's accent and the fall leaf. The trade's own job carries the proof: there are no before/after photos, because the hero is a dusk street scene (a big fall tree, a dirty house, a driveway running down from its garage) and the visitor's finger is the pressure wand. The "after" is whatever they wash themselves, and the grime creeps back so the job is never quite done. Leaves fall from the tree, settle on the roof, yard and driveway, and get blown about by the same pointer that washes. Water seams sheet across every section boundary.

It is built for a phone held in one hand inside Facebook's in-app browser. Density is low and the targets are big: 56px pill buttons at full width, 44px-plus everything else, and a sticky thumb bar once the hero buttons scroll away. Type is the system font stack set heavy and uppercase for headings (the stack is a PRODUCT.md constraint for this pitch site: fast inside the in-app browser), with plain sentence-case body.

It rejects the stock-hero and icon-card template of the client's current lovable.app site, and it rejects black grounds: the deepest surface (footer) is still blue.

**Key Characteristics:**
- Navy/cream alternating grounds joined by animated wet-edge seams, never a straight color edge.
- One accent, orange, used for the primary action, the leaf and the focus ring on dark grounds (navy on cream, for 3:1).
- One button component: same 2px orange outline, same 56px height, two fills.
- A living hero drawn from the trade's own job (a dirty house, a driveway, a fall tree, water, leaves) that reacts to finger and mouse.
- Everything animated runs on one shared loop, pauses off screen, and becomes a still frame under reduced motion.

## Colors

A two-ground palette (navy dusk, cream concrete) with a single warm accent; every other hue is either the accent's own family (rust, gold in the leaves) or water (mist).

### Primary
- **Leaf Orange** (`orange`): the primary-button fill, the 2px outline shared by every button, the `em`/`span` accent words in the hero and closing headlines, numbered step discs, the "This season" fall row wash, the focus ring on dark grounds (on cream, in the quote card and light sections, the ring is navy), text selection, caret, and the center line of each wet seam. It is the leaf and the call to action at once, so it stays rare on any one screen.
- **Lit Orange** (`orange-hi`): hover fill of the primary button only (desktop, `hover:hover`).

### Secondary
- **Rust Leaf** (`rust`): photo-hint icon in the quote card, and a member of the leaf sprite palette. Reserved for warm detail inside light surfaces.
- **Rust Text** (`rust-text`): the "Not on the list? Ask anyway." line under the town pills; the text-safe rust on cream.
- **Dry Gold** (`gold`): leaf sprite palette only (canvas). Not used on UI chrome.

### Tertiary
- **Spray Mist** (`mist`): water. The two outer lines of each wet seam (as `rgba(207,227,240,.55/.4)`), and the family of the spray droplets (`rgba(214,234,248,.85)`) and the wet sheen the wand leaves on siding and concrete. Never a UI fill.

### Neutral
- **Dusk Navy** (`navy`): page ground, hero base, close base, primary-button text, selected-chip fill, service-row cue disc, promise discs. `ink` carries the same value as the text color on cream.
- **Deep Dusk** (`navy-2`): the quote section ground; one step lighter than the page so the cream quote card reads as lifted daylight.
- **Night Navy** (`navy-3`): footer only; the darkest surface, and it is still blue.
- **Concrete Cream** (`cream`): daylight section ground (services, area) and the quote card. `text-on-dark` carries the same value as headline and body text on navy.
- **Weathered Cream** (`cream-2`): 2px service-list dividers, town-pill outline, the photo-hint panel ground.
- **Dusk Slate** (`muted-on-dark`): secondary copy on flat navy (ledes, step body, hours, footer); 7.4:1 or better on both navies.
- **Dusk Haze** (`pitch-on-scene`): the pitch line under the hero headline. Lighter than Dusk Slate because it sits over the drawn scene (sky, canopy, siding) rather than flat navy: 7.8:1 on the dusk sky, 5.4:1 on clean siding, about 4.3:1 over the darkest canopy cluster, always with the scene shadow.
- **Scene Shadow** (`scene-shadow`): the text-shadow color under the hero headline and pitch only (see Elevation).
- **Wet Slate** (`muted-on-light`): secondary copy on cream (ledes, row descriptions, promise body, optional-field hint); 6.0:1 on cream.
- **Panel Slate** (`panel-text`): copy inside the inner cream panels (photo hint, ticket); 7.4:1 on `cream-2`.
- **Field Line** (`field-line`) and **Field Fill** (`field-fill`): the outline and fill shared by inputs, select, textarea and the quote chips; Field Fill is also the town-pill ground. See the contrast note under Inputs.
- **Placeholder** (`placeholder`): input placeholder text (4.6:1 on Field Fill).
- **Ticket Dash** (`ticket-line`): the dashed edge of the read-only message ticket only. At 1.45:1 on cream it is decoration around text, never the sole boundary of an interactive control.
- **Error Brick** (`error`): inline validation messages (5.9:1 on cream). The invalid field's outline uses the lighter `error-line`.

### Section gradients (hero and close)
The hero ground falls from `dusk-sky` at the top to `navy` at 55% (it is the sky behind the tree and house); the close rises from `dusk-floor` at the bottom to `navy` at 60%. They bracket the page like the sky at both ends of the scroll; they are not grounds for reuse elsewhere.

### Named Rules
**The Still-Blue Rule.** No ground is black or near-black. The darkest surface is `navy-3`; anything darker must keep the navy hue.

**The One Leaf Rule.** Orange is the only accent. It marks the primary action, the leaf, and focus; no second accent color is introduced for UI.

## Typography

**Display Font:** system stack (`-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`)
**Body Font:** the same stack
**Label/Mono Font:** none distinct

**Character:** One family, two voices: heavy uppercase headings with tight negative tracking for the shout of a job-site sign, and plain sentence-case body at a comfortable 17px for the friendly local voice.

### Hierarchy
All headings (h1–h3) share: weight 900, uppercase, letter-spacing -0.02em, line-height 0.98, `text-wrap: balance`.
- **Display** (900, clamp(2.35rem, 10.6vw, 5.4rem), 0.98, max 12ch): hero headline only, carrying the scene shadow; at 1000px+ it narrows to clamp(3.2rem, 4.6vw, 4.6rem) so the copy stays in the left half while the house holds the right. The closing h2 is the same voice at clamp(2.3rem, 10vw, 5rem), max 14ch. Accent words take `orange`, no italics.
- **Headline** (900, clamp(2rem, 8.4vw, 3.8rem), 0.98): section h2s.
- **Title** (900, 22px, -0.01em): service row h3s; the quote card h3 at 24px; promise titles at 19px. The pull-line promise sits between title and headline at clamp(1.5rem, 6.2vw, 2.4rem), line-height 1.08, max 20ch.
- **Pitch** (400, clamp(16px, 4.5vw, 20px), 1.4, max 36ch): the one line under the hero headline, `pitch-on-scene` with the place name bolded (700) in `text-on-dark`, carrying the scene shadow. Capped at 20px.
- **Lede** (400, 18px, max 46ch): the paragraph under every section h2.
- **Body** (400, 17px, 1.55): base. Secondary body sizes are 16px (row descriptions, promise body, chips) and 15px (footer, after-links, ticket, errors). The hero hint is 700/14px; nothing is smaller than 13px (the one inline tag).
- **Label** (800, 16px): form field labels and the chip-group legend; the "(optional)" suffix drops to 500 in `muted-on-light`.
- **Button** (800, 17px, line-height 1): every button; phone numbers inside buttons drop to 700 at 85% opacity.

### Wordmark
No logo exists, so the brand is set: "T&J" at 900/24px/-0.03em in `orange`, baseline-aligned beside "EXTERIOR / MAINTENANCE" at 800/14px/uppercase/+0.06em on two lines.

### Named Rules
**The Shout-and-Talk Rule.** Headings are 900 uppercase; nothing else is uppercase except the wordmark subtitle. Body, labels, buttons and chips stay sentence case.

**The 16px Floor Rule.** Reading text is never below 16px on phones; 15px is reserved for footnote-grade lines (footer, errors, the ticket), and the 14px hero hint is a transient instruction, not reading text.

## Layout

Phone first: the design width is 360–430px and every decision is judged at 390px. Content sits in a single container, max 1180px, with a 20px gutter (`gutter`) on both sides. Sections pad 64px top / 72px bottom; the close pads 84px / 96px. The `html` scroll offset is 76px so anchor jumps clear the 60px sticky top bar.

**Hero.** One canvas fills the whole hero behind the copy; the copy layer ignores pointer events except on its links and buttons. The copy stack is headline, pitch, then a full-width two-button stack (12px gap), then a ground band (clamp(170px, 30vh, 330px)) where the yard and driveway open out and the hint sits. The scene is composed from the copy's own measured positions, so it re-lays itself on every resize:
- **Phone (canvas under 760px), per Ellie's sketch:** the house stands on the right (53%–95% of the width) behind the copy, its eave level with the middle of the headline and its gable peak near the headline's top; the ground line sits at the top of the buttons. The tree trunk stands at 19% of the width and its canopy spans from just off the left edge to 84% of the width, draping over the headline and the roof. The driveway leaves the garage and runs down-left under the buttons to the bottom of the hero.
- **Desktop (760px and wider):** the ground line sits 26px into the ground band; the house fills the right half (width min(34% of the hero, 540px), right edge at min(width − 48px, center + 610px)), its eave halfway between the headline top and the ground. The tree stands just left of the house with its canopy reaching over the roof's left side; the driveway runs down-left from the garage.

Breakpoints:
- **760px:** the hero copy top padding grows from 22px to 64px; hero buttons go side by side (auto width, 30px padding, 14px gap); the hint aligns to the container's left edge; the scene switches to its desktop composition; the top-bar call pill shows its number; the sticky thumb bar is removed; footer bottom padding drops from 120px (clearance for the bar) to 40px. Phone counts in TUNE apply below 760px (`max-width: 759px`).
- **900px:** services, quote and area become two-column grids with a 64px gap: services and quote at 5fr/7fr (intro left, working surface right, services intro sticky at top 100px); area at 7fr/5fr (towns left, promises right). The quote send buttons sit side by side.
- **1000px:** the hero copy column caps at min(48vw, 640px) and the headline steps down to its desktop size, so the copy keeps the left half and the house keeps the right.

Input-mode queries matter as much as width: hover effects live only under `(hover: hover)`, and the quote send order swaps under `(hover: hover) and (pointer: fine)` (see Components).

### Named Rules
**The First-Screen Rule.** At 390px the first viewport holds wordmark + call pill, the three-line benefit headline under the canopy, the one-line pitch, both full-width buttons, and the washable scene: the house beside and behind the copy and the head of the driveway under the buttons. Nothing pushes the scene below the fold.

**The Proof-in-the-Hole Rule.** When a wide layout opens a column, it is filled with something working (the washable house in the hero's right half, the quote card beside the steps), never left empty.

## Elevation & Depth

Mostly flat, with depth carried by the ground change (navy to cream), two soft navy-tinted shadows, and one text shadow where type sits over the drawn scene. There are no hairline highlights or inner glints anywhere. Translucent navy plus backdrop blur is used for the two fixed/sticky bars so they float over the moving hero.

### Shadow Vocabulary
- **Card lift** (`box-shadow: 0 24px 50px -24px rgba(5,12,22,.7)`): the quote card; daylight floating on dusk.
- **Button press-in shadow** (`box-shadow: 0 8px 18px -10px rgba(6,14,24,.55)`): primary button only.
- **Focus halo** (`box-shadow: 0 0 0 4px rgba(232,137,43,.25)`): inputs on focus, with the border turning `orange`.
- **Scene shadow** (`text-shadow: 0 2px 6px` in `scene-shadow`): the hero headline and pitch only, so they hold over the canopy, roof and siding. Not for type on flat grounds.
- **Frosted bar** (top bar `rgba(22,38,58,.88)` + 10px blur; thumb bar `rgba(15,28,43,.92)` + 12px blur).

### Named Rules
**The No-Glint Rule.** Surfaces never carry a thin white highlight line or inset rim. Depth comes from tinted soft shadow, shading and ground change.

## Shapes

Round and friendly. Every control is a full pill (`pill`, 999px): buttons, chips, the call pill, town pills, the hero hint, the inline tag. The container that holds work (the quote card) uses a generous 24px corner (`card`); inputs and inner panels (photo hint, ticket) use 14px (`field`). The focus outline rounds at 10px (`focus`). Icon cues and step numbers sit in full circles (`circle`, 44px for row cues and promise discs, 40px for step numbers). Strokes are a consistent 2px on every outlined control and divider. The only non-rectangular silhouettes are the wet seams, the leaves, and the hero scene (gabled roof, tree).

## Components

### Buttons
One component, two fills, same outline, same height.
- **Shape:** full pill (999px), 2px solid `orange` outline on every variant, minimum height 56px (52px inside the thumb bar), 22px side padding (30px in the hero and close at 760px+), 10px icon gap, 22px stroke icons.
- **Primary:** `orange` fill, `navy` text, the press-in shadow.
- **Ghost:** translucent navy `rgba(22,38,58,.55)` with cream text on dark grounds and over the hero canvas; transparent with `ink` text on cream grounds and inside the quote card.
- **Hover (desktop only):** primary lifts 2px and fills `orange-hi`; ghost lifts 2px and takes a 14% orange wash. Transform eases on `cubic-bezier(.16,1,.3,1)` over .25s.
- **Active:** scale(.97) on every button, every device.
- **Pairing:** the primary/ghost pair always appears together: "Get a free quote" + "Call (732) 644-6757" in hero and close; "Send by text" + "Send by email" in the quote card; "Call" + "Free quote" in the thumb bar.

### Chips
- **Style:** pill, 46px tall, 16px side padding, 700/16px, `field-fill` with a 2px `field-line` outline. The native checkbox is visually hidden but stays focusable.
- **Selected:** fills `navy` with `cream` text and a navy outline; this is the only "selected" treatment in the system.
- **Focus:** 3px `navy` ring at 2px offset on the visible pill. **Active:** scale(.96).

### Cards / Containers
- **Quote card:** 24px corner, `cream` on `navy-2`, card-lift shadow, padding 22px 18px 24px on phones and 34px at 900px+.
- **Photo hint:** 14px corner, `cream-2` panel, rust camera icon, 15px `panel-text` copy; it tells the visitor to attach photos in their messaging app.
- **Ticket:** 14px corner, 2px dashed `ticket-line`, 14px 16px padding, pre-wrapped 15px `panel-text` message; hidden until a send or copy, then drops in (6px, .5s).

### Inputs / Fields
- **Style:** full width, min-height 52px (textarea 96px, vertical resize), 12px 14px padding, 14px corner, 2px `field-line` outline on `field-fill`, 500/17px `ink`. Select uses a drawn chevron in `ink` and 40px right padding. Placeholder in `placeholder`.
- **Focus:** native outline removed; border turns `orange` and the 4px orange focus halo appears.
- **Error:** the field wrapper gets the bad state: outline turns `error-line` and a 700/15px `error` message appears below in plain words naming what to add. Validation runs on send, focuses and centers the first bad field, then re-validates live on input while any error is showing. `aria-invalid` mirrors the state.
- **Contrast:** `field-line` (#8f8676) measures 3.54:1 against `field-fill`, above the 3:1 non-text floor. Focus rings on cream are navy, because orange on cream is 2.3:1.

### Quote builder (signature)
The quote request is the product. It composes one plain-text message ("Hi T&J! I'd like a free quote." + Services, Name, Phone, Town, optional Notes, and a photos line) and rewrites both send links on every input: `sms:` with `?&body=` and `mailto:` with subject "Free quote request – {town}".
- **Fields:** service chips (at least one), name, 10-digit phone (11 with a leading 1 accepted), town select (17 towns + "Somewhere else nearby"), optional notes.
- **Send order by device:** on phones, "Send by text" is primary and first. Under `(hover: hover) and (pointer: fine)` the email button moves first and takes the primary fill, the text button turns ghost, and its label becomes "Text (732) 644-6757". The fill follows the channel the device can actually use.
- **After-links:** "Copy the message" and "Or just call", 700/15px `ink` text with an orange underline at 4px offset, 44px tall tap rows. Copy reports "Copied" or, when blocked (the Facebook in-app browser), "Select the message below" and shows the ticket so the text can be selected by hand.
- **Preselection:** every service row carries `data-pick`; clicking it checks exactly those chips and clears the service error.
- **Steps beside the card:** a three-item numbered list with 40px `orange` discs (900, `navy` numerals) and 800 `text-on-dark` step titles over `muted-on-dark` body.

### Service rows
The whole row is the link; there is one arrow-in-a-circle cue per row, not a repeated "Get a quote" label. Rows are separated by 2px `cream-2` rules (top rule on the list). The cue is a 44px `navy` disc with a cream arrow; on desktop hover it slides 4px right, scales 1.06 and turns `orange`. The seasonal row gets a left-to-right 16% orange wash and an orange cue, and bleeds to the gutter edge on phones.

### Navigation
- **Top bar:** sticky, 60px tall, frosted navy; wordmark left, call pill right. The call pill is 44px tall with a 60%-opacity orange outline and shows only the phone icon below 760px, the number at 760px+.
- **Thumb bar (phones only, under 760px):** fixed to the bottom, two equal columns ("Call" ghost, "Free quote" primary), 10px gap, padding 10px 12px plus the safe-area inset, frosted `rgba(15,28,43,.92)`. It slides up (.45s, `cubic-bezier(.16,1,.3,1)`) only when the hero buttons have scrolled out of view **and** the quote card is less than 15% visible, so it never duplicates buttons already on screen. Without IntersectionObserver it is simply always on.

### Hero: dusk scene, fall tree, wand (signature)
One canvas behind the hero copy draws a single dusk scene: a big fall tree, a dirty house, and a driveway through the yard (geometry under Layout). The scene's paints are canvas-only and are not UI tokens.
- **Layers, back to front:** the sky is the hero's CSS gradient. Base: a dark-green yard (`#1b3127` to `#25432f`, darker blotches) with shrubs along the foundation; a dusk-concrete driveway (`#8f8e88` to `#bdb8ad`, lighter toward the viewer) with broom texture and perspective control joints; clean blue-grey lap siding (`#46586e`) with light corner trim; a ribbed garage door; lit windows (warm `#f6c374` to `#b8722f` glow, light frames, dark muntins); a dark shingled roof (`#222b37`) with a light gutter along the eave. Then the wet sheen, then the grime, then the window glow at 38% so lit windows show faintly through the dirt. Then the falling and resting leaves, then the tree trunk and limbs (`#2c211b`, with a soft ground shadow), then the canopy, the wand and the spray.
- **Grime (half resolution):** the siding is mildew-dark (`#383c31`) with black streaks running down from the eave and from under each window, and green algae low on the wall. The driveway carries a grey-brown film (`#4d4b43`), blotches, two tire tracks that widen toward the viewer, three oil stains and moss in the joints.
- **Wash:** finger or mouse erases grime with a soft radial brush (radius 24px phone, 34px desktop), interpolating up to 14 stamps on fast drags so the clean line is continuous; it lays down wet sheen, throws water droplets (3 per stamp on phones, 5 on desktop, capped at 260, gravity 420) and blows nearby leaves. On phones any touch in the hero washes; on desktop the mouse washes only over the scene (yard and driveway, the house and roof, the canopy) and elsewhere just blows leaves.
- **Creep-back and drying:** grime returns at `regrow` per frame and the sheen dries at `wetFade`, so the house and driveway never stay finished.
- **Wand:** drawn only while washing (220ms after the last stroke): a dark lance with a brass `#c99a3c` nozzle, angled up-left from the touch point.
- **Autopilot:** after `idleMs` of stillness, the wand glides on a damped spring between targets, three spots on the siding then three on the driveway, 1.4s each, washing at a lighter strength (.75 vs .9 for the user).
- **Canopy:** `canopyPhone` / `canopyDesktop` leaf clusters packed into a lumpy dome that droops over the trunk on one side and over the roof on the other. Each cluster is a pre-drawn sprite of about 70 small leaves in one of three fall color sets, shaded darker underneath so it reads as volume; 40% sit behind, smaller and dimmed. Wind is a slow gust that travels across the tree plus each cluster's own flutter, scaled by `wind`, with the tips moving most. The wand (user or autopilot) pushes clusters within 70px (phone) / 100px (desktop) and they spring back with a little wobble; a hard shove shakes leaves loose.
- **Leaves:** leaf sprites in 3 shapes (oval, maple, oak) by 6 fall colors (`#e8892b`, `#c9602a`, `#e6b44a`, `#a8462a`, `#d97a1f`, `#8a5a2b`), each shaded with a soft diagonal gradient and a center vein, no glints. They fall on layered sine sway with their own phase and swelling amplitude, flip in 3D (scale-y by cos), and come to rest at 90% opacity on the roof slope (just over half of those that fall over it) or on the yard and driveway. 60% start resting so the first frame reads as fall; when the bed passes 75%, the tree occasionally drops a fresh leaf from a cluster by recycling a resting one, so the count never grows. Blown leaves take gravity and drag, then settle back into a drifting fall.
- **Hint:** a pill "Drag to wash the house and driveway" with a hand icon at the bottom-left of the ground band, 18px up; translucent navy `rgba(22,38,58,.78)`, 700/14px. It fades out (.6s) the first time the visitor washes.
- **Quieter zones:** the area and close sections each run their own leaf field (7 leaves phone, 14 desktop) at 85% opacity, blown by the pointer at 70% force, with no scene.

**TUNE constants** (the single place to adjust feel):

| Constant | Value | Effect |
|---|---|---|
| `leavesPhone` / `leavesDesktop` | 44 / 90 | hero leaf count (most resting on roof, yard, driveway) |
| `canopyPhone` / `canopyDesktop` | 70 / 95 | leaf clusters in the tree |
| `wind` | 1.0 | canopy sway speed |
| `zoneLeavesPhone` / `zoneLeavesDesktop` | 7 / 14 | area and close leaf count |
| `brushPhone` / `brushDesktop` | 24 / 34 | wash radius, CSS px |
| `regrow` | 0.0009 | grime creep-back per frame (0 = stays clean) |
| `wetFade` | 0.03 | how fast the wet sheen dries |
| `idleMs` | 3200 | stillness before the autopilot wand starts |
| `blowRadius` / `blowForce` | 90 / 520 | leaf push radius and strength |
| `seamSpeed` | 1.0 | wet-seam animation speed multiplier |

Canvas device-pixel ratio is capped at 1.75 on phones and 2 on desktop.

### Wet-edge seams (signature)
Every section boundary is a 46px SVG seam overlapping both sections by 23px. The upper ground fills the box; the lower ground fills below a moving water line, so the color edge follows the line exactly with no gap. Three lines ride the surface: a 3px `orange` center line and two 2px mist lines above and below (55% and 40%). Each line is a swell of two sines at different speeds and directions plus a faster ripple whose amplitude itself breathes; each seam gets its own phase offset. Grounds in order: hero `navy` → services `cream` → quote `navy-2` → area `cream` → close `navy`.

### Motion rules
- **One loop.** A single requestAnimationFrame loop drives the hero, both leaf zones and all seams; each registers once. Frame delta is clamped to 50ms.
- **Pause off screen.** Each item has its own IntersectionObserver (80px root margin); invisible items are skipped, and when nothing is visible the loop stops until something re-enters.
- **Reduced motion.** Under `prefers-reduced-motion: reduce` the loop never starts. The hero draws one still frame with a clean stripe already washed across the siding and another across the driveway, with the canopy and resting leaves in place; leaf zones draw their resting leaves, seams render once at t=0, CSS transitions drop to .01ms and smooth scroll is off. Validation scrolling also goes instant.
- **Touch never blocks scroll.** All touch listeners are passive and the ground band is `touch-action: pan-y`.
- **UI easing.** State transitions use `cubic-bezier(.16,1,.3,1)` (buttons .25s, row cue .3s, chips .2s, thumb bar .45s, ticket .5s); color-only transitions use the default ease at .2s.

## Do's and Don'ts

### Do:
- **Do** keep every button on the one component: 2px `orange` outline, 56px minimum height, pill shape, primary or ghost fill only.
- **Do** join any new section to its neighbor with a wet-edge seam whose fill follows the line, using the two grounds' exact token values.
- **Do** register any new animated element with the shared loop and its own off-screen pause, and give it a still frame under reduced motion.
- **Do** keep the washable house and the head of the driveway in the first phone viewport, composed from the copy's measured positions, and let touch scroll vertically over the scene.
- **Do** give any type set over the hero scene the scene shadow and a color at least as light as `pitch-on-scene`.
- **Do** make the whole row or card the link, with a single 44px arrow-in-a-circle cue.
- **Do** offer calling beside any text option, and keep the copy button a convenience with a visible fallback.
- **Do** put hover-only effects under `(hover: hover)`; every interaction must work by tap and drag.
- **Do** adjust motion feel through the TUNE constants rather than by editing physics inline.

### Don't:
- **Don't** use a black or near-black ground; the darkest surface is `navy-3`.
- **Don't** introduce a second UI accent; orange is the action, the leaf and the focus.
- **Don't** add thin white highlight lines, inset rims or glints to buttons, cards, leaves or the scene.
- **Don't** use stock or AI before/after photos as proof; the washable house and driveway are the proof.
- **Don't** set body, labels, buttons or chips in uppercase.
- **Don't** lighten `field-line` or use the orange focus ring on cream: both drop below the 3:1 non-text floor (orange on cream is 2.3:1).
- **Don't** use `ticket-line` as the boundary of anything interactive; it is decoration on a read-only panel.
- **Don't** show the thumb bar on screens 760px and wider, or while the hero buttons or the quote card are already in view.
