📊 Linear Regression Lab on Ecommerce Customers Dataset
📌 Description : 
In this lab, we applied Linear Regression to analyze the Ecommerce Customers dataset. The objective is to predict the Yearly Amount Spent based on customer behavior features.


⸻


📂 Dataset : 
The dataset used is Ecommerce Customers.csv, which includes:
Avg. Session Length
Time on App
Time on Website
Length of Membership
Yearly Amount Spent (Target Variable)
Non-numerical features such as Email, Address, and Avatar were removed as they are not suitable for the model.


⸻


⚙️ Steps Performed
1. Data Loading : 
The dataset was loaded into a Pandas DataFrame.
2. Data Exploration : 
We explored the dataset using:
.head()
.info()
.describe()
3. Data Cleaning : 
Missing values were checked and handled if needed.
4. Feature Selection : 
Irrelevant columns were removed, and important features were selected.
5. Data Splitting : 
The data was split into training and testing sets (80% training, 20% testing).
6. Model Training : 
A Linear Regression model was trained using the training data.
7. Model Evaluation : 
The model performance was evaluated using:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
A scatter plot was used to compare actual and predicted values.

📈 Results

The model showed a good linear relationship between the predicted and actual values, indicating that Linear Regression is suitable for this dataset.
