# 📊 Linear Regression Model for Predicting Yearly Amount Spent

## 📝 Project Overview
This project builds a linear regression model to predict the `Yearly Amount Spent` by customers based on various numerical features, such as:
- `Avg. Session Length` 🕒
- `Time on App` 📱
- `Time on Website` 💻
- `Length of Membership` 📅

The dataset contains customer-related metrics, and the goal is to analyze the relationship between these features and customer spending behavior.

## 📂 Dataset Information
The dataset includes the following columns:
- **📧 Email**: Customer's email (not used for modeling)
- **🏠 Address**: Customer's address (not used for modeling)
- **🎨 Avatar**: Customer's avatar color (not used for modeling)
- **🕒 Avg. Session Length**: Average time spent in a session
- **📱 Time on App**: Time spent using the app
- **💻 Time on Website**: Time spent on the website
- **📅 Length of Membership**: Duration of customer membership
- **💰 Yearly Amount Spent**: Target variable (amount spent by the customer annually)

## 📦 Dependencies
To run this project, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🚀 How to Run
1. Load the dataset (ensure it is in a CSV format or preloaded into a DataFrame).
2. Select the relevant numerical features and the target variable.
3. Split the data into training and testing sets.
4. Train a linear regression model using `scikit-learn`.
5. Evaluate the model using performance metrics such as:
   - 📉 Mean Absolute Error (MAE)
   - 📉 Mean Squared Error (MSE)
   - 📉 Root Mean Squared Error (RMSE)
   - 📊 R-squared score
6. Visualize the actual vs. predicted values using `seaborn`.

## 📈 Model Performance
The trained model provides insights into how different features impact customer spending. The model coefficients help determine the significance of each feature.

## 📊 Visualization
A scatter plot is generated to compare actual and predicted values, allowing an assessment of model accuracy.

## 🔮 Future Enhancements
- 🔍 Experiment with feature engineering to improve accuracy.
- 📏 Try other regression techniques like Ridge or Lasso regression.
- 🗂️ Explore additional data sources for deeper insights.

## 👨‍💻 Author
Developed by Abhishek 🚀

## 📜 License
This project is licensed under the MIT License. Feel free to use and modify it as needed.
