# get_viral_haplotypes

## Problem that I am trying to solve

I have a set of viral genome sequences in aligned FastA format. For example, this could be a set of SARS-CoV-2 genomes
that have been aligned against the [Wuhan-Hu-1 reference genome]{https://www.ncbi.nlm.nih.gov/nuccore/MN908947.3}.
The alignment might have been performed using MAFFT as
described [here]{https://mafft.cbrc.jp/alignment/software/closelyrelatedviralgenomes.html}.
I want to perform some phylogenetic or population genetics analysis on this set of genomes, which requires that the
genome sequences are converted into haplotypes. Those haplotypes are required in standard formats FastA and Nexus.
It would also be useful to have a spreadsheet containing details of the haplotypes.
