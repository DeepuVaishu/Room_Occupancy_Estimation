
# Room Occupancy Analysis
![image](https://github.com/user-attachments/assets/be28c55f-b0e1-4ea1-8bd0-cb1baf497cc6)

## 📌 Overview
This project focuses on developing a machine learning model to predict room occupancy levels based on sensor data. By leveraging real-time environmental factors, such as temperature, humidity, light, sound, CO2 levels, and motion detection, the model aims to accurately estimate the number of occupants in a room.

The project follows a structured approach:
- **Data Exploration & Preprocessing**
- **Feature Engineering & Selection**
- **Model Training & Evaluation**
- **Predictions on Unseen Data**

---

## 📂 Dataset Details
- **Source**: UCI Machine Learning Repository
- **Dataset Name**: Room Occupancy Estimation
- **Instances (Rows)**: 10,129
- **Features (Columns)**: 18 (Sensor-based readings)
- **Target Variable**: `Room_Occupancy_Count` (Values: 0, 1, 2, 3 occupants)

### 📊 Key Features
| Feature Name | Description |
|-------------|-------------|
| `Temperature` | Room temperature in Celsius |
| `Light` | Light intensity (lux) |
| `CO2` | CO2 concentration (ppm) |
| `Sound` | Noise levels in the room |
| `Motion Sensors (PIR)` | Motion detection flags (binary) |

---
## Repository Contents

- **LICENSE** – License information for this project.
- **Occupancy_Estimation.csv** – Dataset used for occupancy estimation.
- **room_occupancy_unseen_data.csv** – Unseen data for model validation.
- **README.md** – Documentation and project details.
- **Room Occupancy Analysis-phase 1** – Initial phase of data analysis and preprocessing.
- **Room Occupancy Analysis- phase 2** – Further analysis,feature engineering and  model training and evaluation.
- **Room Occupancy Analysis Phase 3** – Creating pipelines for predicting the unseen data.
- **Room_Occupancy_Analysis-Final_Project** – Final report and results.

---

## 🎯 Project Objectives
1. **Understand the Dataset**
   - Conduct Exploratory Data Analysis (EDA) to uncover patterns and relationships.
   - Identify missing values, outliers, and distributions of sensor readings.
2. **Preprocess the Data**
   - Handle missing values and outliers using Winsorization.
   - Apply Box-Cox transformation for feature normalization.
   - Standardize numerical features to improve model performance.
3. **Feature Selection & Engineering**
   - Select the most important features using statistical techniques.
   - Perform correlation analysis to avoid redundancy.
4. **Train and Evaluate Models**
   - Implement various classification models (Random Forest, etc.).
   - Use metrics like accuracy, precision, recall, and F1-score.
5. **Predict Occupancy on Unseen Data**
   - Test the model with real-time or unseen data inputs.

---

## 🛠️ Tools & Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Processing: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`, `imbalanced-learn`
  - Feature Engineering: `scipy`

---

## 🏆 Key Results & Insights
1. **Model Performance**
   - **Random Forest Classifier achieved 99% accuracy** on the test set.
   - Feature importance analysis showed that **motion sensors, light, and CO2 levels were the most influential variables**.
2. **Prediction on Unseen Data**
   - Successfully tested on a new dataset with predictions aligning well with real occupancy values.
   - Class probabilities showed **high confidence in most predictions**, demonstrating model reliability.

| Predicted Class | Count |
|----------------|-------|
| 0 (Empty Room) | 440   |
| 1 (One Occupant) | 116  |
| 2 (Two Occupants) | 115  |
| 3 (Three Occupants) | 164 |

---

## 🚀 How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone <repository_link>
   cd Room_Occupancy_Analysis
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook Room_Occupancy_Analysis-Final_Project.ipynb
   ```

---

## 🔥 Future Improvements
- **Hyperparameter Tuning**: Fine-tune the Random Forest model for even better generalization.
- **Deployment**: Implement a real-time web dashboard or API for occupancy monitoring.
- **Additional Data Sources**: Incorporate other sensor readings for better accuracy.
- **Time-Series Analysis**: Explore sequential data patterns for occupancy forecasting.

---

## 📝 Conclusion
This project successfully built a robust machine learning pipeline for room occupancy prediction. By leveraging sensor data and applying advanced preprocessing and feature selection techniques, we achieved **high model accuracy** and **reliable predictions on unseen data**. Future enhancements could improve real-world applicability, making this approach useful for **smart buildings, energy management, and automated room control systems**.

---

🤝 Contributions

If you'd like to contribute, feel free to fork the repository and submit pull requests! Feedback is always welcome.

---

📜 License

This project is licensed under the MIT License.

---

📬 Contact

For any queries, feel free to reach out via GitHub or email!

🚀 Happy Coding!

---
