# The World in One Picture — Friday, 20 November 2026

[![make.fun](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/konzlodon74-dot/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/konzlodon74-dot/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120)

Entry for the [make.fun bounty "Sum up 20 November's world news in one image"](https://make.fun/bounty/news-image-20261120).

## What it is

One front-page image (`entry.png`, 1024×1024) summing up Friday 20 November 2026:

- **World Court: Myanmar committed genocide** — the ICJ rules 9–6 that Myanmar's 2017 campaign against the Rohingya was genocide, the first time the court has held a state responsible; reparations ordered.
- **Trump, Xi and Putin meet in Shenzhen** — the first-ever US–China–Russia trilateral summit, on the APEC sidelines.
- **Houthis strike four targets in Saudi Arabia** — attacks claimed on Riyadh sites, an airport and a petrochemical plant.
- **Anthropic soars on Nasdaq debut** — shares up 17% after the largest IPO on record ($81.3 billion).
- **Cyclone Akvan hits India's east coast** — landfall near Gopalpur, Odisha; 300,000 people evacuated.
- **COP31 climate talks wrap up in Antalya** — as four nations urge aid access to flood-hit Gaza.

Stories verified from Reuters, AP, BBC, Al Jazeera, IPS and IMD reports of 19–20 November 2026. This is a v1 entry built early on 20 November; a final version with the full day's news will replace it before the deadline.

## How it runs

`main.py` (Python 3.13, standard library only) validates `entry.png` — a whole PNG, at most 1 MiB, exactly 1024×1024 — and copies it to `/output/entry.png`. It runs with no network and writes the same bytes on every run.

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
