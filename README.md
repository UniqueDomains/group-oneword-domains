# Available .GROUP One-Word Domains (10,760)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C760%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .group one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,760 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,760 domains

**Last updated:** 2026-05-01  
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

- `group.csv` — public CSV extract (1,000 rows)
- `group.json` — public JSON extract (1,000 rows)
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

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| bucketlist.group   | available | $10.99    | —             | 80             | 23     | 11     | name.com                                                  |
| fleet.group        | resell    | —         | —             | 64             | 68     | 5      | Porkbun LLC                                               |
| smiths.group       | premium   | $69.30    | $138.60       | 50             | 16     | 6      | namecheap                                                 |
| Snapchat.group     | available | $35.98    | —             | 88             | 22     | 8      | namecheap                                                 |
| online.group       | resell    | —         | —             | 70             | 62     | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| plz.group          | premium   | $69.30    | $138.60       | 72             | 14     | 3      | namecheap                                                 |
| CapeCod.group      | available | $35.98    | —             | 78             | 22     | 8      | namecheap                                                 |
| design.group       | resell    | —         | —             | 90             | 49     | 6      | Porkbun LLC                                               |
| bubbles.group      | available | $10.99    | —             | 72             | 21     | 7      | name.com                                                  |
| tech.group         | resell    | —         | —             | 86             | 48     | 4      | Porkbun LLC                                               |
| rules.group        | available | $10.99    | —             | 66             | 21     | 5      | name.com                                                  |
| water.group        | resell    | —         | —             | 92             | 45     | 5      | Porkbun LLC                                               |
| ratings.group      | available | $10.99    | —             | 53             | 19     | 7      | name.com                                                  |
| bank.group         | resell    | —         | —             | 70             | 38     | 4      | Porkbun LLC                                               |
| reservations.group | available | $10.99    | —             | 50             | 17     | 12     | name.com                                                  |
| WiFi.group         | resell    | —         | —             | 83             | 37     | 5      | DNSPod, Inc.                                              |
| landscaping.group  | available | $10.99    | —             | 80             | 16     | 11     | name.com                                                  |
| notes.group        | resell    | —         | —             | 73             | 37     | 5      | Dynadot Inc                                               |
| reps.group         | available | $10.99    | —             | 73             | 16     | 4      | name.com                                                  |
| modern.group       | resell    | —         | —             | 80             | 36     | 6      | Porkbun LLC                                               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 1,000-row public sample | 10,760 live domains                              |
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

> Unique Domains. *Available .GROUP One-Word Domains*. Version 2026-05-01. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .GROUP page](https://unique.domains/domains/tld/group?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_group_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
