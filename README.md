# Supplementary material: Survey of Uncertainty Quantification in Large Language Models

Supplementary material for the survey article "Survey of Uncertainty Quantification in Large Language Models: Detection, Mitigation, and Human-Centered and Agentic Perspectives" (I. Fareed and M. W. Totaro). This material is not part of the article.

| File | Content | Rows |
|---|---|---|
| `table_S1.csv` | Per-paper literature matrix (problem, technique, key results, limitations) | 57 |
| `table_S2.csv` | Per-paper coding behind the counts in Section 5.1 (year, setting, human-subjects study, task type, primary metric, formal guarantee) | 57 |
| `table_S3.csv` | Update-search log, searched 14 October 2026 | 19 queries |
| `table_S4.csv` | Disposition of each of the 126 distinct records from that search | 126 |
| `table_S5.csv` | Cost and deployment constraints by method family | 6 families |
| `table_S6.csv` | Stage-5 screening of the 83 records left unread by the update search (classification, evidence basis, method family, decision) | 83 |
| `table_S7_families.csv` | Method families: approximate corpus counts before (45) and after (57) stage 5, and records among the 83 | 15 families |
| `table_S8.csv` | Gap-analysis verification log for stage 5 | 8 queries |
| `supplement.pdf` | Tables S1-S8, typeset, with `supplement.tex` as source | |

The CSV files were generated from `supplement.tex`; the typeset tables are the reference version if the two ever differ. Build the PDF with `pdflatex`, `bibtex`, `pdflatex`, `pdflatex`.

Notes
- Table S3 was screened by title and snippet only. Stage 5 (October 2026) then screened the 83 eligible records not added in stage 4 by title and abstract (Table S6); eight were added to the corpus (items 48, 49, 51-55, 57 in S1 and S2), and four foundational papers (items 46, 47, 50, 56) were added from a gap analysis (Table S8). The corpus is now 57 papers.
- Four of the 87 title-screened candidates were added in stage 4 (items 42-45 in S1 and S2).
- Item 52 (UaIT) was read from its abstract only. Several other additions were read through text that was incomplete for some sections; the manuscript and S1 say where.
- Citation counts were not used to select papers.
