## Customer Segmentation (K-means, PCA based model)

**Project description:** Customer segmentation is a smart way businesses group their customers into different categories based on things they have in common. This helps businesses understand what their customers like and how they act. By knowing this, companies can make their products and marketing better to suit each group of customers.

The main goal of this project is to understand how to perform customer segmentation using clustering techniques with a specific dataset. I have utilized a dataset from Kaggle for this purpose. This big dataset has lots of information about more than a million times when people used a bank in India. It tells us about the people, their ages, where they are, and how much money they have in their accounts. I use this data to learn more about the customers and put them into groups that make sense. 

```javascript
data = pd.read_csv('/kaggle/input/bank-customer-segmentation/bank_transactions.csv')

```

### Techniques/ Algorithms / Metrics

In the initial phase, I applied a variety of data analysis methods and visualization techniques. Subsequently, I conducted Exploratory Data Analysis (EDA), selected relevant features, reduced dimensions, built and chose models, and evaluated them. This comprehensive process led to the final cluster results. Following are the techniques that I mainly used in this project.

1. K-means
2. Principal Component Analysis (PCA)
3. RFM (Recency, Frequency, Monetary) analysis
4. Elbow method
5. Silhouette Score 




