# Identification of Cancer-Causing Genes from Microarray Data Using Metaheuristics and Machine Learning.
### Overview

Cancer is still one of the most notable causes of death worldwide. Identifying cancer-causing genes is essential for understanding cancer development and its progression. 
This repository presents a structured framework for the research project titled "Identification of Cancer-Causing Genes from Microarray Data Using Metaheuristics and Machine Learning." The project utilized existing metaheuristics and machine-learning approaches to enhance the identification of the most significant genes from microarray data. To ensure biological relevance, enrichment analysis, a statistical method, was also integrated. This might help in finding more suitable genes that could be valuable for early diagnosis, personalized therapitucal targets, and future oncogenetic research.

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
- Weka
- Jupyter Notebooks
- Enrichr for enrichment analysis

#### Steps

Clone the Repository:
```bash
git clone https://github.com/Shamima21/CancerGeneIdentification.git
cd CancerGeneIdentification
```
## Comparative Methods Accuracy Evaluation
We evaluated the accuracy of two state-of-the-art methods on our training dataset, validated using our test set. Additionally, we validated the accuracy using methods such as LOOCV and 10-fold CV. The results of these comparisons, including accuracy evaluations, overlap analysis, and biological relevance analysis, are provided in [Comparative Evaluation](https://github.com/Shamima21/CancerGeneIdentification/tree/main/Comparative%20Evaluation)

