# Business-Analytics-QC-scRNA-seq-Analysis
In this project, I performed quality control (QC) analysis on three single-cell RNA sequencing (scRNA-seq) datasets. The goal was to filter out outlier cells using two common QC metrics: the number of UMIs per cell and the number of genes per cell.

I plotted the distributions of these variables, noting their positive correlation. Then, I established minimum and maximum cutoffs to define outliers based on visual inspection and statistical reasoning. I further visualized these cutoffs on the distribution plots.

After filtering out the outlier cells, I saved new dataframes containing only the cells that passed QC. As a bonus, I explored additional plots to aid in outlier detection and wrote a function to automate the process of choosing cutoffs for these distributions.
