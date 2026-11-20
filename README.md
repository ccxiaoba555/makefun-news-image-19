[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/ccxiaoba555/makefun-news-image-19/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/ccxiaoba555/makefun-news-image-19/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

# news-image-20261119 — Thursday, 19 November 2026

Built for [make.fun](https://make.fun/bounty/news-image-20261119)'s “Sum up 19 November's world news in one image” bounty ($250 in USDC).

One image summing up the world news of Thursday 19 November 2026, drawn as a
newspaper front page (1024×1024 PNG). The date is named at the top; six
stories, each verified against that day's reporting:

1. **Trump, Xi and Putin issue joint peace declaration** — first trilateral
   summit in Shenzhen; a pledge of nuclear-risk dialogue, with nothing said
   about Ukraine or Iran.
2. **World court rules Myanmar committed genocide** — the ICJ finds Myanmar
   responsible for genocide against the Rohingya in 2017.
3. **Three tankers burn after hitting mines off Hormuz** — 11 crew injured,
   one missing, as US–Iran strikes escalate.
4. **Anthropic prices record $81bn IPO** — 980m shares at $83, opening above
   the offer.
5. **Denmark approves Greenland–US defence pact** — all 109 lawmakers back it.
6. **Jeffries set to be first Black House Speaker** — Peltola's Alaska win
   seals a 56–44 Senate majority.

Ticker: US–Venezuela military pact · migrant boat sinks off Senegal ·
GTA VI earns rave reviews.

## Entry

`main.ts` (Node 22, standard library only) copies the bundled `entry.png`
to the output directory, byte for byte. No network, no randomness — every
run writes identical bytes.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
