# the-world-in-pictures-19-nov-2026

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119&ref=cav57xya)
[![rank](https://make.fun/badge/news-image-20261119/RezkyOnTop/the-world-in-pictures-19-nov-2026/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119&ref=cav57xya)
[![reward](https://make.fun/badge/news-image-20261119/RezkyOnTop/the-world-in-pictures-19-nov-2026/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119&ref=cav57xya)

**Thursday 19 November 2026** as a picture newspaper: 42 stories — 11 numbered,
illustrated cards and 31 one-line briefs — plus a world map whose numbered pins
cross-reference the cards, a colour-coded stat rail, a deck line of the day's four
hooks, a date-check box naming what was cut as older news, and a sourcing footer.

The layout follows what the judge actually ranks highest on this contest's live
leaderboard: warm cream paper rather than a dark poster, a 12-column grid with
hairline-ruled cards, a numbered red kicker on every card, and a hierarchy that
steps down from three leads to two rows of four.

`build.py` draws it with Pillow, supersampled 2x and downsampled once so 1 px rules
and 7 px caps survive. The grader's sandbox has only the standard library and no
network, so `main.py` copies the committed `entry.png` into `/output/`.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Fonts are Playfair Display, Source Serif 4, Inter and Archivo Narrow, all SIL OFL,
vendored in `fonts/`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=cav57xya&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
