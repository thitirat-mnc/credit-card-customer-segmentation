# Credit Card Customer Segmentation 
- This project focuses on **customer segmentation** to analyze customer data, identify distinct segments, and predict future cluster memberships for targeted marketing strategies and personalized customer interactions

- Exploratory Data Analysis **(EDA)** to understand the dataset
- **K-means** clustering for grouping similar customers based on characteristics
- Dimensionality reduction techniques like Principal Component Analysis **(PCA)** and **autoencoders**
- **Logistic Regression** is utilized to predict future customer clusters based on their features
<br>

# Key Features:

- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [K-means Clustering & PCA & Autoencoder for Dimensionality Reduction](#k-means)
- [Logistic Regression for Future Cluster Prediction](#logistic-regression)
- [Insights from Customer Segmentation](#customer-segmentation-insights-from-credit-card-usage-data)


---

## Exploratory Data Analysis (EDA)
- 8950 raw data observations
- visualize to explore the distribution and correlation

### Heatmap
![creditcard_heatmap_ver2](https://github.com/thitirat-mnc/credit-card-customer-segmentation/assets/134206687/9627bf4a-3c6f-4112-92b8-2db7b95c659a)

### Pairplot
<br>![creditcard_pairplot](https://github.com/thitirat-mnc/credit-card-customer-segmentation/assets/134206687/43d43f78-df1e-4757-a02c-15731b840f60)
<br>

---

## K-means
- visualize K-means cluster (with PCA n_components = 2) <br>
![scatter_ver1](https://github.com/thitirat-mnc/credit-card-customer-segmentation/assets/134206687/53d64c12-3318-4a1b-bd4a-d7a22641d60e)

<br>

---

## **Logistic Regression**
- confusion matrix results for Logistic Regression prediction <br>
![confusion_matix](https://github.com/thitirat-mnc/credit-card-customer-segmentation/assets/134206687/65004bb4-cb35-4388-98c5-12b9f1ed094b)

---

## Customer Segmentation Insights from Credit Card Usage Data

Our model has identified **three distinct customer segments** based on behavioral patterns. Each segment represents a unique opportunity for strategic targeting and value creation.

---

### 🔹 Cluster 1: **Conservative Spenders**
**🧍 Proportion**: `68.36%` of total customers  
**💼 Profile**:
- Low balance
- Low credit limit
- Low purchase and cash advance usage
- Moderate purchase frequency

**🧠 Behavioral Insight**:  
These customers use their credit card mainly for emergencies or occasional expenses. They generate low transaction volume and minimal interest, making them less profitable — **but** their moderate usage signals potential for growth.

**🎯 Strategic Recommendations**:
- 💸 **Incentivize Spending**: Offer cashback and tailored promotions to encourage more frequent purchases.
- 🧾 **Introduce Installment Plans**: Provide low-interest options to ease larger transactions.
- 📚 **Educate for Empowerment**: Share financial literacy content on credit usage and benefits.
- 📈 **Increase Credit Gradually**: Reward responsible users with credit limit upgrades.

> ✅ **Goal**: Transition these low-engagement users into active spenders through value-driven incentives and education.

---

### 🔹 Cluster 2: **Frequent Purchasers**
**🧍 Proportion**: `13.77%` of total customers  
**💼 Profile**:
- Moderately high balance
- High volume of purchases (one-off and installment)
- Low cash advance usage
- High credit limit
- Strong repayment behavior

**🧠 Behavioral Insight**:  
These customers actively use their credit cards for day-to-day purchases and pay off their balances on time. They represent the **most profitable and least risky segment** — ideal for retention and upselling.

**🎯 Strategic Recommendations**:
- 🏆 **Reward Loyalty**: Offer enhanced cashback, discounts, and travel perks.
- 💎 **Premium Benefits**: Early access to sales, VIP customer support, and luxury experiences.
- 🚀 **Upsell Credit**: Encourage more spending by offering increased credit limits.
- 💼 **Cross-Sell Opportunities**: Suggest premium cards, loans, or investment products.

> ✅ **Goal**: Deepen engagement and loyalty with premium experiences and tailored financial offerings.

---

### 🔹 Cluster 3: **Revolvers / High-Balance Borrowers**
**🧍 Proportion**: `17.84%` of total customers  
**💼 Profile**:
- Very high balance
- Low purchase frequency
- Frequent and high cash advance usage
- High minimum payments and credit limits

**🧠 Behavioral Insight**:  
These customers often use credit cards as a **borrowing tool**, relying heavily on cash advances rather than purchases. While they generate substantial **interest revenue**, they also pose the **highest credit risk**.

**🎯 Strategic Recommendations**:
- 🛡 **Credit Risk Monitoring**: Closely track usage and adjust exposure as needed.
- 🧭 **Support Responsible Repayment**: Offer debt consolidation or financial counseling services.
- 🔄 **Offer Better Alternatives**: Recommend personal loans or lines of credit better suited to their needs.
- 🚫 **Discourage Overuse**: Implement safeguards to reduce dependency on cash advances.

> ⚠️ **Risk**: High revenue potential from interest, but with elevated default risk.

---

### 🧾 Summary Table

| Segment                   | % of Customers | Profitability       | Risk Level | Key Opportunity                          |
|---------------------------|----------------|----------------------|------------|-------------------------------------------|
| Conservative Spenders     | 68.36%         | Low (growable)       | Low        | Increase engagement and transaction volume |
| Frequent Purchasers       | 13.77%         | High (transactional) | Low        | Retain and upsell premium services         |
| High-Balance Borrowers    | 17.84%         | High (interest-based)| High       | Manage risk, offer better financial tools  |

---

### 📌 Takeaway

By understanding and strategically addressing the needs of each segment, businesses can:

- 💡 Maximize revenue from high-value users  
- 🔄 Convert low-usage customers into active spenders  
- 🛡 Mitigate risk from high-balance, high-dependency users  


