# Image slots — where each photo goes

Drop the photos from the Drive into these two folders using the **exact
filenames** below. As soon as a file exists at the path, its card on the
website switches from the "Photo slot" placeholder to the real image
automatically — no code change needed.

Recommended: landscape ~1200×1000px for collections, portrait ~900×1200px
for customer diaries. JPG or WebP.

## assets/collections/  (product cards)
| Filename                | Card on site                          |
|-------------------------|---------------------------------------|
| versace-medusa.jpg      | Versace Medusa Collection             |
| armani-clip-ons.jpg     | Emporio Armani Clip-Ons               |
| rayban-hexagon.jpg      | Ray-Ban Hexagon Frames                |
| rimless.jpg             | Rimless Frame Options                 |
| oakley-drivewear.jpg    | Oakley Prescription (Drive-Wear)      |
| contact-lenses.jpg      | Contact Lenses (Acuvue, Biofinity)    |

## assets/diaries/  (customer & store cards)
| Filename                      | Card on site                    |
|-------------------------------|---------------------------------|
| customer-01.jpg               | Customer — new frames           |
| customer-armani-clipon.jpg    | Armani clip-on customer         |
| customer-sunglasses.jpg       | Sunglasses fitting              |
| customer-zeiss-uv.jpg         | Zeiss — full UV protection      |
| store-brand-wall.jpg          | In store — designer walls       |
| store-display.jpg             | In store — Ray-Ban & Carrera    |
| team.jpg                      | Our team                        |
| customer-oakley.jpg           | Oakley prescription customer    |

To add more cards, copy any `<figure class="shot …">` (collections) or
`<figure class="gallery-item …">` (diaries) block in index.html and point
its `data-img` / `<img src>` at a new file.
