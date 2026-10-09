# T&J Exterior Maintenance — handoff at ~60%

**Live file:** index.html · **Repo:** https://github.com/10elizabethbell/tAndJExteriorMaintenance · **Built:** 2026-10-08 from Muse brief 2026-10-08 (FB group post, Ocean County small businesses)

## What's built
- **World:** dusk on a Jersey Shore driveway. Their navy as the ground, their orange as the fall leaf, clean-concrete cream for the light sections. System font, heavy uppercase heads.
- **Signature (redrawn from Ellie's sketch, 2026-10-08):** the whole hero is one dusk scene. A big fall tree on the left, full of leaf clusters that sway in the wind, drapes over the headline and the roof. A dirty house (black streaks, algae, grimy siding, warm lit windows, garage) sits on the right, and a dirty driveway runs from the garage down-left through the yard. Leaves fall from the tree and pile up on the roof, yard and driveway. Dragging a finger or mouse works as a pressure washer: it cleans the siding and the concrete, blows leaves away, and shoves the canopy, which springs back and shakes leaves loose. Grime creeps back slowly. When nobody touches it, the wand glides between the wall and the drive on its own. Phone: house behind the copy on the right, as sketched. Desktop: same scene with the house in the right half.
- **Phone:** sticky Call / Free quote bar appears once the hero buttons scroll away and hides while the form is on screen.
- Tunables are in `TUNE` (also `canopyPhone/canopyDesktop` leaf clusters and `wind` sway speed) at the top of the script (leaf counts, brush size, regrow speed, dry speed, autopilot delay, seam speed).

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
- Make "Gutters clear" literal: leaves collect in the gutter line and the wand flushes them out.
- Seasonal swap of the tree (bare in winter, green in spring) with the same house.
- Seasonal headline swap (spring: "Siding, driveway, deck: back to new").
- A small "your town" detector line ("Serving Brick") from the form's town choice.

## Not verified
- Real-device touch on iOS/Android and inside Facebook's in-app browser (headless touch sweep passed).
- SMS handoff with the pre-filled body on iOS and Android (the `?&body=` form is used for both).
- Frame rate on older phones (phone uses 16 hero leaves, half-res slab layers).
- Clipboard copy inside the FB in-app browser (fallback shows the message to select by hand).

## Review round
One Impeccable finish review (verdict: fix). Applied: driveway read of the slab, brighter clean stripe + slower regrow, drawn wand, desktop hero card, CTAs → form, desktop send order, honest message/claims, contrast on "Not on the list?". Detector clean before and after.

## Hero v2 (Ellie's sketch)
Replaced the slab + desktop picker card with the tree/house/driveway scene. The picker card is gone because the house now fills the desktop hero's right half; service rows below still preselect the quote form.

## Quote form: text only (Ellie, 2026-10-08)
Email send button removed: too many options. The form now sends by text only (`sms:` with the composed message); "Copy the message" and "Or just call" stay as fallbacks. The email address is still in the footer. **Confirm with the owner that (732) 644-6757 takes texts**; if it doesn't, the single send button should become email or call.

## Before & after section (Ellie, 2026-10-08)
New navy section between Services and the quote form: two drag sliders (driveway, trash bin) built from two before/after composites Ellie supplied as T&J's work. Originals and crops live in `src-assets/work/` (git-ignored); the page embeds 640px WebP crops (q78, ~155KB total) that load only near the viewport. The driveway "before" is shifted 16px to line up with the "after"; the bin shots are framed differently, so the line shows a small jump. Top strip of the bin shots trimmed (vehicle parts).
- **Confirm with the owner:** that both jobs are theirs, and whether trash-bin cleaning is a service they offer (it's not in their published list; the caption only says "Washed out").
- More pairs slot in by copying one `<figure class="ba-card">` and adding two `<script type="text/plain" id="img-...">` blocks at the end of the page.
