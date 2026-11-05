# Wildlife Impacts on Aviation – Exploratory Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a dataset of recorded wildlife impacts on aviation.

Wildlife strikes are an important aviation safety concern because encounters between aircraft and wildlife can affect flight safety, cause aircraft damage, and result in financial losses.

The analysis explores patterns in wildlife incidents across **time, seasons, airports, aircraft operators, aircraft types, wildlife species, flight phases, time of day, weather conditions, damage, and repair costs**.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Understand the structure and characteristics of the wildlife impacts dataset.
* Identify and handle missing values and duplicate records.
* Analyze wildlife incidents across different years and months.
* Examine airports, aircraft operators, and aircraft types associated with incidents.
* Analyze the wildlife species involved in recorded incidents.
* Investigate the relationship between wildlife incidents and aircraft damage.
* Study incidents across different flight phases and times of day.
* Analyze seasonal patterns in wildlife incidents.
* Examine numerical variables such as aircraft height and speed.
* Identify potential outliers and validate numerical values.
* Explore relationships between numerical variables using correlation analysis.
* Create meaningful visualizations to communicate the findings.

---

## 🛠️ Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn


## 📌 Key Findings

The major findings from the EDA are:

* Recorded wildlife incident counts generally increased over the analyzed period.
* Autumn has the highest recorded number of incidents under the season mapping used.
* Summer has the second-highest recorded number of incidents.
* Unknown bird categories represent a substantial portion of recorded species classifications.
* Most records are categorized as causing **no damage**.
* The **approach** phase has the highest number of reported incidents.
* **Daytime** incidents are the most frequent time-of-day category.
* Height and speed show a strong positive correlation.
* Height and speed contain potentially extreme observations that require domain validation.
* Engine counts and HHMM time values require variable-specific validation rather than standard continuous-variable outlier treatment.

---


## 🚀 Future Improvements

Possible improvements include:

* Documenting the original dataset source and measurement units.
* Validating the seasonal mapping against the geographic context of the dataset.
* Adding flight-volume data to calculate incidents per flight or aircraft movement.
* Performing deeper statistical analysis.
* Building predictive models for wildlife strike risk.
* Developing an interactive dashboard using Power BI, Tableau, or Streamlit.
* Investigating high-risk airports, aircraft types, and flight phases in greater detail.

---

## 📝 Conclusion

This project provides a descriptive analysis of recorded wildlife impacts on aviation.

Through data cleaning, visualization, feature engineering, trend analysis, correlation analysis, and data validation, the project identifies important patterns related to **time,**
