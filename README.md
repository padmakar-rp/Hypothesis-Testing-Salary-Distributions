# 📊 Salary Comparison Using Independent T-Test

This project performs a statistical comparison of salaries between two departments using an **Independent Samples T-Test**. It generates synthetic salary data, calculates summary statistics, conducts hypothesis testing, and visualizes the distributions.

---

## 📌 Project Overview

The script:

- Generates salary data for two departments using a normal distribution
- Computes the mean salary for each department
- Performs an independent t-test using `scipy.stats`
- Interprets the hypothesis test results
- Visualizes the salary distributions using KDE plots

---

## 🧪 Hypothesis Testing

We test:

- **Null Hypothesis (H₀):** There is no significant difference between the mean salaries of Department A and Department B.
- **Alternative Hypothesis (H₁):** There is a significant difference between the mean salaries.

### Significance Level
```
α = 0.05
```

### Decision Rule

- If **p-value < 0.05** → Reject H₀ (Significant Difference)
- If **p-value ≥ 0.05** → Fail to Reject H₀ (No Significant Difference)

---

## 📦 Libraries Used

- `numpy`
- `matplotlib`
- `scipy`
- `seaborn`

---

## ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/salary-t-test-analysis.git
cd salary-t-test-analysis
```

### 2️⃣ Install Required Libraries

```bash
pip install numpy matplotlib scipy seaborn
```

### 3️⃣ Run the Script

```bash
python salary_analysis.py
```

---

## 📊 Output

The program prints:

- Mean salary for Department A
- Mean salary for Department B
- T-statistic
- P-value
- Hypothesis test conclusion

It also displays a KDE plot comparing salary distributions with mean lines.

---

## 📈 Visualization Details

The generated graph includes:

- Smoothed salary distribution curves
- Mean salary lines (dashed)
- Visual comparison of both departments

This helps in understanding both statistical and visual differences between groups.

---

## 📁 Project Structure

```
salary-t-test-analysis/
│
├── salary_analysis.py
└── README.md
```

---

## 🎯 Key Concepts Demonstrated

- Random data generation using normal distribution
- Independent samples t-test
- Hypothesis testing
- Data visualization with seaborn
- Statistical decision-making

---

## 📚 Learning Purpose

This project is ideal for:

- Students learning hypothesis testing
- Beginners in data analysis
- Practicing statistical inference in Python
- Understanding A/B testing concepts

---

⭐ If you found this helpful, consider giving the repository a star!
