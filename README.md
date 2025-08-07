# 💳 Maximizing Revenue by Payment Method – A/B Testing Case Study

This project investigates whether the **payment method (credit card vs. cash)** influences the **average fare revenue** for a ride-hailing company.

Using **hypothesis testing**, we simulate an A/B test scenario to guide business decisions based on real-world data from January 2020 NYC yellow taxi trips.

---

## 📊 Business Problem

> Can nudging users toward credit card payments increase revenue?

Ride-hailing companies want to maximize fare revenue without disrupting the user experience. One hypothesis is that **credit card users tend to generate higher fares** than cash users.

---

## 🔍 Project Goals

- Determine if the **average fare amount differs** significantly based on payment method
- Simulate an A/B test using observational data
- Provide **data-backed recommendations** to business stakeholders

---

## 🧪 Methodology

1. **Data Preparation**  
   Cleaned and filtered NYC taxi dataset (January 2020) using pandas

2. **Exploratory Data Analysis**  
   - Summary statistics
   - Fare distributions by payment type

3. **Assumption Checks**  
   - Normality (Q-Q plots, Shapiro-Wilk test)

4. **Hypothesis Testing**
   - **Two-sample t-test** (parametric)
   - **Mann–Whitney U test** (non-parametric)

5. **Result Interpretation**  
   Statistical significance and business interpretation of findings

6. **Recommendations**
   Actionable next steps to optimize payment strategy

---

## ✅ Key Findings

- **Fare distributions are not normal** → non-parametric test used
- **Mann–Whitney U test** confirms a **statistically significant difference** in fare amounts between payment types
- **Card payments tend to yield higher fares** than cash payments

---

## 💡 Business Recommendations

- Encourage card payments via:
  - Loyalty rewards or discounts
  - Faster service prioritization
  - App default settings

- Potential revenue uplift: Even a **$1 increase per ride × 1M monthly rides = $1M/month**

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, SciPy, Seaborn, Matplotlib)
- Jupyter Notebook
- Statsmodels for Q-Q plots
- NYC Yellow Taxi Dataset (Jan 2020)

---

## 📁 Files in This Repository

| File                             | Description                           |
|----------------------------------|---------------------------------------|
| `maximizing_revenue.ipynb`      | Main notebook with full analysis      |
| `cleaned_yellow_tripdata_2020_01.csv` | Cleaned subset of data used         |
| `README.md`                      | This file                             |

---

## 📎 License

This project is for educational and portfolio purposes only. The NYC taxi dataset is publicly available.

---

## 🤝 Connect

Feel free to connect on [LinkedIn]((https://www.linkedin.com/in/kaushaljavangula/)) or reach out if you'd like to collaborate or discuss this project!
