# Lysosomal Enzyme Sequence Analysis — CTSD (Cathepsin D)

## Individual Laboratory Activity

**Student:** Hobe Palopalo, BSBIO-III  
**Subject:** Cell and Molecular Biology  
**Activity:** Exploring Lysosomal Enzymes Using NCBI and R  
**Selected Gene:** CTSD  
**Enzyme:** Cathepsin D  
**Organism:** Homo sapiens  

## 1\. Enzyme Information

-   **Gene Symbol:** CTSD

-   **Enzyme Name:** Cathepsin D

-   **Enzyme Classification:** Lysosomal Aspartic Protease

-   **NCBI Protein Accession:** NP\_001900.1

-   **Protein Length:** 412 amino acids

-   **NCBI Protein Record:** [https://www.ncbi.nlm.nih.gov/protein/NP\_001900.1](https://www.ncbi.nlm.nih.gov/protein/NP_001900.1)

### Normal Function

Cathepsin D is a lysosomal enzyme responsible for breaking down proteins into smaller peptide fragments. It plays an important role in intracellular protein degradation, recycling, and maintaining normal cellular function. By helping digest proteins inside lysosomes, Cathepsin D contributes to the removal and processing of cellular materials.

## 2\. Objective

The objective of this laboratory activity is to download and analyze the human Cathepsin D (CTSD) protein sequence from the National Center for Biotechnology Information (NCBI) using RStudio. Specifically, the activity aims to determine the protein length, examine amino acid composition, identify potential N-glycosylation motifs, and visualize the results using graphs.

## 3\. Methodology

The human CTSD protein sequence was obtained from the NCBI Protein database using the RefSeq accession NP\_001900.1. The R package `rentrez` was used to retrieve the protein sequence in FASTA format, while `ggplot2` was used to generate graphical representations of the results.

The R script calculated the total protein length, counted the occurrence and percentage of each standard amino acid, and searched for potential N-glycosylation motifs following the N-X-S/T pattern, where X is any standard amino acid except proline.

The results were saved as CSV files, and two figures were generated to illustrate the amino acid composition and potential N-glycosylation motif positions.

## 4\. Results

### Protein Sequence Summary

| Parameter | Result |
| --- | --- |
| Gene Symbol | CTSD |
| Protein Accession | NP\_001900.1 |
| Protein Length | 412 amino acids |
| Potential N-Glycosylation Motifs | 2 |

### Five Most Common Amino Acids

| Amino Acid | One-Letter Code | Count | Percentage |
| --- | --- | --- | --- |
| Leucine | L | 41 | 9.95% |
| Glycine | G | 39 | 9.47% |
| Serine | S | 37 | 8.98% |
| Valine | V | 34 | 8.25% |
| Alanine | A | 28 | 6.80% |

Leucine was the most abundant amino acid in the CTSD protein sequence, followed by glycine, serine, valine, and alanine.

### Potential N-Glycosylation Motifs

| Motif | Position | Sequence |
| --- | --- | --- |
| 1 | 134 | NGT |
| 2 | 263 | NVT |

Two potential N-glycosylation motifs were identified at positions 134 and 263. Both sequences follow the N-X-S/T pattern, indicating possible glycosylation sites. However, these findings do not confirm actual glycosylation.

## 5\. Figures

### Figure 1. Amino Acid Composition of CTSD

**Figure 1.** Amino acid composition of the human CTSD protein showing the counts of the 20 standard amino acids.

### Figure 2. Potential N-Glycosylation Motifs of CTSD

**Figure 2.** Positions of the two predicted N-glycosylation motifs along the 412-amino-acid CTSD protein sequence.

## 6\. Guide Questions and Answers

### 1\. What does your enzyme normally break down inside lysosomes?

Cathepsin D (CTSD) normally breaks down proteins inside lysosomes into smaller peptide fragments. This process helps cells recycle proteins and remove materials that are no longer needed. It is important for maintaining normal cellular function.

### 2\. What is the total length of your protein, and which amino acids are most common?

The CTSD protein contains 412 amino acids. Based on the sequence analysis, the five most common amino acids are leucine (41; 9.95%), glycine (39; 9.47%), serine (37; 8.98%), valine (34; 8.25%), and alanine (28; 6.80%). Leucine is the most abundant amino acid in the protein sequence.

### 3\. How many potential N-glycosylation motifs did you find? Where are they located?

The analysis identified two potential N-glycosylation motifs in the CTSD protein. The first motif is NGT, located at amino acid position 134, while the second motif is NVT, located at position 263. Both follow the N-X-S/T pattern, where X is not proline. These motifs represent possible glycosylation sites rather than confirmed modifications.

### 4\. Why can glycosylation matter for lysosomal proteins? Does finding a motif prove the protein is glycosylated?

Glycosylation is important for lysosomal proteins because it can support proper protein folding, stability, and transport to the correct cellular location. Some lysosomal enzymes receive mannose-6-phosphate tags that help direct them to lysosomes. However, finding a potential N-glycosylation motif does not prove that the protein is glycosylated or carries a mannose-6-phosphate tag. Additional experimental evidence is needed to confirm these modifications.

### 5\. What could happen in the cell if your enzyme did not work properly?

If Cathepsin D did not function properly, the breakdown of certain proteins inside lysosomes could be disrupted. As a result, materials that should normally be degraded might accumulate, affecting cellular recycling and lysosomal function. This could interfere with normal cellular processes and contribute to cellular dysfunction.

## 7\. Conclusion

This laboratory activity successfully analyzed the human Cathepsin D (CTSD) protein sequence using NCBI and RStudio. The protein was found to contain 412 amino acids, with leucine as the most abundant amino acid. Two potential N-glycosylation motifs were identified at positions 134 and 263. The analysis provided information about the sequence characteristics of CTSD and possible glycosylation sites. However, further experimental studies would be needed to confirm actual glycosylation and enzyme activity.

## 8\. Tools and Resources

-   NCBI Protein Database — [https://www.ncbi.nlm.nih.gov/protein/](https://www.ncbi.nlm.nih.gov/protein/)

-   R and RStudio

-   `rentrez` R package

-   `ggplot2` R package

-   GitHub

## 9\. References

-   National Center for Biotechnology Information (NCBI). Human Cathepsin D protein record, RefSeq accession NP\_001900.1. [https://www.ncbi.nlm.nih.gov/protein/NP\_001900.1](https://www.ncbi.nlm.nih.gov/protein/NP_001900.1)

-   R Core Team. R: A Language and Environment for Statistical Computing. [https://www.r-project.org/](https://www.r-project.org/)

-   Wickham, H., et al. ggplot2: Create Elegant Data Visualisations Using the Grammar of Graphics. [https://ggplot2.tidyverse.org/](https://ggplot2.tidyverse.org/)
