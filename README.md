Lab 5: Decision Tree Classifier
This repository contains the code and explanation for implementing Decision Tree Classifiers to predict the safety of a car. The lab demonstrates building two decision tree models: one using the Gini index criterion and the other using the Entropy criterion.

Aim
To build a Decision Tree Classifier to predict the safety of a car.
To implement two models: one using the Gini Index and another using the Entropy criterion.
Files
Lab_5_Decision_Tree.ipynb: Jupyter notebook containing the decision tree classification models on the car safety dataset.
car_evaluation.csv: Dataset used for training the decision tree models.
Dataset
The dataset used is car_evaluation.csv, which evaluates cars based on several factors like price, maintenance cost, and safety to determine whether the car is acceptable or not.

Features:
buying: Buying price
maint: Maintenance cost
doors: Number of doors
persons: Capacity in terms of persons
lug_boot: Size of the luggage boot
safety: Car safety score
Target:
class: Class of the car (acceptable, unacceptable, etc.)
Prerequisites
To run the code in this repository, you need the following installed:

Python 3.x
Jupyter Notebook or Jupyter Lab
The following Python libraries:
numpy
pandas
matplotlib
seaborn
scikit-learn
graphviz (for visualizing decision trees)
You can install these packages using pip:

bash
Copy code
pip install numpy pandas matplotlib seaborn scikit-learn graphviz
Usage
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/yourusername/decision-tree-lab.git
Open the Jupyter notebook:
bash
Copy code
jupyter notebook Lab_5_Decision_Tree.ipynb
Run the cells in the notebook to perform decision tree classification on the car safety dataset.
Steps in the Notebook
Data Loading and Preprocessing:

Load the dataset car_evaluation.csv and perform exploratory data analysis (EDA).
Handle categorical variables using label encoding for the columns (buying, maint, doors, persons, lug_boot, safety).
Splitting the Dataset:

Split the dataset into training and testing sets (67% train, 33% test).
Decision Tree with Gini Index:

Build a Decision Tree Classifier using the Gini index criterion.
Evaluate the model using accuracy, training score, testing score, and confusion matrix.
Visualize the decision tree using graphviz.
Decision Tree with Entropy:

Build another Decision Tree Classifier using the Entropy criterion.
Evaluate the model similar to the Gini Index model and visualize the decision tree.
Model Evaluation:

Print the classification report with metrics like precision, recall, F1-score, and confusion matrix for both models.
Example Output
After running the notebook, you will see:

Decision tree model predictions for both the Gini and Entropy models.
Performance metrics like accuracy, precision, recall, F1-score, and confusion matrix.
Visualization of the decision tree structure using graphviz.
