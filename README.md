# Solar Flare Analysis

This project aims to characterize solar activity and evaluate predictive models for flare behavior using the **ASR (Archival Solar Flares) catalog** (Berretti & Mestici et al., 2025). 

The repository provides a comprehensive pipeline to process, analyze, and model solar flare data, from statistical trend analysis to machine learning classification.

## Project Structure
The core of this project is contained within the analysis notebook:

👉 **[Open Solar_Flares.ipynb](Solar_Flares.ipynb)**

The analysis is structured as follows:

1. **Data Preparation**: Processing the historical catalog (over 350,000 events) and localized subsets (2010–2024) to extract physical trends and flare morphology.
2. **Chronological Flare Forecasting**: Modeling the relationship between X-ray background flux and flare frequency using Linear Regression.
3. **Multi-Class Intensity Analysis**: In-depth examination of flare classes (C, M, and X) to distinguish between background-driven activity and stochastic extreme events.
4. **Predictive Duration and Class Inference**: Applying Random Forest regressors to link energy flux with flare duration and inferring flare classes via error-link visualizations.
5. **Active Region Persistence Analysis**: Implementing spatio-temporal tracking and comparative ML models (Random Forest, XGBoost, SVM, and Neural Networks) to predict active region stability and lifespan.
