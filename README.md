
A Python tool to analyze DNA sequences for specific motifs, calculate GC and AT content, and visualize motif densities with clustered heatmaps. Ideal for genomics and regulatory sequence analysis projects.

---

## Overview

This project allows users to input a FASTA file containing DNA sequences. The script scans each sequence for specific motifs, calculates motif counts and densities, computes GC and AT content, and generates a clustered heatmap of motif densities across sequences. It is suitable for motif discovery, genomic feature analysis, and educational purposes.

---

## Features

- Scan DNA sequences for user-defined motifs
- Count motif occurrences and calculate motif density
- Calculate GC content (%) and AT content (%) per sequence
- Generate **clustered heatmaps** of motif density across all sequences
- Works with large FASTA files
- Produces publication-ready visualizations

---

## Requirements

- Python 3.8+
- Packages:
  - [Biopython](https://biopython.org/)
  - [Pandas](https://pandas.pydata.org/)
  - [Matplotlib](https://matplotlib.org/)
  - [Seaborn](https://seaborn.pydata.org/)

Install required packages using:

```bash
pip install biopython pandas matplotlib seaborn
```

## Usage 
Example Inputs
```shell
>sequence_1
ATGCGTATGCGCGTATATCGC
>sequence_2
TATCGCATGCGATATCGCGT
```
Edit the Motifs in the Script
```python
motifs = ["ATG", "TAT", "CGC"]
```
## Output
- Densities and Counts of motifs per sequence
- GC and AT content per sequence
- Cluster heatmap with density patterns across sequences

## Project Structure
```powershell
project_folder/
│
├── data/
│   └── example_sequences.fasta   # Input DNA sequences
├── dna_motif_analysis.py         # Main script
├── heatmaps/                     # Generated heatmap images
└── README.md
```
## Future Improvements 
This is a display of Basic skills, howvever
- Motif Discovery
- genome annotations
- Export results to CSV/Excel

 ## License 
 This project is licensed under the MIT License.

 ## Author
 Bailey O'Donnell
 https://github.com/%3Cyour-github-BaileyOD
