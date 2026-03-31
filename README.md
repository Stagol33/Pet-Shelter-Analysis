# Austin Animal Center Data Analysis Project

### Data Analyst: Breck

---

## 🏗️ Project Overview

This project analyzes datasets from the **Austin Animal Center** (Intakes, Outcomes, and Combined) to provide actionable insights for shelter management. The goal was to identify patterns in animal intake, calculate adoption success rates, and estimate operational costs for medical procedures.

## 📊 Key Business Questions Addressed

- **Geographic Trends:** Identified the top 5 "hotspots" where pets are found to assist animal control.
- **Operational Planning:** Calculated average monthly intake to help the shelter plan for resource needs.
- **Success Metrics:** Measured the ratio of incoming pets vs. those successfully adopted.
- **Demographic Analysis:** Analyzed how **breed, color, and age** impact adoption rates.
- **Financial Budgeting:** Estimated the total expenditure for spay/neuter surgeries in 2015.

---

## 🛠️ Tools & Technologies

- **Language:** Python 3.x
- **Libraries:** \* **Pandas:** For data manipulation, filtering, and aggregation.
  - **JupyterLab:** For interactive development and analysis.
- **Datasets:** `aac_intakes.csv`, `aac_outcomes.csv`, `aac_intakes_outcomes.csv`.

---

## 🧪 Methodology

1.  **Data Cleaning:** Converted date strings into `datetime` objects for time-series analysis.
2.  **Feature Engineering:** \* Created an `age_group` classifier to bucket animals into **Baby, Young, Adult, and Senior** life stages.
    - Used string filtering to handle "Intact" status for surgical cost calculations.
3.  **Aggregation:** Leveraged `.groupby()` and `.value_counts()` to calculate percentages and frequency distributions.

---

## 📈 Key Findings

- **Top Intake Location:** The most frequent area for strays was **[Insert Top Location]**.
- **Adoption Success:** Approximately **[Insert %]** of incoming animals were successfully adopted.
- **Surgery Costs:** The 2015 budget for spay/neuter procedures ($100/dog, $50/cat) was estimated at **$[Insert Total Cost]\*\*.
- **Repeats:** Identified **[Insert Number]** animals that were returned to the shelter multiple times.

---

## 🚀 How to Run

1. Ensure `pandas` is installed: `pip install pandas`.
2. Place the CSV files in the same directory as the notebook.
3. Execute the cells in order, starting with the **Setup and Data Loading** block.
