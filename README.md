# Culturally Adaptive Conversational AI Review

Supplementary research materials for **Culturally Adaptive Conversational AI: A Scoping Review and Design Implications for Human–AI Interaction** (HCI SI 2026).

The review covers **51 publications** on culturally adaptive chatbots and conversational AI. It examines cultural representations, adaptation approaches, evaluation practices, human involvement, and implications for human–AI interaction.

## Repository structure

- [`methodology/culturally_adaptive_chatbots_review_workbook_v2.xlsx`](methodology/culturally_adaptive_chatbots_review_workbook_v2.xlsx) — original blank extraction template and initial coding framework (dated 16 April 2026). This documents the early framework; its metadata does not independently authenticate every later coding decision.
- [`data/master_review_analysis_workbook_FINAL_RECHECKED.xlsx`](data/master_review_analysis_workbook_FINAL_RECHECKED.xlsx) — final rechecked 51-study extraction and descriptive analysis.
- [`verification/round14_final_codebook_review.xlsx`](verification/round14_final_codebook_review.xlsx) — subsequent claim-level codebook reconciliation and evidence-status audit. See [`verification/README.md`](verification/README.md).
- [`search_strategy/`](search_strategy/) — database searches and related search documentation.
- [`references/`](references/) — included-study references and links.
- [`paper/`](paper/) — manuscript-related materials.
- [`RELEASE_NOTES_v1.1.md`](RELEASE_NOTES_v1.1.md) — changes in the v1.1 evidence-audit update.

## Methods and selection

Database searches were conducted on **16 April 2026** in Scopus, Web of Science Core Collection, IEEE Xplore, and PubMed. The documented selection flow was:

| Stage | Records |
|---|---:|
| Identified | 210 |
| Duplicates removed | 84 |
| Screened | 126 |
| Excluded at title/abstract | 69 |
| Full texts sought | 57 |
| Not retrieved | 2 |
| Full texts assessed | 55 |
| Excluded after full-text review | 4 |
| Included | **51** |

The final sample comprises 42 direct-fit and 9 adjacent-fit publications. A two-citation scope-control threshold introduces selection and recency limitations; the results should not be interpreted as field-wide prevalence estimates.

## Reading the quantitative results

The manuscript's mechanism and metric tables report **coded literature-presence categories**, not counts of independently confirmed implementations or measured outcomes. Categories may overlap across the 51 publications.

The Round 14 audit adds a stricter, source-oriented distinction between implemented, evaluated, proposed, discussed, measured, phase-qualified, or insufficiently supported evidence. These stricter tallies remain **provisional** and must not be presented as definitive implemented-only or measured-only rates.

For example, 37 publications were coded in the broad SUS/usability family, but only three publications were confirmed in the audit to have administered the standard ten-item System Usability Scale. These are different measures.

## Versions

- [`v1.0-hci-si-2026`](https://github.com/Vid-Pejovnik-FERI/culturally-adaptive-conversational-ai-review/releases/tag/v1.0-hci-si-2026) — original analytical release.
- [`v1.1-hci-si-2026-evidence-audit`](https://github.com/Vid-Pejovnik-FERI/culturally-adaptive-conversational-ai-review/releases/tag/v1.1-hci-si-2026-evidence-audit) — addition of the Round 14 evidence-verification materials and codebook documentation.

The existing v1.0 and v1.1 Git tags are historical snapshots. Later documentation changes on `main` do not automatically alter either snapshot.

## Reuse and reproducibility

The original publications are not redistributed here. Consult their DOI or publisher links and respect third-party copyrights and licences. The verification workbooks may include brief source-derived notes and qualified decisions; users should consult the supporting articles before treating an attribution as independently confirmed.

See the repository [`LICENSE`](LICENSE) for licensing information about repository-owned material; third-party content retains its original rights.

## Use of generative AI

ChatGPT (OpenAI) assisted with language revision, translation, restructuring, formatting, and occasional interpretive cross-checking during the review and manuscript preparation. Final research decisions and conclusions are the responsibility of the human authors. See the manuscript's Generative AI declaration for the full description.

## Author

**Vid Pejovnik**  
Faculty of Electrical Engineering and Computer Science, University of Maribor, Slovenia  
vid.pejovnik1@um.si
