## Analysis resources for muscle Iso-Seq publication
Brian Uapinyoying, updated: 7/15/2020

Uapinyoying P, Goecks J, Knoblach SM, Panchapakesan K, Bonnemann CG, Partridge TA, Jaiswal JK, and Hoffman EP. A long-read RNA-seq approach to identify novel transcripts of very large genes. Genome Res. 2020;10.1101/gr.259903.119. doi:10.1101/gr.259903.119
- https://genome.cshlp.org/content/early/2020/07/02/gr.259903.119

### Table of contents:

1. `s0_isoseq_notes` contains the IsoSeq bench protocols related to sequencing on the PacBio RS II and notes on the bioinformatics processing steps of the raw h5 files to aligned bam files.

2. `s1_isoseq_data_processing` has all the scripts used to process the data through the IsoSeq method using smrtAnalysis 2.3 on a cluster with Slurm. A few custom scripts were used for demultiplexing and merging fastq files.

3. `s1b_shortread_data_processing` contains all scripts to process published short-read data used to compare with our long-read (isoseq) data. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6070147/

3. `s2_exCOVator_analysis_pipeline` - scripts for identifying unannotated and differentially used exons using an exon-based method.

4. `s3_exPhaser_analysis_pipeline` - scripts for phasing multiple exons of a transcript, mapping the phasing pattern to known annotations and quantifying the number of sample reads matching the pattern.
