# title-abstract-screening-ai

## What is this?

This is the github repository hosting the code and a data file related to the following publication.

---

Fabio Dennstädt, Johannes Zink, Paul Martin Putora, Janna Hastings, Nikola Cihoric.\
Title and Abstract Screening for Literature Reviews using Large Language Models: An exploratory study in the biomedical domain.\
*Syst. Rev.* **13**, 158 (2024). [doi: 10.1186/s13643-024-02575-4](https://doi.org/10.1186/s13643-024-02575-4)

---


The publications is about doing an automated title abstract screening in the biomedical domain using artificial-intelligence methods, or more precisely, using large language models to obtain a relevance score for the title and the abstract of a given publication.

## Content

### script.ipynb

A python jupyter script used to run the experiments reported in the article.
It accesses four large language models, which are asked to classify how relevant a publication for a specific task is.
At the end, evaluation scores of the results are computed.

### dataset(CDSS_in_RO).csv

A new, manually created dataset classifying publications on whether they are relevant or irrelevant for *Clinical Decision Support System (CDSS) tools for physicians in radiation oncology*.
It includes 521 publications, 36 of which are classified as being relevant.
In the article, this data set is named ``CDSS_RO``.

