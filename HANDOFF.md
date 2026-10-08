# T&J Exterior Maintenance — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/tAndJExteriorMaintenance · **Built:** 2026-10-08 from Muse brief 2026-10-08 (FB group post, Ocean County small businesses)

## What's built
- **World:** dusk on a Jersey Shore driveway. Their navy as the ground, their orange as the fall leaf, clean-concrete cream for the light sections. System font, heavy uppercase heads.
- **Signature:** the hero's bottom band is a grimy concrete driveway slab (tire tracks, oil stains, moss in the joints). Drag a finger or mouse across it and it pressure-washes clean (spray droplets, a wet sheen that dries, grime that slowly creeps back so it's always playable). A dark lance with a brass nozzle follows the finger. When nobody touches it, an autopilot wand washes a figure-eight. Leaves fall with layered-sine sway, settle on the slab, and get blown off by the wand. Leaves also drift through the area and closing sections; animated wet-edge seams (orange waterline + mist lines) join every section.
- **Sections:** hero ("Leaves gone. Gutters clear. Driveway clean.") → services (6 tappable rows, Fall cleanup first; each preselects its service in the quote form) → quote builder → service area + their own promises → close ("Restore your curb appeal this fall.") → footer with "Demo one-pager — free sample."
- **Quote builder (the core pitch):** services chips, name, phone, town, notes → composes one message, sent by **text** (`sms:+17326446757` with body) or **email** (mailto with subject "Free quote request – <town>"). Tells the visitor to attach photos in their app; the message ends "(Photos below, if I added any.)" rather than claiming photos are attached. Every quote button lands on the form itself, not the section heading. Inline errors, copy-message fallback, call link.
- **Desktop hero:** right half holds a "What needs doing?" card whose chips jump to the form with that service picked. On desktop, email is the primary send and the text button shows the number.
- **Phone:** sticky Call / Free quote bar appears once the hero buttons scroll away and hides while the form is on screen.
- Tunables are in `TUNE` at the top of the script (leaf counts, brush size, regrow speed, dry speed, autopilot delay, seam speed).

## Assumptions I made
- **Service grouping** (Driveways & concrete / House washing / Pavers / Decks & wood / Commercial): the brief's list is verbatim but flat. I grouped it in its own order, which matches the image names on their site (driveway, softwash, pavers, deck, commercial). "Pressure washing" sits under Pavers because that's where it falls in their list.
- **Colors:** navy #16263a and orange #e8892b approximate their site (exact hex unknown).
- **Process steps 2–3** ("Send it with photos", "Get your free estimate"): step 1 is theirs ("Send us a quick message with photos"); the rest describe the demo flow plus their stated free estimates.
- **Promise copy** under Fully insured / Locally owned / Free estimates is my one-line gloss on their own badges. "A local Shore crew, not a franchise call center" is inferred from "Locally owned" (home base not confirmed).
- **Insurance line** reads "Ask T&J for proof of insurance with your quote" (their badge says Fully insured; coverage scope is unknown).
- **"5-Star Service" and the three testimonials are left out:** Muse couldn't find the Google listing their site cites, so they're unverified.
- Headline and town chips: towns verbatim from their site; "Not on the list? Ask anyway." is my line.

## Placeholders and gaps
- **No real photos.** Their site's images are AI-generated (the "before/after" pairs don't match; the hero's wand floats). Not used. The washable slab is the before/after for now.
- Group post photo (fbid 122130093627341401) couldn't be fetched: Facebook needs a login.
- No logo: set as a "T&J / Exterior Maintenance" wordmark.
- Owner name, years in business, address: unknown, not shown.
- `src-assets/lovable/` holds their site's images for reference only (ignored by git).

## Questions for the owner
- Do you take texts at (732) 644-6757? If not, make email the primary send and drop the text button.
- Any real before/after photos (leaf piles, driveways, siding)? They'd go into slider viewers beside the services.
- Roof soft washing: a testimonial on your site mentions it but it's not in your services list. Offer it?
- Fences: also only in a testimonial. Add to "Decks & wood"?
- Do you have a Google Business Profile? Your site says "Based on Google reviews" but none could be found. Setting one up is a quick win.
- Want a custom domain instead of lovable.app?

## Ideas not built (yours to pick)
- **Runner-up world:** rain gutters and downspouts. Water sheeting off a roofline and a gutter you can clear of leaves by flicking them, so the water runs. Stronger for the gutter season, weaker for pressure washing.
- Real photo upload with a tiny backend (Formspree/Cloudflare worker) so photos come in with the form instead of via the messaging app.
- Before/after sliders once real pairs exist (desktop: one viewer beside services, swapping on hover; phone: one under each row).
- Make "Gutters clear" visible in the world: a gutter edge along the top of the slab that the wand can flush.
- Seasonal headline swap (spring: "Siding, driveway, deck: back to new").
- A small "your town" detector line ("Serving Brick") from the form's town choice.

## Not verified
- Real-device touch on iOS/Android and inside Facebook's in-app browser (headless touch sweep passed).
- SMS handoff with the pre-filled body on iOS and Android (the `?&body=` form is used for both).
- Frame rate on older phones (phone uses 16 hero leaves, half-res slab layers).
- Clipboard copy inside the FB in-app browser (fallback shows the message to select by hand).

## Review round
One Impeccable finish review (verdict: fix). Applied: driveway read of the slab, brighter clean stripe + slower regrow, drawn wand, desktop hero card, CTAs → form, desktop send order, honest message/claims, contrast on "Not on the list?". Detector clean before and after.
