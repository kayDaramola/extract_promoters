# extract_promoters.sh
Rim Gubaev, 2018

extract_promoters.sh is intended to extract promoter regions with required lenght. The script works well with NCBI data (i.e. fasta   and gff files). It perfectly fits for organisms with poorly annotated genomes which are basically presented by large sets of contigs. 

**Note:** the script works correct with gff files from NCBI since start position of the gene in NCBI corresponds to transcription start site.

**Input files**
1. multi-fasta file with genomic sequences (i.e contigs or chromosomes)
2. gff file for above multi-fasta file

**Output files**
1. genes.gff shorter version of gff file that contains information on location of genes
2. 


**Required packages:**
1. [samtools](http://samtools.sourceforge.net/)
2. [bedtools](http://bedtools.readthedocs.io/en/latest/)

Email:rimgubaev@gmail.com
