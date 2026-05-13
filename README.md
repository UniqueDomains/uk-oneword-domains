# Available .UK One-Word Domains (6,210)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-6%2C210%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .uk one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **6,210 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 6,210 domains · **Median ask:** $9.31 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
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

- `uk.csv` — public CSV extract (1,000 rows)
- `uk.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/uk-oneword-domains/main/uk.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                          |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------------- |
| CapeCod.uk       | available | $9.98     | —             | 78             | 22     | 8      | namecheap                                          |
| ElSalvador.uk    | resell    | —         | —             | 72             | 98     | 11     | Dynadot, LLC t/a Dynadot                           |
| steeltoeboot.uk  | premium   | —         | —             | 66             | 1      | 14     | —                                                  |
| playin.uk        | available | $9.98     | —             | 80             | 10     | 7      | namecheap                                          |
| online.uk        | resell    | —         | —             | 70             | 62     | 7      | CSL Computer Service Langenbach Gmbh t/a Joker.com |
| goby.uk          | available | $6.49     | $6.49         | 74             | 9      | 5      | namesilo                                           |
| agents.uk        | resell    | —         | —             | 56             | 50     | 6      | Alan Drury                                         |
| splits.uk        | available | $6.49     | $6.49         | 70             | 9      | 6      | namesilo                                           |
| stage.uk         | resell    | —         | —             | 68             | 43     | 5      | Mr DJ Wood t/a Unforgettable Domains Ltd           |
| VirginiaBeach.uk | available | $9.98     | —             | 58             | 9      | 14     | namecheap                                          |
| coins.uk         | resell    | —         | —             | 56             | 41     | 5      | Dynadot, LLC t/a Dynadot                           |
| midlifecrisis.uk | available | $9.98     | —             | 58             | 9      | 15     | namecheap                                          |
| dave.uk          | resell    | —         | —             | 76             | 38     | 4      | Mr DJ Wood t/a Unforgettable Domains Ltd           |
| vales.uk         | available | $6.49     | $6.49         | 56             | 9      | 5      | namesilo                                           |
| partners.uk      | resell    | —         | —             | 61             | 32     | 8      | Backorder Ltd                                      |
| cometo.uk        | available | $9.98     | —             | 74             | 8      | 7      | namecheap                                          |
| ring.uk          | resell    | —         | —             | 60             | 32     | 4      | Mr DJ Wood t/a Unforgettable Domains Ltd           |
| changeup.uk      | available | $9.98     | —             | 70             | 8      | 9      | namecheap                                          |
| trends.uk        | resell    | —         | —             | 60             | 32     | 6      | Private Equity Systems Ltd t/a British Hosting     |
| grands.uk        | available | $6.49     | $6.49         | 66             | 8      | 6      | namesilo                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 6,210 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/uk?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/uk?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set is entirely focused on one-word .uk domains. It includes very short strings, clear dictionary words, category terms, and more unusual words with brand potential. Examples such as psychic.uk, microphone.uk, basket.uk, soccer.uk, and partyhat.uk show the range: some names are direct and commercial, while others are broader or more stylized. When comparing these domains, weigh memorability, spelling clarity, and how tightly the word matches a market or use case. For buyers focused on resale, generic words can have broader buyer pools. For founders, the best picks are usually easy to say, easy to type, and specific enough to feel ownable.

- Includes short, dictionary, generic, and brandable one-word .uk names
- Median ask is 9.31 across this selection
- Generic words may offer broader buyer interest
- Prioritize clear spelling and strong commercial fit

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .UK One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .UK page](https://unique.domains/domains/tld/uk?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_uk_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
