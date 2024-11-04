# COMP90089 Group Project README

This project explores the use of machine learning to predict anaphylactic reactions in hospital patients using data from the MIMIC-IV dataset. Given the rising incidence of anaphylaxis and its impact on hospital resources, our objective is to assist clinicians in the early identification of high-risk patients, thus enabling timely intervention and improved patient outcomes. We analyze clinical and physiological features to build models that classify patients as likely or unlikely to experience anaphylaxis during hospitalization.

## Group details

Group Number: 12

Group Members:
- Glenna Guan
- Kae Chinchilla Flores
- Leyao Lyu
- Rowan Shurey

## Running the files
`Data pre-analysis and cleanup.ipynb`: This notebook performs initial data exploration, preprocessing, and cleaning to prepare the dataset for further analysis. It addresses issues like missing values and inconsistencies in the data. Run this file on **Google Colab** due to its use of the MIMIC-IV dataset.

`Project Digital Phenotyping.ipynb`: This file focuses on feature engineering, specifically creating digital phenotypes from raw MIMIC-IV data, transforming time-series data into features useful for machine learning. Run on **Google Colab** for MIMIC data access and processing power.

`Data_selection.ipynb`: This notebook allows for data selection and merging from multiple sources within MIMIC-IV. Running this file will produce a combined dataset, `merged_df.csv`, which is required for modelling. Run this on **Google Colab** to work effectively with MIMIC data.

`Models.ipynb`: This notebook contains the implementation and evaluation of various machine-learning models. It is recommended to run this file on your **local machine**, and the `merged_df.csv` should be in the same folder as this notebook.
