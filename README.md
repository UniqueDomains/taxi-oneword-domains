# Available .TAXI One-Word Domains (17,877)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C877%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .taxi one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,877 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,877 domains · **Median ask:** $11.12 · **High-demand under $2,500:** 2

**Last updated:** 2026-08-21
**Canonical page:** `https://unique.domains/domains/tld/taxi`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/taxi?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./taxi.csv">CSV</a> / <a href="./taxi.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TAXI search](https://unique.domains/domains/tld/taxi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TAXI search](https://unique.domains/domains/tld/taxi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TAXI one-word domain catalog.

### Files

- `taxi.csv`, public CSV extract (1,000 rows)
- `taxi.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/taxi-oneword-domains/main/taxi.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| aft.taxi      | available | $8.98     | $69.98        | low            | low    | 3      | namecheap         |
| bot.taxi      | resell    | —         | —             | high           | medium | 3      | Automattic Inc.   |
| org.taxi      | premium   | $500      | —             | medium         | medium | 3      | name.com          |
| apt.taxi      | available | $10.99    | —             | high           | low    | 3      | name.com          |
| gold.taxi     | resell    | —         | —             | high           | medium | 4      | Sav.com, LLC - 26 |
| happy.taxi    | premium   | $500      | —             | high           | medium | 5      | name.com          |
| awe.taxi      | available | $10.99    | —             | high           | low    | 3      | name.com          |
| moon.taxi     | resell    | —         | —             | high           | medium | 4      | Dynadot Inc       |
| manila.taxi   | premium   | $118.80   | $118.80       | high           | low    | 6      | namesilo          |
| bce.taxi      | available | $10.99    | —             | medium         | low    | 3      | name.com          |
| park.taxi     | resell    | —         | —             | high           | low    | 4      | Porkbun LLC       |
| madison.taxi  | premium   | $118.80   | $118.80       | high           | low    | 7      | namesilo          |
| ccc.taxi      | available | $8.98     | $69.98        | low            | medium | 3      | namecheap         |
| chain.taxi    | resell    | —         | —             | medium         | low    | 5      | GoDaddy.com, LLC  |
| discount.taxi | premium   | $118.80   | $118.80       | high           | low    | 8      | namesilo          |
| cut.taxi      | available | $10.99    | $84.99        | high           | low    | 3      | name.com          |
| water.taxi    | resell    | —         | —             | high           | medium | 5      | Spaceship, Inc.   |
| cxx.taxi      | available | $8.98     | $69.98        | low            | low    | 3      | namecheap         |
| bullet.taxi   | resell    | —         | —             | high           | low    | 6      | Sav.com, LLC      |
| DJI.taxi      | available | $10.99    | —             | high           | low    | 3      | name.com          |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,877 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 2 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/taxi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/taxi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set of 12,348 .taxi domain names covers short, compound phrases across transportation, travel, and everyday-life themes, from messages.taxi and destination.taxi to takeabreak.taxi and honeymooning.taxi. The median asking price sits at $12.67, giving a fast read on typical entry cost before renewal. Because the .taxi extension is niche but memorable, brandability and clarity matter more than length alone when narrowing down a shortlist. Compare each name for spelling ease, trademark conflicts, and renewal cost to separate ownable, launch-ready picks from higher-risk options.

- 12,348 .taxi domain names in this selection, updated daily
- Median asking price across the selection: $12.67
- Compound, brandable names like destination.taxi and hangon.taxi
- Check spelling, trademark risk, and renewal before choosing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TAXI One-Word Domains*. Version 2026-08-21. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TAXI page](https://unique.domains/domains/tld/taxi?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_taxi_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
