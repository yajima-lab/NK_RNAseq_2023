# Analysis template

Template for analyses repositories. Folders that should be present in all such repositories are:

 * **metadata:** files such as sample manifests, YAML control files
 * **scripts:** additional scripts created for analysis of data
 * **resources** link to project directory on google drive, meeting agenda, and project goals doc

Optional directories are:

 * **notebooks:** notebooks for processed data
 * **results:** any files that will be provided to the collaborator

# Project Information: 

* **Project directory:** https://drive.google.com/drive/folders/1Z3G3h8Hvqa6-k7XTnKGmaF2B8nFw7BE8?usp=drive_link   
* **Project overview:** 
	G4 quadruplexes are higher order, tertiary, structures formed from RNA (ribonucleotides) or DNA. These structures
are comprised of stacks of G-tetrads, structures of four guanine nucleotides bonded together with H-bonds, and can have 
variable elements within their composition (ex: intermediate loops of nucleotides between the tetrads) that may influence their 
overall topology and interactions with their surrounding environment. G4-motifs are sequences that are likely to form G4 quadruplexes,
and can be assessed as such through a number of parameters such as their guanine content, the amount of cytosines in their surrounding 
environment, and so on. Understanding where these G4 motifs are in the genome or transcriptome is important, since the formation of G4
quadruplexes in certain regions can influence the regulation and role of said regions. As a result, the formation of G4 quadruplexes in certain 
genomic regions, such as telomeric areas at the ends of chromosomes, has been hypothesized to influence their regulation even at a transcriptional
or translational level. 
	Hence, understanding where and how G4 quadruplexes form is important towards gaining insight towards the role and functions of 
protein regulators such as Vasa. However, existing wet lab research on G4s - while able to discern many structural characteristics of G4s - are 
limited by their lack of high throughput power, making it hard for them to profile the location and structural aspects of G4 across an 
entire genome or transcriptome. Thus, new computational methods - using approaches ranging from Regex expression-based detection or machine 
learning - have emerged to the fore as a new way to provide predictions on potential G4s across entire genomes or transcriptomes. 
	G4 RNA screener is one of these computational methods, that uses a medley of scoring techniques to evaluate the validity of any 
particular sequence fed into it as a G4 or not. By processing the sea urchin transcriptome and list of potential G4s among Vasa targets (previously obtained byRegex screening) using G4 RNA screener, we can find new potential G4 candidates for subsequent, downstream, analysis.  

* **Meeting notes:**   
7/x: 
7/x: 
7/x: 

* **Analysis notes:** 
	Dockerfile/Docker container was generated based on the Scott Lab's information of the required dependencies for G4 RNA screener, linked here: https://github.com/scottgroup/g4rna_screener. Required output files were generated using the script "screen.py", as described in the relevant bash file for execution (rna_screener.sh). Any subsequent merging of the sequence information was performed in RStudio, though the "merge.py" script provides an identical functionality.
All figures and downstream results were generated using Rstudio (all scripts are available in the scripts folder) -- using the AnnotationHub package, ggplot, and dplyr. 

  **References:**  
1. 
2. 
3. 
```
title:
tags:
analysts:
git_repo_url:
resources_used:
summary:
project_id:
```
