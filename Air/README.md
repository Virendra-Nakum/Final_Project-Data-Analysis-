# Air Quality Data Analysis

### Analyzing Global Air Pollution Using Python, Pandas, and Data Visualization

This project analyzes global air quality data to understand pollution levels across different countries and cities. It uses Python, Pandas, Matplotlib, and Seaborn for data analysis and visualization.

## Installation

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Download or clone this project.
2. Open the project folder in Jupyter Notebook or VS Code.
3. Install the required libraries using the command above.
4. Open `air_quality_analysis.ipynb`.
5. Run the notebook cells one by one.
6. Select any option from the analysis or visualization menu to see the results.

## Project Structure

```text
│
├── main.ipynb
├── air_quality_data.csv
└── README.md
```

## Dataset Columns

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

## Data Analysis

- Total countries, cities, and pollutants
- Country-wise air quality analysis
- City-wise air quality analysis
- Highest and lowest pollution values
- Average pollution value by country
- Most common pollutants
- Latest updated air quality records
- Trend analysis using last updated date

## Data Visualization

- Bar Plot — Country-wise average pollution value
- Line Plot — Pollution value over time
- Scatter Plot — Pollution value distribution
- Histogram — Pollution value distribution
- Pie Chart — Top pollutants
- Heatmap — Correlation between numeric columns
- Subplot — Multiple graphs in one figure

## Conclusion

This project helps to understand air pollution levels across different countries and cities. It identifies common pollutants and shows how pollution values change over time. The analysis and visualizations make it easier to identify highly polluted areas and understand air quality trends.

## Author

**Virendra Nakum**