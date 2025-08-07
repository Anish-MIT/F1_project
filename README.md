# F1_project
project done under IIT Jammu for data science and data analytics

F1 Hungarian GP 2025 – Race Position Prediction with Machine Learning

Welcome to our Formula 1 Machine Learning project! This repository contains our work on predicting the finishing positions of drivers in the 2025 Hungarian Grand Prix using state-of-the-art machine learning models.
🚦 Project Overview

Formula 1 races are thrilling, unpredictable, and packed with variables—driver skills, team performance, race strategy, weather, and more. In this project, we set out to answer:
Can machine learning help predict the finishing order of drivers for a future F1 race?

We combined real-world race results (via the FastF1 API) with synthetic data simulating realistic scenarios for 2025. Using advanced models like Gradient Boosting and Random Forest, we built and evaluated a predictive system that produces robust, explainable race finish forecasts.

📦 Key Features
    Accurate Position Forecasts: Predicts where each driver is likely to finish, using classification models trained on rich, domain-specific features.
    Explainability: Visualizes which factors (grid position, team strength, driver skill) contribute most to the model's output.
    Flexible Data Pipeline: Combines real and simulated data, with robust preprocessing, scaling, and feature engineering.
    Insightful Evaluation: Includes code for quantitative validation (accuracy, MAE, Top-n accuracy) and clear performance visualizations.

🏎️ What’s Inside
    Python code for training and predicting race results using sklearn, pandas, numpy, FastF1, and visualization libraries.
    Functions for data extraction, synthetic scenario generation, feature engineering, modeling, and result evaluation.
    Example outputs: predicted race orders, bar charts, scatter plots, feature importance graphs, heatmaps, and more.
    Project report describing methodology, results, team roles, and future directions (see Hungarian_GP_2025_Project_Report.docx).

📊 Project Highlights
    Train Accuracy: 95%+
    Cross-Validation Accuracy: ~73%
    Top-3 Accuracy: ~92–94% (within ±2 positions)
    Key Predictors: Grid Position, Team Strength, Driver Skill, Championship Points

🚀 How to Use
    Clone this repo and install the requirements.
    Run the main notebook/script to generate and evaluate predictions.
    Visualize the model's outputs and performance metrics.
    Explore and modify features or models to improve real-world predictive power!

🔮 Future Directions
    Integrate even more detailed race data (sector times, tire strategies).
    Introduce live-data-based simulation for real-time grid updates.
    Deploy as a web-based prediction tool for fans and analysts.

📄 License

This project is for educational and demonstration purposes.

Have fun exploring the intersections of data science and F1 with us!
