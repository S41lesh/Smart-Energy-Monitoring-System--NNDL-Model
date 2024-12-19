# Smart Meter Energy Monitoring System (IoT)  

## Overview  
This project implements a Smart Energy Meter using an ESP32 microcontroller and an LSTM-based machine learning model for anomaly detection. It combines IoT technology with cloud services to provide real-time energy consumption monitoring, predictive analytics, and system anomaly detection.

---

## Objective  
The primary goal is to enable real-time monitoring and anomaly detection of household energy consumption through an IoT-based system integrated with cloud services. The system leverages a deep learning model (LSTM) for time-series prediction to detect unusual patterns in energy usage.

---

## Tools & Technologies  
### **Hardware:**  
- ESP32 Microcontroller  
- PZEM-004T Energy Meter Sensor  

### **Cloud Services:**  
- AWS IoT Core  
- AWS DynamoDB  
- AWS Sagemaker  

### **Machine Learning:**  
- TensorFlow (Keras)  
- LSTM Neural Networks  

### **Software & Frameworks:**  
- Python (Data Processing & ML)  
- Seaborn & Matplotlib (Data Visualization)  
- Scikit-learn (Data Preprocessing)  

### **Architecture:**  
- Microservices-based design for scalability and fault tolerance  

---

## Key Features  
- **Real-Time Energy Monitoring:** Tracks power consumption and system status in real-time.  
- **Anomaly Detection:** Identifies unusual power usage patterns using a trained LSTM model.  
- **Data Storage & Insights:** Logs data to AWS DynamoDB and provides insightful visualizations.  
- **Scalable & Reliable:** Cloud-native, microservices-based, ensuring scalability and system reliability.  

---

## How It Works  
1. **Data Collection:** Energy data is collected from the PZEM-004T sensor and sent to the ESP32 microcontroller.  
2. **Data Transmission:** The ESP32 sends data to AWS IoT Core using MQTT.  
3. **Data Storage:** Data is stored in AWS DynamoDB for real-time and historical analysis.  
4. **Model Inference:** The LSTM model, deployed on AWS Sagemaker, processes the data to detect anomalies.  
5. **Alerts & Visualization:** Anomalies trigger alerts, and data visualizations provide system insights.

---

## Getting Started  
### **Prerequisites:**  
- ESP32 Board & PZEM-004T Sensor  
- AWS Account (IoT Core, DynamoDB, Sagemaker)  
- Python 3.x Environment  

---

## Results  
- Real-time energy monitoring with optimized efficiency.  
- Accurate anomaly detection, ensuring system reliability and energy savings.

---


