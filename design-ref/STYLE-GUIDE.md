# Style Guide

Source: https://www.figma.com/design/gBuFIS35DNwX2xbtBksMR4/Website?node-id=0-1

Derived from Kavya's Figma file ("Website", frames: MacBook Air 1–2, reference
page, NavBar component). Screenshots live in this folder (`figma-*.png`).
The reference-page palette swatches are authoritative — hex codes below are
taken from them, not sampled from screenshots.

## Color palette

| Token | Hex | Name | Used for |
|---|---|---|---|
| `--midnight-green` | `#104F55` | Midnight green | Deepest accent / dark text on light greens |
| `--myrtle-green` | `#32746D` | Myrtle green | Navbar pill, photo arch frames, primary brand green |
| `--verdigris` | `#5EAAA8` | Verdigris | Lighter green accent |
| `--burnt-sienna` | `#E07A5F` | Burnt sienna | Warm accent; oversized background type ("PGH NYC NJ", likely at reduced opacity) |
| `--sunset` | `#F2CC8F` | Sunset | Warm section backgrounds (About) |
| `--linen` | `#F4EAE0` | Linen | Off-white backgrounds / light surfaces |

Neutrals seen in frames: white `#FFFFFF` for text on photos/green, and a
near-black (~`#1E1E1E`) for body text on warm backgrounds.

## Typography

- **Display / headings / nav:** tall condensed sans, mixed case, white when on
  photos or green. Closest match: **Oswald** (Google Fonts). Used for the huge
  hero name ("Kavya Casula"), "TITLE TEXT", nav links, and the "kc" logo
  (lowercase Oswald).
- **Body:** clean grotesque sans — looks like **Inter** (Figma's default).
  Regular weight, generous line height; bold + italic used inline for emphasis
  ("cool", "one of the best", "Flxpped Co.").
- Oversized display type is also used *decoratively* as a background texture
  (city abbreviations bleeding off the right edge of the About section).

> Font identification is by eye from screenshots — confirm in Figma dev mode
> (select text → right panel shows the font) if exactness matters.

## Layout & components

- **Hero (MacBook Air - 1):** full-bleed landscape photo; nav overlaid on top;
  name centered-ish in huge condensed type with a smaller subtitle
  ("Engineering X Design") in body font below it.
- **NavBar component:** rounded pill (fully-rounded ends), Myrtle green fill,
  "kc" logo left, links right: Projects · About · KC's Camera Roll · Flxpped Co.
  ("Caught by KC" in the Figma was renamed to "KC's Camera Roll", July 2026.)
  In the hero frame the nav sits directly on the photo (no pill visible) —
  the pill version is the standalone component; treat the pill as canonical.
- **About (MacBook Air - 2):** Sunset background; photo in an **arched
  (round-top) frame** with a thick Myrtle green border and a white outer
  outline; text block beside it; giant Burnt-sienna place-name type stacked on
  the right edge, cropped by the viewport.
- Recurring motifs: arched photo frames, pill shapes, oversized cropped type,
  real photography as texture.

## Mood reference (Pinterest board)

`moodboard-pinterest.png` — added July 2026 as a second visual reference
alongside the Figma. Takeaways to lean into:

- **Type as the hero**: huge display letterforms overlapping and cropping
  behind/through photos (validates the "PGH NYC NJ" motif — push it further).
- **Retro poster / streetwear editorial energy**: chunky condensed type,
  confident color blocking, graphic compositions over timid minimalism.
- **Warm saturated accents** (reds, oranges, mustard) — maps to our Burnt
  sienna + Sunset; use them boldly, not just as trim.
- **Photography as texture**: grainy, candid shots integrated into layouts
  rather than framed as gallery objects.

## Voice / feel

Warm, personal, playful-but-composed. Earthy greens + sunset warmth over
photography. First-person, casual copy ("Hi! I'm Kavya.").

## Content pulled from the Figma (for later)

- Tagline: "Engineering X Design"
- Nav items: About, Projects, Flxpped Co, Caught by KC
- About copy: engineer, passion for making things look and feel cool; fashion,
  cars, entrepreneurship; CMU undergrad; FSAE; Flxpped Co.
- Places: PGH / NYC / NJ
