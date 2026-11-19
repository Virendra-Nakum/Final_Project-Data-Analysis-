# 🌍 Air Quality Data Analysis

### A Python-based data analysis project to explore air pollution levels across countries, cities, and pollutants.

---

## 📌 Project Overview

This project analyzes the **Air Quality Dataset** using Python.  
It helps us understand pollution levels in different countries and cities, the most common pollutants, and how pollution values change over time.

The project includes data cleaning, exploratory data analysis, visualizations, correlation analysis, and result interpretation.

---

## 📊 Dataset

The dataset contains air quality measurements from different countries, cities, and monitoring locations.

### Dataset Columns

| Column Name | Description |
|---|---|
| Country Code | Short code of the country |
| City | Name of the city |
| Location | Monitoring station or location name |
| Coordinates | Latitude and longitude of the location |
| Pollutant | Type of pollutant, such as PM2.5, NO2, SO2 |
| Source Name | Name of the data source or monitoring station |
| Unit | Unit of the pollution value |
| Value | Pollution measurement value |
| Last Updated | Date and time when the record was updated |
| Country Label | Full name of the country |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Project Structure

```text
│
├── main.ipynb
├── air_quality_data.csv
└── README.md
```

### Files Description

| File Name | Description |
|---|---|
| `main.ipynb` | Main Jupyter Notebook containing the complete analysis |
| `air_quality_data.csv` | Dataset used for analysis |
| `README.md` | Project documentation |

---

## ⚙️ Installation

Make sure Python is installed on your system.

Install the required libraries using this command:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

---

## 🚀 How to Run

1. Download or clone this project.
2. Open the project folder.
3. Open Command Prompt or Terminal in that folder.
4. Run Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `main.ipynb`.
6. Run all cells one by one.
7. Select any option from the analysis or visualization menu.
8. Check the graphs and analysis results.

---

## 📈 Analysis Performed

- Total Countries, Cities, and Pollutants
- Country-wise Air Quality Analysis
- City-wise Air Quality Analysis
- Highest and Lowest Pollution Values
- Average Pollution Value by Country
- Most Common Pollutants
- Latest Updated Air Quality Records
- Pollution Trend Analysis by Date

---

## 📉 Visualizations

- Country-wise Average Pollution Bar Chart
- Pollution Value Over Time Line Chart
- Pollution Value Scatter Plot
- Pollution Value Histogram
- Top Pollutants Pie Chart
- Correlation Heatmap
- Multiple Graphs Using Subplot

---

## 🔍 Key Insights

- Pollution levels differ across countries and cities.
- Some pollutants are more commonly recorded than others.
- Average pollution value helps to compare air quality between countries.
- Pollution values can change over time based on the last updated date.
- Correlation shows relationships between variables, not direct cause-and-effect.

---

## 📌 Future Improvements

- Add more years of air quality data.
- Perform city-wise deep analysis.
- Create interactive dashboards.
- Use machine learning to predict pollution levels.
- Compare pollution levels with weather and traffic data.

---

## 👨‍💻 Author

**Virendra Nakum**
