# Commands-for-bioinformatic-analysis-of-SRR24415235
`gunzip SRR24415235.fastq.gz`

`conda activate fastqc`

`fastqc SRR24415235.fastq`

`conda deactivate fastqc`

`conda activate flye`

`flye --nano-raw SRR24415235.fastq --genome-size 5.5m --threads 12 -o assembly`
