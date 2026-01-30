# Bioinformatics Python Notebooks (Sequence • Expression • Genomics Utilities)

A curated set of Python notebooks demonstrating practical **bioinformatics / computational biology workflows**:
DNA sequence analysis, FASTA parsing, gene expression statistics, GFF feature parsing, BLAST automation,
visualization (histograms/box plots), normalization, and data cleaning.

This repository is designed to be **job-application friendly**: clear structure, reproducible setup,
and concise notebooks focused on real-world data handling.

---

## Highlights

- **DNA / Sequence analytics**: nucleotide counts, proportions, pattern search, replacements, coordinate reporting
- **FASTA parsing (Biopython)**: build header→sequence dictionaries, extract target gene/protein (RAD21), export FASTA
- **Gene expression statistics**: min/max/mean/sum/variance; ranking top genes by mean and variance
- **Genome annotation parsing (GFF)**: extract gene coordinates and generate randomized gene subsets for downstream tasks
- **Local BLAST workflow**: create BLAST database, run `blastp`, parse XML output (Biopython)
- **Visualization & normalization**: histograms + box plots; column-wise normalization; save outputs
- **Tabular cleanup (Pandas)**: handle missing values, cap outliers, filter columns by pattern (e.g., `Context_`)

---

## Repository layout

- `notebooks/` — main deliverables (clean, runnable notebooks)
- `data/` — place your input datasets here (not included by default)
- `outputs/` — generated plots and processed files
- `src/` — optional helper utilities to reuse code across notebooks
- `docs/` — project documentation (assumptions, reproducibility notes)

---

## Quickstart

### 1) Create environment
```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows
pip install -r requirements.txt
