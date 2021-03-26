# NGS-group-workflow
GOAL: Build your one workflow in Galaxy in order to perform species identification 
and determine which antibiotics resistance genes are present resulting from paired-end ILLUMINA data. 
The data has been generated using Nextera ILLUMINA sequencing. 

WORKFLOW contains: 

- Quality check of the ILLUMINA data (before and after trimming) in FastQC

- Trimming of the data in Trimmomatic

- Assembly in SPAdes and in Unicycler to determine the best assembler (Unicycler has our preference)

- Assessment of the quality of the assembly in Quast

- Micro-organism identification using Kraken 2 (standard database 2020-6-24), Convert Kraken and Krona pie chartt for visualisation 

- Antibiotics resistance gene identification in staramr  





 
