# A/B Testing of Subscription Conversion

This project analyzes an A/B test to evaluate the effect of price framing on user conversion to paid subscription.

## 🧪 Context

- **Group A**: Users were offered a standard subscription at $4.99/month.
- **Group B**: Same price, but with a label: "50% off".

## 🎯 Goal

To determine if the "50% off" framing increases conversions from free users to paid plans.

## 📊 Data

- Format: CSV (`ab_test_data.csv`)
- Fields: user_id, test_group, conversion, timestamp

## ⚙️ Tools & Methods

- Python, Pandas, Seaborn, Matplotlib, SciPy
- Chi-Square Test for Independence
- Confidence Interval (95%)
- Data visualization with barplot and error bars

## 📈 Key Results

- **Conversion A**: 6.1%  
- **Conversion B**: 8.9%  
- **Statistical significance**: ✅ (p < 0.01)

📌 Conclusion: "50% off" framing has a statistically significant positive impact on subscription conversion.

---

> This project is part of my data analytics portfolio.
