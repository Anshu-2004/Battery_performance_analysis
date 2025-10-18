# Battery Performance Analysis: KOKAM SLPB 52495 Pouch Cell

## Overview 🔋

This project provides a comprehensive analysis of the charge-discharge cycle performance of a KOKAM SLPB 52495 pouch cell battery. Using experimental data from a charge-discharge test, this analysis visualizes key battery performance metrics and calculates its operational efficiency. The primary goal is to understand the battery's behavior under simulated real-world usage conditions through data analytics and visualization techniques in Python.

## Features & Analysis 📊

The analysis is conducted within a Jupyter Notebook (`Battery_Performance_Analysis (1).ipynb`) and leverages Python libraries such as Pandas, Matplotlib, Seaborn, and Plotly to perform the following:

* **Data Cleaning and Preparation:** The initial dataset is loaded, inspected for missing values, and cleaned to ensure accuracy for the subsequent analysis.
* **Charge-Discharge Cycle Visualization:** A dual-axis plot visualizes the battery's **voltage (V)** and **current (A)** profiles over time, clearly showing the distinct phases of charging, discharging, and rest periods.
* **Capacity Analysis:** The project tracks and plots the cumulative charge and discharge capacity (Ah) over the entire cycle to observe the battery's energy handling characteristics.
* **Power & Voltage Correlation:** A scatter plot with a regression line is used to analyze the relationship between the battery's voltage and its power output, providing insights into performance correlation.
* **Hysteresis Loop:** A Voltage vs. Capacity plot illustrates the hysteresis loop, which visually represents the difference in the charging and discharging voltage profiles and provides an indication of energy loss.
* **Charge Factor Calculation:** A key output of the analysis is the **charge factor** (coulombic efficiency), which is calculated by comparing the total charge capacity put into the battery against the discharge capacity obtained from it. This metric quantifies the battery's efficiency for the given cycle.
