# Online supplement: Survey of Uncertainty Quantification in Large Language Models

Supplementary material for the survey article "Survey of Uncertainty Quantification in Large Language Models: Detection, Mitigation, and Human-Centered and Agentic Perspectives" (I. Fareed and M. W. Totaro). This material is not part of the article.

| File | Content | Rows |
|---|---|---|
| `table_S1.csv` | Per-paper literature matrix (problem, technique, key results, limitations) | 45 |
| `table_S2.csv` | Per-paper coding behind the counts in Section 5.1 (year, setting, human-subjects study, task type, primary metric, formal guarantee) | 45 |
| `table_S3.csv` | Update-search log, searched 14 October 2026 | 19 queries |
| `table_S4.csv` | Disposition of each of the 126 distinct records from that search | 126 |
| `table_S5.csv` | Cost and deployment constraints by method family | 6 families |
| `supplement.pdf` | The same five tables, typeset (25 pages), with `supplement.tex` as source | |

The CSV files were generated from `supplement.tex`; the typeset tables are the reference version if the two ever differ. Build the PDF with `pdflatex`, `bibtex`, `pdflatex`, `pdflatex`.

Notes
- Table S3 was screened by title and snippet only; the 83 eligible records not added to the corpus were not read.
- Four of the 87 title-screened candidates were added to the corpus (items 42-45 in S1 and S2).
- Citation counts were not used to select papers.
