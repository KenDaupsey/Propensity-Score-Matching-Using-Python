# Propensity-Score-Matching-Using-Python

This project demonstrates the implementation of propensity score matching, a statistical technique used to estimate the treatment effect in observational studies. Propensity score matching aims to mimic the characteristics of a randomized controlled trial by balancing the covariates between the treatment and control groups.

Project Description
The project involves loading a dataset containing information about individuals, their demographic characteristics, baseline health status, treatment assignments, and outcomes. It performs data exploration, visualizes covariate distributions, and splits the data into treatment and control groups. Two propensity score models are built using Logistic Regression and K-Nearest Neighbors (KNN) algorithms. The propensity scores are calculated and visualized for each model. Propensity score matching is then performed to create balanced treatment and control groups. Finally, the average treatment effect is calculated, and the balance of covariates is assessed after matching.

Getting Started
To run this project, you'll need Python 3 and the following libraries installed:

pandas
numpy
scikit-learn
matplotlib
seaborn
statsmodels
You can install the required libraries using pip:


Copy code
pip install pandas numpy scikit-learn matplotlib seaborn statsmodels
Usage
Clone the repository or download the project files.
Navigate to the project directory.
Run the Python script containing the code.
The script will load the dataset, preprocess the data, build propensity score models, calculate and visualize propensity scores, perform propensity score matching, calculate the average treatment effect, and assess the balance of covariates after matching.

Dataset
The dataset used in this project is available on the URL:
"https://raw.githubusercontent.com/KenDaupsey/Propensity-Score-Matching-Using-Python/main/Propensity%20Score%7EDataset.csv"

Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
The scikit-learn, matplotlib, seaborn, and statsmodels libraries used for data analysis and visualization.
