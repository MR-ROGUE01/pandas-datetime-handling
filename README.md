# ⏳ Date & Time Feature Engineering with Pandas

Transforming raw date and time data into meaningful features for Machine Learning using Python and Pandas.

---

## 🚀 Project Overview

In Machine Learning, models cannot directly understand date-time values like:

```python
2024-08-15 14:35:20
```

This project demonstrates how to convert date and time columns into powerful numerical and categorical features that can improve model performance and data analysis.

---

## 📚 Concepts Covered

### 📅 Date Features
✔️ Year Extraction  
✔️ Month Extraction  
✔️ Month Name Extraction  
✔️ Day Extraction  
✔️ Day of Year Extraction  
✔️ Day of Week Extraction  
✔️ Day Name Extraction  

### ⏰ Time Features
✔️ Hour Extraction  
✔️ Minute Extraction  
✔️ Second Extraction  
✔️ Time-only Extraction  

### 🎯 Feature Engineering
✔️ AM / PM Classification  
✔️ Session Creation (Morning, Afternoon, Evening, Night)  
✔️ Timedelta Calculations  
✔️ Days Difference Calculation  

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Jupyter Notebook | Development Environment |

---

## 📂 Dataset Used

- orders.csv
- messages.csv

The datasets contain date and timestamp information used for feature extraction and datetime manipulation.

---

## 🔥 Key Operations Performed

```python
pd.to_datetime()
.dt.year
.dt.month
.dt.month_name()
.dt.day
.dt.day_of_year
.dt.day_of_week
.dt.day_name()
.dt.hour
.dt.minute
.dt.second
.dt.time
.dt.strftime()
```

---

## 💡 Custom Feature Engineering

Created a custom session feature based on time of day:

| Time Range | Session |
|------------|----------|
| 00 - 11 | Morning 🌅 |
| 12 - 16 | Afternoon ☀️ |
| 17 - 20 | Evening 🌇 |
| 21 - 23 | Night 🌙 |

---

## 📈 Learning Outcomes

After completing this project, I learned:

- Handling datetime data in Pandas
- Extracting meaningful date features
- Extracting useful time features
- Creating custom temporal features
- Working with Timedelta objects
- Preparing date-time data for Machine Learning

---

## 📁 Project Structure

```text
📦 Date-Time-Feature-Engineering
 ┣ 📜 orders.csv
 ┣ 📜 messages.csv
 ┣ 📓 datetime_feature_engineering.ipynb
 ┗ 📄 README.md
```

---

## 🎯 Future Improvements

- Cyclical Encoding (Sin/Cos Transformation)
- Time Series Feature Engineering
- Lag Features
- Rolling Window Features
- Business Day Calculations

---

## 👨‍💻 Author

**Raj Kumar**  
B.Tech CSE (AI & ML)

> Turning raw timestamps into machine-learning-ready features.
