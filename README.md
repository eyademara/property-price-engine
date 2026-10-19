# Property Price Intelligence Engine

A system that ingests real rental listings from **Barcelona** (Inside Airbnb), predicts a fair price **with an uncertainty range** ("this flat should cost €90–€120/night"), explains *why* with SHAP, and flags overpriced and bargain listings, all served through a Streamlit web app.

## Why this project
- **Real, messy data**: text, dates, locations, amenities, missing values
- **Price ranges, not a single number**: quantile regression and Bayesian uncertainty
- **Explainability for non-technical users**: SHAP explanations per listing

## Tech stack
Python · PostgreSQL · SQLAlchemy · scikit-learn · LightGBM · XGBoost · CatBoost · Optuna · SHAP · H3 · Streamlit

## Project structure
