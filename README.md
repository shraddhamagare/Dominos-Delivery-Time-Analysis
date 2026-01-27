## **🍕 Dominos Delivery Time Analysis (EDA)**
**📖 Project Overview**

Dominos promises its customers pizza delivery within 31 minutes — failing which the pizza is delivered for free.
To maintain brand standards, Dominos evaluates its franchise stores using a strict performance metric:

95% of orders must be delivered within 31 minutes

In this project, I performed an Exploratory Data Analysis (EDA) on real delivery order data to understand whether a Dominos store is meeting this requirement and to identify operational risk areas.

**🎯 Objective**

The goal of this analysis is to:

- Measure delivery performance using the 95th percentile metric

- Identify how delivery time varies across different hours

- Detect SLA violations and potential business risks

- Provide insights that can help improve operational efficiency

**📊 Dataset Description**

The dataset contains 15,000 pizza orders with the following fields:

- Column Name	Description
- order_id	Unique identifier for each order
- order_placed_at	Timestamp when the order was placed
- order_delivered_at	Timestamp when the order was delivered

From these columns, delivery time was calculated and analyzed.

**🔍 Exploratory Data Analysis Steps**

1️⃣ Data Cleaning & Preparation

- Converted timestamp columns to datetime format

- Calculated delivery time in minutes

- Extracted order hour for time-based analysis

**2️⃣ Delivery Time Analysis**

- Analyzed average delivery time

- Calculated the 95th percentile delivery time (primary SLA metric)

- Identified orders exceeding the 31-minute limit

**3️⃣ Hour-wise Performance Analysis**

- Grouped orders by hour of the day

- Calculated 95th percentile delivery time for each hour

- Detected peak hours contributing to delays

**4️⃣ Visualization**

- Plotted hour-wise delivery performance

- Compared delivery times against the 31-minute SLA threshold

- Highlighted risky time windows visually

**📈 Key Insights**

- ✔ Overall store performance meets the SLA requirement
- ⚠ Certain hours show higher delivery delays
- ⏱ Peak hours significantly impact delivery performance
- 📌 A small percentage of late orders can heavily affect the 95th percentile

**💡 Business Takeaways**

- This analysis shows how a few delayed orders can put a franchise at risk, even when average delivery time looks good.

**Recommended actions:**

- Increase staffing during peak hours

- Monitor 95th percentile daily instead of average time

- Optimize delivery radius during rush periods

- Proactively flag orders approaching SLA breach

**🛠 Tools & Technologies**

- Python

- Pandas

- Matplotlib

- Exploratory Data Analysis (EDA)

**Business KPI Analysis**

▶️ How to Run
pip install pandas matplotlib
jupyter notebook Dominos_Delivery_Time_EDA.ipynb

**👩‍💻 About Me**

I am an aspiring Data Scientist with a strong interest in solving real-world business problems using data.
This project reflects my approach to combining analytics, storytelling, and decision-making.

Shradha
Data Science | Machine Learning | AI

⭐ If you like this project, feel free to star the repo!
