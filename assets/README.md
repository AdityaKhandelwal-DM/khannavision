# Image slots — where each photo goes

Every photo the client shared on WhatsApp has a dedicated slot on the site.
Drop the **original high-res files** into these folders using the **exact
filenames** below. As soon as a file exists at the path, its card switches
from the "Photo slot" placeholder to the real image automatically — no code
change needed.

Sizes: collections ~1200×1000px landscape · diaries/testimonials
~900×1200px portrait · JPG or WebP. (Do NOT crop from WhatsApp screenshots —
use the originals, or the client will reject on quality.)

## assets/collections/  (6 product cards)
| Filename              | Card / WhatsApp source                     |
|-----------------------|--------------------------------------------|
| versace-medusa.jpg    | Versace Medusa Collection (3:03pm)         |
| armani-clip-ons.jpg   | Emporio Armani Clip-Ons — product (2:55pm) |
| rayban-hexagon.jpg    | Ray-Ban Hexagon frames (3:03pm)            |
| rimless.jpg           | Rimless frame options (3:03pm)             |
| oakley-drivewear.jpg  | Oakley prescription / Drive-Wear (2:57pm)  |
| contact-lenses.jpg    | Contact lenses — Acuvue/Biofinity (2:59pm) |

## assets/diaries/  (10 customer & store cards)
| Filename                        | Card / WhatsApp source                       |
|---------------------------------|----------------------------------------------|
| team-welcome.jpg                | Team greeting, 3 staff namaste (2:54pm)      |
| customer-diaries-collage.jpg    | #CustomerDiaries polaroid collage (2:55pm)   |
| customer-trying-frames.jpg      | Lady in red trying frames (2:55pm)           |
| customer-with-bag.jpg           | Customer with Khanna Vision bag (2:56pm)     |
| customer-sunglasses.jpg         | Denim-jacket sunglasses customer (3:00pm)    |
| customer-zeiss-uv.jpg           | Zeiss "Full UV protection" customer (3:04pm) |
| customer-armani-clipon.jpg      | Armani clip-on customer (3:05pm)             |
| store-brand-walls.jpg           | Store interior — designer brand walls (3:00pm)|
| store-display.jpg               | Store interior — Ray-Ban/Carrera (3:00pm)    |
| cleaning-regime.jpg             | Spectacles Cleaning Regime graphic (3:00pm)  |

## assets/testimonials/  (3 graphics + 1 video)
| Filename               | Card / WhatsApp source              |
|------------------------|-------------------------------------|
| surabhi.jpg            | Surabhi 5★ testimonial (2:57pm)     |
| ilyasa-soni.jpg        | Ilyasa Soni 5★ testimonial (2:57pm) |
| nidhi-hirawat.jpg      | Nidhi Hirawat 5★ testimonial (2:57pm)|
| kavita-madhukar.mp4    | Kavita Madhukar testimonial VIDEO (2:57pm) |
| kavita-poster.jpg      | (optional) poster frame for the video |

To add more cards, copy any `<figure class="shot …">` (collections) or
`<figure class="gallery-item …">` (diaries/testimonials) block in
index.html and point its `data-img` / `<img src>` at a new file.
