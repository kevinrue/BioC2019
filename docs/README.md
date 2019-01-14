# iSEE: interactive SummarizedExperiment Explorer

# Instructor(s) name(s) and contact information

* Kevin Rue-Albrecht (kevin.rue-albrecht@kennedy.ox.ac.uk)

# Workshop Description

This workshop demonstrates the use of the [_iSEE_](http://bioconductor.org/packages/iSEE/) package to create and configure interactive applications for the exploration of various types of genomics data sets.

This workshop will be presented as a lab session that combines an instructor-led live demo, followed by hands-on experimentation guided by completely worked examples and stand-alone notes that participants may continue to peruse after the workshop.

The instructor-led live demo comprises three parts:

1. Brief lecture of the package concept and functionality
2. Introduction to the user interface
3. Instructions to preconfigure iSEE apps

The hands-on lab comprises three part:

1. Inspection of single-cell RNA-seq data at various steps of a typical computational workflow, including quality control and dimensionality reduction
2. Addition of custom panels to the user interface for advanced visualization.
3. Additional questions from the participants, including individual use cases and suggestions for future developments

Participants are encouraged to ask questions at any time during the workshop.

## Pre-requisites

List any workshop prerequisites, for example:

* Basic knowledge of R syntax and the use of data-frames
* Familiarity with the [`SummarizedExperiment`](http://bioconductor.org/packages/SummarizedExperiment) and [`SingleCellExperiment`](http://bioconductor.org/packages/SingleCellExperiment) classes
* Familiarity with the [`shiny`](https://CRAN.R-project.org/package=shiny) CRAN package
* Familiarity with the [`scRNAseq`](http://bioconductor.org/packages/scRNAseq/) package and [vignette](https://bioconductor.org/packages/release/data/experiment/vignettes/scRNAseq/inst/doc/scRNAseq.html)

Additional background reading about the programming environment, relevant packages, and example use cases:

* Shiny from RStudio: https://shiny.rstudio.com
* SummarizedExperiment paper: https://www.nature.com/articles/nmeth.3252 (Figure 2)
* iSEE paper: https://f1000research.com/articles/7-741/v1

## Workshop Participation

Students will participate by following along an [_R markdown_](https://rmarkdown.rstudio.com/) document, and asking questions throughout the workshop.
There is also scope for participants to apply  [_iSEE_](http://bioconductor.org/packages/iSEE/) to their own data sets, and fuel the discussion with more questions about specific use cases.

## _R_ / _Bioconductor_ packages used

* iSEE
* SummarizedExperiment
* SingleCellExperiment
* scater
* scran

## Time outline

| Activity                                      | Time |
|-----------------------------------------------|------|
| **Lecture**: Overview of package and concepts | 20m  |
| **Live demo**: the user interface             | 20m  |
| **Lab**: Configuring the app interface        | 20m  |
| **Lab**: A single-cell RNA-seq workflow       | 20m  |
| **Lab**: Custom panels                        | 20m  |
| Additional questions                          | 20m  |

# Workshop goals and objectives

## Learning goals

* Recognize the benefits of integrative data containers such as `SummarizedExperiment` and `SingleCellExperiment` for downstream analyses and visualization
* Understand the difference between [RStudio Shiny](https://shiny.rstudio.com) and [_iSEE_](http://bioconductor.org/packages/iSEE/) apps
* Identify biological data that may be combined into insightful graphical outputs
* Utilize interactive UI components and layouts to efficiently extract information from biological data sets
* Describe how to construct interactive apps and custom panels

## Learning objectives

* Memorize the key information available in `SummarizedExperiment` and `SingleCellExperiment` objects
* Set up a local environment for running iSEE apps
* Interact with components of the iSEE user interface to visually inspect and discuss various data sets
* Identify and locate configurable aspects of iSEE apps
* Practice interactive visualization along a single-cell RNA-sequencing workflow
* Design custom iSEE panels for advanced use cases
* Imagine use cases and future developments for interactive visualization as part of computational workflows
