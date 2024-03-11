# Wind_Energy_Generation_Prediction

**Project Overview: Energy Prediction with XGBoost and Flask**

**Objective**

This project aims to predict renewable energy generation using a machine learning model powered by XGBoost, wrapped in a Flask web application for user interaction. By analyzing temporal data, the model forecasts energy production, aiding in planning and optimization efforts in the energy sector.

**Data Description**

The core of the project revolves around temporal data relevant to energy generation. Features like hour, minute, day, month, year, day of the week, and day of the year are used to predict future energy generation rates.

**Methodologies**

- **Model Development:** Utilizes XGBoost, a powerful and efficient implementation of gradient boosting, for prediction. The model is trained on historical data encompassing various time-based features to forecast energy generation.
- **Feature Engineering:** Time-based features are extracted from input data to enhance the model's predictive capabilities. This includes hour, minute, day, month, year, day of the week, day of the year, and week of the year.
- **Flask Web Application:** A user-friendly web interface allows users to input a date range for prediction. The application then displays the forecasted energy generation for the specified period.

**Application Workflow**

1. **User Input via Web Interface:** Users input a start and end date for the prediction period.
2. **Data Processing and Feature Engineering:** The application generates a DataFrame with time-based features for the specified period.
3. **Prediction:** The XGBoost model predicts energy generation rates for the input range.
4. **Visualization:** The application visualizes the predictions in a plot, which is displayed to the user.

**Results**

The project successfully demonstrates how to integrate a machine learning model with a web application to provide actionable forecasts. The use of XGBoost ensures accurate and efficient predictions, while Flask facilitates easy user interaction and result visualization.

**Conclusion**

This project exemplifies the practical application of machine learning in the energy sector, offering a scalable solution for predicting renewable energy generation. By leveraging XGBoost and Flask, it provides a robust framework for energy forecasting that can be extended to various other applications.

**Setup and Usage**

- **Requirements:** Python 3.x, Flask, XGBoost, Pandas, NumPy, Matplotlib, Seaborn.
- **Running the Application:** Execute `python app.py` to start the Flask server and navigate to the displayed URL in a web browser to interact with the application.

**OUTPUT**

![Recording 2024-03-11 113231](https://github.com/Zakeertech3/Wind_Energy_Generation_Prediction/assets/162958697/dd2b25c4-cd47-4493-b800-b4416d4628bf)
