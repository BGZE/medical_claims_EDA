In the U.S, insurance claim denials have been a major issue, affecting both patients and healthcare providers. Inspired by the case of Luigi from the U.S., who highlighted frequent insurance denials, this project explores underclaimed medical expenses using EDA and Machine Learning.

Note: The dataset used is from 2010 and earlier, possibly synthetic, but the methodology can be applied to real-world data.

🔍 Objectives
Understand why some medical expenses go unclaimed and how physicians have biased in it 
Analyze trends and patterns in underclaims and how features like physicians, status, and severity affect it
Use Machine Learning (Random Forest Classifier) to predict underclaims

***Data & Methodology
*Dataset: Medical claims data (2010 and earlier, possibly synthetic)
*Techniques Used:
-Data Cleaning & Preprocessing using pandas

-Exploratory Data Analysis (EDA) using matplot and sns

-Feature Engineering & Selection

-Machine Learning Model (Random Forest)

-Model Evaluation & Feature Importance Analysis

***Key Insights
✔️ Having a private attorneys clearly has an impact on the claim amount, which means that physicians tend to have a huge impact on the amount which should be investigated.
✔️ Demographic factors & claim amounts played a role in underclaim patterns.

*** Future Work & Applications
-Obtain modern datasets to analyze recent insurance claim trends
-Compare Random Forest with XGBoost & Explainable AI methods
-Develop a web app for users to check underclaim likelihood
