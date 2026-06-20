# AquaCrop-AI 🌱💧

### AI-Powered Crop Water Requirement Prediction System

A machine learning-based smart agriculture solution that predicts crop water requirements using crop characteristics, soil conditions, and environmental parameters to support efficient irrigation management.

---

## 📌 Overview

AquaCrop-AI is a precision agriculture project designed to assist farmers and agricultural stakeholders in optimizing water usage. The system analyzes agricultural and environmental data and predicts the amount of water required for crops using a Machine Learning model.

The project helps reduce water wastage, improve irrigation planning, and promote sustainable farming practices.

---

## Dataset

The project uses a crop water requirement dataset containing agricultural and environmental parameters used for irrigation prediction.

Location:

```text
dataset/DATASET - Sheet1.csv
```

Features include:
- Crop Type
- Soil Type
- Weather Condition
- Water Requirement
- Environmental Parameters



## 🎯 Objectives

- Predict crop water requirements accurately.
- Support intelligent irrigation decision-making.
- Reduce unnecessary water consumption.
- Improve agricultural productivity.
- Promote sustainable resource management.

---

## 🚀 Features

### Data Analysis
- Dataset exploration and visualization.
- Statistical analysis of agricultural data.
- Missing value detection and validation.
- Data quality assessment.

### Data Preprocessing
- Handling categorical and numerical features.
- One-Hot Encoding for categorical variables.
- Feature engineering and transformation.
- Dataset preparation for machine learning.

### Correlation Analysis
- Correlation matrix generation.
- Heatmap visualization.
- Identification of factors affecting water requirements.
- Feature importance exploration.

### Machine Learning
- Random Forest Regression model.
- Training and testing data split.
- Water requirement prediction.
- Performance evaluation using multiple metrics.

### Model Evaluation
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

## 🏗 Workflow

```text
Agricultural Dataset
         │
         ▼
 Data Loading
         │
         ▼
 Data Cleaning
         │
         ▼
 Exploratory Data Analysis
         │
         ▼
 One-Hot Encoding
         │
         ▼
 Feature Engineering
         │
         ▼
 Correlation Analysis
         │
         ▼
 Train-Test Split
         │
         ▼
 Random Forest Regressor
         │
         ▼
 Water Requirement Prediction
         │
         ▼
 Performance Evaluation
```

---

## 📊 Dataset Features

The model utilizes agricultural and environmental parameters such as:

- Crop Type
- Soil Type
- Weather Conditions
- Environmental Factors
- Water Requirement (Target Variable)

---

## 🧠 Machine Learning Model

### Algorithm Used

**Random Forest Regressor**

Parameters:

```python
RandomForestRegressor(
    n_estimators=100,
    min_samples_leaf=4,
    min_samples_split=10
)
```

### Why Random Forest?

- Handles nonlinear relationships effectively.
- Robust against overfitting.
- Works well with mixed feature types.
- Provides strong predictive performance.

---

## 📈 Model Evaluation Metrics

The model is evaluated using:

### Mean Absolute Error (MAE)

Measures average prediction error.

### Mean Squared Error (MSE)

Penalizes larger prediction errors.

### R² Score

Measures how well the model explains variability in water requirements.

---

## 🛠 Technology Stack

### Programming Language
- Python

### Data Analysis
- Pandas
- NumPy

### Visualization
- Matplotlib
- Seaborn

### Machine Learning
- Scikit-Learn

### Development Environment
- Google Colab
- Jupyter Notebook

---

## 📂 Project Structure

```text
AquaCrop-AI/
│
├── Arch_&_Iot_project.ipynb
├── DATASET - Sheet1.csv
├── README.md
│
└── Output Visualizations
```

---

## 🔬 Methodology

### Step 1: Data Loading
- Import dataset using Pandas.
- Inspect dataset structure.

### Step 2: Data Exploration
- Display sample records.
- Analyze dataset dimensions.
- Check unique values.

### Step 3: Data Wrangling
- Detect missing values.
- Validate dataset quality.

### Step 4: Feature Processing
- Separate categorical and numerical features.
- Apply One-Hot Encoding.

### Step 5: Correlation Analysis
- Generate correlation matrix.
- Create heatmap visualizations.
- Identify influential features.

### Step 6: Model Training
- Split dataset into training and testing sets.
- Train Random Forest Regressor.

### Step 7: Evaluation
- Generate predictions.
- Calculate MAE, MSE, and R² Score.

---

## 🌍 Applications

- Smart Irrigation Systems
- Precision Agriculture
- Water Resource Management
- Sustainable Farming
- Agricultural Decision Support Systems
- AI-Driven Farming Solutions

---

## 📈 Benefits

- Reduces water wastage.
- Supports data-driven irrigation.
- Improves crop productivity.
- Enables efficient resource utilization.
- Promotes sustainable agriculture.

---

## 🔮 Future Enhancements

- Real-time IoT sensor integration.
- Weather API integration.
- Mobile application deployment.
- Cloud-based prediction service.
- Deep learning-based forecasting.
- Smart irrigation automation.

---

## 👨‍💻 Author

**Manthan Dixit**

B.Tech Computer Science Engineering (IoT)

---

## 📜 License

This project is intended for educational, research, and academic purposes.

---

## ⭐ If you find this project useful, consider giving it a star.
