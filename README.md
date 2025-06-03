# CodeAlpha_EDA
# Exploratory Data Analysis (EDA) on Diwali Sales Data

## Project Overview

This repository contains the Exploratory Data Analysis (EDA) performed on the **Diwali Sales Data**. The goal was to uncover meaningful insights, trends, and patterns within the dataset to facilitate data-driven decision-making.

This project is a part of the **CodeAlpha Internship Program**.

### Objectives

* Formulate meaningful questions before the analysis.
* Explore the data structure, including variables and data types.
* Identify trends, patterns, and anomalies in the data.
* Test hypotheses and validate assumptions using statistical methods and visualizations.
* Detect potential data issues or problems to address for further analysis.

---

## Dataset Description

The dataset used is `Sales Data.csv`, containing:

* **Rows:** 11,251
* **Columns:** 15

This dataset includes information such as:

* Customer demographics
* Product categories
* Sales figures
* Transaction details

---

## Methodology

The analysis was performed in the following steps:

1. **Data Preparation:**

   * Imported required Python libraries.
   * Loaded the dataset into a DataFrame.
   * Explored the structure and size of the dataset.

2. **Exploratory Analysis:**

   * Examined variables and their data types.
   * Conducted statistical analysis to summarize data.
   * Visualized key relationships and trends using:

     * Histograms
     * Scatter plots
     * Box plots
     * Heatmaps

3. **Hypothesis Testing:**

   * Tested assumptions and validated hypotheses using statistical tools.
   * Compared variables to understand their impact on sales.

4. **Data Issues:**

   * Identified missing, duplicate, or inconsistent data.
   * Suggested measures for data cleaning and improvement.

---

## Tools and Libraries Used

* **Python Libraries:**

  * `numpy`: For numerical computations.
  * `pandas`: For data manipulation and analysis.
  * `matplotlib` & `seaborn`: For data visualization.

---

## Insights and Outcomes

* Highlighted customer segments contributing the most to sales.
* Identified top-performing product categories.
* Revealed trends in seasonal sales.
* Addressed anomalies and proposed solutions for improvement.

---

## Repository Structure

```
project-repo/
├── CodeAlpha_EDA.ipynb      # Jupyter Notebook with EDA
├── Sales Data.csv    # Dataset 
├── README.md                # Project documentation (this file)
```

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/aqsa-stats/CodeAlpha_EDA.git
   ```
2. Install the required Python libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook and execute the cells sequentially:

   ```bash
   jupyter notebook CodeAlpha_EDA.ipynb
   ```

---

## Future Work

* Perform predictive modeling on cleaned and processed data.
* Integrate more advanced visualizations using interactive tools like Plotly.
* Extend analysis to include time-series trends for better forecasting.
---

## Acknowledgments

Special thanks to the internship program for providing this task for analysis.
