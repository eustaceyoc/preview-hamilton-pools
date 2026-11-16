# Hamilton Pools: sample site

A one-page sample site I put together for Hamilton Pools (Allen, TX). It's a concept, not their official website, and it says so at the top of the page and in the footer.

Live preview: https://preview-hamilton-pools.vercel.app

The request form doesn't send anything to a server. It just opens your own email app with a message addressed to luke@hamiltonpoolstx.com, and the phone buttons dial (214) 402-8677. There's no tracking or analytics, and the fonts are self-hosted.

## What's on the page

Only details from Hamilton Pools's own website and public listings: business name, owner first name Luke, Allen, phone, email, office hours, the after-hours emergency email instruction, the services and service areas listed on hamiltonpoolstx.com, and one short customer quote published on that site. Anything I couldn't confirm is left out or marked to be confirmed. There are no reviews, ratings, prices, years in business or team photos.

## Photos

Stock photos from Pexels, used under the Pexels License (https://www.pexels.com/license/). They're there for mood. None of them shows Hamilton Pools, its people or its work.

- `dusk-pool.jpg`: "A luxury villa with a swimming pool at dusk" by Ahmet ÇÖTÜR on Pexels (https://www.pexels.com/photo/a-luxury-villa-with-a-swimming-pool-at-dusk-28054849/)
- `night-pool.jpg`: "Holiday Home Villa Pavruka Yayla in Kalkan" by Ahmet ÇÖTÜR on Pexels (https://www.pexels.com/photo/holiday-home-villa-pavruka-yayla-in-kalkan-19075395/)
- `handrail-night.jpg`: "Handrail in the Swimming Pool" by Ata Ebem on Pexels (https://www.pexels.com/photo/handrail-in-the-swimming-pool-11311194/)

Fonts: Playfair Display, Inter Tight (Google Fonts, SIL Open Font License). Full details are in `assets/provenance.json`.

## Indexing

The page has `noindex, nofollow` in a meta tag and in the `X-Robots-Tag` header (`vercel.json`), and `robots.txt` disallows everything, so it shouldn't turn up in search.

Eustace Crentsil
