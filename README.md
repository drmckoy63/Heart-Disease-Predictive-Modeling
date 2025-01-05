Heart Disease Prediction: Analyzing the Impact of Biking and Smoking

This project explores the relationship between physical activity (biking), smoking habits, and the likelihood of a person being diagnosed with heart disease. By leveraging data analysis and machine learning techniques, the project demonstrates the use of a scatter plot for visualization, linear regression for modeling, and key metrics for evaluating the model's performance.

Key Features:

1. Data Visualization:  
   A scatter plot is used to illustrate the relationship between biking, smoking, and the presence of heart disease. The visualization helps identify patterns and trends in the dataset.

2. Modeling with Linear Regression:  
   A linear regression model is trained using the dataset to quantify the relationship between the independent variables (biking and smoking) and the dependent variable (heart disease diagnosis). This is implemented using the `scikit-learn` library.

3. Evaluation Metrics:  
   To assess the model's performance, the following metrics are calculated:  
   - Mean Absolute Error (MAE): Measures the average magnitude of the errors in predictions, providing insight into the model's accuracy.  
   - Mean Squared Error (MSE): Penalizes larger errors more heavily, offering a more sensitive metric for error assessment.  
   - R² Score**: Indicates the proportion of variance in the dependent variable that is predictable from the independent variables, reflecting the model's explanatory power.  

4. Prediction:  
   Using the trained regression model, predictions are made to estimate the likelihood of a person being diagnosed with heart disease based on their biking and smoking behavior. This is achieved through the `model.predict()` command.

Applications:  
This project serves as a foundational example for understanding the relationship between lifestyle factors and health outcomes. It also demonstrates the practical use of regression modeling and performance evaluation in predicting medical conditions.
