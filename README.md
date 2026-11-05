# Sree Furnitures — Google review page

Single-page site that helps customers of **Sree Furnitures**, Bhimavaram, leave a Google review in a few taps.
Same layout and behaviour as the Rao's Vandana page, themed with the shop's yellow and blue logo colours.

> Demo page. Not an official website of the business.

## Shop details

| | |
|---|---|
| Google place ID | `ChIJkwI0eQDTNzoRDH39znWIHUM` |
| Review link | https://search.google.com/local/writereview?placeid=ChIJkwI0eQDTNzoRDH39znWIHUM |
| Maps listing (CID) | https://maps.google.com/?cid=4836171614431051020 |
| Address | 3-1-168, Undi Road, opp. Hotel Ratnam, near Town Railway Station, Balusumoodi, Bhimavaram, Andhra Pradesh 534202 |
| Hours | Mon–Sat 10 am – 9:30 pm, Sunday closed |
| Phone | 99487 24499 (Google, Instagram, website) · 95503 36363 (Facebook) |
| Email | sreefurnituresin@gmail.com (Facebook) |
| Website | https://www.sreefurnitures.com/ |
| Instagram | https://www.instagram.com/sreefurnitures/ |
| Facebook | https://www.facebook.com/people/Sree-Furnitures/61566823019995/ |

## Editing

Config sits at the top of the `<script>` block in `index.html`: `SOCIAL`, `PLACE_ID`, `CID`, and `GBP_REVIEW`.
If the owner shares the official review short link (Business Profile > Ask for reviews, `https://g.page/r/.../review`),
paste it into `GBP_REVIEW` for a one-tap review box.

The logo is embedded as a data URI, so the page is self-contained. It was taken from the shop's Instagram profile
picture (150 px); swap in a higher-resolution original if the owner has one.

## Publishing

Push `index.html` to a GitHub repo, then Settings → Pages → Branch `main`, folder `/ (root)`.
The page is marked `noindex` while it is a demo.
