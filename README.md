# MLPC
## 🧠 Project Overview

This notebook presents a streamlined machine-learning workflow for wildfire detection and intensity estimation using the VIIRS satellite dataset for Sweden in 2018. It begins with loading and exploring the data—including key features like brightness temperatures (bright_ti4, bright_ti5) and fire radiative power (frp)—then filters and prepares a clean dataset for regression modeling. The code sets up a feature matrix and target variable (frp), providing the foundation for training regression models (such as RandomForest or Linear Regression) to predict fire intensity from satellite-derived spectral measurements. It is written with maintainability and performance in mind, leveraging libraries like pandas, NumPy, scikit-learn, and joblib for clear structure, efficient computation, and easy extension to full model training and evaluation.

This project implements a machine learning pipeline designed to classify input data using Python. Key components include:

- **Data loading and preprocessing**  
- **Feature engineering**  
- **Model training and evaluation**  
- **Performance logging and result visualization**

The pipeline is modular and can be easily adapted to new datasets or models.

---
