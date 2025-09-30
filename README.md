# Data Visualization Project

This repository contains multiple Jupyter notebooks that demonstrate **different types of data visualizations** using Python libraries such as **Matplotlib**, **Seaborn**, and **Plotly**.  
Each plot type is explained with its **purpose** and **importance in data science / machine learning**.

---

## 📘 Contents

---

### 1. `Data_Visualization.ipynb`
Visualizations of NYC Census data:

---

#### Bar Plot – Compare population across boroughs
💡 **Importance**: Useful to compare categorical variables and spot the largest/smallest groups in data.

<p align="center">
  <img width="1266" height="735" src="https://github.com/user-attachments/assets/e41b33ce-5091-4c57-ac06-95d70419199f" />
</p>

---

#### Histogram – Distribution of Income Per Capita
💡 **Importance**: Helps understand the shape of data (normal, skewed) which is critical for ML assumptions.

<p align="center">
  <img width="1268" height="673" src="https://github.com/user-attachments/assets/95ed3937-c2d5-403a-a986-1518295578c8" />
</p>

---

#### Scatter Plot – Relationship between Income and Population
💡 **Importance**: Detects correlations, clusters, and outliers which influence feature selection in ML.

<p align="center">
  <img width="1285" height="686" src="https://github.com/user-attachments/assets/15bda23a-c1a0-4637-ba43-63e877e11cf1" />
</p>

---

#### Box Plot – Distribution of income across boroughs
💡 **Importance**: Highlights spread, median, and outliers, helping with data preprocessing.

<p align="center">
  <img width="1294" height="740" src="https://github.com/user-attachments/assets/6b42d481-74fa-4f11-b495-ff2ce038ca19" />
</p>

---

#### Pie Chart – Gender distribution
💡 **Importance**: Simple way to show proportions within categorical data.

<p align="center">
  <img width="809" height="729" src="https://github.com/user-attachments/assets/3352e52e-7ee4-488c-b300-d3c521d0fe04" />
</p>

---

#### Violin Plot – Income distribution with density
💡 **Importance**: Shows both distribution shape and spread, deeper than a box plot.

<p align="center">
  <img width="1293" height="732" src="https://github.com/user-attachments/assets/12e6bc76-a388-4730-b86c-821e6ee3a96c" />
</p>

---

#### Heatmap – Correlation of economic factors
💡 **Importance**: Key for **feature selection** in ML by identifying highly correlated variables.

<p align="center">
  <img width="1076" height="658" src="https://github.com/user-attachments/assets/1f685590-6e26-4c81-b339-f30c3778f31a" />
</p>

---

#### Pair Plot – Multiple variable relationships
💡 **Importance**: Helps identify feature interactions and possible multicollinearity.

<p align="center">
  <img width="1233" height="599" src="https://github.com/user-attachments/assets/6787c93e-da08-43e7-9795-68d7ca5d4bdf" />
  <img width="1233" height="636" src="https://github.com/user-attachments/assets/d2da5a31-9999-4d81-a66d-184c96f58f30" />
</p>

---

#### Stacked Bar Plot – Gender distribution across boroughs
💡 **Importance**: Good for understanding group comparisons with subcategories.

<p align="center">
  <img width="1261" height="737" src="https://github.com/user-attachments/assets/333300bc-354e-4b7b-800c-4554eed9bb42" />
</p>

---

#### Donut Chart – Race distribution
💡 **Importance**: Variant of pie chart for showing proportions, useful for demographic analysis.

<p align="center">
  <img width="637" height="621" src="https://github.com/user-attachments/assets/fd4d8b3d-a8e8-445e-9508-61ff36326db9" />
</p>

---

### 2. `Data_Visualization_2_Map.ipynb`
Geographical plots using **Plotly Express**:

---

#### Mapbox Scatter Plot – Locations of distribution centers
💡 **Importance**: Geospatial visualization helps identify location-based trends and clusters.

<p align="center">
  <img width="1721" height="693" src="https://github.com/user-attachments/assets/12d0ed39-d57f-4604-8ae3-9c98f95b0dac" />
</p>

---

### 3. `Data_Visualization_3.ipynb`
Weather data visualization:

---

#### Line Plot – Temperature trend over time
💡 **Importance**: Shows trends and seasonality, critical for time-series ML models.

<p align="center">
  <img width="1063" height="710" src="https://github.com/user-attachments/assets/c0cd5fdc-474a-42a6-9bf0-8eba84124d93" />
</p>

---

#### Step Line Plot – Pressure changes as step values
💡 **Importance**: Good for discrete changes in sensor/time-series data.

<p align="center">
  <img width="1272" height="716" src="https://github.com/user-attachments/assets/120f5be2-ef53-4e86-9193-c8145fd2c5b4" />
</p>

---

#### Area Plot (Fill Between) – Wind speed over time
💡 **Importance**: Shows magnitude of change while emphasizing cumulative effects.

<p align="center">
  <img width="1246" height="714" src="https://github.com/user-attachments/assets/da17c024-c014-4342-ba63-ca99d9268e9b" />
</p>

---

#### KDE Plot – Temperature density distribution
💡 **Importance**: Reveals probability distribution, useful for statistical modeling.

<p align="center">
  <img width="1280" height="691" src="https://github.com/user-attachments/assets/189172cf-093a-4441-8e5b-fd93471e40e9" />
</p>

---

#### Bubble Chart – Temperature vs Humidity with Wind Speed as bubble size
💡 **Importance**: Displays multi-dimensional relationships, helps with feature interaction understanding.

<p align="center">
  <img width="1058" height="681" src="https://github.com/user-attachments/assets/fec132b2-1e72-4676-9581-e69720721e8c" />
</p>

---

#### 3D Scatter Plot – Temperature, Humidity, Wind Speed
💡 **Importance**: Visualizes **three variables together**, helpful for detecting hidden clusters.

<p align="center">
  <img width="793" height="717" src="https://github.com/user-attachments/assets/472b750f-e391-40b3-b794-942fa1a03dd6" />
</p>

---

#### Rotated 3D View – Alternative perspective
💡 **Importance**: Provides deeper insight by rotating axes for better clarity.

<p align="center">
  <img width="785" height="717" src="https://github.com/user-attachments/assets/d006f8d5-ef38-442c-9cba-ac6f0d40d63d" />
</p>

---

#### 3D Surface Plot – Interpolated weather surface
💡 **Importance**: Useful for understanding complex spatial/temporal relationships in datasets.

<p align="center">
  <img width="792" height="717" alt="image" src="https://github.com/user-attachments/assets/9ef25042-007e-40cd-8820-b67b372d5cc9" />
</p>

---

## 🛠 Libraries Used
- **Matplotlib** (`plt`)
- **Seaborn** (`sns`)
- **Pandas** (`pd`)
- **NumPy** (`np`)
- **Plotly Express** (`px`)
- **Scipy** (for 3D surface interpolation)

---

## 🎯 Why Visualization Matters in Machine Learning
- **Data Quality Check**: Detects missing values, outliers, and skewed distributions.  
- **Feature Understanding**: Shows correlations, interactions, and importance of features.  
- **Model Selection**: Helps decide between linear vs. nonlinear models based on relationships.  
- **Communication**: Simplifies complex insights for stakeholders.  

---
