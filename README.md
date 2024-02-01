# Machine Learning Code Samples
This repository features work I completed for the *Machine Learning for Biomedical Informatics* course in the MScBMI program at UChicago.
In these examples, I build and compare the performance of different machine learning models.

The dataset used in these projects is a de-identified file from a "30-Day Hospital Readmission" study. Data points include patients' age, gender, race, lab values, date of visits, 30-day Readmission, and 30-day mortality.

**ML for BioInformatics 1:** This assignment includes an exploratory data analysis, CHI2 analysis, and preliminary Train/Test data split.

**ML for BioInformatics 2:** In this project, we predicted 30-day readmission and mortality rates for patients in the study. We compared the AUC values of the following models: Logistic Regression, Random Forest, and Gradient Boosted Machine.

**ML for BioInformatics 3:** In this project, we predicted 30-day readmissions using the following models: 
- Naïve model: only patient characteristics (age, gender, and race) to predict 30-day readmission in a logistic regression framework.
- GLM model: patient characteristics and lab recordings to predict 30-day admissions in a logistic regression framework.
- Neural Net Classifier model: patient characteristics and recent lab recordings to predict 30-day admissions using a neural network model. Feature engineering steps include balancing classes using SMOTE as well as data normalization/standardization of continuous variables.
5-Fold cross-validation was used to build the models.
