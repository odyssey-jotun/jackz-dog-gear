# Jackz Dog Gear: website

Landing page for Jackz Dog Gear, Courtney Sanderson's treat bag, leash and barn hunt training business in Northwest Arkansas. Built by Outset Web Design.

## Source of truth

- Copy: the "Jackz Dog Gear" Google Doc (Courtney and Izzi's May 2026 revision, approved by Marc on 2026-06-03).
- Brand script: "Story Brand Framework" Google Doc in the Drive folder "Jack's Dog".
- Photos: Drive folder "Courtney Jack's website". Originals are kept out of this repo; the graded, renamed copies used on the page are in `img/`.

## Still needed from Courtney

- A logo (the header uses a type-only JACKZ wordmark for now).
- A photo of the treat bag itself (the treat bag section shows the leash colors as a stand-in).
- Where "Buy Now" should go (Amazon listing or a store) and her booking link. Both currently open an email to her.
- Return policy, shipping time and the class location for the FAQ.

## Notes

- Single static page, no build step. Fonts are self-hosted in `fonts/`.
- Every page is `noindex` and `robots.txt` blocks crawlers until launch.
- No external links. Rounded photo corners, no eyebrow labels.

## Preview locally

```
python3 -m http.server 8791
```
