#  Traffic Accident Data Analysis

##  Project Overview

This project analyzes traffic accident data to identify patterns related to accident severity, weather conditions, time of day, and geographical locations. The analysis uses Python for data preprocessing, exploratory data analysis (EDA), data visualization, and interactive mapping to uncover meaningful insights from the dataset.

---

##  Objective

The objective of this project is to analyze traffic accident data and identify patterns related to:
- Accident severity
- Weather conditions
- Time of occurrence
- Day and month trends
- State-wise accident distribution
- Accident hotspots

---

##  Dataset

**Dataset:** US Accidents Dataset (March 2023)

The dataset contains approximately **7.7 million accident records** with **46 features**, including:
- Severity
- Start Time
- End Time
- Latitude & Longitude
- Weather Condition
- Temperature
- Visibility
- Humidity
- Wind Speed
- State
- Sunrise/Sunset
- and many more.

---

## 🛠 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Folium
- VS Code

---

##  Data Science Lifecycle

### 1. Data Collection
Loaded the traffic accident dataset using Pandas and selected a sample of records for efficient analysis.

### 2. Data Understanding
Explored the dataset structure, columns, missing values, and descriptive statistics.

### 3. Data Cleaning
- Removed duplicate records
- Converted datetime columns
- Removed invalid timestamps
- Handled missing values

### 4. Feature Engineering
Created additional features including:
- Hour
- Day
- Month

### 5. Exploratory Data Analysis
Performed detailed analysis using multiple visualizations.

### 6. Data Visualization
Generated charts including:
- Accident Severity Distribution
- Accidents by Hour
- Accidents by Day
- Accidents by Month
- Weather Condition Analysis
- Day vs Night Analysis
- Top States with Most Accidents
- Temperature Distribution
- Visibility Distribution
- Correlation Heatmap

### 7. Geospatial Analysis
Created an interactive Folium map to visualize accident hotspots using latitude and longitude.

### 8. Results
The analysis identified:
- Most common accident severity
- Peak accident hours
- Most accident-prone states
- Frequently occurring weather conditions
- Geographic accident hotspots

---

##  Project Outputs

- Severity Distribution
-  Hour-wise Accident Analysis
-  Day-wise Accident Analysis
-  Monthly Accident Analysis
-  Weather Condition Analysis
-  Day vs Night Comparison
-  State-wise Analysis
-  Temperature Distribution
-  Visibility Distribution
-  Correlation Heatmap
- Interactive Accident Hotspot Map

---

##  Project Structure

```
Traffic-Accident-Analysis/
│
├── traffic_accident_analysis.py
├── README.md
├── requirements.txt
├── Accident_Hotspots.html
├── severity_distribution.png
├── accidents_by_hour.png
├── accidents_by_day.png
├── accidents_by_month.png
├── weather_conditions.png
├── day_night_accidents.png
├── top_states.png
├── temperature_distribution.png
├── visibility_distribution.png
└── correlation_heatmap.png
```

---

##  Conclusion

This project demonstrates the complete data analysis workflow, from data collection and preprocessing to visualization and geospatial analysis. The insights obtained from the dataset can support better understanding of traffic accident patterns and contribute to informed decision-making for road safety.

---

Developed as part of a Data Science internship project.
