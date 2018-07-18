# riboseq_mito
This repository contains tools of analyzing mitoribosome profiling data

## Workflow of mitoribosome profiling data

1. Install required software

2. Download sequencing data in the `data` folder 

3. Determine the mapping rule

4. Generate codon count table and other analysis


### Install required software
Download `miniconda`, `bioconda` and `plastid`
Download the folder of riboseq_mito


### Download sequencing data in the `data` folder 
From Galaxy, download the `.bam` files in the `data` folder
Go to the `mapping_config` 
sample names that will be analyzed.
The pipeline will run two functions from `plastid`: `read_phasing` and `mapping_by_size`

`read_phasing` generates read length and phasing distribution, which is helpful as a quality control
`mapping_by_size` will look at five prime or three prime alignment of start and stop codons

### Determine the mapping rule


### Generate codon count table and other analysis
Once the mapping rule has been determined the the user, then 

