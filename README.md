# CoRAL Workshop

Website for **CoRAL 2026** — the workshop on **Co**ntrol, **R**obotics, **A**utonomy and **L**earning,
hosted by the Robert Bosch Centre for Cyber-Physical Systems, IISc Bengaluru, in December 2026.

Served by GitHub Pages at <https://coralworkshop.github.io>.

## Structure

Everything is in a single file, [`index.html`](index.html) — one page, no build step, no
JavaScript, no dependencies apart from the Open Sans webfont. Edit it and push to `main`;
Pages redeploys within a minute or two.

Page order: About → Speakers → Schedule → Registration → Organizing committee →
Sponsors → Participating institutes.

Every nav label matches its section heading exactly; there are no other section labels.

Faculty organizers and student volunteers are two subsections inside Organizing committee,
which is why volunteers no longer has its own nav entry.

Images live in [`assets/`](assets/) — `people/` for organizer photos, `logos/` for institute
and sponsor logos.

## Placeholders to fill in

| What | Where |
| --- | --- |
| Dates — currently `December 2026`, exact days unconfirmed | hero eyebrow, hero facts, key dates, `#schedule` intro |
| Speakers (both `#speakers` and `#schedule` say "to be announced") | `#speakers`, `#schedule` |
| Session titles and times | `#schedule` |
| Registration form URL (`href="#"`) | `#register` |
| Student volunteer names (Sasidhar Reddy Alavala is listed) | `#organizers` |
| Sponsors (currently "to be announced") | `#sponsors` |
| Participating institutes (IISc + CPS as host, plus five IITs) | `#institutes` |
| Contact address (`coralworkshop@example.org`) | `#register`, `#sponsors`, footer |

Faculty organizer entries are real: Pushpak Jagtap and Ravi Prakash, with photos from
`assets/people/`. Verify the affiliation line reads how they want it.

Participating institutes currently show IIT Bombay, Delhi, Madras, Kanpur and Kharagpur,
using the logo files in `assets/logos/` — see [`SOURCES.md`](assets/logos/SOURCES.md) there
for the file-to-institute mapping and how to add more.

## Design

White background, black text, blue (`--link: #0b57d0`) hyperlinks, Open Sans. The palette is
the `:root` block at the top of `index.html`.

The schedule renders Day 1 and Day 2 as two parallel columns, stacking below 820px.
Institute logos sit in a `.logo-grid`; each tile is a `.logo-card` with an image and a caption.

## Local preview

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
