#CGI_MMLP: A synergistic Metaheuristics-Machine Learning framework for Cancer Gene Identification with Pathway-Enrichment based Validation

![Copy of 0419052090_M Sc Thesis Proposal pptx](https://github.com/Shamima21/CancerGeneIdentification/assets/25305468/ca44d9f7-b8be-4425-935d-10b85bca4518)

Cancer is still one of the most notable causes of death worldwide. Identifying cancer-causing genes is essential for understanding cancer development and its progression. 

This repository presents a structured framework for the research project titled "Identification of Cancer-Causing Genes from Microarray Data Using Metaheuristics and Machine Learning." The project utilized existing metaheuristics and machine-learning approaches to enhance the identification of the most significant genes from microarray data. To ensure biological relevance, enrichment analysis, a statistical method, was also integrated. This might help in finding more suitable genes that could be valuable for early diagnosis, personalized therapeutical targets, and future oncogenetic research.
# Reproducibility

This repository contains the complete implementation of the proposed framework described in the manuscript.

The repository includes:

- Source code
- Raw and preprocessed datasets
- Experimental scripts
- Selected genes
- Comparative evaluation
- Enrichment analysis
- Results reported in the manuscript

The reproducible version corresponding to the published manuscript is available as **Release v1.0**.

Repository:
https://github.com/Shamima21/CancerGeneIdentification

Release:
https://github.com/Shamima21/CancerGeneIdentification/releases/tag/(CGI_MMLP)v1.0

## Key contributions
Our main contributions are as follows:

#### Hybrid Wrapper Method:
 Combined metaheuristics and machine learning for efficient gene selection. [see here](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Gene%20Selection)

#### Enrichment Analysis:
Developed a framework to identify gene associations with cancer pathways. [see here](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Enrichment%20Analysis)
#### Data Normalization: 
A [Data Transformation](https://github.com/Shamima21/High-Dimensional-Data-Transformation-) method for normalizing microarray data.
#### Optimization:
 Utilized eight metaheuristics and five classifiers to enhance gene selection and classification.
#### Empirical Validation: 
Tested the methodology on three public microarray cancer [datasets](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Data/Preprocessed%20Data)
#### Integration: 
Overall, Combined computational approaches with the biological relevance of cancer development.

## Getting Started

### Installation

#### Prerequisites
Before you begin, ensure you have met the following requirements:
- You have installed Java (required for Weka).
- You have a basic understanding of command-line operations.
  
This project contains several components:
- Python
- [Weka](https://waikato.github.io/weka-wiki/downloading_weka/)
- [Jupyter Notebooks](https://colab.research.google.com/)
- [Enrichr](https://maayanlab.cloud/Enrichr/) for enrichment analysis
## Datasets

The experiments were conducted using publicly available microarray datasets.

- Leukemia
- DLBCL
- Prostate Cancer

The datasets are available in the [Data](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Data) directory.

#### Steps


## Running the Experiments
The experiments can be run both from the Weka UI and  Jupyter Notebook on Google Colab.
### For Weka
#### 1. Preprocess Data
Open Weka:
Download and install Weka.
Launch Weka and load the microarray data files from the [raw data](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Data/Raw) folder.
Split Train-Test
Apply Normalization:

Normalize the Train data according to the methods detailed in the thesis to ensure consistency and comparability.
#### 2. Feature Selection
Pearson-Correlation Based Ranking:

Hybrid Wrapper Method:

Use the hybrid wrapper method implemented in Weka to select significant genes.
Save the selected genes for further analysis.
#### 3. Classification and Validation
Load Selected Genes:

Import the selected genes into Weka.
Apply Classifiers:

Use classifiers such as SVM, Naive Bayes, Random Forest, and others.
Evaluate the performance using metrics like accuracy, precision, recall, and F1-score.
Validation Techniques:

#### 4. Enrichment Analysis
Perform Enrichment Analysis:

Use the selected genes to conduct enrichment analysis.
Identify significant pathways and assess the biological relevance of the gene sets.

### Running From Scripts

#### 1. Clone the Repository:
```bash
git clone https://github.com/Shamima21/CancerGeneIdentification.git
cd CancerGeneIdentification
```


## Comparative Methods Accuracy Evaluation
We evaluated the accuracy of two state-of-the-art methods on our training dataset, validated using our test set. Additionally, we validated the accuracy using methods such as LOOCV and 10-fold CV. The results of these comparisons, including accuracy evaluations, overlap analysis, and biological relevance analysis, are provided in [Comparative Evaluation](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Comparative%20Evaluation)

