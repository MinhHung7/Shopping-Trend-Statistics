# Hello there 🖐
This is my external project combined my knowledges about 
- **Data Science Introduction**
- **Data Science Programming**
- **Data Visuallization**
## 👉 Here are some information about this project
The dataset I use is [Customer Shopping (Latest Trends) Dataset](https://www.kaggle.com/datasets/bhadramohit/customer-shopping-latest-trends-dataset). You can click the link to navigate to dataset source.
About this dataset's information as columns names, columns meaning, you can look into my file notebooks, or simply look at dataset source

---
In this project, I visuallize attributes relationships and build systems using ML algorithms.
The two first systems I build are:

- **Customer Segmentation System**:
  - This system's purpose is to categorize customers into segments for personalized marketing.
  - The input features consists of `Age`, `Gender`, `Location`, `Frequency of Purchases`, `Preferred Payment Method`, `Subscription Status`.
  - The output is classification assign segments:
      - **Frequent Shoppers with Normal Purchases Subscriptions**
      - **Occasional Shoppers with High Purchases**
      - **Frequent Shoppers with High Purchases and Subscriptions**
      - **Infrequent Shoppers**
  - I use `KMeans` algorithms to cluster customer, then use `PCA` algorithms to visuallize clusters
- **Review Sentiment Analysis and Recommendation System**
  - This system's purpose is to analyze customer reviews and recommend products.
  - The input features consists of `Category`, `Review Rating`, `Size`, `Color`, `Season`.
  - The output is recommend items
  - I use `KNN` algorithms to find k neighbor customer, for `non-numeric` attributes like `Category`, `Size`, `Color`, `Season`, I use `OneHotEncoder` to encode them into numeric vector columns
