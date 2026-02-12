Sample bTB project for QUB Analytathon 2026. Contains Jupyter notebook for dataset generation, and txt file for example sample data.

Analytathon Challenge: Predicting and Preventing Bovine TB – A Multi-Modal Data Challenge

Challenge Overview
Bovine Tuberculosis (bTB) poses a persistent and costly threat to the UK's cattle industry, impacting animal welfare, farmer livelihoods, and international trade. Effective control strategies require a deep understanding of risk factors, early detection capabilities, and targeted interventions.

This Analytathon challenges you to act as a data science consultant for a national agricultural body. Your mission is to leverage diverse data sources – including farm-level records, geographic information, and environmental imagery – to develop advanced analytical models that can predict bTB risk and inform strategic surveillance and prevention programmes.

Overall Goal
To develop a comprehensive, data-driven solution that identifies farms at high risk of Bovine TB and provides actionable recommendations for surveillance and prevention, utilising insights from both tabular and image data.

Scenario Context
You have been provided with a dataset pertaining to cattle farms in a specific region of the UK. This data includes historical TB test results, farm characteristics, and geographic locations. Crucially, you also have access to aerial imagery for each farm, which may contain visual cues related to environmental risk factors (e.g., proximity to wildlife habitats).

Data Provided
You will receive the following datasets:

farm_data.csv (Tabular Data):


Challenge Tasks
Your team should address the following key areas:

Data Exploration & Preprocessing:
Perform exploratory data analysis (EDA) on both the tabular and image datasets.
Handle missing values, outliers, and data inconsistencies.
Engineer relevant features from the tabular data (e.g., temporal features from Test_Date, farm-level aggregates).
Geographic Risk Analysis:
Visualise: Plot farm locations and positive TB cases on a map to identify potential spatial clusters or hotspots.
Quantify: Use spatial analysis techniques (e.g., distance calculations, density measures, spatial autocorrelation) to identify geographic risk factors.

Environmental Risk Classification from Imagery (CNN Task):
Objective: Build a Convolutional Neural Network (CNN) model to accurately classify the Environmental_Risk_Label for each farm based on its associated image.
