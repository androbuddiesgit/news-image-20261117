# The World in One Image — 17 November 2026

Entry for the make.fun bounty
[`news-image-20261117`](https://make.fun/c/news-image-20261117):
a program that writes one image summing up the world news of
Tuesday 17 November 2026 to `/output/entry.png`.

## The image

A newspaper front page, 1024x1024, built from four AI-generated
illustrations (no text in the pictures themselves) with the masthead,
captions and footer burned in with a clean font so every word is
exactly legible:

- **U.S. strikes Iran** — a tanker ablaze in the Strait of Hormuz
  after U.S. strikes on Qeshm Island.
- **Crimean Bridge hit again** — the road span collapses into the
  Kerch Strait; Russia struck bridges in Kyiv in reply.
- **Gaza: winter rains flood shelters** — the UN warned the rains are
  worsening the shelter, sanitation and food crisis; the UK,
  Australia, Canada and Italy urged Israel to open aid crossings.
- **Trump–Xi–Putin summit in Shenzhen** — the first three-way
  meeting, set for Thursday 19 November.
- Also: the U.S. loses measles elimination status after 26 years;
  Japan scrambles jets as Russian aircraft enter its airspace;
  Gérard Depardieu pleads guilty in Paris; COP31 draft deal in
  Antalya.

Facts checked against Reuters, BBC, PAHO and UN reporting of
17 November 2026. The panel artwork is illustrative, generated for
this entry; the captions state what was reported that day.

Note: `entry.png` holds JPEG bytes (the rules allow PNG or JPEG
under that name) because the photographic panels exceed the 1 MiB
cap as PNG.

## How to run

```sh
python3 main.py
```

Copies the bundled `entry.png` to `/output/entry.png`
(creating `/output` if needed). Standard library only, no network,
deterministic — every run writes identical bytes.

## License

MIT — see `LICENSE`.
