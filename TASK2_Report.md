# SWYNEX Internship – Task 2: Data Cleaning and Basic Analysis

## Dataset
**Escherichia coli str. K-12 substr. MG1655 – complete reference genome**

- NCBI RefSeq accession: **NC_000913.3**
- Genome size: **4,641,652 bp**
- Genome type: **complete circular chromosome**
- Reported GC content: **50.79%**
- Reported coding sequences: **4,285**
- Source: **NCBI RefSeq / Nucleotide**

## Objective
To clean the selected reference genome sequence and calculate basic sequence statistics and quality indicators using Python.

## Analysis performed
1. Downloaded the FASTA sequence from NCBI.
2. Removed FASTA formatting/whitespace and converted the sequence to uppercase.
3. Calculated total sequence length.
4. Counted A, T, G, C and N bases.
5. Calculated GC% and AT%.
6. Checked for unexpected characters.
7. Calculated the percentage of ambiguous bases.
8. Exported the results as a CSV summary.

## Key reference results
The complete MG1655 chromosome is **4,641,652 bp** and has approximately **50.79% GC content**. Published comparisons list **4,285 CDSs** for MG1655.

## Interpretation
The dataset is a complete reference genome, making it suitable for basic sequence-quality analysis. The cleaning step ensures that the sequence contains standardized nucleotide characters before statistics are calculated. GC content provides a basic compositional summary, while the ambiguous-base check is a simple indicator of sequence completeness/quality.

## Files
- `Task2_Data_Cleaning_and_Basic_Analysis.ipynb` – Python analysis notebook
- `task2_sequence_summary.csv` – generated summary table after running the notebook
- `TASK2_Report.md` – concise report

## Source
NCBI RefSeq: NC_000913.3  
https://www.ncbi.nlm.nih.gov/nuccore/NC_000913.3
