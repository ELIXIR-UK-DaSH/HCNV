---
layout: default
---


# WP3 - Exploitation of the datasets by the Galaxy Community. 


## 1.Intergrating a Copy number variant (CNV) detecting tools into Galaxy. 

Although several CNV detection tools have been developed over the recent years [Zhao et al. (2013)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-S11-S1) only a few of them were integrated into the Galaxy
and only a couple of them are supported and functional

The following compilation presents a comprehensive list of tools designed for the identification of hCNV (heterogeneous Copy Number Variation) in Whole Exome Sequencing datasets. The list provides the names of these tools, their associated links, an indication of their presence on the Galaxy platform, and details regarding their maintenance status, whether they are actively supported or have become obsolete.

[CNVkit Table](https://github.com/users/khaled196/projects/1)


 
 
 
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
