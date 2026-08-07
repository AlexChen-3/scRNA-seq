# Progress Log

8/3-8/7/2026:
- Validated GSE147523 to GSE111893 to see what cell types do the upregualted DEGs show up in
- Found that the upregulated DEGs showed up most in Uncommitted HSPC, GMPs, and Monocyclic Precursors compared to healthy controls
  - Disease signature ramps at GMPs and Monocyclic Precursors
- Discovered what DEGs belong to GMPs and B Progenitors
- Next Steps:
  - Need to compare JMML Monocytic Precursors vs. Control Monocytic Precursors gene by gene
  - Need to examine cell-type frequency/compositional permutation test (ie. seeing if CD34+ cells are more significant in JMML samples)


7/27-7/31/2026:
- Restarted QC of GSE111893
- Research Question posed:
  - "Are the bulk DEGs identified in JMML (GSE147523) driven by true cell-intrinsic dysregulation within hematopoietic stem/progenitor cells, or are they artifacts reflecting shifts in progenitor cell-type proportions?"
- Finished Scanpy standard QC workflow, moving onto investigation


07/21-24/2026:
- Continued QC of GSE111893
- Found HVGs and Normalized data with plots
- Scaled and ran PCA and Harmony and plotted UMAP but UMAP needs help


07/20/2026:
- Performed Enrichment on upregulated signatures
- Found top 10 Affected Pathways in JMML and plotted on bar graph
- Began scRNA-seq on GSE111893
  - Compared JMML Signature Scores vs Bulk
  - Began QC of dataset


07/17/2026:
- Created Volcano plot and saved it to figures folder and filed away upregulated genes of interest in JMML vs control


07/15/2026:
- Organized local and Re-organized GitHub directory situation to make it all clean and ready for processing/data
- Ran PyDESeq2 on GSE147523
  - Found that ['FCGR3B', 'HDC', 'HRH4', 'SPRY2', 'IL1R2', 'LOC107986127', 'LOC107986924', 'ETV5', 'LOC112268150', 'SLC1A2'] are the most statistically significant, differentially expressed genes (JMML vs Control)
