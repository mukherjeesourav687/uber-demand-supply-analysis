# 🚖 Uber Demand-Supply Gap Analysis

Understanding why ride requests fail is more important than just counting completed trips.

This project focuses on identifying the **root causes behind ride failures** using a real-world dataset.

---

## 📌 Problem Statement

Users are booking rides, but many requests fail due to:
- Driver cancellations
- No cars available

The goal is to analyse:
- When failures happen
- Where failures happen
- Why they happen

---

## 📊 Dataset

The dataset contains:
- Request ID
- Pickup Point (City / Airport)
- Driver ID
- Status (Completed, Cancelled, No Cars Available)
- Request Timestamp
- Drop Timestamp

---

## 🛠️ Tools & Technologies

- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

---

## 🔍 Approach

- Data cleaning and preprocessing
- Handling missing values
- Converting timestamps to datetime
- Extracting hour for time-based analysis
- Using groupby for aggregation
- Analysing:
  - Demand vs Supply
  - Failure types
  - Time patterns
  - Location patterns

---

## 📈 Key Insights

- Ride failures are **not random**
- Peak hours show a **high demand-supply gap**
- Airport trips face more **"No Cars Available" issues**
- City trips see more **driver cancellations**
- Missing values indicate **unassigned drivers or incomplete trips**

---

## 💡 Conclusion

The problem is driven by:
- Time-based demand spikes
- Location-based inefficiencies
- Different types of failures requiring different solutions

---

## 🚀 Future Improvements

- Add interactive dashboard (Power BI / Tableau)
- Predict demand using ML models
- Optimise driver allocation strategy

---

## 📂 Files

- `uber_data_analysis.ipynb` → Full analysis notebook
- `uber-data.csv` → Dataset

---

## 🙌 Acknowledgement

This project was completed as part of learning from Scaler under the guidance of **Sourabh Kango**.

---

## 📬 Connect with Me

If you found this useful, feel free to connect or share feedback!
