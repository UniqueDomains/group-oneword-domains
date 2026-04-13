# Available .GROUP One-Word Domains (8,000)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C999%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C000%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .group one-word domains from Unique Domains.

> **Important:** this repository is a **public 7,999-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,000 domains** on the canonical page below.

**Public extract:** 7,999 rows · **Live catalog:** 8,000 domains

**Last updated:** 2026-04-13  
**Canonical page:** `https://unique.domains/domains/tld/group`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/group?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./group.csv">CSV</a> / <a href="./group.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .GROUP search](https://unique.domains/domains/tld/group?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .GROUP search](https://unique.domains/domains/tld/group?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .GROUP one-word domain catalog.

### Files

- `group.csv` — public CSV extract (7,999 rows)
- `group.json` — public JSON extract (7,999 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/group-oneword-domains/main/group.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| monitoring.group | available | $10.99    | —             | 76             | 27     | 10     | name.com                                                |
| summary.group    | resell    | $10.99    | $33.99        | 71             | 17     | 7      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| review.group     | premium   | $128.70   | $128.70       | 94             | 39     | 6      | namecheap                                               |
| ugly.group       | available | $10.99    | $33.99        | 96             | 26     | 4      | name.com                                                |
| supervisor.group | resell    | $10.99    | —             | 72             | 13     | 10     | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| check.group      | premium   | $41.25    | $41.25        | 76             | 35     | 5      | name.com                                                |
| broken.group     | available | $10.99    | —             | 64             | 25     | 6      | name.com                                                |
| mixing.group     | resell    | $10.99    | —             | 70             | 12     | 6      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| sad.group        | premium   | $123.75   | $123.75       | 72             | 26     | 3      | name.com                                                |
| danger.group     | available | $10.99    | —             | 74             | 24     | 6      | name.com                                                |
| mixture.group    | resell    | $10.99    | —             | 70             | 11     | 7      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| moi.group        | premium   | $21.45    | $42.90        | 72             | 22     | 3      | namecheap                                               |
| damn.group       | available | $10.99    | $33.99        | 140            | 23     | 4      | name.com                                                |
| rocky.group      | resell    | —         | —             | 64             | 99     | 5      | Chengdu West Dimension Digital Technology Co., Ltd.     |
| coy.group        | premium   | $123.75   | $123.75       | 64             | 13     | 3      | name.com                                                |
| pepsi.group      | available | $10.99    | —             | 88             | 22     | 5      | name.com                                                |
| wink.group       | resell    | —         | —             | 104            | 98     | 4      | Chengdu West Dimension Digital Technology Co., Ltd.     |
| tobacco.group    | premium   | $21.45    | $42.90        | 56             | 12     | 7      | namecheap                                               |
| pull.group       | available | $10.99    | —             | 74             | 21     | 4      | name.com                                                |
| bound.group      | resell    | —         | —             | 64             | 98     | 5      | Chengdu West Dimension Digital Technology Co., Ltd.     |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,999-row public sample | 8,000 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/group?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/group?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=related_pricing)

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
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .GROUP One-Word Domains*. Version 2026-04-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GROUP page](https://unique.domains/domains/tld/group?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
