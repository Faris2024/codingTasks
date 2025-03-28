

# Titanic Survival Prediction Using Decision Tree

## Description
This coding task implements a decision tree classifier to predict the survival of passengers on the Titanic. The project includes data cleaning, preprocessing (handling missing values and categorical encoding), splitting data into training/development/test sets, model training with and without depth restrictions, hyperparameter tuning for the optimal max_depth, and visualization of the decision tree. Learning to build and tune decision tree models is crucial for understanding overfitting and model interpretability in machine learning.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [Credits](#credits)

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Faris2024/codingTasks.git
   cd codingTasks/Titanic_Decision_Tree
   ```
2. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```
3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage
After installation, you can run the script directly from the command line:
```bash
python decision_tree_titanic_task.py
```
The program will:
- Load and preprocess the Titanic dataset.
- Split the data into training, development, and test sets.
- Train a decision tree model with various depths and visualize the results.
- Plot the accuracy results for training and development sets.
- Finally, select the optimal model based on development accuracy and evaluate it on the test set.

## Screenshots
Below is an example of what the decision tree visualization might look like:
![Decision Tree Visualization](https://github.com/user-attachments/assets/4e800d73-fffb-46ae-8ca5-d92ee65d5fe4)

## Credits
- **Author:** [Faris Al Waly](https://github.com/Faris2024)
