#Predicting Binding Affinity of Drug Compounds for BACE1
##Introduction
Alzheimer's disease is a devastating neurodegenerative disorder, and the search for effective treatments is of utmost importance. Beta-secretase 1 (BACE1) is a key enzyme associated with Alzheimer's, making it an attractive target for drug discovery. This project aims to predict the binding affinity of drug compounds for BACE1 using machine learning techniques. By understanding the bioactivity of compounds and identifying potential BACE1 inhibitors, we can pave the way for the development of novel Alzheimer's treatments.

## Project Overview
In this project, we utilized the following tools and technologies:

Python: 
Jupyter Notebook
Google Colab

## Project Steps:
- 1). Installing ChEMBL Web Service Package: The ChEMBL web service package was installed to retrieve bioactivity data from the ChEMBL Database. Specifically, we extracted bioactivity data for Human BACE1 (CHEMBL4822) that were reported as pChEMBL values.

- 2). Data Retrieval and Pre-processing: We retrieved bioactivity data and handled missing values, dropping compounds with missing values for the standard_value and canonical_smiles columns.

- 3). Exploratory Data Analysis (Chemical Space Analysis): We conducted an exploratory data analysis using Lipinski descriptors to analyze the chemical space of the compounds.

- 4). Labeling Compounds: The compounds were labeled as active, inactive, or intermediate based on their bioactivity data.

- 5). Saving Curated Data: All curated data, including bioactivity and molecular fingerprints, were saved in the BACE_Data folder.

- 6). Machine Learning and Regression Models: We built regression models of BACE1 inhibitors using several ML algorithms. For the hyperparameter optimization, we employed random search CV.

- 7). Statistical Analysis: The Statistical analysis | Mann-Whitney U Test folder contains the statistical analysis of Lipinski descriptors for active and inactive molecules.

## How This Project is Beneficial
This project plays a crucial role in drug discovery for Alzheimer's disease by predicting the binding affinity of drug compounds for BACE1. By identifying potential BACE1 inhibitors, we can accelerate the search for new therapeutic candidates. The predictive models built in this project can be valuable tools for drug researchers, as they provide insights into the bioactivity of compounds, ultimately contributing to the development of innovative Alzheimer's treatments.

## Acknowledgments
Special thanks to the YouTube channel of "Data professor" for providing valuable educational content and guidance throughout the project.

Feel free to explore the repository for the code, data, and in-depth analysis of the BACE1 inhibitors. We hope this project contributes to advancing Alzheimer's research and inspires further investigations into potential drug candidates.







