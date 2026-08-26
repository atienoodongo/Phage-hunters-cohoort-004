# Phage-hunters-cohort-004
Phage genomics coursework
**Tool	What it does	Takes in	Gives back*
fasterq-dump	Downloads reads from NCBI's SRA	An accession number	FASTQ files
gzip	Compresses files	Any file	Same file, ~4× smaller
FastQC	Inspects read quality	FASTQ	An HTML report
fastp	Trims adapters, drops bad reads	FASTQ	Cleaner FASTQ + a report
Unicycler	Assembles reads into a genome	Cleaned FASTQ	assembly.fasta
QUAST	Measures assembly quality	FASTA	Report with length, contigs, N50, GC
SeqKit	Quick sequence statistics	FASTA	A table of numbers
BLAST	Finds what your sequence matches	FASTA	Ranked list of database hits
