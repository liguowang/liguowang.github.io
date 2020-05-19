---
layout: default
title: Research Interests
---

# Research Interests
---------------------

### Bioinformatics tools/algorithms development
Develop bioinformatics tools and analytic approaches to analyze next generation sequencing
data including genomic, epigenomic and transcriptomic data. At the same time, we actively
collaborate with biologists and physician scientists working on prostate cancer, kidney cancer,
central nervous system (CNS) tumors and other diseases. 

We have developed many useful tools to analyze and visualize high dimensional biomedical data .
These tools have been widely used by academic institutions and industries, and have been
cited hundreds of times. For example:

- We developed the [RSeQC](http://rseqc.sourceforge.net) package
to comprehensively evaluate different aspects of RNA-Seq experiments. RSeQC has been
downloaded tens of thousands of time by people all over the world.  It has been installed
in institute level computing clusters of many institutions including [NIH](https://hpc.nih.gov/apps/rseqc.html),
Boston University, Pennsylvania State University (Galaxy platform), etc.

-  We developed [CPAT](http://lilab.research.bcm.edu/cpat) - to quickly recognize noncoding
RNAs from protein coding mRNAs. CPAT uses a logistic regression model built with four
sequence features. CPAT is not only accurate (sensitivity: 0.96, specificity: 0.97),
but also much more efficient (~10,000 times faster) than other tools, which enables the
users to process thousands of transcripts within seconds. We also developed a web interface
for CPAT that allows users to submit sequences and receive the prediction results almost
instantly.

- We developed [CrossMap](http://crossmap.sourceforge.net/), a versatile and efficient
tool for converting genome analysis results between assemblies. It has been used by
[Ensembl](http://www.ensembl.org/) since 2015 to lift over genomic analysis results, it
is also incorporated into Illumina [BaseSpace cloud computing platform](https://basespace.illumina.com/home).
 

### Biomarker discovery

Identification of biomarkers (i.e., SNPs, mutations, DNA methylations, copy number variations,
RNA splice variants) that are associated with certain phenotypes such as poor prognosis,
tumor subtypes, drug resistance, etc. With the aim to help developing new therapeutic agents,
and enable stratified healthcare and precise medicine. For example:

- Identification of genomic and transcriptomic aberrations associated with primary resistance
to abiraterone acetate (ZYTIGA®) treatments in metastatic castration-resistant prostrate cancer
(mCRPC), we performed whole-exome and RNA sequencing of 86 metastases (and blood) in pre-chemotherapy
mCRPC patients initiating abiraterone acetate/prednisone treatment. We found that genes involved
in the Wnt/β-catenin pathway are frequently mutated, and negative regulators of the Wnt pathway
such as DKK4, SFRP2 and LRP6 were more frequently deleted in patients exhibiting intrinsic resistance
to abiraterone acetate.
[Ann Oncol, 2018](https://www.ncbi.nlm.nih.gov/pubmed/29069303)

- Only a small portion of people who receive immunotherapy will respond to the treatment.
Through integrative analyses of the copy-number profiles of 10,759 patients across 31
cancer types from The Cancer Genome Atlas (TCGA) project, we found the homozygous deletion
of interferon (P = 0.0029, OR = 11.8) and defensin (P = 0.06, OR = 2.79) genes are significantly
associated with resistance to anti-CTLA4 immunotherapy.
[Clin Cancer Res. 2018](https://www.ncbi.nlm.nih.gov/pubmed/29618619)

- The alpha-1 antitrypsin (A1AT) protein is encoded by a gene called *SERPINA1*.
A1AT is an alpha1–proteinase inhibitor which protects tissues from enzymes of inflammatory cells.
People with *SERPINA1* mutation produce functionally defective A1AT or cannot produce sufficient A1AT
(called Alpha-1 antitrypsin deficiency or **A1AD**), and often develop liver and lung diseases.
Despite the common gene mutation, A1AD is characterized by marked heterogeneity in presentation and progression.
Through analyzing the DNA methylation (5-methylcytosine [5mC]) profiles of 94 A1AD patients, we identify
DNA methylation signature that can be used to stratify patients for liver disease risk. 
[Hepatology, 2019](https://www.ncbi.nlm.nih.gov/pubmed/30681738)

### Data mining and integration 

High dimensional biomedical data mining and integration using system biology and machine
learning approaches. With the aim to use data science approaches to build descriptive model
or predictive models to improve healthcare.  