# Air Quality Analysis and Environment Data Visualization

## 1. Problem Statement
To analyze air quality data, compare PM2.5 levels, examine seasonal and monthly AQI trends, and visualize air pollution indicators to understand environmental conditions.

## 2. Dataset Source and Description
**Source:** [WHO Ambient Air Quality Database](https://www.who.int/data/gho/data/themes/air-pollution/who-air-quality-database)

The project uses an Excel dataset containing city-wise PM2.5 levels, seasonal and monthly AQI values, WHO guideline limits, AQI categories, and air pollution health impact indicators.


## 3. Steps Followed
- **Data Collection:** Uploaded and imported the Excel dataset using Pandas.
- **Data Cleaning:** Removed duplicate records, trimmed extra spaces, converted numeric values, and checked missing values.
- **Data Analysis:** Calculated summary statistics and compared air quality indicators.
- **Data Visualization:** Created bar charts and line charts using Matplotlib and Seaborn.
- **Summary:** Displayed record counts, dataset categories, and highest and lowest values where available.

## 4. Key Findings
- City-wise PM2.5 levels can be compared to identify higher and lower recorded values.
- Seasonal and monthly AQI visualizations help examine changes in air quality.
- PM2.5 values can be compared with the WHO annual guideline of 5 µg/m³ when the data represents annual averages.
- AQI category ranges and health impact indicators provide additional environmental context.


## 5. How to Run the Project
1. Open [Google Colab](https://colab.research.google.com/).
2. Upload or paste the Python code into a notebook.
3. Run the code and upload the Excel dataset when prompted.
4. Ensure the workbook contains a sheet named `Cleaned data`.
5. View the generated charts and summary statistics.

Required libraries:

```bash
pip install pandas matplotlib seaborn openpyxl
```

## 6. Screenshots of Charts

The project generates these visualizations:

- City-wise Average PM2.5 Levels
- Seasonal Comparison of AQI
- Monthly AQI Trend
- City PM2.5 Levels Compared with WHO Guideline
- WHO Annual Air Quality Guideline Limits
- Upper AQI Limit by Air Quality Category
- Global Air Pollution Health Impact Indicators


Example:

```markdown
![City-wise PM2.5 Levels](screenshots/city_pm25.png)
```

## 7. Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab
- Excel
