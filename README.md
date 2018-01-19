# ZooFlow
Amplicon analysis pipeline for interogation of COI sequence data.

# Workflow notes

Read trimming (SeqTK - https://github.com/lh3/seqtk)

Paired-end reads merged using (PEAR - https://www.h-its.org/en/research/sco/software/#NextGenerationSequencingSequenceAnalysis or FLASH - https://sourceforge.net/projects/flashpage/files/)

Barcode assignment (optional)

Chimeric sequence remove using ref and de novo

Clustering (UCLUST in QIIME - open and closed ref) also, Deblur and Dada2

Singletons removed

Beta-analysis - DCA
