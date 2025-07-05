Sales Prediction Using Python:

Overview: 

This project aims to build a machine learning model to predict product sales based on advertising expenditure across different platforms such as TV, Radio, and Newspaper. The model is trained using a regression algorithm in Python and helps understand how different advertising channels contribute to overall sales.

By forecasting sales, businesses can plan their advertising strategies more effectively and make data-driven decisions to improve revenue.

Objective:

Analyze advertising and sales data

Build a predictive model using machine learning

Evaluate model performance using regression metrics

Help businesses make better advertising investment decisions

Dataset: 

The dataset used in this project is called advertising.csv, which contains the following columns:

TV: Advertising budget spent on TV
Radio: Advertising budget spent on Radio
Newspaper: Advertising budget spent on Newspaper
Sales: Sales of the product

Tools and Technologies Used: 

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Project Steps:

Data Loading:
The dataset is loaded into a Pandas DataFrame and previewed to understand its structure.

Data Exploration and Visualization:
Basic statistics and data types are explored. Correlation and pairplots are created to examine relationships between features.

Data Preprocessing:
Missing values are checked. The dataset contains only numerical features, so no encoding is required.

Model Building:
The dataset is split into training and testing sets. A Linear Regression model is trained using the training set.

Model Evaluation:
The model is evaluated using Mean Squared Error (MSE) and R² Score on the test set. A scatter plot is also used to compare actual vs predicted values.

Result Analysis:
Based on the model, the impact of advertising channels on sales is analyzed. TV and Radio appear to be stronger predictors of sales compared to Newspaper.

How to Run:
Clone the repository
git clone https://github.com/swatijoshi765/Codsoft-Task-4---SALES-PREDICTION-USING-PYTHON.git

Navigate to the project directory
cd sales-prediction-python

Install dependencies (if using virtual environment)
pip install -r requirements.txt

Run the notebook
Open sales prediction.ipynb in Jupyter Notebook or any IDE that supports Python notebooks.

Conclusion
This project demonstrates how sales can be predicted using simple regression techniques. The model helps understand how different advertising strategies influence sales, enabling companies to invest wisely in marketing channels.
