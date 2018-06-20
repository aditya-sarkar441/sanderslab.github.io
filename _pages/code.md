---
title: "Sanders Lab - Code"
layout: textlay
excerpt: "Sanders Lab -- Code."
sitemap: false
permalink: /code/
---


# Code

---

## [wgsPowerTest](https://github.com/stephansanders/wgsPowerTest)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/wgspower.png" style="width: 500px"> 

This R package runs power calculations for the discovery of variants in whole genome sequencing data.

- <a href="https://github.com/stephansanders/wgsPowerTest"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/29184211"><i class='fa fa-book'></i> Paper</a>


---


## [CNVision](https://sourceforge.net/projects/cnvision/)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/cnvision.png" style="width: 500px"> 

CNVision is designed for detecting and scoring Copy Number Variants (CNVs) from Illumina SNP genotyping data. It runs in a UNIX environment and works with all Illumina chips (from 300k to latest Omni). CNVs are predicted using PennCNV, QuantiSNPv2.3, and GNOSIS (an in-built algorithm). The predicted CNVs are merged, joined (if appropriate), and scored based on the per SNP variability in the raw genotyping data. CNVision can also identify de novo CNVs in family-based data using the per SNP variability algorithm. Comparison with 1000 Genomes, the Genome Structural Variation Consortium, and replicate Illumina data demonstrates the efficacy of the CNV scoring method in both inherited and de novo CNVs.
​
CNVision was written to analyze data for the Simons Simplex Collection autism data. A full description of methods are given in the following paper which can be used to reference ([Sanders et al. (2015)](https://www.ncbi.nlm.nih.gov/pubmed/26402605))

- <a href="https://sourceforge.net/projects/cnvision/"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/26402605"><i class='fa fa-book'></i> Paper</a>


---


## [Identity check](http://genomic-identity.wikidot.com/)
​
​Managing large genomic datasets requires accurate estimation of sample identity. This script rapidly identifies all BAM files and Illumina SNP genotyping FinalReports on a cluster, generates a SNP barcode from each one, and uses BLAT to identify duplicates and/or matches. It is run off aligned, indexed BAM files directly (hg18 or hg19) and FinalReports directly (hg18 or hg19). Cross platform (BAM to FinalReport) and cross genome build (hg18 to hg19) is handled automatically.

- <a href="https://sourceforge.net/projects/cnvision/"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/26402605"><i class='fa fa-book'></i> Manual</a>

---

## [UNIX treasure hunt tutorial]()
​
This perl script will install a series of directories and clues that teaches basic UNIX command line skills including cd, ls, grep, less, head, tail, and nano. Run the perl script from the command line on a UNIX based machine (e.g. Mac or Linux) using the command: perl treasureHunt_v2.pl. Then use 'ls' to find the first clue. A PDF of command line commands is also available to download.

- <a href="https://www.dropbox.com/s/kyf3y0cfqr01ffe/treasurehunt_v2.pl?dl=0"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.dropbox.com/s/qhzushxh5s3zia3/Unix_basics.pdf?dl=0"><i class='fa fa-book'></i> Manual</a>

---

