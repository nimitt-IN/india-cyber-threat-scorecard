# India Cyber Threat Scorecard

Aggregate counts of observed cyber threat activity affecting organisations in India, across
23 industry verticals. Published monthly by BitScore Cybertech LLP.

**Three editions in this snapshot:**

| Edition | Window | Cadence | Counted incidents |
|---------|--------|---------|-------------------|
| `2026-08` (baseline) | 30 May – 30 Aug 2026 | quarterly | 36 |
| `2026-09` | 31 Aug – 30 Sep 2026 | monthly | 67 |
| `2026-10` | 1 Oct – 1 Nov 2026 | monthly | 55 |

## Files

| File | What it is |
|------|------------|
| `india-threat-scorecard-YYYY-MM.json` | One edition: window, totals, all 23 verticals with counts by category, ransomware counts by group, notes. |
| `india-threat-scorecard-YYYY-MM.csv` | The same edition, one row per vertical. Categories as `name:count`, pipe-separated. |
| `india-threat-scorecard-all-editions.csv` | The three edition CSVs stacked, for loading in one read. |
| `schema.json` | JSON Schema for an edition. |

## How to read it

- **Aggregate counts only.** No organisation is named, described or made identifiable.
- **A count is an observation, not a confirmed breach.**
- **A band measures observed threat activity in a vertical**, not the security posture of any
  organisation in it.
- **Zero means none was observed in the window**, not that none occurred. All 23 verticals
  appear in every edition.
- **Band thresholds differ by cadence**, so do not compare the baseline's bands with a monthly
  edition's. Monthly: Elevated is 3 or more incidents, Active is 2, Watch is 1. Baseline
  (quarterly): Elevated is 5 or more, Active is 2 to 4, Watch is 1. Each file carries its own
  `bandThresholds`.
- The baseline window is three months and the later ones are one month, so raw counts are not
  comparable across the two either.

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Credit
**BitScore India Cyber Threat Scorecard — bitscore.in**.

## This is a dated snapshot

Snapshot taken **10 November 2026**, holding the editions to October 2026. A new edition is
published at the start of each month:

- Live page: https://www.bitscore.in/reports/india-threat-scorecard
- Latest edition as JSON: https://www.bitscore.in/scorecard/latest.json
- All open data from BitScore: https://www.bitscore.in/data
