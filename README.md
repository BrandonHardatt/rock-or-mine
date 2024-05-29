# Sonar Data Classification Project

![alt text](dataset-card.jpg)

### Overview

This project aims to classify sonar signals using various machine learning algorithms. The task is to train a classifier to discriminate between sonar signals bounced off a metal cylinder and those bounced off a roughly cylindrical rock. The dataset used is the [Sonar, Mines vs. Rocks dataset](https://archive.ics.uci.edu/ml/datasets/connectionist+bench+(sonar,+mines+vs.+rocks)) from the UCI Machine Learning Repository.

### Dataset

The dataset contains 208 instances, each with 60 attributes representing sonar signal frequencies. The task is to classify each instance as either a rock (R) or a mine (M).

### Installation

To run this project, you need to have Python installed along with the following packages:

`pip install numpy pandas scikit-learn matplotlib`

### Usage

Clone the repository:
`git clone [repository link]`

Navigate to the project directory:
`cd [project directory]`

Run the Jupyter notebook:
`jupyter notebook main.ipynb`

### Project Structure
- main.ipynb: The main Jupyter notebook containing the code for data processing, model training, and evaluation.
- sonar.all-data-uci.csv: The dataset used for training and testing the models.
- README.md: Project documentation.

### Models Used
- Gaussian Process Classifier
- Support Vector Machine
- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier
- Decision Tree Classifier
- MLP Classifier
- K-Nearest Neighbors
- Gaussian Naive Bayes

### Results
The performance of the models is evaluated using precision, recall, F1-score, and accuracy metrics. The best performing model in the current setup achieved an accuracy of 95.24%.

### Disclaimer
Runtime: Please note that running the entire notebook may take approximately 4-5 minutes to complete, depending on your hardware specifications.

### License
This project is licensed under the MIT License. - see the [LICENSE](LICENSE) file for details.