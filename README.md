The Crop Recommendation System is a Machine Learning-based web application designed to assist farmers and agricultural stakeholders in selecting the most suitable crop for cultivation. The system analyzes soil nutrient levels and environmental conditions to provide accurate crop recommendations, helping improve productivity and support data-driven farming decisions.

Unlike traditional recommendation systems that rely only on static input values, this project integrates real-time weather data, enabling more realistic and dynamic predictions based on current environmental conditions. By combining soil characteristics with live weather information, the application provides recommendations that are better aligned with actual field conditions.

Features

🌱 Crop recommendation using Machine Learning algorithms
🌦️ Real-time weather data integration
🌡️ Live temperature and humidity analysis
🧪 Soil nutrient evaluation (Nitrogen, Phosphorus, Potassium)
💧 Rainfall and pH-based recommendations
🖥️ Interactive and user-friendly Streamlit interface
⚡ Fast and accurate predictions
📊 Data-driven decision support for agriculture

Technologies Used

Python
Streamlit
Pandas
NumPy
Scikit-learn
Weather API Integration
Machine Learning

Input Parameters
The model uses the following parameters for prediction:

Nitrogen (N)
Phosphorus (P)
Potassium (K)
Temperature
Humidity
pH Value
Rainfall

How It Works

Users enter soil nutrient values such as Nitrogen, Phosphorus, Potassium, and pH.
The system fetches real-time weather information from a weather API.
The trained Machine Learning model processes both soil and environmental data.
The model predicts the most suitable crop for cultivation.
The recommended crop is displayed instantly through the Streamlit interface.

Objective

The primary goal of this project is to leverage Machine Learning and real-time environmental data to support smart farming practices. By recommending crops that are best suited to current soil and weather conditions, the system aims to improve agricultural efficiency, optimize resource utilization, and enhance crop yield.

Future Enhancements

Disease Detection Module
Multi-language Support
Mobile Application Deployment

Author
Sanskruti Chavan

"Empowering Agriculture with Machine Learning and Real-Time Data." 🌱🚜🌍
