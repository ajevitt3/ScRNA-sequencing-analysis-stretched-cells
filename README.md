# ScRNA-sequencing-analysis-stretched-cells

This repository contains the R script used in "Developmental regulation of epithelial cell cuboidal-to-squamous transition in Drosophila follicle cells" by Dongyu Jia, Allison Jevitt, Yi-Chun Huang, Belen Ramos, and Wu-Min Deng (Developmental Biology, 2022). 
To perform the analysis and reproduce figures from this paper, follow the instructions below.

## Download publically available, single-cell RNA sequencing data from [Jevitt et al., 2020](https://pubmed.ncbi.nlm.nih.gov/32339165/)

1. Navigate to the [GSE146040](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE146040) data entry on the GEO database.
2. Select "custom" download for the GSE146040_RAW.tar supplementary file.
![image](https://user-images.githubusercontent.com/50276545/166982623-f83d3b4d-5fa7-40dd-b69a-3565984cd1c6.png)

4. Select the last three files and click download
![image](https://user-images.githubusercontent.com/50276545/166982747-0c99da81-2c69-4e13-86b3-c46757e901bb.png)
5. Unzip the files and place them in a new directory called "Data". 
7. Remove the "GSM4363298_WTDmelOvary3days_14825cells_" prefix from each of the three files so that they simply read:
   - barcodes.tsv
   - genes.tsv
   - matrix.mtx
