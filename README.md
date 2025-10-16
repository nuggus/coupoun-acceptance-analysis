# 🧠 coupon-acceptance-analysis  
Data analysis and visualization of coupon acceptance behavior using Python, Seaborn, and Plotly — exploring the factors that influence whether drivers accept mobile coupons.

---

## 🧾 Project Overview  

This project analyzes **driver behavior and coupon acceptance patterns** using data from the *UCI Machine Learning repository and was collected via a survey on Amazon Mechanical TurkDataset*.  

By applying **data visualization and exploratory analysis** in Python, the project identifies **key demographic, social, and situational factors** that influence whether drivers accept mobile coupons.  

The findings reveal actionable insights — such as how **age, passenger type, income, and time of day** affect coupon usage for different offer types (e.g., bars and coffee houses) — helping businesses design more **targeted and effective marketing campaigns**.

---

## 📦 Dataset Description  

The dataset contains **12,684 rows and 26 columns**, collected via a survey on Amazon Mechanical Turk.  
Each record represents a driving scenario with variables such as **destination, weather, time, passenger, and income**, along with a binary target variable **`Y`** indicating whether the driver **accepted (1)** or **rejected (0)** a coupon.  
There are five coupon types in total — *Bar, Coffee House, Carry Out & Take Away, Restaurant (<$20), and Restaurant ($20–$50)*.

---

## 📊 Summary of Findings  

### **Observations on the Dataset**
1. The `car` column has **~99% missing values**, making it unsuitable for analysis.  
2. There are **74 duplicate rows**, which were removed to avoid data bias.  
3. The `age` column is stored as an **object type** (categorical text) and required transformation for numerical analysis.

---

### **Findings: Bar Coupons**
1. Drivers who **visit bars more than once a month** are significantly more likely to accept bar coupons.  
2. **Younger drivers (under 30 years)** show higher acceptance rates compared to older age groups.  
3. Drivers **traveling without children** are more likely to accept bar coupons than those with kids.  
4. Drivers **earning less than \$50K annually** and those who **frequently visit low-cost restaurants** show higher acceptance rates.  
5. Drivers with occupations **outside of farming, fishing, and forestry** are more likely to accept bar coupons, suggesting a more urban and social lifestyle.

---

### **Findings: Coffee House Coupons**
1. Drivers **traveling with friends**, particularly during **morning or early afternoon hours**, are more likely to accept coffee house coupons.  
2. Acceptance of coffee house coupons appears to be driven by **social connections, casual meetings, and time of day** — people prefer coffee earlier in the day rather than later.  

---

## 🚀 Next Steps and Recommendations  

- **Target Audience:** Focus marketing on **socially active, younger adults** who already visit bars or affordable restaurants.  
- **Personalization:** Use **data-driven personalization** to tailor coupon delivery to driver demographics and preferences.  
- **Timing:** Send **bar coupons in the evening** and **coffee coupons in the morning or early afternoon** to maximize acceptance.  
- **Continuous Improvement:** Build a **predictive model** to forecast coupon acceptance and refine targeting over time.  

---

## 💻 Jupyter Notebook  
You can explore the full analysis and visualizations in the notebook below:  
🔗 [coupon_acceptance_analysis.ipynb](https://github.com/nuggus/coupoun-acceptance-analysis/blob/master/coupon_acceptance_analysis.ipynb)

---

## 🧩 Tools and Technologies  
- **Python** (Pandas, NumPy)  
- **Seaborn / Matplotlib / Plotly** for visualization  
- **Jupyter Notebook** for exploration and reporting  

---

## 📈 Key Takeaways  
> Coupon acceptance is most influenced by **social behavior, lifestyle, and timing**.  
> Younger, socially active, and price-conscious individuals are the most likely to engage with **bar** and **coffee house** coupons.  
> Businesses can leverage these insights to **target marketing efforts more effectively** and increase coupon redemption rates.

---
