# **Sensor Anomaly Detection**

This project focuses on **developing and deploying machine learning models** to detect anomalies in numerical data collected from sensors. It leverages various anomaly detection techniques such as **One-Class SVM**, **DBSCAN**, and **Isolation Forest** to identify abnormal behavior in sensor readings. The goal is to enable proactive monitoring of systems and early detection of potential failures.

## **Features**

- **Data Preprocessing**  
  Scaled the sensor data using `StandardScaler` and handled missing values to ensure clean and reliable data.

- **Anomaly Detection Algorithms:**
  - **One-Class SVM** for novelty detection to identify outliers in the data.
  - **DBSCAN** for density-based clustering and detecting anomalies.
  - **Isolation Forest** for anomaly detection by isolating data points.
  
- **Model Evaluation:**  
  Comprehensive evaluation using classification metrics such as precision, recall, and F1 score to assess the model's performance.

- **Data Visualization:**  
  Utilized **matplotlib** and **seaborn** to visualize sensor data and the results of anomaly detection.

## **Installation**

To set up the project, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/username/sensor-anomaly-detection.git

## **Install dependencies:**
Create a virtual environment (optional but recommended) and install the required libraries using pip:

pip install -r requirements.txt
-Note: Ensure you have a requirements.txt file in your repository that includes necessary dependencies like scikit-learn, numpy, pandas, matplotlib, seaborn, etc.

Anomaly Detection Models
- One-Class SVM:
Detects outliers in high-dimensional sensor data, useful for novelty detection.

- DBSCAN (Density-Based Spatial Clustering of Applications with Noise):
Groups sensor data based on density and identifies outliers as anomalies.

- Isolation Forest:
Anomaly detection by isolating data points. It works by building random trees and identifying the isolated anomalies.

## **Project Evaluation**
The model evaluation provides important classification metrics for each model:

- Precision: Measures how accurate the model is in identifying anomalies.
- Recall: Measures the ability of the model to correctly identify all anomalies.
- F1 Score: Harmonic mean of precision and recall, providing a balanced evaluation of model performance.
  
## **Data Visualization**
- Sensor Data Distribution:
Visualized the distribution of sensor data to observe trends and potential outliers.

- Anomaly Detection Results:
Plotted anomalies identified by each model (One-Class SVM, DBSCAN, and Isolation Forest), comparing performance.

## **Conclusion**
This project demonstrates the ability to detect abnormal signs in sensor data using different anomaly detection techniques. The performance of each model is evaluated based on its accuracy in identifying anomalies. This approach can be utilized for predictive maintenance and early warning systems in various industries, improving system reliability and minimizing downtime.

# **About**
This project aims to showcase anomaly detection models applied to sensor data for various real-world applications such as predictive maintenance and system monitoring.
