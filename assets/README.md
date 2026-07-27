# Image assets — current state

The website is now LIVE with the client's real WhatsApp photos placed in
every slot. Files were sourced from ~/Downloads (originals sent 2026-07-17).
Folder names are lowercase on purpose — Vercel/Linux is case-sensitive.

## PLACED (live on site)

### assets/collections/  (6 product cards, square 1080×1080)
versace-medusa.jpg · armani-clip-ons.jpg · rayban-hexagon.jpg ·
rimless.jpg · oakley-drivewear.jpg · contact-lenses.jpg

### assets/diaries/  (10 customer & store photos)
team-welcome · customer-diaries-collage · customer-trying-frames ·
customer-with-bag · customer-sunglasses · customer-zeiss-uv ·
customer-armani-clipon (shades on) · customer-armani-clear (clip off) ·
store-brand-walls · store-display

### assets/testimonials/  (3 review graphics)
surabhi.jpg · jigyasa-soni.jpg · nidhi-hirawat.jpg
NOTE: the graphic reads "Jigyasa Soni" (not "Ilyasa"). Verify with client.

## PENDING — 2 items the client sent but were NOT in the download set
1. **Spectacles Cleaning Regime** graphic — no file found. Ask client to
   re-send, then drop as assets/diaries/cleaning-regime.jpg and add a card.
2. **Kavita Madhukar testimonial video** — a video exists in Downloads
   (`WhatsApp Video 2026-07-17 at 3.02.22 PM.mp4`) but it's unconfirmed as
   Kavita's testimonial. Confirm, then add as assets/testimonials/kavita-madhukar.mp4.

## Swapping/adding an image later
Each card is `<figure class="shot …">` (collections/testimonials) or
`<figure class="gallery-item …">` (diaries) with a single
`<div class="slot"><img src="assets/…" alt="…"></div>`. Replace the src, or
copy a whole <figure> block to add a card. Slots are square (object-fit:cover).
