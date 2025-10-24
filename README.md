# Fiber Bragg Grating (FBG) Temperature & Strain Analysis using Machine Learning

# Overview :
This repository contains experimental datasets from Fiber Bragg Grating (FBG) sensors used to measure temperature, strain, and combined effects.
The collected data was processed and analyzed using machine learning models to identify correlations between wavelength shifts and external parameters for improved sensing accuracy.

# Dataset Description
The dataset includes three sets of experiments:
Temperature Experiment — Variation of wavelength with temperature.
Strain Experiment — Variation of wavelength with applied strain.
Combined Temperature & Strain Experiment — Simultaneous variation of both.
Each .xlsx file contains:
Acquisition rate: 5000 Hz
Sensor type: Hyperion FBG module
Channels: CH1–CH4
Columns: Time (s), Channel configuration, and Wavelength (pm)

# Machine Learning Work
Preprocessing: Extracted data from .docx files → converted to .csv.
Feature Engineering: Selected relevant wavelengths and normalized data.
Modeling: Trained regression and classification models to predict:
   Temperature from wavelength shifts.
   Strain from spectral changes.
Algorithms Used: Linear Regression, Random Forest, Support Vector Machine (SVM).
Evaluation Metrics: RMSE, R²-score, and accuracy percentage.

# Results
The ML model achieved a correlation of ~98% between predicted and actual temperature/strain values.
Visualization graphs were generated to show predicted vs actual outputs.

<img width="1395" height="570" alt="Screenshot 2025-09-21 121024" src="https://github.com/user-attachments/assets/cf557015-1d08-46c7-a91d-1cf7b0b03c9e" />
<img width="1383" height="569" alt="Screenshot 2025-09-21 121204" src="https://github.com/user-attachments/assets/30ea273f-d2b3-45ca-8523-78ed610622f8" />
<img width="1392" height="573" alt="Screenshot 2025-09-21 121242" src="https://github.com/user-attachments/assets/831b9e33-89fa-4818-a86d-2f310ad4e3cd" />

# Tools & Libraries
Python (NumPy, Pandas, Matplotlib, Scikit-learn).
Jupyter Notebook/Google colab.

# Future Work
Integration with real-time monitoring systems.
Use of neural networks for enhanced non-linear fitting.
Temperature-strain cross-sensitivity compensation.

# How to Use
git clone "https://github.com/Shreyank86/Fiber_Grating_Experiment-using-ML.git"
