# Predictive-Maintenance-for-Industrial-System
Project Overview:
This project is focused on predictive maintenance—a smart way to monitor industrial machinery and predict failures before they happen. The goal is to help industries avoid unexpected downtimes and reduce costs by suggesting maintenance only when necessary.

We use real-time sensor data and operational metrics to build machine learning models that can forecast how long a machine will continue to function properly.By training a regression model, we predict the Remaining Useful Life (RUL) of each machine, allowing better planning for servicing.A classification model determines whether a machine currently needs maintenance, providing a binary decision (yes/no).
We also employ clustering (KMeans) to detect anomalies in sensor behavior that may indicate potential issues not captured by traditional thresholds.The dataset includes sensor readings and usage data, which are normalized and split for training and testing.

Streamlit is used to build an interactive dashboard, allowing users to visualize data, input new values, and receive predictive insights instantly.Users can generate random sensor readings or manually input values to simulate real-world machine conditions.The visualizations—such as histograms, scatter plots, and line charts—help in interpreting sensor trends and maintenance needs.
Overall, this tool empowers maintenance teams to make data-driven decisions and extend machinery life while minimizing cost and risk.

What the App Does:
The application uses machine learning models to analyze sensor data from machines and provides:

1. Remaining Useful Life (RUL): 
   It estimates how many hours a machine will continue to operate before it fails.

2. Maintenance Status:  
   It predicts whether the machine needs maintenance or is operating normally.

3. Anomaly Detection: 
   It checks for unusual patterns in sensor data to flag potential issues early.

The Data:
The system uses a dataset with:
- Sensor readings (e.g., temperature, vibration, etc.)
- Operational hours (how long a machine has been running)
- Labels indicating how much life the machine has left (RUL)
- Labels on whether the machine required maintenance
This data may have some missing values, which the app handles smoothly by filling in with previous values.

How Machine Learning Helps:
The project uses three key ML techniques:

1. Regression Model (Random Forest Regressor): 
   Predicts the remaining time before the machine fails (RUL).

2. Classification Model (Random Forest Classifier):  
   Tells if the machine is likely to need maintenance soon.

3. Clustering Model (KMeans):  
   Groups sensor data into "normal" and "abnormal" patterns, which helps in detecting anomalies.

These models are trained using past machine data and then used to make predictions for new input values.

Why This Project Is Valuable:
- Prevents Unplanned Downtime:By predicting when a machine might fail.
- Saves Money: Maintenance is done only when needed.
- Improves Safety:Detecting anomalies early can prevent accidents.
- Real-time Decision Making: Engineers can use it as a daily tool to monitor system
