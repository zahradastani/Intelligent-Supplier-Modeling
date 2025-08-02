# Intelligent Supplier Entry & Allocation Process Modeling in the Steel Supply Chain

**Client:** Sangan Steel Company  
**Affiliation:** Ferdowsi University of Mashhad  
**Project Duration:** April 2024 – May 2025  

**Technologies & Techniques:**  
R, Python, MLP Neural Networks, K-Nearest Neighbors (KNN), Support Vector Regression (SVR), Lasso Regression, Time Series Analysis

## Project Overview  
This project aims to optimize supplier selection and allocation in the steel industry by applying advanced machine learning and data mining techniques. The initiative is structured into two main phases:
- **Entry Phase:** Assessing supplier eligibility based on historical performance and operational capacity.  
- **Allocation Phase:** Predicting supplier performance across sequential time periods to enhance dynamic allocation decisions.

## Objectives  
- Streamline and improve the supplier onboarding process by identifying key inefficiencies.  
- Integrate and harmonize semi-annual supplier data from operational systems.  
- Develop robust predictive models to assess supplier eligibility and forecast ongoing performance.  
- Evaluate and compare alternative algorithms in terms of predictive accuracy, robustness, and interpretability.  
- Deliver a practical, data-driven decision-support tool for supplier selection and allocation.

## Dataset Overview  
The project utilizes proprietary datasets containing historical and operational data about suppliers over a multi-year period.
- **Input Variables:** Supplier identity, financial strength, technical credentials, delivery records, and quality control metrics.  
- **Output Variables:** Key performance indicators such as responsiveness, technical proposal quality, success in bidding, quality compliance, and delivery punctuality.
> **Confidentiality Notice:** Raw datasets are not publicly available due to their sensitive nature.  
> **Dataset Documentation:** Detailed dataset description and structure are available in the [`data/README.md`](./data/README.md) file.

## Data Analysis Pipeline  
The end-to-end workflow is organized as follows:
1. **Exploratory Data Analysis (EDA)**  
   Examined distributions, patterns, and anomalies to inform preprocessing.  
2. **Preprocessing & Cleaning**  
   - Removal of outliers and noisy data based on business rules  
   - Normalization and feature scaling  
   - Imputation of missing values and reconciliation of supplier records across time  
3. **Feature Engineering**  
   Constructed time-sensitive and behavior-based features to enhance model predictive power.
4. **Modeling**  
   Built and tested various machine learning models addressing both classification and regression tasks.
5. **Evaluation**  
   Assessed performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with attention to data sparsity challenges.

## Contribution & Responsibilities  
As a key contributor in a collaborative data science team, I was responsible for several critical tasks across the project lifecycle:
- Preprocessing and harmonizing longitudinal supplier datasets to ensure consistency and analytical integrity  
- Designing dynamic, time-aware features that reflect behavioral trends and performance variations over time  
- Developing and validating a diverse set of predictive models—including Lasso Regression, Support Vector Regression (SVR), K-Nearest Neighbors (KNN), and Multilayer Perceptron (MLP) neural networks—using both R and Python  
- Applying advanced machine learning techniques to extract business-relevant insights from complex, high-dimensional data  
- Interpreting model outputs and translating findings into actionable recommendations for supplier evaluation and allocation  
- Documenting methodologies, model specifications, and evaluation results in a transparent and reproducible manner  
My work was aligned with the broader project strategy and complemented the efforts of other team members to ensure a cohesive and impactful analytical solution.

## Confidentiality Statement  
Due to the sensitive nature of operational data, raw datasets and client-specific model results are not published. Only high-level summaries and general modeling procedures are shared in this repository.

## Keywords  
`Supplier Evaluation` · `Machine Learning` · `SVR` · `Neural Networks` · `Time Series Modeling` · `Data Analytics` · `Predictive Modeling` · `Python` · `R`
