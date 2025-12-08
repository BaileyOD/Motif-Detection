# 🧬 DNA Motif Analysis & Clustered Heatmap

This project performs **motif frequency analysis**, **base composition analysis**, and **clustered heatmap visualization** on DNA sequences stored in a FASTA file. It calculates the occurrences and density of selected DNA motifs, measures GC/AT content, and visualizes motif density using hierarchical clustering.

---

## 📁 Project Overview

This pipeline:

🔎 Parses a FASTA file using **Biopython**  
🧬 Counts occurrences of target DNA motifs  
📊 Calculates motif **density** (motif count per sequence length)  
🧪 Computes **GC and AT content** percentages  
🌡️ Visualizes motif density with a **clustered heatmap** (Seaborn)

---

## 🧪 Example Motifs Used
```python
motifs = ["ATG", "TAT", "CGC"]
