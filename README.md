# Dataset-1-and-2---Manuscript-Pyrrhulina

This repository contains two datasets used to perform the analysis in https://www.frontiersin.org/articles/10.3389/fgene.2022.869073/full

Dataset1 - a matrix of polymorphic single nucleotide polymorphisms (SNPs), with a single SNP per locus to prevent the presence of closely linked SNPs based in the “.usnps.geno”

Dataset2 -  phased sequence file for each loci that was implemented only in the genetic diversity and differentiation analyzes based in the “.alleles format”

SAMPLING

28 individuals of the genus Pyrrhulina, of five different species (P. australis, P. brevis, P. obermulleri, P. marilynae and P. semifasciata), from 4 different localities distributed in the Amazon basin and in the Paraná basin.

METHODS

Liver tissue from all individuals was used to perform DArTseq sequencing procedures at Diversity Arrays Technology Pty Ltd. This sequencing method uses a combination of restriction enzymes (SbfI and PstI) that enrich hypomethylated regions (Kilian et al., 2012). Sequencing of the obtained libraries was carried out on the Illumina HiSeq 2500 platform.

The raw data were processed in two different ways to generate the following datasets: (I) a matrix of SNPs using Ipyrad (Eaton and Overcast, 2017) and (II) a phased sequence file with pyRAD v3.0.66 (Eaton, 2014). In both, the sequencing adapters were trimmed, and all sequences shorter than 35 base pairs or presenting more than 5 low-quality bases (Q < 20) were not considered. In dataset I, a single SNP per loci was selected, to reduce the inclusion of linked SNPs, and the SNPs were coded as 0 for reference state homozygotes, 1 for heterozygotes, and 2 for alternative state homozygotes. 

The raw data is available in the database of the National Center for Biotechnology Information, whose project access code is PRJNA804560 (access link:  https://www.ncbi.nlm.nih.gov/Traces/study/?acc=PRJNA804560&o=acc_s %3Aa). 
