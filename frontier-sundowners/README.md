# Frontier Sundowners

A retro mini-game invitation. Play *Quorum* — catch drinks and colleagues, dodge
committees — and the invite appears. Players who lose or skip reach it too.

**The event:** Mindjoy Frontier Sundowners, Wednesday 30 September, 17:30–19:30,
The Athletic Club & Social, Cape Town.

## Publishing

`index.html` is the entire site. No build step, no dependencies, no assets
folder — the Mindjoy lockup is embedded in the file, so the only external
request is Google Fonts.

To host on GitHub Pages: Settings → Pages → deploy from `main`, folder `/ (root)`.

## Editing

Everything lives in `index.html`:

- `RSVP_URL` (near the bottom, in the script) — where the RSVP button goes.
  Currently https://luma.com/6u29zo8a
- The invite card markup — date, time, venue and copy.
- `GOOD` and `BAD` — the falling items and the labels they carry.
- `WIN_SCORE` — how many catches make quorum (10).
