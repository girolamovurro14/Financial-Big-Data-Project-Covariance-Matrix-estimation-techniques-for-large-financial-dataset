# Covariance Matrix estimation techniques for large financial dataset - Financial Big Data (FIN-525)

This repository contains the code and report for the final project of the course Financial Big Data of the Master in Financial Engineering at EPFL. The following files are:
-`Financial_Big_data_Project.ipynb` which contains the code with the implementations of the vairous Covariance Matrix Estimation techniques.
-`Project_report_Big_Data.pdf` which is the report of this project.
Please note that due to the dimension of the files, it was not possible to upload the data that we analyzed (below a short description is provided), however the dataset can be required via email at the following address: girolamovurro@gmail.com

# Project Structure
## Presentation
The aim of this project is to empirically assess the importance of covariance filtering in the prediction of the risk of a portfolio. For this purpose, we compare the out-of-sample risk of the Global Minimum Variance Portfolio. The dataset that we used consists into daily close-to-close return observation of the US equity markets
data for 42 years: from 01-01-1980 to 31-03-2022. We select the 1135 stocks with the largest market capitalization using WRDS. Therefore, in total, we have 5598 rows and 1135 columns.
The report is tructured with the following sections:
1. Introduction: General overview and presentation of the procedure.


2. The Dataset: Description of the data used for the analysis.


3. Methodologies: Description of the estimation methods that were applied for the data analysis.


4. Implementation of the Rolling Window: Illustration of the procedure that was followed in order to obtain the results.

5. Results: Description and illustrations (through plots) of the different portfolios built by using different methods of Covariance Estimation. In this section we also provide a brief interpretation of the results and of the various metrics of comparison.

6. Conclusion.

7. Appendix.





## Methods

We first compute the Covariance Estimation naively and then with each of the following methods: 
- Eigen values clipping, 
- Rotationally Invariant Estimators (RIE), 
- Average Oracle (AO) 
- Bootstrap Average linkage Hierarchical Clustering (BAHC)

We analyze also the Optimal Mean-Variance portfolio performance for each of the mentioned techniques.

## Results

We have observed as Average Oracle, BAHC and Eigenvalue clipping could lead to significant improvement of the analyzed portfolio strategies with respect to the naive method, especially when the N/T ratio increases.


