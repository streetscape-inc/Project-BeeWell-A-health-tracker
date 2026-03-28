# Project-BeeWell-A-health-tracker
# 🐝 BeeWell: Your Hive of Wellness

**BeeWell** is an interactive AI/ML-powered wellness dashboard that helps you understand your health, predict risks, and take actionable steps to improve your lifestyle.  

It combines your age, weight, height, lifestyle habits, exercise, diet, and sleep patterns to produce:  

- **Overall Health Score** (0–100)  
- **Lungs & Liver Risk Assessment**  
- **Life Expectancy Projection**  
- **Frequency-Based Habit Impact** (Daily / Weekly / Occasionally)  
- **Personalized Health Recommendations**  

BeeWell is designed to be **engaging, intuitive, and visually interactive**, making health tracking both informative and fun! 🏋️‍♂️🍎💤

---

## 🌟 Features

- Interactive sliders to input **biometric & lifestyle data**  
- **Predictive Health Score** using Random Forest ML model  
- **Frequency-based projections** to show the effect of daily, weekly, or occasional habits  
- **Organ risk alerts** for lungs and liver  
- **Life expectancy estimates**  
- **Actionable lifestyle recommendations**  
- Health **visualizations & motivational notes** with emojis

---

## 🖥 How It Works

1. **Data Simulation**  
   - A synthetic dataset of 500 users with age, weight, height, smoking, alcohol, exercise, sleep, calories, and caffeine.  
   - Overall health score computed using weighted factors for lifestyle, BMI, and age.  

2. **Machine Learning Model**  
   - **Random Forest Regressor** predicts overall health score from input features.  
   - Features scaled using **MinMaxScaler** for accurate predictions.

3. **Prediction & Frequency Analysis**  
   - Computes health score, lungs & liver risk, life expectancy.  
   - Adjusts predictions for **habit frequency**: Daily / Weekly / Occasionally.  

4. **Interactive Dashboard**  
   - Built with **ipywidgets** and **matplotlib** for real-time sliders and visualization.  
   - Displays **graphs, tables, and motivational notes** with casual emojis for engagement.  

---

## ✅ Conclusion

**BeeWell** is more than just a health predictor — it’s an **interactive wellness companion**. By combining AI/ML predictions with engaging visualizations and actionable recommendations, it empowers users to **understand the impact of their lifestyle choices** and take steps toward better health.  

With its frequency-based projections, organ risk assessments, and motivational feedback, BeeWell transforms abstract health data into **clear, practical insights**. Whether it’s improving sleep, exercising more, or moderating habits like smoking and alcohol, users can make informed decisions every day.  

BeeWell demonstrates the **power of AI in personal health management**, and sets a foundation for future enhancements like real-world datasets, mental health indicators, and personalized diet guidance — making it a **complete, forward-looking wellness tool**.  
