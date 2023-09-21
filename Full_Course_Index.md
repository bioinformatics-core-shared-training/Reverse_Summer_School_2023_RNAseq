# Introduction to Bulk RNA-seq data analysis

![](images/CRUK_Cambridge_Institute.png)

## Outline

In this workshop, you will be learning how to analyse RNA-seq data. This will
include read alignment, quality control, quantification against a reference,
reading the count data into R, performing differential expression analysis, and
gene set testing, with a focus on the DESeq2 analysis workflow. You will learn
how to generate common plots for analysis and visualisation of gene expression
data, such as boxplots and heatmaps.

This workshop is aimed at biologists interested in learning how to perform
differential expression analysis of RNA-seq data.

> ## Prerequisites
>
> __**Some basic experience of using a UNIX/LINUX command line is assumed**__
>
> __**Some R knowledge is assumed and essential. Without it, you will struggle on this course.**__
> If you are not familiar with the R statistical programming language we
> strongly encourage you to work through an introductory R course before
> attempting these materials.
> We recommend our [Introduction to R course](https://bioinformatics-core-shared-training.github.io/r-intro/)


### Day 1


1. [Introduction to RNAseq Methods](Bulk_RNAseq_Course_Base/Markdowns/01_Introduction_to_RNAseq_Methods.html) - Chandra

2. [Raw read file format and QC](Bulk_RNAseq_Course_Base/Markdowns/02_FastQC_introduction.html) - Adam
  - [Practical](Bulk_RNAseq_Course_Base/Markdowns/02_FastQC_practical.html)  
  - [Practical solutions](Bulk_RNAseq_Course_Base/Markdowns/02_FastQC_practical.Solutions.html)  

3. [Alignment and Quantification of Gene Expression with Salmon](Bulk_RNAseq_Course_Base/Markdowns/03_Quantification_with_Salmon_introduction.html) - Adam
  - [Practical](Bulk_RNAseq_Course_Base/Markdowns/03_Quantification_with_Salmon_practical.html)  
  - [Practical solutions](Bulk_RNAseq_Course_Base/Markdowns/03_Quantification_with_Salmon_practical.Solutions.html)  
    
4. [QC of alignment](Bulk_RNAseq_Course_Base/Markdowns/04_Quality_Control_introduction.html) - Abbi
  - [Practical](Bulk_RNAseq_Course_Base/Markdowns/04_Quality_Control_practical.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/04_Quality_Control_practical.pdf))  
  - [Practical solutions](Bulk_RNAseq_Course_Base/Markdowns/04_Quality_COntrol_practical.Solutions.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/04_Quality_Control_practical.Solutions.pdf))  

15.30 - 17.30 [Data Exploration in R](Bulk_RNAseq_Course_Base/Markdowns/05_Data_Exploration.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/05_Data_Exploration.pdf)) - Jiayin
 - [Practical solutions](Bulk_RNAseq_Course_Base/Markdowns/05_Data_Exploration.Solutions.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/05_Data_Exploration.Solutions.pdf))  
 - [Live script](live_scripts/data_exploration.R)  


### Day 2

**Trainers in-room:** Jiayin, Chandra, Jon, Abbi (OL)  
**Trainers online:** Adam, Raquel, Ulrika

<!-- Welcome Announcements - Abbi -->
9:30 - 10:15  [Introduction to RNAseq Analysis in R](Bulk_RNAseq_Course_Base/Markdowns/06_Introduction_to_RNAseq_Analysis_in_R.html) - Jiayin

10:15 - 13:00 Statistical Analysis of Bulk RNAseq Data

- Part I: [Statistics of RNA-seq analysis](Bulk_RNAseq_Course_Base/additional_scripts_and_materials/RNA-seq_stats.pdf) - Chandra

- Part II: [Linear Models in R and DESeq2](Bulk_RNAseq_Course_Base/Markdowns/07_Linear_Models.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/07_Linear_Models.pdf)) - Chandra
  - [Slides](Bulk_RNAseq_Course_Base/additional_scripts_and_materials/Statistical_models_in_R_DESeq2.pdf)  
  - Find the worksheet in `Course_Materials/stats/models_in_r_worksheet.R`  

13:00 - 14:00 Lunch

14:00 - 17:30 - [Differential Expression for RNA-seq](Bulk_RNAseq_Course_Base/Markdowns/08_DE_analysis_with_DESeq2.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/08_DE_analysis_with_DESeq2.pdf)) - Jon
  - [practical solutions](Bulk_RNAseq_Course_Base/Markdowns/08_DE_analysis_with_DESeq2.Solutions.html) ([pdf](Bulk_RNAseq_Course_Base/Markdowns/08_DE_analysis_with_DESeq2.Solutions.pdf))  
  - [live script](live_scripts/deseq_day2_afternoon.R)  
  - [extra models plots](Bulk_RNAseq_Course_Base/additional_scripts_and_materials/Expl_all.pdf)  

### Day 3

**Trainers in-room:** Abbi, Hugo, Raquel, Jiayin (OL)  
**Trainers online:** Jon, Adam

9.30 - 9.45 - [Recap of Day 1 and 2](Bulk_RNAseq_Course_Base/additional_scripts_and_materials/Analysis_of_RNA-seq_data_day3recap.pdf) - Abbi

9.45 - 12.30 [Annotation and Visualisation of RNA-seq results](Bulk_RNAseq_Course_Base/Markdowns/09_Annotation_and_Visualisation.html) - Raquel
  - [practical solutions](Bulk_RNAseq_Course_Base/Markdowns/09_Annotation_and_Visualisation_Solutions.html)  
  - [live script](live_scripts/ann_and_vis_day3_morning.R) -->

12.30 - 13.30 Lunch

13.30 - 16:30  [Gene-set testing](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing_introduction.html) - Abbi
  - [Practical (html)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.html) [(rmd)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.Rmd) [(pdf)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.pdf)
  -  - [Practical solutions (html)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.Solutions.html) [(rmd)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.Solutions.Rmd) [(pdf)](Bulk_RNAseq_Course_Base/Markdowns/10_Gene_set_testing.Solutions.pdf) 
   - [Live Script](live_scripts/geneSet.R) 

<!-- Goodbye: Abbi -->

## Source Materials for Practicals

The lecture slides and other source materials, including R code and
practical solutions, can be found in the course's [Github
repository](https://github.com/bioinformatics-core-shared-training/Bulk_RNASeq_Course_March23)

## Extended materials

The [Extended Materials](Extended_index.md) contain extensions to some of the
sessions and additional materials, including instruction on downloading and
processing the raw data for this course, a link to an excellent R course, and
where to get further help after the course.

## Additional Resources

* [Bioconductor for relevant R packages](https://bioconductor.org/)
* [DESeq2 Vignette](https://bioconductor.org/packages/release/bioc/vignettes/DESeq2/inst/doc/DESeq2.html)  
* [RNAseq Workflow](http://master.bioconductor.org/packages/release/workflows/vignettes/rnaseqGene/inst/doc/rnaseqGene.html)  
* [RStudio CheatSheets](https://rstudio.com/resources/cheatsheets/)

## Acknowledgements

This course is based on the course [RNAseq analysis in
R](http://combine-australia.github.io/2016-05-11-RNAseq/) prepared by [Combine
Australia](https://combine.org.au/) and delivered on May 11/12th 2016 in
Carlton. We are extremely grateful to the authors for making their materials
available; Maria Doyle, Belinda Phipson, Matt Ritchie, Anna Trigos, Harriet
Dashnow, Charity Law.

![](Bulk_RNAseq_Course_Base/images/combine_banner_small.png)

The materials have been rewritten/modified/corrected/updated by various
contributors over the past 5 years including:

Abigail Edwards
Ashley D Sawle
Chandra Chilamakuri
Dominique-Laurent Couturier
Guillermo Parada González
Hugo Tavares
Jon Price
Mark Dunning
Mark Fernandes
Oscar Rueda
Sankari Nagarajan
Stephane Ballereau
Tom Smith
Zeynep Kalender Atak

Apologies if we have missed anyone!
