---
layout: default
---


# WP3 - Exploitation of the datasets by the Galaxy Community. 


## 1. Integrating Copy number variant (CNV) detecting tools into Galaxy. 

Although several CNV detection tools have been developed over the recent years [Zhao et al. (2013)](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-S11-S1) only a few of them were integrated into the Galaxy
and only a couple of them are supported and functional


## WP3 Deliverables part 1

### Listing the available CNV tools for WES
The following [compilation](https://github.com/users/khaled196/projects/1) presents a comprehensive list of tools designed for the identification of hCNV (heterogeneous Copy Number Variation) in Whole Exome Sequencing datasets. The list provides the names of these tools, their associated links, an indication of their presence on the Galaxy platform, and details regarding their maintenance status, whether they are actively supported or have become obsolete.



### Wrap CNVkit library tools into Galaxy

* [cnvkit_access](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=efd56a79b8a51c16)
* [Cnvkit_antitarget](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=a0a390e388fb7b25)
* [Cnvkit_autobin](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=2eb3e47445bbca39)
* [Cnvkit_batch](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=cc84b6ddffeb2dbc)
* [Cnvkit_breaks](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=976845d7269b45d3)
* [Cnvkit_call](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=e3842df8028f01d5)
* [Cnvkit_coverage](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=3479ce3d4a24f7e3)
* [Cnvkit_diagram](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=4579795a18ea6732)
* [Cnvkit_fix](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=49eeebcaabafce08)
* [Cnvkit_genemetrics](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=8bdc4524718e506e)
* [Cnvkit_heatmap](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=d824f2824319c3e1)
* [Cnvkit_reference](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=7514ecb6bdfaf4e8)
* [cnvkit_scatter](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=7bf0bbfb13765090)
* [cnvkit_segment](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=742eb6184a4a9139)
* [cnvkit_segmetrics](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=9f4fda3e1c67a9ac)
* [cnvkit_sex](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=50d8e9f0cb76d020)
* [cnvkit_target](https://toolshed.g2.bx.psu.edu/repository/browse_repositories?f-free-text-search=cnvkit&sort=name&operation=view_or_manage_repository&id=76a501ee1b1b1233)


# Galaxy tutorial on how to wrap tools into Galaxy. 
 
[Galaxy training network community](https://training.galaxyproject.org/training-material/) provided a [comprehensive tutorial](https://training.galaxyproject.org/training-material/topics/dev/tutorials/tool-from-scratch/tutorial.html) to instruct the users in the full process of integrating a tool into Galaxy through the process of
 - Creating the bioconda recipe for a new tool
 - Building the Galaxy tool wrapper
 - Testing and deployment of this tool into both a local and public Galaxy environment. 

This document presents a case study of integrating [CNVkit](https://cnvkit.readthedocs.io/en/stable/) into the Galaxy using the above tutorial 

## 2. Benchmarking hCNV detection tools. 
Choosing a specific tool to carry on the analysis requires information about CNV detection accuracy, execution time and required infrastructure.

Our plan includes :

1. Do a benchmark test for the CNV detection workflow in Galaxy to measure the run time and detect CNV

2. Compare them with a reference CNV test.

The [reference CNV workflow](https://www.nist.gov/programs-projects/genome-bottle)
 
The [workflow and the tools/code](https://github.com/NCBI-Hackathons/TheHumanPangenome/tree/master/MHC/e2e_notebooks) used

## WP3 Deliverables part 2 

We have published the [workflow](https://workflowhub.eu/workflows/676) created using Contol-FREEC to detect somatic variants on the workflow hub. 
 

# WP4 - Training and dissemination 

## WP4  Deliverables

We have created a tutorial to show how to use Control-FreeC to detect variants and shared it on the Galaxy training network.

The [link](https://training.galaxyproject.org/training-material/topics/variant-analysis/tutorials/somatic-variant-discovery/tutorial.html) for the tutorial


