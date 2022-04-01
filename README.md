[comment]: <> (Hi. If you are seeing this message, please open this file with markdown preview or jupyter notebook. You can do this by right clicking on the readme file and picking 'open with'.)
# INBRE Google Cloud Training Tutorials

## Overview

Included here are several tutorials in the form of 'Jupyter notebooks'.

The purpose of these tutorials is to help users familiarize themselves with the Google Cloud environment in the specific context of running bioinformatics workflows.

These tutorials do this by going step-by-step through specific workflows. These workflows cover the start to finish of basic bioinformatics analysis; starting from downloading raw sequence data, and extending to differential gene expression analysis, and producing common plots in R. 

## Workflows

![RNA-Seq workflow](images/RNA-Seq_Notebook_Homepage.png)

Each notebook covers a specific workflow, and contains a written and visual summary at its head for further information. Access each tutorial for more information:

[Workflow One:](training_demo_short.ipynb) A short introduction to downloading and mapping sequences to a transcriptome using Trimmomatic and Salmon.

[Workflow One (Snakemake):](training_demo_snakemake.ipynb) Using snakemake to run workflow one.

[Extended Workflow One:](training_demo_extended.ipynb) An extended version of workflow one. Once you have got your feet wet, you can retry workflow one with this extended version that covers the entire dataset, and includes elaboration such as using SRA tools for sequence downloading, and examples of running batches of fastq files through the pipeline. This workflow may take around an hour to run.

[Workflow Two:](r_training_demo.ipynb) Using Deseq2 and R to conduct clustering and differential gene expression analysis.



## Requirements

These piplines run entirely within the virtual machine environment of Google Cloud, and so should require nothing more than the ability to produce a virtual machine environment 'notebook' instance on the cloud. 

We chose for the framework of our virtual machines the basic Python 3 framework, for flexibility.

## Data

These tutorials use example sequence data procured from the Sally Molloy labratory here at University of Maine; which investigates the transcriptome change in prophage infected, versus non-prophage infected M. Chelonae bacteria. The respective article can be found <a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8191103/">here</a>.
