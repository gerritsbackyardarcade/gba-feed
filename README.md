# gba-feed

Live data for https://gerritsbackyardarcade.com. Updated automatically Monday, Wednesday and Friday.

- `marketplace.json`: current Facebook Marketplace listings shown in Fresh Picks
- `events.json`: upcoming events from the GBA Events Google Calendar
- `shop.json`: "Inside the Booth" photos and star rating from the Google Business Profile (business photos plus customer review photos)
- `img/`: listing photos (600x600 WebP), named by Marketplace item ID

## Event banners
In a GBA Events calendar entry, add a line to the description:
`image: swapcon` (built-in banner) or `image: https://...` (any image URL).
Events with no image line get the default GBA banner.
