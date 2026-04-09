# Available .MBA One-Word Domains (5,622,476)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-9%2C398%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-5%2C622%2C476%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .mba one-word domains from Unique Domains.

> **Important:** this repository is a **public 9,398-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **5,622,476 domains** on the canonical page below.

**Last updated:** 2026-04-09  
**Canonical page:** `https://unique.domains/domains/tld/mba`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/mba?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_open_search"><b>Open live .MBA search</b></a> ·
  <a href="https://unique.domains/domains/tld/mba?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_create_radar"><b>Create .MBA Radar</b></a> ·
  <a href="https://unique.domains/domains/tld/mba?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_start_project"><b>Start a naming Project</b></a> ·
  <a href="./mba.csv"><b>Download CSV</b></a> ·
  <a href="./mba.json"><b>Download JSON</b></a> ·
  <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_methodology"><b>Methodology</b></a> ·
  <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_api_docs"><b>API docs</b></a>
</p>

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MBA one-word domain catalog.

### Files

- `mba.csv` — public CSV extract (9,398 rows)
- `mba.json` — public JSON extract (9,398 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract
- `assets/chart-demand-buckets.png` — generated demand-buckets chart

### Use this repo to

- inspect a public sample
- download CSV or JSON
- cite the dataset
- understand the fields and scoring inputs

### Use the live page to

- keep the exact search context
- search the full .MBA catalog
- filter by price, demand, status, spelling risk, and fit
- save the exact search as a Radar
- turn the search into a founder Project

## 📊 Snapshot of the live .MBA catalog

![Demand buckets across the live search](./assets/chart-demand-buckets.png)

**Why this chart:** it gives a fast overview of the live search composition using the same preview payload that supplies the README counts.

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/mba-oneword-domains/main/mba.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | purchase_price | renewal_price | attractiveness | demand | length | registrar        |
| -------------- | --------- | -------------- | ------------- | -------------- | ------ | ------ | ---------------- |
| silver.mba     | available | $49.98         | —             | 56             | 99     | 6      | namecheap        |
| easy.mba       | resell    | —              | —             | 128            | 68     | 4      | GoDaddy.com, LLC |
| fast.mba       | premium   | $82.50         | $82.50        | 82             | 53     | 4      | name.com         |
| zero.mba       | available | $19.99         | $50.99        | 112            | 53     | 4      | name.com         |
| space.mba      | resell    | —              | —             | 80             | 61     | 5      | DNSPod, Inc.     |
| travel.mba     | premium   | $260           | $260          | 115            | 48     | 6      | namecheap        |
| clear.mba      | available | $19.99         | $50.99        | 90             | 50     | 5      | name.com         |
| pay.mba        | resell    | —              | —             | 84             | 60     | 3      | Virtualia LLC    |
| custom.mba     | premium   | $82.50         | $82.50        | 110            | 39     | 6      | name.com         |
| snap.mba       | available | $19.99         | $50.99        | 90             | 46     | 4      | name.com         |
| data.mba       | resell    | —              | —             | 70             | 60     | 4      | DNSPod, Inc.     |
| rank.mba       | premium   | $82.50         | $82.50        | 70             | 35     | 4      | name.com         |
| review.mba     | available | $49.98         | —             | 94             | 41     | 6      | namecheap        |
| free.mba       | resell    | —              | —             | 88             | 59     | 4      | Sav.com, LLC - 6 |
| healthcare.mba | premium   | $42.90         | $42.90        | 80             | 33     | 10     | namecheap        |
| learning.mba   | available | $19.99         | —             | 80             | 41     | 8      | name.com         |
| context.mba    | resell    | —              | —             | 108            | 58     | 7      | Porkbun LLC      |
| expert.mba     | premium   | $19.99         | $50.99        | 104            | 32     | 6      | name.com         |
| unity.mba      | available | $19.99         | $50.99        | 70             | 41     | 5      | name.com         |
| smart.mba      | resell    | —              | —             | 74             | 56     | 5      | DNSPod, Inc.     |

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- The live product contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MBA One-Word Domains*. Version 2026-04-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MBA page](https://unique.domains/domains/tld/mba?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_mba_oneword_domains&utm_content=related_pricing)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `hello@unique.domains`
