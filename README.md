Thanks for your patience! Based on the detailed content across your documents (`Team3_Report.docx`, `Smart Insoles_Poster.docx`, and your PPT), here's a **clean, symbol-free README file** for your **Smart Wearable Insole for Gait Monitoring and Healthcare** project — suitable for a GitHub repository or research showcase.

---

## Smart Wearable Insole for Ergonomic Assessment and Healthcare

### Overview

The project focuses on the development of a smart wearable insole designed for **gait monitoring**, **posture evaluation**, and **healthcare applications**. It aims to support early detection of abnormalities in movement, contribute to **rehabilitation**, and assist in **sports performance** analysis. Unlike existing systems, this design combines multiple sensors to offer **real-time feedback** on spatio-temporal gait characteristics.

---

### Problem Statement

Current insole-based health systems often lack real-time analysis, adaptability, and sensor integration necessary for **ergonomic** and **clinical monitoring**. This project addresses these gaps by introducing a sensor-fused insole system capable of identifying **gait abnormalities** and assessing **posture and movement** during activities such as yoga, walking, or rehabilitation.

---

### Objectives

* Design and develop a **wearable insole** embedded with pressure and motion sensors.
* Collect real-time gait data and develop machine learning models for **gait phase classification**.
* Monitor and evaluate changes in gait before and after activities like **meditation** or **exercise**.
* Provide a **user interface** for visualizing gait metrics and storing data for long-term analysis.

---

### Key Features

* Force-Sensitive Resistors (FSRs) for foot pressure measurement.
* Inertial Measurement Unit (IMU) for tracking acceleration and orientation.
* Integration with **ESP32** microcontroller for real-time data acquisition.
* **Bluetooth Low Energy (BLE)** communication for wireless streaming.
* **Machine learning models** (KNN, Random Forest, Gradient Boosting) and **deep learning** (DNN, LSTM, Bi-LSTM) for pattern recognition.
* User interface for **data visualization**, including pressure maps and gait parameters.

---

### Methodology

1. **Sensor Selection and Placement**
   FSRs and IMUs are strategically placed to capture key gait features such as heel strike, toe-off, step length, and cadence.

2. **Hardware Development**
   EVA and TPU materials are used for comfort and durability. Sensors are embedded with laser-cut slots and bonded using flexible adhesives.

3. **Data Acquisition and Filtering**
   Sensor data is streamed via BLE, filtered using **Savitzky-Golay** filters, and prepared for machine learning analysis.

4. **Model Training**
   Collected gait data is used to train various classification models. Evaluation metrics include accuracy, precision, and F1-score.

5. **User Interface and Storage**
   Data is stored locally or on cloud platforms (e.g., Google Drive) and visualized through a desktop/mobile dashboard.

---

### Results

* Achieved accurate detection of **gait events** (heel strike, toe-off).
* Demonstrated classification of gait patterns using both ML and DL models.
* Effective monitoring of gait changes post-intervention (e.g., after yoga or meditation).
* Real-time feedback suitable for **rehabilitation**, **sports training**, and **clinical analysis**.

---

### Applications

* Rehabilitation therapy
* Posture correction and fall-risk analysis
* Monitoring the effects of meditation or stress on gait
* Early detection of gait changes in neurodegenerative or orthopedic conditions

---

### Conclusion

The smart insole developed in this project shows strong potential as a **cost-effective**, **portable**, and **scalable** tool for gait monitoring and ergonomic assessment. The integration of sensor data, machine learning algorithms, and a user-friendly interface makes it a promising solution in the domain of **preventive healthcare**, **sports science**, and **assistive technology**.

---

Would you like me to convert this into a downloadable `README.md` file like the earlier one?
