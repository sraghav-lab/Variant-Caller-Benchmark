# Benchmarking Variant Callers

There are multiple variant calling tools available to detect single nucleotide variants and short insertion and deletions in diploid genomes. Combined with the number of sequence aligners and sequence data pre-processing approaches choosing the best set of tools/methods to perform variant calling becomes challenging. In this approach, we are going to check the performance(resources, time, concordance with truth set) of different variant calling pipelines.

**1) List of aligners**

- BWA (BWAkit)
- Isaac Aligner (Illumina)

**2) List of variant calling tools**

- BCFTOOLS
- BayesTyper
- Freebayes
- GATK
- Strelka2
- Deepvariant
- Dragen? (Not open source)

**3) Data types**

- WGS
- WES

**4) Structural variant callers**

- Manta
- Delly2

**5) Commercial Pipelines **

- DRAGEN, Illumina
- Clara Parabricks, Nvidia
    

**To do**

- [ ]  Collection of GIAB Reference datasets and quality control
- [ ]  Development of python/bash pipeline to capture tool runtime ad resource usage
- [ ]  Hard and soft filtering of detected variation
- [ ]  Calculating statistics against the reference variant calling datasets
- [ ]  Summarising and plotting of results

**Related publications**

[Systematic benchmark of state-of-the-art variant calling pipelines identifies major factors affecting accuracy of coding sequence variant discovery - BMC Genomics](https://bmcgenomics.biomedcentral.com/articles/10.1186/s12864-022-08365-3)

[Accuracy and efficiency of germline variant calling pipelines for human genome data - Scientific Reports](https://www.nature.com/articles/s41598-020-77218-4)

[Best practices for benchmarking germline small-variant calls in human genomes - Nature Biotechnology](https://www.nature.com/articles/s41587-019-0054-x)

**Contributors**

- Arup Ghosh
- Deepak Jena
- Vinit Gupta
- Sudeshna Datta

Feel free to add any tools or publications missed in this document.