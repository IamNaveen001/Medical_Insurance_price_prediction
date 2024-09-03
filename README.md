Medical Insurance Cost Prediction Model

Overview
This project is focused on predicting medical insurance charges using a machine learning model based on various factors such as age, sex, BMI, number of children, smoking status, and region. The goal is to build a predictive model that can estimate the cost of insurance for an individual given these features.

Table of Contents
Project Overview
Installation
Usage
Dataset
Modeling
Results
Contributing
License
Installation
Clone the repository:
bash
Copy code
https://github.com/IamNaveen001/Medical_Insurance_price_prediction.git
Navigate to the project directory:
bash
Copy code
cd insurance-cost-prediction
Create a virtual environment and activate it:
bash
Copy code
python -m venv env
source env/bin/activate  # On Windows, use `env\Scripts\activate`
Install the required packages:
bash
Copy code
pip install -r requirements.txt
Usage
Run the Jupyter Notebook:
bash
Copy code
jupyter notebook
Open the Medical Insurance Cost Prediction Model.ipynb notebook and run the cells to see the analysis and predictions.
Dataset
The dataset used in this project is sourced from [insert source, e.g., Kaggle, UCI Repository]. It includes the following features:

Age: Age of the policyholder.
Sex: Gender of the policyholder.
BMI: Body Mass Index.
Children: Number of children covered by the insurance.
Smoker: Smoking status of the policyholder.
Region: The residential region of the policyholder.
Charges: The medical insurance charges billed to the policyholder.
Modeling
Preprocessing: Categorical variables such as sex, smoker, and region were converted to numerical values.
Model Used: A Linear Regression model was used to predict the insurance charges.
Performance Metrics: The model's performance was evaluated using the R-squared metric:
Training R²: 0.75
Testing R²: 0.74
Results
The model demonstrates a strong correlation between the input features and the insurance charges, with smoking status and BMI being particularly influential.

Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

License
This project is licensed under the MIT License - see the LICENSE file for details.

