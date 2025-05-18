# Healthcare No-Show Appointments Analysis

Analyzing patient appointment data to uncover patterns behind missed appointments and identify actionable insights that can help improve attendance rates.

---

##  Dataset

* **Source**: [Kaggle - No-show appointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)
* The dataset contains information on over 100,000 medical appointments in Brazil and whether or not patients showed up.

---

## Tools & Technologies

* Python (pandas, matplotlib, seaborn)
* Jupyter Notebook
* Data Cleaning & Exploratory Data Analysis (EDA)

---

## Project Goals

* Identify the percentage of no-shows
* Analyze the impact of SMS reminders
* Explore no-show behavior by age group
* Understand appointment attendance trends by day of the week

---

## Key Steps

1. **Loaded data** from CSV and inspected structure
2. **Cleaned data**:

   * Converted date columns to datetime
   * Standardized column names
   * Removed duplicates
   * Created `waiting_days` column (gap between scheduled and appointment day)
3. **Performed EDA**:

   * Calculated no-show rates
   * Grouped data by SMS reminders, age groups, and weekdays
   * Visualized trends using bar plots and pie charts

---

## Key Insights

*  **Overall no-show rate**: \~20.1%
*  Patients who received SMS reminders had a **higher no-show rate (\~27.6%)** than those who didn’t (\~16.5%)
*  The **Young Adult** group (19–35) accounted for the **highest no-show volume**
*  **Tuesday and Wednesday** had the **most no-shows**; **Thursday and Friday** had the fewest

---

## Example Visualization

![No-shows by Day of the Week](download.png)

---

## Project Structure

```
|-- healthcare-no-show-analysis/
|   |-- NoShowAppointments.ipynb
|   |-- cleaned_data.csv (optional)
|   |-- README.md
```

---

## Future Improvements

* Build a predictive model for no-shows
* Integrate more external datasets (weather, location, etc.)
* Visualize with Power BI or Tableau

---

## License

For educational and portfolio purposes only.

---

👩‍💻 Created by **Deepthi**
Feel free to explore, fork, or connect on [LinkedIn](https://www.linkedin.com/in/deepthi-p-reddy-6b147655/)
