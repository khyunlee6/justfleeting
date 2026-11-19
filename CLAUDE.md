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

## Home page

The home page uses the original layout from Kevin's Framer design: the headline "Slowing the
world down, long enough to hold a glimmer.", two offset photos, one wide photo, a fourth
series beside its photo, then a short "Behind the camera" strip. It is not the centred
editorial layout.

## Gallery and series pages

- The gallery is organised by place. Each series is one place (Nevada, California, Kauai,
  Oregon, Utah, Colorado, Mexico, Argentina, Iceland, Korea, Japan, Elsewhere).
- A series is named by its place only. There are no taglines.
- Each series page shows a cover, then every other photo in a mosaic of columns at the
  photo's own proportions (three columns on desktop and tablet, two on phone).
- "Elsewhere" holds photos whose place is not known yet. Ask Kevin before guessing a place.
- Kevin sorts photos in the folder "Website photos (selected)" on his Desktop, one folder
  per place. When he asks, read that folder and make the mock-up and the site match it.

## Story structure (draft, mock-up only)

Kevin is still developing a narrative about people, places, food and moments. A draft of it
lives on the "Editorial" boards of the mock-up as four chapters whose titles read as one
sentence: "It starts with a place." "Then the people in it." "What was on the table."
"And the moments in between." It is not on the live site. Do not move it there unless Kevin asks.

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
4. Publish, with Kevin's approval first: never commit or push site changes to `main`, and
   never merge. Put site changes on the branch `preview` and keep one open pull request
   from `preview` into `main` titled "Sync site with mock-up". Describe each change in the
   pull request in plain language. Kevin merges it himself, and the live site updates about
   a minute later. After he merges, load the live page and confirm the change is there.

The narrative and the wording are still being developed. Treat all text in the mock-up as
a draft that Kevin may change, and never move a draft to the live site outside the pull request.

Report back in plain language: what changed, where, and anything left as a placeholder.
