Contents of this repository

* `TCGA-KIRC_GDC_dataDownload.html` and `TCGA-KIRC_GDC_dataDownload.Rmd`
  + RMarkdown of TCGA-KIRC gene expression, gene mutation status, and gene-level copy number status data retrieval from GDC via [`TCGAbiolinks`](http://bioconductor.org/packages/release/bioc/html/TCGAbiolinks.html)
  + Rendered document [here](https://jeremymsimon.github.io/Zhang_TCGA-KIRC_GDC_dCas9screen/TCGA-KIRC_GDC_dataDownload.html)

* `TCGA-KIRC_GDC_TumorNormal_DESeq2.html` and `TCGA-KIRC_GDC_TumorNormal_DESeq2.Rmd`
  + RMarkdown of TCGA-KIRC tumor vs normal differential expression analysis using [`DESeq2`](http://bioconductor.org/packages/release/bioc/html/DESeq2.html)
  + Rendered document [here](https://jeremymsimon.github.io/Zhang_TCGA-KIRC_GDC_dCas9screen/TCGA-KIRC_GDC_TumorNormal_DESeq2.html)

* `dCas9screen_DESeq2.html` and `dCas9screen_DESeq2.Rmd`
  + RMarkdown of differential abundance analysis of dCas9 screen results using [`DESeq2`](http://bioconductor.org/packages/release/bioc/html/DESeq2.html)
  + Rendered document [here](https://jeremymsimon.github.io/Zhang_TCGA-KIRC_GDC_dCas9screen/dCas9screen_DESeq2.html)
  
* `TCGA-KIRC_GDC_survival.html` and `TCGA-KIRC_GDC_survival.Rmd`
  + RMarkdown of Kaplan-Meier and Cox proportional hazard testing for putative target genes using [`survminer`](https://rpkgs.datanovia.com/survminer/)
  + `TCGA_KIRC_GDC_survival_survminer_results.pdf` includes Kaplan-Meier curves and associated statistics for each gene
  + Rendered document [here](https://jeremymsimon.github.io/Zhang_TCGA-KIRC_GDC_dCas9screen/TCGA-KIRC_GDC_survival.html)

* `TCGA-KIRC_GDC_plotAssembly.html` and `TCGA-KIRC_GDC_plotAssembly.Rmd`
  + RMarkdown of final plot assembly, containing dCas9 screen results, expression of putative target genes in TCGA-KIRC samples, association with patient Overall Survival, VHL mutation status, and VHL gene-level copy number
  + Rendered document [here](https://jeremymsimon.github.io/Zhang_TCGA-KIRC_GDC_dCas9screen/TCGA-KIRC_GDC_plotAssembly.html)

* All associated input and output data files
