# Podcast hosting prices and price changes, 2023 to 2026

Every plan and price for 12 podcast hosts plus Spotify for Creators, read off each host's own pricing
page. Also 19 verified price and plan changes since January 2023, each linked to Internet Archive
copies of the host's pricing page from before and after the change, so you can check any of them in
two clicks.

Maintained by [Podcast Host Lab](https://podcasthostlab.com/podcast-hosting-price-tracker/). The live
tracker is re-checked on the first of every month. There are no affiliate links in these files.

Hosts covered: Acast, Blubrry, Buzzsprout, Captivate, Castos, Libsyn, Podbean, RSS.com, Riverside,
Simplecast, Spreaker, Transistor, and Spotify for Creators.

## Files

| File | What's in it |
|---|---|
| `podcast-hosting-prices.csv` | 44 plans across the 13 services: month-to-month price, annual price per month, upload limit, number of shows, video support, and the pricing page each row came from |
| `podcast-hosting-price-changes.csv` | 19 verified price and plan changes, newest first, with the old and new prices and links to Internet Archive copies on either side |
| `castos-libsyn-price-history.png` | Chart of two entry-plan price stories: Castos going from $19 to $29 a month in November 2023 and back by April 2024, and Libsyn's 3-hour plan going from $7 to $12 in December 2025 |

## Columns

**podcast-hosting-prices.csv**

| Column | Meaning |
|---|---|
| `check_date` | Date of the first full read of every pricing page (2026-09-24). See "How the prices are checked" for later checks |
| `host` | The hosting service |
| `plan` | The plan name as the host writes it |
| `monthly_billed_usd` | Price in US dollars a month when billed month to month. 0 means a free plan |
| `annual_billed_per_month_usd` | Price in US dollars a month when billed yearly. Blank means the host offers no annual option |
| `upload_limit` | The plan's upload, storage, or download allowance, as the host states it |
| `shows` | Number of podcasts the plan allows. Blank means the pricing page doesn't say |
| `video` | Whether the plan hosts video: yes, no, or blank if the pricing page doesn't say |
| `source_url` | The pricing page the row was read from |

**podcast-hosting-price-changes.csv**

| Column | Meaning |
|---|---|
| `first_seen` | The earliest date the new price was seen, from an Internet Archive copy or from our own check |
| `host` | The hosting service |
| `plan` | The plan or plans that changed |
| `summary` | One sentence describing the change |
| `before` | The price or terms before the change |
| `after` | The price or terms after the change |
| `archive_snapshot_before` | Internet Archive copy of the pricing page before the change |
| `archive_snapshot_after` | Internet Archive copy after the change. Blank when the Internet Archive hasn't saved the page since |

## How the prices are checked

Each price is read off the host's own pricing page, with the monthly and annual switch checked both
ways. The full read was on 2026-09-24, with corrections on 2026-09-25 and 2026-10-25. The tracker is
re-checked on the first of every month, and the 2026-11-01 check found no list-price change. Prices are
the list prices in US dollars as shown on each page.

Past changes come from Internet Archive copies of each pricing page going back to January 2023. Each
change links the copies on either side of it. The newest one (Buzzsprout, October 2026) has only the
before copy in this release, because the Internet Archive had not saved that page again when it was
logged.

## License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
You can use, chart, and republish this data for any purpose. The only condition is credit: name
Podcast Host Lab and link to https://podcasthostlab.com/podcast-hosting-price-tracker/

## How to cite

Podcast Host Lab. (2026). *Podcast hosting prices and price changes, 2023 to 2026* (Version 2026.11)
[Data set]. https://podcasthostlab.com/data/

## Corrections

Spotted a price that has changed? Email hello@podcasthostlab.com and we'll check it and update the data.
