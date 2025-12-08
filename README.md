# DNA Motif Analysis & Clustered Heatmap

This project performs **motif frequency analysis**, **base composition analysis**, and **clustered heatmap visualization** on DNA sequences stored in a FASTA file. It calculates the occurrences and density of selected DNA motifs, measures GC/AT content, and visualizes motif density using hierarchical clustering.

---

## Project Overview

This pipeline:

1. Parses a FASTA file using Biopython  
2. Counts occurrences of target DNA motifs  
3. Calculates motif density (motif count per sequence length)  
4. Computes GC and AT content percentages  
5. Visualizes motif density with a clustered heatmap (Seaborn)

---

## Example Motifs Used
```python
motifs = ["ATG", "TAT", "CGC"]
