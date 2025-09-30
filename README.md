# Data Visualization

This repository contains multiple Jupyter notebooks demonstrating different types of **data visualizations** using Python libraries such as **Matplotlib**, **Seaborn**, and **Plotly**. Each notebook explores a dataset with a variety of plots, where the figure sizes (`plt.figure(figsize=(...))`) are set to ensure clear and spacious visualizations.

---

## 📘 Contents

### 1. `Data_Visualization.ipynb`
Visualizations of NYC Census data:
- **Bar Plot**: Total population by Borough.
- **Histogram**: Income per capita distribution with KDE.
- **Scatter Plot**: Income vs Population colored by Borough.
- **Box Plot**: Income distribution by Borough.
- **Pie Chart**: Gender distribution.
- **Violin Plot**: Income distribution.
- **Heatmap**: Correlation of economic factors.
- **Pair Plot**: Multiple variable relationships.
- **Stacked Bar Plot**: Gender distribution across Boroughs.
- **Donut Chart**: Race distribution.

---

### 2. `Data_Visualization_2_Map.ipynb`
Geographical plots using **Plotly Express**:
- **Mapbox Scatter Plot**: Distribution center locations.
- **Colored Mapbox Scatter**: Centers sized by `sell_quantity`.
- **Mapbox with Hover Data**: Displays name, country, and state details.

---

### 3. `Data_Visualization_3.ipynb`
Weather data visualization:
- **Line Plot**: Temperature over time.
- **Step Line Plot**: Pressure variation over time.
- **Area Plot (Fill Between)**: Wind speed trend.
- **KDE Plot**: Density of temperature distribution.
- **Bubble Chart**: Temperature vs Humidity with Wind Speed as size.
- **3D Scatter Plot**: Temperature, Humidity, Wind Speed.
- **Rotated 3D View**: Different angle for scatter visualization.
- **3D Surface Plot**: Interpolated weather surface.

---

## 🛠 Libraries Used
- **Matplotlib** (`plt`)
- **Seaborn** (`sns`)
- **Pandas** (`pd`)
- **NumPy** (`np`)
- **Plotly Express** (`px`)
- **Scipy** (for 3D surface interpolation)

---
