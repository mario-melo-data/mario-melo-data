# Mario Melo

First-Class Finance and Accounting graduate (BSc Hons, 83.5%, Anglia Ruskin University) with a recently completed MSc in Data Science from City St George's, University of London (taught-module average 72.6%, Distinction level; dissertation submitted, result pending). Eligible for nine ACCA exemptions.

## Looking for

Entry-level and graduate roles in credit risk analytics and modelling, model risk and validation, decisioning and strategy, and data science in financial services and fintech. Based in London with the right to work in the UK and EU.

## MSc dissertation with Registry Trust: Predictive Modelling of Area-Level Credit Risk in England

* Consumer County Court Judgments (CCJs) mark problem debt that has escalated to court, yet no published study was found predicting neighbourhood-level CCJ concentration in England. Designed a machine learning framework to predict which of England's 33,755 neighbourhoods (LSOAs) will fall into the top 10% for CCJ rates a year ahead.
* Linked Registry Trust counts covering 4.4 million consumer judgments (2020 to 2025) with ONS adult population and Indices of Deprivation 2025 data, reconciling the extract to supplier totals and quantifying a 316,048-judgment (6.7%) suppression gap.
* Built a leakage-safe, time-ordered panel and compared Logistic Regression, Random Forest, XGBoost and LightGBM under expanding walk-forward (out-of-time) validation, with pre-registered tuning grids, cross-fitted Platt calibration and a pre-fixed selection rule.
* The selected Logistic Regression reached mean PR-AUC 0.731 (7.3 times the 0.100 baseline), ROC-AUC 0.959 (Gini 0.92) and KS 0.79, and beat the persistence benchmark in all 4 test years. Calibration cut the Brier score by 45% to 58% in every fold, and bootstrap 95% intervals quantify the uncertainty.
* Explained the model with SHAP, K-means explanation profiles and DiCE counterfactual scenarios; the prior-year rate, income and crime deprivation were the main drivers. A disparity audit found the model flagged 72.7% of areas in the most deprived decile and none in the least deprived.
* Tested sensitivity to suppressed counts and to 5% and 20% targets, checked residual spatial dependence with Moran's I, and produced 2026 forecasts for all 33,755 areas.

The code is not yet published on GitHub, and the Registry Trust data are not publicly available.

## Projects

* [credit-default-prediction](https://github.com/mario-melo-data/credit-default-prediction) - Logistic Regression and Random Forest predicting serious delinquency (90+ days past due within 2 years) for 150,000 borrowers (ROC-AUC 0.863), with isotonic calibration and an illustrative cost-sensitive threshold analysis.
* [financial-sentiment-analysis](https://github.com/mario-melo-data/financial-sentiment-analysis) - general-domain BERT and finance-specific FinBERT fine-tuned under identical settings on Financial PhraseBank and compared with classical baselines (macro-F1 0.9422 and 0.9302 against 0.7948 for TF-IDF), with class-weighted loss and manual error analysis.
* [bigdata-image-pipeline-spark-gcp](https://github.com/mario-melo-data/bigdata-image-pipeline-spark-gcp) - PySpark image preprocessing pipeline on Google Cloud Dataproc writing TFRecords, with RDD caching (29.89 times faster), partition tuning and 1-, 4- and 8-machine cluster comparisons within an 8 vCPU budget.
* [credit-risk-visual-analytics](https://github.com/mario-melo-data/credit-risk-visual-analytics) - visual analytics of credit-card default, using visualisation to drive feature engineering, probability reliability assessment and threshold sensitivity analysis.
* [diabetes-prediction](https://github.com/mario-melo-data/diabetes-prediction) - PyTorch MLP and SVM on imbalanced BRFSS data, showing how SMOTE and class weighting raise recall (from 0.079 to 0.765 and 0.781) at almost unchanged ROC-AUC.
* [bank-marketing-prediction](https://github.com/mario-melo-data/bank-marketing-prediction) - Decision Tree and Random Forest in MATLAB with stratified sampling, cross-validation, out-of-bag estimation and ROC-AUC evaluation.
* [air-quality-visualisation](https://github.com/mario-melo-data/air-quality-visualisation) - interactive Observable notebook on London NO2 and PM2.5 against the WHO 2021 guidelines, with IMD 2025 deprivation context and exceedance exploration.

## Tools

* **Python:** pandas, NumPy, SciPy, scikit-learn, XGBoost, LightGBM, imbalanced-learn, PyTorch, TensorFlow, HuggingFace Transformers and Datasets, NLTK, SHAP, DiCE, libpysal, esda, matplotlib, seaborn
* **Big data and cloud:** PySpark (RDDs, partitioning, caching), Google Cloud Dataproc and Cloud Storage, gcloud CLI, TFRecords, Parquet
* **Other languages:** MATLAB (Statistics and Machine Learning Toolbox), JavaScript (Observable, Observable Plot)
* **Visualisation and BI:** Power BI, Tableau, Excel (PivotTables, XLOOKUP)
* **Environment:** Jupyter, Google Colab, Conda, Git and GitHub

## Methods

* **Machine learning:** Logistic Regression, Decision Trees, Random Forest, XGBoost, LightGBM, SVM, neural networks (MLP), transformers (BERT, FinBERT), TF-IDF, K-means clustering, PCA
* **Model development:** feature engineering, class imbalance (class weighting, SMOTE), hyperparameter tuning (grid and randomised search, early stopping), cross-validation, leakage controls
* **Validation and statistics:** out-of-time (walk-forward) validation, probability calibration (Platt, isotonic), PR-AUC, ROC-AUC, Gini, KS, Brier score, precision, recall, F1, bootstrap confidence intervals, sensitivity analysis, linear regression, permutation tests, false discovery rate control
* **Credit risk:** borrower-level delinquency probability estimation and calibration, cost-sensitive decision thresholds, area-level credit risk modelling, financial statement and ratio analysis (DuPont, Altman Z-Score)
* **Explainability and fairness:** SHAP (exact and KernelSHAP), permutation importance, DiCE counterfactuals, disparity auditing (statistical parity and equal opportunity differences)
* **Spatial analysis:** global and local Moran's I, k-nearest-neighbour spatial weights
* **Data quality:** reconciliation to supplier totals, schema and validity checks, exploratory data analysis

## Learning focus

SQL, IFRS 9 expected credit loss and probability of default (PD) model development.

## Languages

English (fluent), Spanish (native), German (B2).

## Contact

* Location: London, UK
* LinkedIn: [linkedin.com/in/mariomelo-](https://linkedin.com/in/mariomelo-)
* Email: [mariodres@hotmail.com](mailto:mariodres@hotmail.com)
