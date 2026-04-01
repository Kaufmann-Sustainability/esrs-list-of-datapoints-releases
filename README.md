# ESRS November 2025 — Datapoint Register

> A structured Excel register of every disclosure requirement, paragraph, and Application Requirement across all 12 ESRS standards — built from the EFRAG Knowledge Hub.

![License](https://img.shields.io/badge/license-MIT-green)
![Standards](https://img.shields.io/badge/standards-ESRS%201%2C%202%2C%20E1--E5%2C%20S1--S4%2C%20G1-lightgrey)
![Source](https://img.shields.io/badge/source-EFRAG%20Nov%202025-orange)

---

## The problem this solves

EFRAG's IG3 Excel covers the original 2023 ESRS. No updated structured list exists for the **2025 Draft Simplified ESRS (Nov 2025)**. Practitioners preparing ESRS sustainability statements need a machine-readable, filterable register of all disclosure requirements — including what changed, what is new, and which Application Requirements apply to each paragraph.

This register fills that gap. It is built directly from the live [EFRAG Knowledge Hub](https://knowledgehub.efrag.org) and compiled into a clean Excel file you can filter, annotate, and integrate into your reporting workflow.

---

## Download

**[→ Download the latest release](../../releases/latest)**

No installation required — just open the `.xlsx` file in Excel or any compatible spreadsheet tool.

---

## Output

`ESRS-Nov2025-Datapoints.xlsx` — **1,156 rows** across 14 sheets:

| Sheet | Rows | Content |
|-------|------|---------|
| About | — | Coverage, disclaimer, licence |
| Instructions | — | Column reference and usage notes |
| ESRS 1 | 283 | General Requirements |
| ESRS 2 | 194 | General Disclosures |
| ESRS E1 | 174 | Climate Change |
| ESRS E2 | 42 | Pollution |
| ESRS E3 | 36 | Water & Marine Resources |
| ESRS E4 | 51 | Biodiversity & Ecosystems |
| ESRS E5 | 52 | Resource Use & Circular Economy |
| ESRS S1 | 161 | Own Workforce |
| ESRS S2 | 48 | Workers in the Value Chain |
| ESRS S3 | 38 | Affected Communities |
| ESRS S4 | 34 | Consumers & End-Users |
| ESRS G1 | 43 | Business Conduct |

---

## Column reference

| Column | Example | Description |
|--------|---------|-------------|
| ID | `ESRSE1-0041` | Unique row identifier, sequential within each standard |
| Standard | `ESRS E1` | Standard name |
| Chapter | `3. Double materiality` | Top-level chapter |
| Sub-chapter | `3.2. Impact materiality` | Second-level heading |
| Sub-sub-chapter | `Disclosure Requirement E1-6` | DR name or third-level heading |
| Para # | `41` / `AR 20` | Integer for paragraphs; `AR N` for Application Requirements |
| Sub-item | `(a)` | Letter sub-item; blank for parent rows |
| Sub-sub-item | `(i)` | Roman numeral sub-item; blank if none |
| Type | `DR` / `AR` / blank | Disclosure Requirement, Application Requirement, or context |
| DR? | `Y` / `N` | `Y` if text contains a disclosure verb (*shall disclose*, *shall report* …) |
| AR ref | `AR 20 for para. 41(a)` | Full AR reference string |
| Parent para | `41` | Para number extracted from the AR ref |
| Text | *exact wording* | Rich text — bold defined terms (ESRS Glossary) are preserved |
| Amendment | `New` / `Amended` / `Unchanged` | Change status relative to the 2023 ESRS |
| Indicative amendment assessment | `Amended` / `Renumbered` | `Amended` = EFRAG explicitly flagged a content change · `Renumbered` = only a para cross-reference given, no explicit content-change flag. Indicative only — verify against the official text. |
| Previous para ref | `45` / `AR 10` | Original para/AR replaced by this row (Amended rows only) |
| Defined terms | `materiality, impact` | Glossary terms identified in the source text |
| Source | `2025 Draft Simplified ESRS (Nov 2025)` | |

**Row colouring:** blue = DR · grey = AR · white = context paragraph.

---

## Known limitations

| Issue | Detail |
|-------|--------|
| Formula images | Where EFRAG uses an image for a formula, `[IMAGE]` is appended to the row. Affects E1 AR 22, E5 AR 3, S1 AR 35. |
| EFRAG HTML inconsistencies | Some sub-chapters are structured incorrectly in the HTML (e.g. E5-5 Products/Waste). These are detected and handled but may differ from the PDF layout. |
| Live source dependency | Built from the live Knowledge Hub. If EFRAG updates the HTML, counts or content may shift. |

---

## Disclaimer

This register has been compiled by **Kaufmann Sustainability GmbH** solely for informational and working-document purposes. It is derived from the EFRAG Knowledge Hub HTML as published under the 2025 Draft Simplified ESRS (Nov 2025) and has been processed by an automated parser. While reasonable care has been taken to ensure accuracy and completeness, Kaufmann Sustainability GmbH does not warrant that this register is free from errors, omissions, or misinterpretations of the source material.

This register does not constitute legal, regulatory, or professional advice. It is the sole responsibility of the user to verify all disclosure requirements against the official ESRS texts as adopted or endorsed by the European Commission. Kaufmann Sustainability GmbH expressly excludes any liability for losses, penalties, regulatory findings, or other consequences arising from reliance on this register.

---

## Licence

MIT — free to use, modify, and distribute. See [LICENSE](LICENSE) for details.
