# customer_behaviour_analysis



## Customer Shopping Behavior Analysis

This repository contains an end-to-end data analytics pipeline analyzing 3,900 customer retail transactions. The primary objective is to process raw transactional data, uncover demographic and behavioral purchasing patterns, and deliver actionable insights to optimize marketing and retention strategies.

### Overview & Technology Stack

The project workflow encompasses data loading, handling missing values (such as median imputation for 37 missing review ratings), engineering new behavioral features, and relational database integration.

* **Core Languages:** Python, SQL
* **Data Processing:** Pandas, NumPy
* **Database Management:** PostgreSQL for secure integration and advanced querying
* **Visualization:** Matplotlib, Seaborn

### Exploratory Data Insights

After preprocessing the 18-column dataset and engineering features like age groups and purchase frequency, several core trends emerged from the analysis:

* **User Segmentation:** The customer pipeline consists of 50% new buyers, 35% returning shoppers, and a critical 15% base of high-value loyal customers.
* **The Subscription Advantage:** While subscribers generate 45% of total revenue, they represent a massive 78% repeat purchase frequency, proving their long-term lifetime value.
* **Shipping & Spend Correlation:** Users opting for express shipping spend an average of $65 per transaction, which is a 12% premium over standard shipping users.
* **Product Satisfaction:** Blouses and dresses achieved perfect 5-star satisfaction ratings, while shirts maintained strong 4-star approval, establishing clear inventory winners.

### Strategic Business Impact

By bridging the gap between raw data and business strategy, this analysis provides several data-grounded recommendations for immediate implementation:

* **Targeted Conversions:** Deploy targeted campaigns aimed at converting the large 50% new-buyer segment into recurring, subscribed shoppers.
* **Revenue Optimization:** Promote express shipping options at checkout and tailor exclusive discount strategies to high-spending "smart shoppers" who wait for deals to maximize their cart value.
* **Inventory Positioning:** Anchor ad spend and premium website placement around top-performing 5-star products to guarantee high initial customer satisfaction.

---

Do you plan to link a live interactive dashboard (like Power BI) in this repository, or are you keeping it focused strictly on the Python and SQL source code?
