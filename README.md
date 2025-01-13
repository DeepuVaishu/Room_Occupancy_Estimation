
# Room Occupancy Estimation Project

## 📘 Overview
This project uses the **Room Occupancy Estimation dataset** from the UCI Machine Learning Repository to develop a machine learning model that predicts room occupancy levels based on sensor data. The project is structured in phases, with this submission covering **Phase 1: Data Understanding and Preprocessing**.

---

## 📂 Dataset Details
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/864/room+occupancy+estimation)
- **Characteristics**: Multivariate, Time-Series
- **Instances (Rows)**: 10,129
- **Features (Columns)**: 18
- **Target Variable**: `Room_Occupancy_Count` (0 to 3 occupants)

---

## 🎯 Project Objectives
1. **Understand the dataset**:
   - Explore the characteristics and structure of the data.
   - Analyze distributions, trends, and potential outliers.
2. **Perform data preprocessing**:
   - Handle missing values (if any).
   - Identify and address outliers using Winsorization.
   - Scale the data for consistent modeling.
3. **Prepare the data for modeling**:
   - Feature selection and engineering.
   - Dataset splitting into training and testing sets.

---

## 🛠️ Tools and Libraries
- **Languages**: Python
- **Key Libraries**: 
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - scipy

---

## 📊 Key Insights from Phase 1
1. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions and relationships.
   - Addressed outliers through Winsorization (limits set to 0.05 and 0.95).
2. **Data Preprocessing**:
   - Scaled numerical features to standardize the dataset.
   - Retained the integrity of data trends while ensuring compatibility for machine learning models.

---

## 🚀 Next Steps
- Build and evaluate classification models to predict room occupancy levels.
- Optimize and tune hyperparameters for improved performance.
- Validate results and ensure model reliability.

---

## 🧑‍💻 How to Run
1. Clone the repository:
   ```
   git clone <repository_link>
   ```
2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook for Phase 1:
   ```
   cd notebooks
   jupyter notebook ROOM OCCUPANCY ANALYSIS.ipynb
   ```
