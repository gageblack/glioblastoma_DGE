# glioblastoma_DGE

This is a differential gene expression analysis using RNA sequencing data from glioblastoma samples publicly available by TCGA.
This analysis is done using the count data from the TCGA, Cell 2013 project.
 * Clinical data downloaded from: https://www.cbioportal.org/study/clinicalData?id=gbm_tcga_pub2013
 * Gene count files and sample sheet were downloaded from the DGC Data Portal: https://portal.gdc.cancer.gov/repository?filters=%7B%22op%22%3A%22and%22%2C%22content%22%3A%5B%7B%22content%22%3A%7B%22field%22%3A%22cases.case_id%22%2C%22value%22%3A%5B%22set_id%3Afz3ffYUBwT6ZqKJs2D9f%22%5D%7D%2C%22op%22%3A%22IN%22%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.access%22%2C%22value%22%3A%5B%22open%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.data_category%22%2C%22value%22%3A%5B%22transcriptome%20profiling%22%5D%7D%7D%2C%7B%22op%22%3A%22in%22%2C%22content%22%3A%7B%22field%22%3A%22files.experimental_strategy%22%2C%22value%22%3A%5B%22RNA-Seq%22%5D%7D%7D%5D%7D
    + This link will take you to the files that were downloaded. Add all to cart, click on the cart, and download files. 
    + This is also where the sample sheet can be downloaded.

The R Markdown file contains all code used for this analysis, including the following analyses:
* Differential Gene Expression based on MGMT methylation status
* Functional Enrichment Analysis
* Gene Set Enrichment Analysis
