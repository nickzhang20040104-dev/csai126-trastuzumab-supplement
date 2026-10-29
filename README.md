# CSAI 2026 Paper 126 — Supplementary Materials

**Evaluating AI-Based Trastuzumab Affinity Workflows in a Two-Variant Case Study**

Ningquan Zhang, Hui Lin, Tangchen and Billy Li.

This repository hosts the complete Supplementary Appendix A1–A8 moved from the final manuscript, with its original scientific text, 17 numbered tables and two figures. Relocation does not change the study’s results or conclusions. The manuscript and response to reviewers cite a fixed commit of this repository.

## Read or download

- [Read the full appendix online](Appendix.md)
- [Download the appendix PDF](CSAI126_Supplementary_Appendix.pdf)
- [Download the editable Word appendix](CSAI126_Supplementary_Appendix.docx)

## Appendix index

| Section | Contents |
| --- | --- |
| [A1](Appendix.md#a1) | Sequences and experimental reference |
| [A2](Appendix.md#a2) | Protocol and reproducibility records |
| [A3](Appendix.md#a3) | Structural quality and confidence |
| [A4](Appendix.md#a4) | Raw binding scores and analysis selection |
| [A5](Appendix.md#a5) | Mean energies and conditional affinity |
| [A6](Appendix.md#a6) | Scorer association and strict-tier sensitivity |
| [A7](Appendix.md#a7) | Structural visualization and reference-aligned heavy-chain comparison |
| [A8](Appendix.md#a8) | Conformer exclusion sensitivity |

## Tables and numerical precision

`Table_A01.csv` through `Table_A17.csv` reproduce the displayed appendix tables. They retain displayed rounding and are not substitutes for full-precision computation inputs.

The eight `Data_*.csv` files are byte-identical copies of selected files from the retained 15 October 2026 full-precision reproducibility package. They provide group summaries, variant contrasts, all 160 single-conformer deletion results, full-order diagnostics, source-versus-report precision comparisons, selected-record lineage, and the 52-candidate ESMFold2 selection inventory. SHA-256 checksums and original archive-member names are recorded in `publication_manifest.json`.

## Scope and limitations

The Supplementary Appendix does not include the original data package.

The study is an exploratory two-variant case study. Conditional dissociation constants use an experimental WT anchor and an uncalibrated energy-to-free-energy assumption. Conformers are dependent computational samples, not independent experimental replicates. No new experimental result or model run was generated for this repository.

## Provenance

Appendix source: the final single-column Word manuscript, SHA-256 `67375ac7ff7ab96519f6da77b04b363036b0c60ff54f47c395dd815bf85ed471`. The standalone appendix preserves all A1–A8 paragraphs, table cells and figure pixels; the manuscript’s 12 references are reproduced at its end for standalone reading. Markdown/CSV files are accessibility and reuse formats of that content. Word equation subscripts and superscripts are retained in the DOCX/PDF; HTML scientific scripts are used in Markdown.

Published for the final submission on 29 October 2026. Cite the fixed commit URL stated in the manuscript. No software executables, model weights, credentials, unpublished reviewer comments or payment documents are included.
