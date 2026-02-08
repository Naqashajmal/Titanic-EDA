# 🚀 Titanic Exploratory Data Analysis (Task 2)

## Project Overview
This project involves a comprehensive **Exploratory Data Analysis (EDA)** of the Titanic dataset using Python. The goal was to uncover patterns in passenger survival based on factors like **gender**, **age**, and **ticket class**.

## Key Technical Challenges & Solutions
* **Survived Column Mapping:** The original dataset used "yes/no" strings, which prevented numerical analysis. I used the `map()` function in **Pandas** to convert these into **1s and 0s**.
* **Handling Missing Data:** I identified **177 missing entries** in the age column and filled them with the **median age** to maintain data integrity without skewing the results with outliers.
* **Structural Cleaning:** Removed unnecessary "Unnamed" columns and hidden characters to ensure a clean DataFrame for visualization.

## Visualizations & Insights
* **Survival by Gender:** Female passengers had a significantly higher survival rate compared to males.
* **Survival by Class:** Passengers in **1st Class** were prioritized and had a higher survival probability than those in **3rd Class**.
* **Correlation Heatmap:** Visualized the relationships between Fare, Age, and Survival to identify key drivers of passenger safety.

## Tools Used
* **Python:** Core programming language.
* **Pandas:** Data manipulation and cleaning.
* **Seaborn & Matplotlib:** Data visualization and plotting.

<img width="3000" height="1800" alt="titanic_heatmap" src="https://github.com/user-attachments/assets/b427ceed-0ed2-4001-b486-33ddcfa3efc9" />
<img width="1920" height="1440" alt="survival_by_gender" src="https://github.com/user-attachments/assets/716f4f9d-f1ee-4911-b22d-f7615ec993f8" />
