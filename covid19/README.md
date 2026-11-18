# 🦠 COVID-19 Data Analysis & Visualization

A Python-based data analysis project that explores COVID-19 data through data cleaning, statistical analysis, country-wise comparisons, and interactive visualizations.

## 📌 Project Overview

This project uses Python libraries to analyze COVID-19 datasets and understand the spread, deaths, recoveries, and active cases across different countries.

It allows users to load a CSV dataset, perform basic data-cleaning operations, analyze important statistics, and visualize results using different types of graphs.

## 🚀 Features

### 1. Dataset Loading
- Load COVID-19 datasets in CSV format.
- Enter the dataset file path manually.
- Read data using Pandas.

### 2. Data Cleaning
- Handle missing values.
- Remove duplicate records.
- Convert columns into appropriate data types.
- Rename column names.

### 3. Data Analysis
- Calculate total confirmed cases.
- Calculate total deaths.
- Calculate total recovered cases.
- Calculate active cases.
- Perform country-wise analysis.
- Find minimum and maximum cases.
- Calculate death rate and recovery rate.

### 4. Data Visualization

The project supports six types of visualizations:

| Visualization | Purpose |
|---|---|
| Bar Plot | Compare deaths across countries |
| Line Plot | Analyze confirmed cases over time |
| Scatter Plot | Compare confirmed cases and deaths |
| Histogram | Understand recovered cases distribution |
| Pie Chart | Show country-wise death percentages |
| Heatmap | Analyze correlations between numerical columns |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure

``` 
├── main.ipynb
├── covid19.csv
└── README.md
```

*Note: `data.csv` represents your COVID-19 dataset. Keep the actual dataset in the project folder or provide its correct path.*

## ⚙️ Installation & Setup

### Step 1: Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the Project Folder

```bash
cd COVID-19-Data-Analysis
```

### Step 3: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Run Jupyter Notebook

```bash
jupyter notebook
```

Open `main.ipynb` and execute the cells sequentially.

## 📊 Dataset Requirements

The notebook expects a CSV dataset containing columns such as:

- Date
- Country/Region
- Confirmed
- Deaths
- Recovered
- Active

Enter the dataset path when prompted.

## 🎯 Learning Outcomes

Through this project, I practiced:

- Data loading and exploration.
- Data cleaning and preprocessing.
- Handling missing and duplicate values.
- Pandas GroupBy operations.
- Statistical calculations.
- Data visualization using Matplotlib and Seaborn.
- Understanding correlation between numerical variables.

## 👨‍💻 Author

**Virendra Nakum**
 
