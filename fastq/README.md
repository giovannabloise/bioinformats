# FASTQ files :computer:

Similar to the [FASTA](https://github.com/giovannabloise/bioinformats/tree/main/fasta) file, FASTQ is also a text-based file, but with quality parameters. The file extension are `.fq` anf `.fastq` files and they are the gold-stardart extension to high-throughput sequencing data.

```
 @SEQ_ID
GATTTGGGGTTCAAAGCAGTATCGATCAAATAGTAAATCCATTTGTTCAACTCACAGTTT
+
!''*((((***+))%%%++)(%%%%).1***-+*''))**55CCF>>>>>>CCCCCCC65
```

A FASTQ file has four line-separated fields per sequence:

| Field   | Description                                                                                                                    |
| ------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Field 1 | Begins with a '@' character and is followed by a sequence identifier and an optional description (like a FASTA title line).    |
| Field 2 | is the raw sequence letters.                                                                                                   |
| Field 3 | Begins with a '+' character and is optionally followed by the same sequence identifier (and any description) again.            |
| Field 4 | Encodes the quality values for the sequence in Field 2 and must contain the same number of symbols as letters in the sequence. |
|         |                                                                                                                                |
## How to visualize :eyes:



##
## References :book:
[FASTQ format
](https://en.wikipedia.org/wiki/FASTQ_format)

[FASTA format description](https://www.bioinformatics.nl/tools/crab_fasta.html)
[The Sanger FASTQ file format for sequences with quality scores, and the Solexa/Illumina FASTQ variants](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2847217/)