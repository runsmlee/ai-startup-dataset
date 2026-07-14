# AI Startup Dataset

A curated open dataset of **4,600+ AI startups**, maintained by [AI Market Watch](https://www.ai-market-watch.com) — a venture-capital intelligence platform.

> **Scope & bias, up front:** This is a *curated sample*, not a global census of every AI startup. Companies are surfaced largely from English-language and Korean sources and editorially verified, so it under-represents some regions (notably non-English markets). Treat country and category **counts** as a view of what we track, not as market-share truth. The most reliable signals are structural (funding concentration, stage mix), which track with broader venture data.

## Contents

`ai-startups.csv` — one row per company:

| Column | Description |
|---|---|
| `company_name` | Company name |
| `category` | AI segment (e.g. AI Agents, AI Infrastructure, AI in Healthcare) |
| `country_code` | ISO country code of headquarters |
| `year_founded` | Founding year |
| `funding_range` | Total disclosed funding, bucketed (Undisclosed, <$1M … $1B+) |
| `profile_url` | Full profile on AI Market Watch |

## Scope of this snapshot

This snapshot lists the full set of tracked companies with coarse fields only. The **richer, continuously updated data** — exact funding amounts and history, one-line and full company descriptions, VC Score breakdowns (Team / Market / Technology / Funding / Growth / Differentiation), founder profiles, investors, peer/DNA comparisons, and daily tagged news — lives on the platform (and the live directory adds companies daily, so it always runs ahead of this file):

- Full directory: https://www.ai-market-watch.com
- Aggregate statistics (updated daily): https://www.ai-market-watch.com/stats
- Quarterly data reports: https://www.ai-market-watch.com/reports

## License & attribution

Released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You may use, share, and adapt this data — **including commercially — with attribution**:

> Data: [AI Market Watch](https://www.ai-market-watch.com), AI Startup Dataset

For research papers: cite as "AI Market Watch, AI Startup Dataset, https://www.ai-market-watch.com".

## Methodology

Companies are sourced from public funding disclosures, launch platforms, and news coverage (English- and Korean-language sources most heavily), then verified and categorized editorially. This sourcing shapes coverage — the set is not a complete or unbiased census. Funding ranges reflect **disclosed amounts only**, in USD. Corrections welcome — each profile page has a "Report Inaccuracy" flow, or open an issue here.
