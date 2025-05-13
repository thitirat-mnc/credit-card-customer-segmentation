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
## **📊 Insights Drawn**
The customer base is segmented into three primary clusters, each with distinct behaviors and profitability profiles:

### 💰 Cluster 1: Conservative Spenders: 68.36% of the customers
> **🔍 Characteristics**:
> * Low balance
> * Low purchases and cash advance usage
> * Moderate purchase frequency
> * Low credit limit

📌 Insights:
* These customers use credit cards mainly for emergencies or occasional spending
* Low profitability due to limited transaction volume and interest generation
* Moderate purchase frequency indicates potential to increase usage

While currently low in profitability, this group shows potential due to their moderate purchase frequency
* These customers mainly use their credit card for emergencies or occasional spending rather than as a primary payment method
* They are not profitable for the bank because they don’t generate much transaction volume or interest fees
* Since they have a moderate purchase frequency, they could potentially be encouraged to spend more

🎯 Strategy:
* *Encourage More Spending*: Offer personalized promotions or cashback rewards on frequent purchases to increase their transaction volume.
* *Installment Plans*: Introduce installment purchase options with low-interest rates to make them more comfortable with larger purchases.
* *Educational Content*: Provide financial literacy materials on how to maximize credit card benefits and build a positive credit history.
* *Gradual Credit Limit Increase*: Offer slight credit limit increases based on responsible usage to encourage more spending.


### 🛍️ Cluster 2:Frequent Purchasers : 13.77% of the customers,
> **Characteristics**: Moderately High balance, high one-off and installment purchases, frequent purchases, low cash advance usage (use their credit card primarily for purchases, not as a loan.), high credit limit, and of course high payment, so they settle their balances well, reducing the bank’s risk.
Strategy:
* Loyalty Rewards: Enhance cashback, discounts, or travel rewards for frequent usage to retain their engagement.
* Exclusive Offers: Provide them with premium benefits such as priority customer service, travel perks, or early access to sales.
* Upsell Higher Credit Limits: Since they are responsible with payments, offering higher limits could increase spending and satisfaction.
* Cross-Selling Financial Products: Suggest additional financial products like premium credit cards, personal loans, or investment services.
* This is the most profitable group in terms of transaction fees and spending volume.
* They pay their bills on time, meaning they are low-risk customers.
* They are ideal candidates for premium services and rewards programs to retain their loyalty.
  
3) Third Customers cluster (Revolvers / High Balance / Cash Advancement): account for 17.84% of the customers
> **Characteristics**: Very high balance, low purchase frequency, high and frequent cash advances (Instead of purchases, they withdraw cash often, likely treating their credit card as a loan, in contrast to the second group
* High minimum payments, which means they accumulate high interest, but also have high credit limits as well. So they have access to large amounts of credit, increasing their borrowing capacity.
* They generate the most interest revenue for the bank but also pose the highest credit risk.
* Since they rarely make purchases, they are not ideal for transaction-based revenue.
* Their high dependence on cash advances suggests financial stress, making them more likely to default on payments.
