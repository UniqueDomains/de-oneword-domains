# Available .DE One-Word Domains (4,044)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-4%2C044%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .de one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **4,044 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 4,044 domains · **Median ask:** $18.26 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/de`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/de?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./de.csv">CSV</a> / <a href="./de.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DE search](https://unique.domains/domains/tld/de?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DE search](https://unique.domains/domains/tld/de?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DE one-word domain catalog.

### Files

- `de.csv` — public CSV extract (1,000 rows)
- `de.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/de-oneword-domains/main/de.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain               | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| -------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| mousearound.de       | available | $19.99    | —             | 57             | 22     | 12     | name.com  |
| regions.de           | resell    | —         | —             | 64             | 59     | 7      | —         |
| votingage.de         | available | $19.99    | —             | 52             | 18     | 10     | name.com  |
| popup.de             | resell    | —         | —             | 84             | 29     | 6      | —         |
| backtosquareone.de   | available | $19.99    | —             | 58             | 16     | 18     | name.com  |
| blackdiamond.de      | resell    | —         | —             | 70             | 29     | 13     | —         |
| getthebetterof.de    | available | $19.99    | —             | 69             | 15     | 17     | name.com  |
| diamonds.de          | resell    | —         | —             | 89             | 27     | 8      | —         |
| naturestudent.de     | available | $19.99    | —             | 46             | 15     | 14     | name.com  |
| full.de              | resell    | —         | —             | 68             | 26     | 4      | —         |
| naturewriter.de      | available | $19.99    | —             | 48             | 14     | 13     | name.com  |
| pops.de              | resell    | —         | —             | 74             | 24     | 4      | —         |
| bowlofcherries.de    | available | $19.99    | —             | 68             | 13     | 16     | name.com  |
| stadia.de            | resell    | —         | —             | 66             | 22     | 6      | —         |
| givesomethingatry.de | available | $19.99    | —             | 68             | 12     | 20     | name.com  |
| results.de           | resell    | —         | —             | 59             | 22     | 7      | —         |
| givesomeoneabreak.de | available | $19.99    | —             | 68             | 12     | 20     | name.com  |
| phones.de            | resell    | —         | —             | 76             | 19     | 6      | —         |
| violetgold.de        | available | $19.99    | —             | 72             | 11     | 11     | name.com  |
| rights.de            | resell    | —         | —             | 50             | 19     | 6      | —         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 4,044 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/de?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/de?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=related_pricing)

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

This selection is defined by one thing: the .de extension. That makes the set relevant for buyers who want German-market signaling, a country-code identity, or a short, memorable word on a recognized European namespace. The sample names range from broad dictionary words like repeat.de, neutral.de, and love.de to more specific terms like printable.de and grandkid.de. When comparing these domains, focus on word familiarity, cross-language readability, and whether the term feels commercially usable in German or international contexts. With a median ask of 18.26, price may be accessible, but fit still matters more than simply buying the cheapest name.

- All domains in this selection use the .de country-code extension
- Sample terms range from broad words to niche dictionary terms
- Median ask is 18.26, so cheap does not guarantee strong fit
- Check language fit, memorability, and trademark exposure

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DE One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DE page](https://unique.domains/domains/tld/de?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_de_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
