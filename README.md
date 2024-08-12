# pain_in_mental_health


[WEBSITE](https://sites.google.com/view/pain-mental-health/)

[BLOG](https://www.maudsleybrc.nihr.ac.uk/posts/2023/august/identifying-mentions-of-pain-in-mental-health-records-text-a-natural-language-processing-approach/)


This repository contains annotation and adjudication guidelines for pain mentions in mental health records, code for calculation of inter-annotator agreements (to be added), code for building various sentence classifiers (to be added), and results from pain studies.

**File: Annotation Guidelines**

Includes instructions that were followed for the annotation of pain and pain-related terms. 
It also includes adjudication guidelines.

**File: SQL_query_for_dco_extraction**

This is the SQL query that was used to extract documents for the annotation exercise.

**Folder: LDN READ Codes**

This folder contains the READ codes for pain diagnosis, treatment and medication that were used to identify patients with pain within the GP records of Lambeth DataNet.

**Folder: classifier**

This folder contains the scripts to train the BERT and non-BERT models

**Folder: cohort**

This folder contains scripts to explore the descriptives of the cohort in question, and generate venn diagrams to examine various overlaps. Also includes STATA code for logistic regression analysis.

**Knowledge Graph Embedding**

The KGE model scripts are located at: https://github.com/jayachaturvedi/pain_kge_model

**Publications:**

Chaturvedi, J., Stewart, R., Ashworth, M., & Roberts, A. (2023). Distributions of recorded pain in mental health records: A natural language processing based study. BMJOpen [https://doi.org/10.1101/2023.09.15.23295064](https://bmjopen.bmj.com/content/14/4/e079923)

Chaturvedi, J., Wang, T., Velupillai, S., Stewart, R., & Roberts, A. (2023). Development of a Knowledge Graph Embeddings Model for Pain. AMIA Annu Symp Proc. 2024 Jan 11 [https://doi.org/10.48550/arxiv.2308.08904](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10785867/)

Chaturvedi, J., Chance, N., Mirza, L., Vernugopan, V., Velupillai, S., Stewart, R., & Roberts, A. (2023). Development of a Corpus Annotated with Mentions of Pain in Mental Health Records: A Natural Language Processing Approach. JMIR Formative Research. [https://doi.org/10.2196/45849]

Chaturvedi, J., Velupillai, S., Stewart, R., and Roberts, A. (2023). Identifying Mentions of Pain in Mental Health Records Text: A Natural Language Processing Approach. Studies in Health Technology and Informatics, 310, 695–699. [https://doi.org/10.3233/SHTI231054] Awarded Best Student Paper at MEDINFO 2023.

Chaturvedi, J., Mascio, A., Velupillai, S. U., & Roberts, A. (2021). Development of a lexicon for pain. Frontiers in Digital Health, 3, 778305. [https://doi.org/10.3389/fdgth.2021.778305]


