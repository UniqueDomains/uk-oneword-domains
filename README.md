# Available .UK One-Word Domains (6,211)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C211%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .uk one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **6,211 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 6,211 domains · **Median ask:** $7.64 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/uk`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/uk?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./uk.csv">CSV</a> / <a href="./uk.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .UK search](https://unique.domains/domains/tld/uk?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .UK search](https://unique.domains/domains/tld/uk?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .UK one-word domain catalog.

### Files

- `uk.csv`, public CSV extract (1,000 rows)
- `uk.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/uk-oneword-domains/main/uk.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                     |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------- |
| half.uk       | resell    | —         | —             | high           | low    | 4      | Stenning Limited t/a Client Domain Management |
| just.uk       | resell    | —         | —             | high           | medium | 4      | GoDaddy.com, LLC.                             |
| party.uk      | resell    | —         | —             | high           | low    | 5      | Alan Drury                                    |
| try.uk        | resell    | —         | —             | high           | low    | 3      | Laughing Banana Enterprises Ltd               |
| metal.uk      | resell    | —         | —             | high           | low    | 5      | GoDaddy.com, LLC.                             |
| demo.uk       | resell    | —         | —             | high           | medium | 4      | Fasthosts Internet Ltd                        |
| only.uk       | resell    | —         | —             | high           | medium | 4      | Richard Kandler t/a Nameplace                 |
| stat.uk       | resell    | —         | —             | high           | low    | 4      | UK Internet Services Ltd                      |
| global.uk     | resell    | —         | —             | high           | medium | 6      | Alan Drury                                    |
| coach.uk      | resell    | —         | —             | high           | low    | 5      | Charles Scott t/a Domain Holdings UK          |
| sign.uk       | resell    | —         | —             | high           | low    | 4      | Charles Scott t/a Domain Holdings UK          |
| ahuh.uk       | available | $6.49     | $6.49         | high           | low    | 4      | namesilo                                      |
| ant.uk        | resell    | —         | —             | high           | medium | 3      | Anthony Appleby                               |
| adviseable.uk | premium   | $6.49     | $6.49         | medium         | low    | 10     | namesilo                                      |
| rile.uk       | available | $9.98     | —             | medium         | low    | 4      | namecheap                                     |
| azo.uk        | resell    | —         | —             | medium         | low    | 3      | Miss Ann-marie Morgan                         |
| annoy.uk      | available | $9.98     | —             | high           | low    | 5      | namecheap                                     |
| bus.uk        | resell    | —         | —             | high           | low    | 3      | Charles Scott t/a Domain Holdings UK          |
| ought.uk      | available | $6.49     | $6.49         | high           | low    | 5      | namesilo                                      |
| dry.uk        | resell    | —         | —             | high           | low    | 3      | Find Your Domain LLC t/a FYD                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 6,211 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/uk?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/uk?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=related_pricing)

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

Each domain in this set carries the .uk extension and consists of a single English word, from half.uk and just.uk to beauty.uk and metal.uk. With 6,211 names in the pool and a median ask near $7.64, this list spans everyday nouns, verbs, and short marketing-ready words. Investors can scan for spread and renewal patterns across UK-specific extensions, while founders can shortlist a name that reads clean, spells easily, and ships fast under a recognizable country-code TLD.

- 6,211 one-word .UK domains, from half.uk to beauty.uk
- Median ask near $7.64 across the full selection
- Single-word names: nouns, verbs, and everyday terms
- Country-code .uk trust signal for UK-facing brands

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .UK One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .UK page](https://unique.domains/domains/tld/uk?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
