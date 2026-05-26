The scripts in this repository follow a computational pipeline to identify allele frequency differences between pooled population data of pink- and white-flowered L. parviflorus plants at Jasper Ridge Biological Preserve. 
This primarily follows the PoPoolation2 tutorial, which converts CRAM files of each pool into BAM file format, converts those into mpileup and sync files, and finally calculates FST and FET from allele count data.
This workflow was performed on four patches at JRBP, each which included a pool of pink- and white-flowered individuals. The scripts for that process are labelled as Step 1 - 7, with the specific process in the name. 
We also combined all pink- and all white-flowered pools respectively to compare across-site allele frequency differences. This process involved combining BAM files of each colored pool prior to mpileup formation. The files titled 
"popacross". 
