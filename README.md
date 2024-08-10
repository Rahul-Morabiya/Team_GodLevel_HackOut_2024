# Team_GodLevel_HackOut_2024
Using Satellite Imagery to Predict Yields, Market Prices, and Crop Distribution Patterns in Agriculture.
Team - GodLevel
Team Leader - Rahul Morabiya (7990363348)

Team Members – Pundrik Shayta, Karm Vyas, Krutagna Kathiya

Introduction

•Title: Using Satellite Imagery to Predict Yields, Market Prices, and Crop Distribution Patterns in Agriculture.
•Context: Agriculture is crucial to global food security, but it faces challenges such as unpredictable yields, 
market volatility, and inefficient resource allocation.
•Problem: Farmers, governments, and businesses often lack timely and accurate information on crop yields, 
market prices, and distribution patterns, resulting in inefficiencies in decision-making. Our idea leverages 
satellite imagery and predictive analysis to provide actionable insights that benefit stakeholders, optimize 
agricultural practices, and enhance market strategies and government schemes.
Proposed Solution
•Title: Satellite-Based Agricultural Analytics Platform
•Core Idea: Using satellite imagery to analyze and predict:

1.Crop Distribution: Identify which crops are being sown in specific areas.

2.Yield Estimation: Predict the potential yield based on various factors.

3.Market Forecasting: Estimate potential prices and stock availability.

4.Quality Assessment: Evaluate the quality of the yield based on environmental conditions.

•Impact: Provides valuable data for farmers to optimize planting and harvesting, helps 
governments in policy-making, and aids businesses in supply chain management. 
Methodology Part - 1

 1. Data Collection
• Satellite Images: Use APIs from sources like Google Earth Engine to obtain high-resolution images of the fields.
• Historical Crop Data: Gather data from agricultural databases or open datasets.
• Weather Data: Use APIs like OpenWeatherMap or historical weather datasets.

 2. Image Processing & Classification
• Preprocess satellite images using OpenCV (resizing, normalization).
• Implement a CNN with TensorFlow/Keras for crop classification, fine-tuning a pretrained model like ResNet or 
MobileNet.

 3. Yield Prediction
• Model Selection: Implement a Random Forest or Gradient Boosting model using Scikit-learn and features could 
include crop type, weather conditions, soil quality, and past yields.
• Training & Testing: Train the model on historical yield data and evaluate the model using metrics like RMSE.

 4. Market Forecasting
• Model Selection: Use time series models like ARIMA or machine learning models like XGBoost for price 
prediction.
• Feature Engineering: Include factors like historical prices, demand trends, and predicted yield.
• Evaluation: Use metrics like MAE or MSE for evaluation.

 5. Quality Assessment
• Environmental Analysis:
• Use weather data and satellite images to assess crop quality.
• Rule-Based or ML Approach:
• Implement a deep learning model to predict the quality of the yield.

 6. Deployment
• Develop a simple web interface using MERN stack.
• Display results in a user-friendly dashboard with charts and maps.
