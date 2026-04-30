# Predictive Modeling of Student Success (OULAD)

## Project Overview
This project applies **Machine Learning** techniques to the *Open University Learning Analytics Dataset (OULAD)*. The primary objective is to develop an **early-warning system** that identifies students at risk of failing based on their engagement during the first **four weeks** of the semester.

---

## Key Exploratory Findings
In line with the project requirements, our analysis focused on identifying **positive relationships** between student behavior and academic success:

* **Positive Engagement Trend:** As the number of `active_days` increases, the probability of a "Pass" outcome increases near-linearly.
* **Consistency vs. Volume:** While `total_clicks` is a useful metric, **regularity of access** (active days) proved to be a more stable positive predictor.
* **Feature Correlation:** The correlation heatmap confirms a strong positive bond between early-resource interaction and final results.

---

## Technical Stack
The following tools were used to build the predictive pipelines:
* **Language:** `Python 3.x`
* **Environment:** `Jupyter Notebook (Anaconda)`
* **Libraries:** * `Pandas` (Data Manipulation)
    * `Scikit-Learn` (Machine Learning)
    * `Seaborn` & `Matplotlib` (Visualization)

---

## How to View the Analysis
The full technical implementation, including data cleaning, feature engineering, and model evaluation, is contained within the notebook:

**[Click here to view the Analysis Notebook](./2540702_OULAD_Final.ipynb)** ---

---

## Usage Guidelines

### 1. Technical Setup
To replicate this analysis or run the predictive pipeline locally:
1. **Download the Dataset:** Obtain the OULAD files from the [official source](https://analyse.kmi.open.ac.uk/open-dataset) and place the `.csv` files in the root directory.
2. **Install Dependencies:** Ensure you have the required libraries installed:
   ```bash
   pip install pandas scikit-learn seaborn matplotlib numpy

---
## Author
* **Name:** Ofentse Tembe
* **Student ID:** 2540702
* **Institution:** University of the Witwatersrand
* **Module:** ELEN4025A

## References
[1] J. Kuzilek, M. Hlosta, and Z. Zdrahal, "Open University Learning Analytics dataset," *Scientific Data*, vol. 4, no. 1, 2017.