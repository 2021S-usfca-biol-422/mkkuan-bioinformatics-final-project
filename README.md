# Bioinformatics Final Project
Mikaela Kuan
mkkuan@dons.usfca.edu

## Ideas

Parts of this pipeline approach are based on the pipeline described in the [Data Carpentry Genomics lessons](https://datacarpentry.org/genomics-workshop/), which are made available under a [CC-BY 4.0 license](https://creativecommons.org/licenses/by/4.0/).

For my final project, I will be using the [NCBI SARS-CoV-2](https://www.ncbi.nlm.nih.gov/sars-cov-2/) [SRA Bioproject ID 627662, or Accession PRJNA627662](https://www.ncbi.nlm.nih.gov/bioproject/627662), to analyze the data against the template repository from the class organization on GitHub that is now forked onto [my repository](https://github.com/mkkuan/mkkuan-bioinformatics-final-project).

All NCBI SARS-CoV-2 datasets can be found from the following URL: https://www.ncbi.nlm.nih.gov/sars-cov-2/

Since the data is from the beginning half of 2020, I want to see if there are any trends in the data and hospitalization in China. Because SARS-CoV-2 strain variants are popping up in 2021, I also want to start by seeing if there were any variants in the strains found in Shanghai.

I will first start by analyzing the template repository and create a graph to see the hospitalization during the the first half of 2020. Then I will look at the data I chose and create a graph to compare with the template data given. Then I will sort both datasets by the variants and see if any matches the COVID varaints from [this article](https://www.nytimes.com/interactive/2021/health/coronavirus-variant-tracker.html).

## How to run this project

Using the Makefile, SRA_RUNTABLE variable was altered on the command line to include the NCBI SRA Runtable dataset instead of the example in the `data/00_sra_runtable`. This ran overnight to process the data and output a bunch of vcf files in the `data/11_vcf_for_R` directory. The vcf files were processed using a block of code Dr. Zimmerman gave to us in the Report.Rmd file. With that metadata, I was able to look through the collected samples and see what data I can work with. The code written for the figures and tables are specific to this BioProject. If using any other NCBI BioProject, I cannot be certain that it will work.

## Change Log
* 2021-05-12: Add the descriptions to the sections in the Report.Rmd file.

* 2021-05-09: Add the graphs and figures into the Report.Rmd file.

* 2021-04-18: A plan was created to guide my intentions for the final project.

* 2021-04-14: The SRA Bioproject was downloaded for analysis.
