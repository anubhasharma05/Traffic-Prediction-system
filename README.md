# Traffic-Prediction-system
An AI/ML project that predicts traffic levels (Low, Medium, High) based on time, day, weather, and road type using a Random Forest model.
[traffic prediction system readme file.txt](https://github.com/user-attachments/files/26334433/traffic.prediction.system.readme.file.txt)
README FILE
 Traffic Prediction System (ai and ml project)

(1) Overview
The Smart Traffic Prediction System is a machine learning-based application designed to predict traffic congestion levels based on real-world influencing factors such as time, day of the week, weather conditions, and type of road.
Traffic congestion is a major issue in urban areas, leading to delays, increased fuel consumption, and environmental pollution. This project demonstrates how Artificial Intelligence and Machine Learning can be applied to analyze patterns and provide predictive insights for better travel planning.

(2) Problem Statement
In daily life, commuters often face unpredictable traffic conditions, especially during peak hours or adverse weather. The absence of a simple predictive system makes it difficult to plan routes efficiently.
This project aims to solve this problem by building a system that predicts traffic levels (Low, Medium, High) using machine learning techniques.

(3) Objectives
This project is highly relevant in modern smart cities where traffic management is crucial. It can be extended to:
-Navigation systems
-Smart city planning
-Logistics and delivery optimization
-Emergency response route planning
-Predict traffic levels (Low, Medium, High)
-Use multiple influencing factors
-Build a practical ML-based solution

(4)Technologies & Tools Used
   1.Programming Language: Python
   2.Libraries:
   -Pandas (data handling)
   -NumPy (numerical operations)
   -Matplotlib (visualization)
   -Scikit-learn (machine learning)

(5)Machine Learning Approach
 1. Algorithm Used: Random Forest Classifier
 2.Why Random Forest?
  -Handles both categorical and numerical data efficiently
  -Provides high accuracy
  -Reduces overfitting compared to decision trees
  -Works well with complex datasets

(6)Project Structure
  traffic prediction system
   -main.py (Main program file)
   -traffic_data.csv (Dataset file)
   -README.md (Project documentation)

(7)Dataset Description
The dataset used in this project is synthetically generated but designed to mimic real-world traffic conditions.
Features:
    Feature	         Description
1.Hour	Time of day     (0–23)
2.Day	Day of week     (0 = Sunday, 6 = Saturday)
3.Weather	        Clear, Rain, Fog
4.Road Type	        Highway or City
5.Traffic	        Target variable (Low, Medium, High)

Dataset Size: 1000 records

(8)How to Run the Project
Step 1: Install Dependencies
pip install pandas numpy matplotlib scikit-learn
Step 2: Run the Program
python main.py
Step 3: Provide Input
    Enter hour (0–23)
    Enter day (0–6)
    Enter weather (Clear/Rain/Fog)
    Enter road type (Highway/City)


(9)Workflow of the Project
1. Data Generation : Synthetic dataset created using NumPy
2. Data Preprocessing : Handling categorical variables using one-hot encoding
3. Model Training : Random Forest model trained on dataset
4. Model Evaluation : Accuracy score and classification report generated
5. Visualization : Traffic distribution plotted using Matplotlib
6.Prediction : User inputs values → system predicts traffic level

(10)Limitations
Dataset is synthetic (not real-time data)
Limited number of features
Does not include live traffic updates


(11)Future Enhancements

Integration with real-time traffic APIs (e.g., Google Maps)
Development of a web-based interface using Streamlit
Use of advanced models like Neural Networks
Deployment as a mobile or cloud-based application
Incorporation of GPS and location-based services


(12)Learning Outcomes
Through this project, the following concepts were understood and implemented:

Supervised Machine Learning
Classification Algorithms
Data Preprocessing Techniques
Model Evaluation Metrics
Real-world problem solving using AI

ANUBHA SHARMA
B.Tech CSE student(1st year)
Fundamentals of AI and ML
