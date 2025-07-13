# 🧬 Recombinant pUC19-GH1 Plasmid Construction
This synthetic biology project features the in silico construction of a recombinant pUC19 plasmid carrying Homo sapiens growth hormone 1 (GH1), transcript variant 3. Tools like SnapGene, BioEdit, NEBcutter, and Addgene etc were used for sequence analysis, editing, restriction mapping, and plasmid visualization. Aimed at simulating gene cloning.

This repository presents a bioinformatics-based **recombinant DNA project** focused on cloning the *Homo sapiens* **Growth Hormone 1 (GH1)** gene (transcript variant 3) into the **pUC19 plasmid vector**, using restriction sites for precise gene insertion. This project uses powerful molecular biology tools such as **BioEdit, SnapGene, NEBcutter**, and **Addgene** to simulate the cloning workflow.

---

## 🔍 Gene of Interest

- **Gene**: *Homo sapiens* growth hormone 1 (GH1), transcript variant 3, mRNA  
- **NCBI RefSeq**: [NM_022560.4](https://www.ncbi.nlm.nih.gov/nuccore/NM_022560.4)  
- **FASTA File**: [`FASTA For GH1 (022560.4).txt`](FASTA%20For%20GH1%20(022560.4).txt)

---

## 🧰 Tools Used

| Tool       | Purpose                                        |
|------------|------------------------------------------------|
| **BioEdit**    | Sequence cleanup, ORF validation             |
| **NEBcutter**  | Restriction enzyme mapping                   |
| **Addgene**    | Source for pUC19 plasmid sequence            |
| **SnapGene**   | In silico digestion, ligation & plasmid design |

---

## 🧪 Cloning Strategy

### 1. **Sequence Acquisition**  
- Downloaded GH1 transcript variant 3 mRNA (RefSeq: NM_022560.4) from NCBI.  
- FASTA format added to SnapGene for further analysis.

### 2. **Restriction Enzyme Analysis**  
- Used **NEBcutter** to identify restriction enzyme sites.  
- Selected **BamHI** and **SmaI**:  
  - These enzymes **do not cut the ORF** region.  
  - They are located at the **flanking ends** of the gene.  
- 📷 Reference Image:  
  ![GH1 Restriction Sites](NebCutter%20file%20022560.4.jpg)

### 3. **Vector Selection and Preparation**  
- Downloaded **pUC19 plasmid structure** from Addgene.  
- File: [`addgene puc19.dna`](addgene%20puc19.dna)  
- Opened in SnapGene to analyze multiple cloning site (MCS) and compatible restriction sites.

### 4. **In Silico Cloning in SnapGene**  
- Loaded pUC19 as the **vector backbone**.  
- Imported GH1 FASTA into SnapGene as a **DNA fragment**.  
- Performed **double digestion** with BamHI and SmaI on both vector and insert.  
- Simulated ligation of GH1 into pUC19.

### 5. **Cloned Construct Output**  
- Final recombinant construct with **GH1 inserted at MCS**  
- Maintains proper orientation and ORF integrity  
- File: [`Cloned Final sequence.dna`](Cloned%20Final%20sequence.dna)

---

## 📁 Files Included

| File | Description |
|------|-------------|
| [`FASTA For GH1 (022560.4).txt`](FASTA%20For%20GH1%20(022560.4).txt) | FASTA format of GH1 transcript |
| [`addgene puc19.dna`](addgene%20puc19.dna) | Raw pUC19 plasmid from Addgene |
| [`Snapgene file for 022560.4.dna`](Snapgene%20file%20for%20022560.4.dna) | SnapGene-compatible GH1 DNA file |
| [`Cloned Final sequence.dna`](Cloned%20Final%20sequence.dna) | Final recombinant plasmid with GH1 |
| ![NEBcutter Restriction Map](NebCutter%20file%20022560.4.jpg) | Restriction enzyme map of GH1 gene |

---

## 📌 Summary

This project showcases a clean and efficient **in silico gene cloning protocol**, where the *GH1* gene is successfully inserted into the **pUC19 plasmid** using **BamHI** and **SmaI** restriction sites. The workflow is ideal for simulating gene insertion strategies in a virtual lab setup.

> 🔬 Ideal for biotechnology students and researchers learning molecular cloning, plasmid design, and bioinformatics tools.

---
