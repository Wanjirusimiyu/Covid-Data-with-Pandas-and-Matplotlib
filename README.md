# COVID-19 Data Analysis with Pandas, Matplotlib & Seaborn

This project explores, analyzes, and visualizes COVID-19 data using Python libraries including **Pandas**, **Matplotlib**, and **Seaborn**. The goal is to gain insights into the spread and impact of COVID-19 across different countries and continents by performing **data cleaning**, **statistical analysis**, and **visualizations**.

---

## Objectives

- Load and understand a real-world dataset (COVID-19 global data from Our World in Data)
- Explore the structure of the dataset and handle missing data
- Perform descriptive statistical analysis
- Create meaningful visualizations to interpret trends and relationships
- Derive insights and observations that can be easily communicated

---

## Dataset Information

- **Source**: [Our World in Data - COVID-19](https://github.com/owid/covid-19-data)
- **File Used**: `owid-covid-data.csv`
- **Description**: The dataset contains daily COVID-19 statistics for countries and regions across the world. It includes new and total cases, deaths, vaccinations, and other public health metrics.

---

## Tools and Libraries Used

| Tool/Library     | Purpose                                |
|------------------|----------------------------------------|
| **Google Colab** | Cloud-based Python environment         |
| **Pandas**       | Data loading, cleaning, and analysis   |
| **Matplotlib**   | Plotting and visualizations            |
| **Seaborn**      | Stylish and advanced visualizations    |
| **NumPy**        | Numerical computations (used indirectly) |



##  Data Cleaning Steps

- Handled missing values by dropping rows with `NaN` in crucial columns (`new_cases`, `new_deaths`, etc.)
- Filtered relevant data columns for visualization and analysis
- Converted date strings to actual `datetime` objects for time-series plots
- Ensured consistency in country and continent names


## Visualizations

### 1. New COVID-19 Cases Over Time in Kenya
- A **line chart** was used to visualize how daily new cases changed over time.
- Showed waves of infection, with visible spikes at certain time periods.

### 2. Average New Cases per Continent
- A **bar chart** grouped countries by continent and showed the **mean new case numbers**.
- Europe and Asia had significantly higher average new cases, possibly due to dense populations and large outbreaks.

### 3. Histogram: Distribution of New Deaths
- A **histogram** plotted the distribution of `new_deaths` to understand how often countries experienced low or high death counts.
- Most countries reported 0–100 new deaths per day, with few extreme outliers.

### 4. Scatter Plot: New Cases vs. New Deaths
- This chart explored the **correlation** between new COVID-19 cases and deaths.
- A general trend showed that days with more new cases also had more deaths, but not always linearly — influenced by medical care, testing, and vaccine rates.


## Key Observations

-  **Continent Comparison**: Europe reported the highest average new COVID-19 cases, followed by Asia and North America.
- **Kenya Time-Series**: Kenya experienced multiple spikes in daily new cases, aligning with known pandemic waves.
-  **Death Distribution**: Most records showed few or zero new deaths per day, but a small portion had very high numbers (likely during major waves).
-  **Correlation Insight**: There's a positive correlation between new cases and new deaths, but other factors like vaccination, age distribution, and healthcare affect this.


##  File Structure
- **covid.ipynb**: Contains all code required for visualization and plotting of graphs.



## How to Use This Project

> You can run this project using [Google Colab](https://colab.research.google.com):

1. Open [Google Colab](https://colab.research.google.com)
2. Upload the `owid-covid-data.csv` file
3. Upload and open the `.ipynb` notebook
4. Run each cell in order to see the analysis and visualizations


## What I Learned

- How to clean and inspect large datasets with Pandas
- How to visualize trends, comparisons, and relationships in data using Matplotlib and Seaborn
- How to interpret real-world public health data and make data-driven observations
- How to use Google Colab for collaborative data analysis


## Future Improvements

- Add interactivity using Plotly or Dash
- Perform time-series forecasting with ARIMA or Prophet
- Explore vaccination data alongside case and death trends
- Build a dashboard or web app to share findings


## References

- [Our World in Data – COVID-19 Data](https://ourworldindata.org/coronavirus)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Matplotlib Documentation](https://matplotlib.org/)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Google Colab Guide](https://colab.research.google.com/notebooks/intro.ipynb)


## Author

**Joy Wanjiru Simiyu**  







  

