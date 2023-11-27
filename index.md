---
layout: default
---


# WP3 - Exploitation of the datasets by the Galaxy Community. 


## 1.Intergrating a Copy number variant (CNV) detecting tools into Galaxy. 

Although several CNV detection tools have been developed over the recent years [Zhao et al. (2013)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-S11-S1) only a few of them were integrated into the Galaxy
and only a couple of them are supported and functional

The following compilation presents a comprehensive list of tools designed for the identification of hCNV (heterogeneous Copy Number Variation) in Whole Exome Sequencing datasets. The list provides the names of these tools, their associated links, an indication of their presence on the Galaxy platform, and details regarding their maintenance status, whether they are actively supported or have become obsolete.

Title|Description|Source|Tool version|CONDA|CONDA source|Wrapper source|Wrapper owner|Wrapper version|Comment|Pull requests (Linked)|Status|Assignees|
|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|:------|
|AbsCN-seq|"AbsCN-seq is an R package for estimation of tumor purity, ploidy, and copy number variation (CNV) in next-generation sequencing|data."|https://bioinformaticshome.com/tools/cnv/descriptions/AbsCN-seq.html|1|NO|||||||To add||
|Accurity|"Accurity is a software tool for inferring tumor cell ploidy, tumor purity, and absolute allelic copy numbers for somatic copy number alterations in whole-genome sequencing|(WGS) data."|https://www.yfish.org/display/PUB/Accurity||NO|||||(whole exome may work too)||To add||
|ADTEx|"A tool for detection of copy number variation (CNV) in whole-genome exome data from paired or healthy tumor samples. The ADTex algorithm uses Hidden Markov Models (HMM) to predict CNV counts, genotypes, polyploidy, aneuploidy, cell contamination, and baseline shifts. The authors originally named ADTex CoNVEX, but they changed the name because of the conflict with another tool."|https://bioinformaticshome.com/tools/cnv/descriptions/ADTEx.html|2|NO|||||||To add||
|aCNViewer|"aCNViewer is a tool for visualization of copy number variation (CNV) and loss of heterozygosity (LOH) in tumor samples. aCNViewer uses the Docker application. Requires: R, Python, Mode, Affymetrix power tools, Ascat, sequenza, and ggplot2."|https://bioinformaticshome.com/tools/cnv/descriptions/aCNViewer.html|2.2|NO|||||||To add||
|Bamgineer|A tool to simulate haplotype-phased allele-specific copy number variation (CNV) into a Binary Alignment Mapping (BAM) and cancer CNVs in exome and targeted cell-free DNA sequencing data.|https://bioinformaticshome.com/tools/cnv/descriptions/Bamgineer.html|2|NO|||||||To add||
|BubbleTree|"BubbleTree is an R package for the analysis of tumor samples in next-generation sequencing (NGS) data. The BubbleTree algorithm can estimate cancer-causing cell impurity, ploidy, clonality, and allele-specific copy number variation (CNV). It displays the results in a graph format. The Authors claim that BubbleTree outperforms THetA2, ABSOLUTE, AbsCN-seq, and ASCAT tools."|https://bioinformaticshome.com/tools/cnv/descriptions/BubbleTree.html|2.14.0|Yes|https://anaconda.org/search?q=BubbleTree||||||To add||
|CANOES|CANOES is a tool for the detection of copy number variation (CNV) in whole-genome exome sequencing data. The CANOES algorithm uses the negative binomial distribution to model read counts and a regression-based method on user-selected reference samples.|https://bioinformaticshome.com/tools/cnv/descriptions/CANOES.html|*** the tool is not currently|NO|||||||To add||
|CODEX2|The tool uses depth information from the sequence to determine the presence or absence of a CNV|[GitHub](https://github.com/yuchaojiang/CODEX2)||NO|||||To add||||
|Control-FREEC|A tool for assessing copy number and allelic content using next-generation sequencing data.|[GitHub](https://github.com/BoevaLab/FREEC)|v11.6|Yes|[CONDA](https://anaconda.org/search?q=Control-FREEC%09)|[GitHub](https://github.com/galaxyproject/tools-iuc/tree/master/tools/freec)|iuc|11.6|Up-to-date||||
|CoNIFER|Uses exome sequencing data to find copy number variants (CNVs) and genotype the copy-number of duplicated genes|[SourceForge](https://sourceforge.net/projects/conifer/)|0.2.1|Yes|[CONDA](https://anaconda.org/search?q=CoNIFER)||||To add||||
|CONTRA|A tool for copy number variation (CNV) detection for targeted resequencing data such as those from whole-exome capture data.|[CONTRA](https://contra-cnv.sourceforge.net/)|v2.0.6|NO||[Toolshed](https://toolshed.g2.bx.psu.edu/repository)|fcaramia|2.4|To update||||
|CoNVaDING|A tool for identification of copy number variation (CNV) specifically in next-generation sequencing (NGS) data.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CoNVaDING.html)|1.2.0|NO|||||To add||||
|CloneCNA|CloneCNA is a tool to detect copy number variation (CNV) in heterogeneous tumor samples in whole-genome exome sequencing data.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CloneCNA.html)|2|NO|||||To add||||
|CNVkit|is a Python library and command-line software toolkit to infer and visualize copy number from high-throughput DNA sequencing data.|[GitHub](https://github.com/etal/cnvkit)|0.9.9|Yes|[CONDA](https://anaconda.org/search?q=CNVkit)||||Up-to-date|khaled196|||
|cn.mops|cn.mops (Copy Number estimation by a Mixture Of PoissonS) is an R package pipeline for analysis of copy number variation (CNV)|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/cn-mops.html)|1.30.0|Yes|[CONDA](https://anaconda.org/search?q=cn.mops)||||To add||||
|CNspector|CNspector is a web-based tool for clinical diagnosis and visualization of copy number variation (CNV) using next-generation sequencing (NGS) data.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CNspector.html)||NO|||||Special methods for WES||To add||
|CNVfinder|CNVfinder is a tool to detect copy number variation in whole-genome exome sequencing data generated using amplicon-based enrichment technologies.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CNVfinder.html)|1.0.0b5|NO|||||To add||||
|CNVnator|A tool for discovery and characterization of copy number variation (CNV) in population genome sequencing data.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CNVnator.html)||Yes|[CONDA](https://anaconda.org/search?q=CNVnator)|[Toolshed](https://toolshed.g2.bx.psu.edu/repository)|fanruimeng||It was used in a paper to detect CNVs in WES data|Neglected|||
|cnvOffSeq|cnvOffSeq is specifically designed for the detection of intergenic copy number variation (CNV) using off-target exome sequencing data.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/cnvOffSeq.html)|0.1.2|NO|||||To add||||
|CN_Learn|CN_Learn is a tool for copy number variation (CNV) detection. The algorithm integrates multiple CNV detection algorithms and learns to identify CNVs based on validated CNVs.|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/CN_Learn.html)||NO|||||To add||||
|DeAnnCNV|DeAnnCNV (Detection and Annotation of Copy Number Variations) is a web-based tool to detect and annotate copy number variation (CNV) in whole genome exome sequencing. The algorithm is based on GPHMM tool (see links).|[BioinformaticsHome](https://bioinformaticshome.com/tools/cnv/descriptions/DeAnnCNV.html)||NO|||||To add||||
|EXCAVATOR2|EXCAVATOR2 is a tool for detecting copy number variation (CNV) in whole-genome exome sequencing data. The EXCAVATOR2 algorithm uses a hidden Markov model (HMM) and a method that classifies genomic regions into five CNV states. EXCAVATOR2 is an enhanced version of EXCAVATOR (see links).|
ExCNVSS|ExCNVSS is a software tool to detect copy number variation (CNV) in whole-genome exome sequencing data. The ExCNVSS algorithm is based on an evaluation of the coverage and uses a scale-space filtering approach to resolve coverage biases.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/ExCNVSS.html)||NO|||||||To add|
ExoCNVTest !!!!!|an exome sequencing analysis pipeline to identify disease-associated CNVs and to generate absolute copy number genotypes at putatively associated loci|[Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3436806/)||NO|||||||To add|
exomeCopy|exomeCopy R package is for detection of copy number variants (CNV) from exome and unpaired sample sequencing. The implementation is based on a hidden Markov model on background read depth and GC-content to normalize copy count.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/exomeCopy.html)|1.30.0|Yes|[Link](https://anaconda.org/search?q=exomeCopy)||||||To add|
ExomeCNV|a tool for detection of copy number variation (CNV) and loss of heterozygosity (LOH). The algorithm uses statistics of sequence coverage and B-allele frequencies for the estimation of CNV and LOH.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/ExomeCNV.html)|1.4|NO|||||||To add|
ExomeDepth|A tool for calling copy number variation (CNV) from targeted exome sequencing data. ExomeDepth tool is specifically designed to address technical variability between the samples.|[Link](https://github.com/vplagnol/ExomeDepth)|1.1.16|Yes|[Link](https://anaconda.org/search?q=ExomeDepth)|[Link](https://toolshed.g2.bx.psu.edu/repository|iuc)|1.1.10|||To update|
|Genovar|"Genovar is a tool for detection of copy number variation (CNV). It can compare detected CNVs with variants in the Database of Genomic Variants ( DGV) to find out whether variants are novel or previously detected. Genovar can visualize genomic source data|e.g.|aCGH and sequence alignment data."|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/Genovar.html)|0.951b|NO|||||||To add|
|HMZDelFinder|HMZDelFinder is a tool for detection of homozygous/hemizygous copy number variation (CNV) in data from Mendelian disease cohorts.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/HMZDelFinder.html)|3.2.1|NO|||||||To add|
|ichorCNA|ichorCNA is an R tool for estimation of tumor fractions in ultra-low pass whole genome sequencing (WGS) and prediction of large-scale copy number variation (CNV). The ichorCNA algorithm uses a hidden Markov model (HMM) for the probabilistic modeling and works in sequencing coverages down to 0.1X.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/ichorCNA.html)|0.1.0|Yes|[Link](https://anaconda.org/search?q=ichorCNA)||||||To add|
|iCNV|"A tool for detecting copy number variation (CNV) in various study designs: whole-genome exome sequencing|whole-genome sequencing|and single nucleotide polymorphism (SNP). iCNV (integrated CNV) algorithm the Hidden Markov Model (HMM) to do platform-specific normalization and to integrate sequencing data with SNP-array data."|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/iCNV.html)|1.4.0|Yes|[Link](https://anaconda.org/search?q=iCNV)|khaled196|||||To add|
|MATCHCLIP|A legacy tool for detecting copy number variation (CNV) breakpoints. The algorithm identified the breakpoint CIGAR strings of reads and their positions. See links for the updated version.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/MATCHCLIP.html)||NO|||||||To add|
|matchclips2|An updated version of matchclips for detecting copy number variation (CNV) breakpoints. The algorithm identified the breakpoint CIGAR strings of reads and their positions. The updated algorithm runs much faster than the original one.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/matchclips2.html)||NO|||||||To add|
|ONCOCNV|ONCOCNV is a tool to detect copy number variation (CNV) in ultra-deep targeted sequencing. The algorithm uses multifactor normalization and annotation techniques to detect large copy number variation in amplicon sequencing data. The Authors claim their method to have comparable precision to CGH techniques.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/ONCOCNV.html)|6.9|NO|||||||To add|
|panelcn.MOPS|A tool for the detection of copy number variation (CNV) in Next Generation Sequencing (NGS) data panels. This tool includes QC criteria for samples and for a region of interest. Implemented as a standalone tool with a graphical user interface for clinical diagnostics usage and as an R package.|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/panelcn-MOPS.html)|1.1.0|Yes|[Link](https://anaconda.org/search?q=panelcn.MOPS)||||||To add|
|Patchwork|"A tool for analysis and visualization of allele-specific copy number variation (CNV) and loss-of-heterozygosity (LOH) in cancer genomes. The Patchwork tool comes in two variants|Patchwork which takes BAM files as input and PatchworkCG takes CompleteGenomics files as input. Alternative name: patchworkCG."|[Link](https://bioinformaticshome.com/tools/cnv/descriptions/Patchwork.html)||NO|||||||To add|
|PennCNV-ExomeSeq|PennCNV Copy Number Variant Call Detection in Exome Sequencing|[Link](https://penncnvexomeseq.sourceforge.net/)||NO|||||||To add|
|PureCN|"PureCN package is for detection of copy number variation (CNV) and single nucleotide variation classification in targeted sequencing data. The PureCN algorithm estimates tumor purity|CNV|loss of heterozygosity (LOH)|contamination|and classifies single nucleotide variants (SNVs) by somatic status and clonality. The algorithm integrates well with various somatic variant detection pipelines
|PropSeg|A regression model for estimating DNA copy number applied to capture sequencing data|https://ccb.nki.nl/software/ocs/|0.9-4|NO|||||||To add|
|PyLOH|PyLOH is a tool for detecting copy number variation (CNV) and loss of heterozygosity in cancer genomes. The algorithm uses a unified probabilistic framework.|https://bioinformaticshome.com/tools/cnv/descriptions/PyLOH.html|1.1|Yes|https://anaconda.org/search?q=PyLOH||||||To add|
|RefCNV|A tool to copy number variation (CNV). The algorithm uses a reference set to estimate the sequence coverage of each exon.|https://bioinformaticshome.com/tools/cnv/descriptions/RefCNV.html||NO|||||||To add|
|RUbioSeq|RUbioSeq is an integrated software suite for primary and secondary analysis of single nucleotide (SNP), copy number variants (CNV), and bisulfite-seq analyses.|https://bioinformaticshome.com/tools/cnv/descriptions/RUbioSeq.html|3.8.1|NO|||||||To add|
|RUbioSeq+|RUbioSeq+ is an updated and extended version of RUbioSeq. It is an integrated software suite for primary and secondary analysis of single nucleotide (SNP), copy number variants (CNVs), and bisulfite-seq analyses. The extended version includes a pipeline for ChIP-seq experiments, DNA-seq experiments, improvements in the parallelization, and multithreading.|https://bioinformaticshome.com/tools/cnv/descriptions/RUbioSeq-plus.html|3.8.1|NO|||||||To add|
|SAAS-CNV|SAAS-CNV is a tool to identify somatic copy number variation (CNV) in next-generation sequencing (NGS) data. The SAAS-CNV algorithm consists of four main steps: (1) reading a reference and alleles at each locus for comparison of the read depth and alleles with tumor and healthy samples, (2) joint segmentation on the two signals, (3) correction of the CNV baseline, (4) calling of somatic CNVs for all detected signals.|https://bioinformaticshome.com/tools/cnv/descriptions/SAAS-CNV.html|0.3.4|NO|||||||To add|
|SeqGene|A tool which integrates mutation identification, annotation, genotyping, expression quantification, copy number variation (CNV), expression quantitative trait loci (eQTLs) detection, allele specific expression (ASE), differentially expressed genes (DEGs) identification, and pathway analysis workflows in a single package.|https://sourceforge.net/projects/seqgene/|2.5|NO|||||||To add|
|Sequenza|Sequenza package provides tools to genotyping cancer samples, cancer cellularity, ploidy, copy number variation (CNV), and infer alleles that are mutated.|https://bioinformaticshome.com/tools/cnv/descriptions/Sequenza.html|3.0.0|Yes|https://anaconda.org/search?q=Sequenza|https://toolshed.g2.bx.psu.edu/repository|artbio|3.0.0+|||Up-to-date|
|SynthEx|SynthEx is a tool to detect copy number alteration (CNA) and to profile tumor heterogeneity in a variety of high-throughput sequencing data. The SynthEx algorithm uses "synthetic normal" to represent the target; Thus, it does not need a matched pair of samples as normals.|https://bioinformaticshome.com/tools/cnv/descriptions/SynthEx.html|1.06|NO|||||||To add|
|TITAN|TITAN is a tool for estimation of copy number variation (CNV) and loss of heterozygosity (LOH) in whole-genome sequencing data consisting of clonal cell populations. The TITAN algorithm uses hidden Markov model (HMM). Alternative name: TitanCNA|https://bioinformaticshome.com/tools/cnv/descriptions/TITAN.html|1.22.0|Yes|https://anaconda.org/dranew/bioconductor-titan||||can also work on WES data||To add|
|VarScan2|A platform-independent mutation caller for targeted, exome, and whole-genome resequencing data generated on Illumina, SOLiD, Life/PGM, Roche/454, and similar instruments.|https://sourceforge.net/projects/varscan/|2.4.0|NO||https://toolshed.g2.bx.psu.edu/repository|"yhoogstrate"|2.4.2|two tools are in the toolshed https://toolshed.g2.bx.psu.edu/repository||Neglected|
|VCF2CNA|VCF2CNA is a tool to detect copy number variation (CNV) in Tumor/Germline Variant Call Format (VCF) files. The VCF2CNA algorithm also computes tumor purity estimates for samples.|https://bioinformaticshome.com/tools/cnv/descriptions/VCF2CNA.html||NO|||||||To add|
|XCAVATOR|a tool for detecting copy number variation (CNV) in whole-genome exome sequencing data|https://sourceforge.net/projects/xcavator/||NO||||||To add|
|XHMM|Recover information on CNVs from targeted exome sequence data by running depth of coverage calculations, data normalization, CNV calling, and statistical genotyping|https://github.com/RRafiee/XHMM||NO||||||To add|
|WISARD|WISARD, a Workbench for Integrated Superfast Association study with Related Data, is a statistical analysis toolkit for the analysis of large-scale single nucleotide polymorphism (SNP), copy number variation (CNV), and next-generation sequencing (NGS) data. With WISARD, you can analyze related and unrelated samples. The code is optimized for running in multi-core CPUs.|https://bioinformaticshome.com/tools/cnv/descriptions/WISARD.html|1.3.2|NO||||||To add|
|Manta|Manta calls structural variants (SVs) and indels from mapped paired-end sequencing reads. It is optimized for the analysis of germline variation in small sets of individuals and somatic variation in tumor/normal sample pairs.|https://github.com/Illumina/manta|v1.6.0|Yes|https://anaconda.org/bioconda/manta|https://toolshed.g2.bx.psu.edu/repository|artbio|1.6+|||Up-to-date|
|CLAMMS|CLAMMS is a scalable tool for detecting common and rare copy number variants from whole-exome sequencing data.|https://github.com/rgcgithub/clamms|1.1|NO||||||To add|
|SeqCNV (check the tool link again)|a novel method for identification of copy number variations in targeted next-generation sequencing data|https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-017-1566-3#Sec9||NO||||||To add|
|Ulysses|accurate detection of low-frequency structural variations in large insert-size sequencing libraries|http://www.lcqb.upmc.fr/ulysses/|1|NO||||||To add|
|CNV-RF|Random Forest–Based Copy Number Variation Detection Method Using Next-Generation Sequencing|https://github.com/getiria-onsongo/tso_cnv/tree/cnv_paper|1.2.2|NO||||||To add|
|GATK gCNV|Precise common and rare germline CNV calling with|GATK|https://aacrjournals.org/cancerres/article/78/13_Supplement/2287/626564||NO||||||To add|


 
 
 
[Galaxy training network community](https://training.galaxyproject.org/training-material/) provide a [comprehensive tutorial](https://training.galaxyproject.org/training-material/topics/dev/tutorials/tool-from-scratch/tutorial.html)to instruct the reader in the full process of integrating a tool into Galaxy thorugh the process of
 - the creation of a bioconda recipe for a new tool
 - writing a Galaxy tool wrapper
 - finally the testing and deployment of this tool into both a local and public Galaxy environment. 

This document present a case study of intergrating[CNVkit](https://cnvkit.readthedocs.io/en/stable/) into the Galaxy using the above tutorial 

## 2. Benchmarking hCNV detection tools. 
Choosing a specific tool to carry on the analysis require information about CNVs detection accuracy, execution time and required infrastructure.

Our plan includes :

1. Do a benchmark test for the CNV detection workflow in Galaxy to measure the run time and detected CNV

2. Compare them with a reference CNV test.

The reference CNV workflow is available in the reference article below.
https://www.nist.gov/programs-projects/genome-bottle
 
The workflow and the tools/code used
https://github.com/NCBI-Hackathons/TheHumanPangenome/tree/master/MHC/e2e_notebooks 
 

# WP4 - Training and dissemination 
Usually, The preprocessing steps for CNVs data (from the quality control to the mapping step) are the similar for all CNVs detecting workflows. The changes occur in the CNVs detection step. 

Our plan is to create a tutorial that allows the user to understand the CNVs detection process and give guidance on how to choose between the available CNVs tools. 

The process to create this tutorial is by: 

1. View the input requirements for some of the available CNVs tools. 

2. Create a shared prepossessing workflow for different tools data. 

3. Make the tool that requires the longest prepossessing as the main tool in the tutorial and locate the sections where we can introduce the different CBV tools for the data. 

4. add links for additional reading to provide the user with further knowledge on how to use a specific CNV tool 

5. Locate most of the CNV detecting tools available in/outside galaxy 

Our current progress can be found here [tutorial](https://github.com/kpbioteam/training-material/blob/project34/topics/variant-analysis/tutorials/somatic-variant-discovery/tutorial.md) that uses Contol-freec to detect CNVs which also can be the backbone tutorial for this cause.


5. Locate most of the CNV detecting tools available in/outside galaxy 

Our current progress can be found here [tutorial](https://github.com/kpbioteam/training-material/blob/project34/topics/variant-analysis/tutorials/somatic-variant-discovery/tutorial.md) that uses Contol-freec to detect CNVs which also can be the backbone tutorial for this cause.
