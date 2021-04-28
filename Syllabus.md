# Syllabus

## Course Overview

💡 This course will aim to cover transcriptions and neuronal plasticity. Basic knowledge of R , linux command line, and and rudimentary statistics background are required. The learning objectives include:

- Sequence alignment
- Introduction to transcriptomics
- Overview of neuronal plasticity

💡 In this course we will learn how to use [DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html) to perform differential expression analysis and other tools to perform functional enrichment. We will also explore neuronal transcriptomics databases such as the [Allen Brain Atlas](https://portal.brain-map.org/). 

💡 Each class will have a pre-assesment and video lecture that are to be completed before the live course. 

## 📅 Schedule

| Date        | Lesson           | Description  |
| ------------- |:-------------| :-----|
|May 5, 2021 |	Lesson 1: Intro to transcriptomics| 	This lesson will cover transcription, how the data is captures, and a basic overview on fastq and fasta files.|
|May 13, 2021|	 Lesson 2: Sequence alignment| 	This lesson will cover the concepts behind sequence alignment, sequence alignment tools, and how to align raw sequencing data and assess alignment quality.|
|May 19, 2021|	Lesson 3: Pre-processing |	This lesson will cover how to extract quality and transcript data from aligned sequences. |
|May 26, 2021|	Lesson 4: Intro to Neuroplasticy|	This lesson will introduce you to the concept of neuronal plasticity as it relates to gene expression.|
|Jun 2, 2021|	Lesson 5: Differential analysis	| |
|Jun 9, 2021|	Lesson 6: Functional enrichment| 	This lesson will cover the statistical elements behind enrichment analyses and  tools that can be used for functional enrichemnt.|
||Gym: Practical Assessment| 	Given a list of selected papers, you will choose one and replicate the bioinformatics analysis|

## 🎓Grading

There will be 6 assignments that are due before each class. All the assignments will be 60% of the grade and the practical assesment will be 40% of the grade.

## 💻Class set up

- Git clone/download [this repo](https://github.com/MelyssaMinto/NeuroGenomics-HackBio) for course materials
- Install these packages in your respective RStudio Server instance

```r
# installing packages from the CRAN repo
install.packages('tidyverse')
install.packages('reshape2')
install.packages('dendextend')

# Installing packages from the Bioconductor repo
if (!requireNamespace("BiocManager", quietly = TRUE))
install.packages("BiocManager")
BiocManager::install("DESeq2")
BiocManager::install("TxDb.Mmusculus.UCSC.mm10.knownGene")
BiocManager::install("org.Mm.eg.db")
BiocManager::install("clusterProfiler")
BiocManager::install("ReactomePA")

```

## 🚧Troubleshooting

You will run into technical issues during this class, just as any Bioinformatician would. It is very important to understand how to troubleshoot these issues. When running into an error 

1. Read the error message to discern what the problem is 
2. Read the man file or help page for the tool you are trouble shooting 
3. Google it 
4. Ask your peers in the slack channel for the course 
5. Ask me for help 

## ☎Contact

Contact me via slack and give me 24hrs to respond!