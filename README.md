# The Silk Profile: Hakeem Obafemi Agaba, SAN

A tribute website marking the 2026 conferment of Hakeem Obafemi Agaba as a Senior Advocate of Nigeria. Developed as a gift by [Michael Alabi](https://mikealabi.com).

It is a single static page with no build step and no dependencies beyond two Google Fonts.

## Run locally

```bash
python -m http.server 3060
```

Then open http://localhost:3060.

## Structure

```
index.html   the whole site (HTML, CSS and JS inline)
assets/      processed photographs used by the page
```

## Page sections

Preloader, hero, scroll-driven "robing" sequence, recognition and firm honours, leadership nameplates, before/after portrait slider, education, timeline, practice areas, insights shelf (links to published articles), peer quotes and a closing congratulations with a gavel sound.

## URL options

| Parameter | Effect |
| --- | --- |
| `?from=Name` | Adds "With admiration, Name" under the gavel button |
| `?skip` | Skips the opening preloader |

## Content and sources

Every claim on the site comes from public sources, listed in the page footer: his Chambers Global profile, The Guardian's report on the 2026 LPPC list, BusinessDay's report on his IPLAN re-election, the Jackson, Etti & Edu profile page, Managing IP and World IP Review. Firm-level awards are labelled as firm-level. Nothing is invented; add new facts only with a source.

## Notes

- The swearing-in is shown as "October 2026" because the exact date was not confirmed.
- Source photographs were low resolution; replace the files in `assets/` with originals when available, keeping the same filenames.
- Photographs and the names of the people and organisations featured belong to their respective owners.

&copy; 2026 The Silk Profile: Hakeem Obafemi Agaba, SAN. All rights reserved.
