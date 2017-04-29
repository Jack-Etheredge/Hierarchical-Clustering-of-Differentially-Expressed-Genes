# Hierarchical-Clustering-of-Differentially-Expressed-Genes
Hierarchical clustering of differentially expressed genes for thesis.

This creates a hierarchical clustering using heatmap.2 from the R library gplots.

In order for a gene to be included included, it must be expressed highly (>100 FPKM) in at least one sample and must be expressed 2-fold above or below the reference sample (combined immature neurons). Fold change must meet a q-value of 0.1 to be considered significant. This q-value is calculated from pairwise (sample1 vs sample2) ANOVAs on every gene. The q-value is an FDR-corrected p-value.
