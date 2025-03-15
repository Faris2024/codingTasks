# Titanic Survival Prediction Using Random Forest

## Description
This project builds a **Random Forest Classifier** to predict the survival of passengers on the Titanic. The dataset undergoes preprocessing, feature selection, and hyperparameter tuning to identify the best model. Understanding how decision trees and ensemble learning techniques like Random Forest work is crucial for improving predictive accuracy in real-world applications.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Faris2024/codingTasks.git
   cd codingTasks/Titanic_Random_Forest
   ```
2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```
3. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
   
## Usage
After installation, you can run the Jupyter Notebook or Python script directly:

**To run in Jupyter Notebook:**
```bash
jupyter notebook random_forest_titantic.ipynb
```

**To run as a Python script:**
```bash
python random_forest_titantic.py
```

### Steps Performed in the Project:
- Load and preprocess the Titanic dataset.
- Train a **Random Forest Classifier** to predict passenger survival.
- Determine the most important feature influencing survival.
- Tune **n_estimators** (number of trees) and **max_depth** (tree depth) using **GridSearchCV**.
- Report model accuracy and compare different configurations.
- Evaluate the best model on a test dataset.

## Screenshots
Below is an example of the feature importance visualization:

![Feature Importance](screenshot.png)
> *Replace "screenshot.png" with an actual image in the repository.*

## Credits
- **Author:** [Faris Al Waly](https://github.com/Faris2024)


