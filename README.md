# Jackz Dog Gear: website

Landing page for Jackz Dog Gear, Courtney Sanderson's treat bag, leash and barn hunt training business in Northwest Arkansas. Built by Outset Web Design.

## Source of truth

- Copy: the "Jackz Dog Gear" Google Doc (Courtney and Izzi's May 2026 revision, approved by Marc on 2026-06-03).
- Brand script: "Story Brand Framework" Google Doc in the Drive folder "Jack's Dog".
- Photos: Drive folder "Courtney Jack's website". Originals are kept out of this repo; the graded, renamed copies used on the page are in `img/`.

## Pages

- `/` home: gear, training, FAQ.
- `/treat-bags/` standalone landing page for the JACKZ Treat Pouch. Copy, specs and the Meet Jack story come from Courtney's Amazon listing (ASIN B0DPM1HGKF); the four quotes are verbatim verified Amazon reviews. Buy buttons go to amazon.com, the one external link on the site.

## Still needed from Courtney

- A logo (the header uses a type-only JACKZ wordmark for now).
- Her booking link. "Schedule a Training Session" currently opens an email to her.
- Return policy, shipping time and the class location for the FAQ.

## Notes

- Single static page, no build step. Fonts are self-hosted in `fonts/`.
- Every page is `noindex` and `robots.txt` blocks crawlers until launch.
- No external links. Rounded photo corners, no eyebrow labels.

## Preview locally

```
python3 -m http.server 8791
```
