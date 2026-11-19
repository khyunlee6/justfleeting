# Kevin Lee Photography: working rules for Claude

This repository is Kevin Lee's personal photography site. It is published with GitHub Pages
from the `main` branch at https://khyunlee6.github.io/justfleeting/.

## What is here

- `index.html`: the whole site. One file holds the styles, the content data (`SERIES`, `PRINTS`)
  and the page views (`home`, `gallery`, `series`, `about`, `prints`, `contact`). Pages are
  switched by the address hash, for example `#gallery` or `#kauai`.
- `img/`: the photographs, as JPEG. Wide photos are about 1800px on the long side.
- The design mock-up lives outside this repository, as a Claude Design canvas called
  "Kevin Lee Portfolio Mock-up" (https://claude.ai/artifact/14mrB2SmUMoT1JcEeWnvGm).
  Kevin reviews and comments there.

## Design rules

- Colours: paper `#f5f3ef`, ink `#1f1d1a`, soft text `#6b6863`, hairline rules `#dbd8d2`.
  Do not introduce other colours unless Kevin asks.
- Type: Cormorant Garamond for headings, Geist for body text, Italiana for the small
  capitals under the logo.
- Logo: the K/L monogram (upright K, a thin slanted hairline, italic L) with "KEVIN LEE" in
  small spaced capitals underneath. It is in the header of every page. The photo viewer
  shows the monogram alone.
- Feel: minimal, quiet, editorial. No ornaments, stamps, drop shadows on text, or bright accents.
- The site must work at three widths: desktop (1200 and wider), tablet (810 to 1199) and
  phone (under 810). The page body must never scroll sideways.

## Writing rules

- Never use em dashes or en dashes. Use periods, commas, colons or parentheses.
- Plain, specific sentences in the first person. Avoid lists of three, "drawn to",
  "this is a space for", and other stock website phrases.
- Only describe what the photographs show. Do not invent facts about Kevin.
- Text Kevin has not written yet stays as a bracketed placeholder, for example `[YOUR PAPER]`.
- Photo slots without a photo stay as labelled placeholders, for example `[ADD PHOTO: FOOD 1]`.

## Story structure (agreed direction for the home page)

The home page tells one story in four chapters. The chapter titles read as one sentence:

1. Places: "It starts with a place."
2. People: "Then the people in it."
3. The table (food): "What was on the table."
4. Moments: "And the moments in between."

## Photographs

- Originals are on Kevin's "One Touch" external drive. Never edit or delete originals.
- Do not publish a photo where a private person is the subject unless Kevin has said that
  person is fine to show.
- Every image needs a short, literal `alt` description.

## How to make a change

Every change goes through these four steps, in order. When the work is split between
agents, give one step to each.

1. Mock-up: apply the change to the desktop, tablet and phone boards of the mock-up, and
   reply in the comment thread if the change came from a comment.
2. Site: make the same change in `index.html` (and `img/` if photos change). The mock-up
   and the site must always match.
3. Check: open the site at 1280, 810 and 390 pixels wide. Confirm there are no broken
   images, no sideways scrolling, no script errors, and that the photo viewer and the
   contact form still work. The agent doing this check should not be the one that made the change.
4. Publish: commit with a one-line message that says what changed for a visitor, push, then
   load the live page and confirm the change is there.

Report back in plain language: what changed, where, and anything left as a placeholder.
