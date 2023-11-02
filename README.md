# Graduate School Acceptance Probability Prediction

This project focuses on creating a Multiple Linear Regression model to predict the probability of being accepted to a graduate school program. The data set used in this project is sourced from Kaggle and provides valuable insights into the factors that influence graduate school admission.

## Project Overview

Admission into a graduate school program is a crucial step in the academic and professional journey of individuals. This project aims to understand how various factors, such as GRE scores, TOEFL scores, university rankings, and letters of recommendation, influence the probability of being accepted to a graduate school. Accurate prediction of acceptance probability can assist students in making informed decisions about their educational pursuits.

## Data

The dataset used in this project is publicly available on Kaggle and contains real-world data related to graduate school admissions. It provides a comprehensive view of the following variables:

-   **GRE Score**: The Graduate Record Examination (GRE) score.
-   **TOEFL Score**: The Test of English as a Foreign Language (TOEFL) score.
-   **University Rating**: The ranking of the applicant's undergraduate institution.
-   **Statement of Purpose Score**: The applicant's statement of purpose score.
-   **Letter of Recommendation Strength**: The strength of letters of recommendation, rated from 1 to 5.
-   **Undergraduate GPA**: The Grade Point Average (GPA) during undergraduate studies.
-   **Research Experience**: Whether the applicant has research experience (0 for no, 1 for yes).
-   **Chance of Admit**: The probability of being accepted into the graduate school program, which serves as the target variable for the model.

## Prerequisites

Before using the code and model, ensure that you have the following tools and libraries installed:

-   Python (3.x)
-   Jupyter Notebook (optional but recommended)
-   Pandas
-   NumPy
-   Matplotlib
-   Scikit-Learn
- Seaborn

You can install these libraries using Python's package manager, pip, or by setting up a virtual environment.

bashCopy code

`pip install pandas numpy matplotlib scikit-learn jupyter seaborn` 

## Getting Started

1.  **Download the Dataset**: Start by downloading the dataset from the Kaggle link provided ([https://www.kaggle.com/datasets/mohansacharya/graduate-admissions](https://www.kaggle.com/datasets/mohansacharya/graduate-admissions)) and save it in the project directory.
    
2.  **Clone the Repository**: Clone this repository to your local machine.
    

bashCopy code

`git clone https://github.com/your-username/GraduateAdmissionPrediction.git
cd GraduateAdmissionPrediction` 

3.  **Run the Jupyter Notebook**: The main code for building the Multiple Linear Regression model can be found in the Jupyter Notebook file, `Graduate_Admission_Prediction.ipynb`. Open this notebook to follow the steps and execute the code.
    
4.  **Explore and Modify**: Feel free to explore the dataset, experiment with the code, and make modifications as needed for your learning and practice.
    

## Model Evaluation

The project evaluates the performance of the Multiple Linear Regression model using standard regression metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R²) values. These metrics will help you assess the accuracy and goodness-of-fit of the model in predicting the probability of acceptance into a graduate school program.

## Conclusion

This project provides an insightful example of using Multiple Linear Regression to predict the probability of being accepted to a graduate school program based on various applicant attributes. The dataset used is real and publicly available, making it a valuable resource for educational and research purposes.

