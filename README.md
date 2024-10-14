
# sinCellTe 2024: scRNA-seq analysis with long reads

Welcome to the sinCellTe 2024 practical session on single-cell RNA sequencing (scRNA-seq) analysis with long reads. This course is split into two main parts, each contained in separate R Markdown files that guide you through the process of preprocessing scRNA-seq isoform datasets and performing differential isoform expression analysis.

## Course Structure

- **scRNAseq_long_read_part_1.Rmd**: Introduces the preprocessing of scRNA-seq isoform datasets. This part covers the creation of a multi-Assay Seurat object which consolidates various data types and preprocessing steps into a structured format suitable for downstream analysis.

- **scRNAseq_long_read_part_2.Rmd**: Uses the Seurat object created in Part 1 to conduct differential isoform expression analysis. This session aims to identify key differences in isoform usage between different cell types, providing insights into cellular functions and behaviors.

## Repository Organization

```
.
├── data/                  # Datasets used in the analyses
├── imports/               # Additional scripts
├── LICENSE                # License details for the repository
├── README.md              # Overview
├── scRNAseq_long_read_part_1.Rmd  # R Markdown file for Part 1
├── scRNAseq_long_read_part_1.html # Compiled HTML from Part 1 R Markdown
├── scRNAseq_long_read_part_2.Rmd  # R Markdown file for Part 2
└── scRNAseq_long_read_part_2.html # Compiled HTML from Part 2 R Markdown
```

## Getting Started

To get started with the practical sessions:
1. Clone the repository to your local machine.
2. Ensure you have R and the necessary packages installed.
3. Open the `.Rmd` files in RStudio to view and run the code.

Feel free to explore the data and scripts provided to enhance your understanding of scRNA-seq analysis with long reads.
