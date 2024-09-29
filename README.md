# Online-Retail-Project
In this project, I'll be working with transactional data from an online retail store. The dataset contains information about customer purchases, including product details, quantities, prices, and timestamps. I'll explore and analyze this dataset to gain insights into the store's sales trends, customer behavior, and popular products.

### Project scenario

An online retail company is looking to interpret its data to help make key business decisions. They want you to use exploratory data analysis on their transactional data, which contains information about customer purchases, including product details, quantities, prices, and timestamps. Your task is to explore and analyze this dataset to gain insights into the store's sales trends, customer behavior, and popular products, in order to help drive business decisions.

### Summary
This project is transactional data from an online retail store. By conducting EDA, I will identify patterns, outliers, and correlations in the data, to make data-driven decisions and recommendations. Some of the main project objectives include:

- Describe data to answer key questions to uncover insights
- Gain valuable insights that will help improve online retail performance
- Provide analytic insights and data-driven recommendations

#### Dataset
The dataset you will be working with is the "Online Retail" dataset. It contains transactional data of an online retail store from 2010 to 2011. The dataset is available as a .xlsx file named Online Retail.xlsx. This data file is already included in the Coursera Jupyter Notebook environment, however if you are working off-platform it can also be downloaded [here](https://github.com/user-attachments/files/17178923/Online.Retail.xlsx).
The dataset contains the following columns:

- InvoiceNo: Invoice number of the transaction
- StockCode: Unique code of the product
- Description: Description of the product
- Quantity: Quantity of the product in the transaction
- InvoiceDate: Date and time of the transaction
- UnitPrice: Unit price of the product
- CustomerID: Unique identifier of the customer
- Country: Country where the transaction occurred

### Solution
As the main objective of this Online Retail Project is to interpret real-world data to make a key business decision, I proceeded with data cleaning and validation, addressing missing values, removing duplicates, and ensuring data consistency. This process significantly improved data quality and reliability, leading to insightful visualizations that highlighted key findings include actionable insights derived from EDA informed strategic decisions.

### Screenshots
This is Bivariate distribution of UnitPrice and Quantity. This a higher concentration of data points at lower UnitPrices, suggesting that items with lower prices tend to have higher quantities sold or available. This shows the distribution of data points is not uniform across different price ranges, showing variability in how Quantity relates to UnitPrice. On the other hand, the Quantity tends to decrease as the UnitPrice increases. This indicates that fewer units are sold or available at higher prices, which is a common trend in many markets.
![Bivariate distribution of UnitPrice and Quantity](https://github.com/user-attachments/assets/bb3a87c7-23f5-4518-a753-30f295f56d4a)

![Heat map](https://github.com/user-attachments/assets/1d18ed60-a1b5-4a85-a849-0974206bb286)

From the graph below, UK has the highest sales volume by a significant margin. Investigate the factors contributing to this success, such as marketing strategies, product preferences, and distribution channels. lower sales countries can be improved by identifing and replicating successful strategies from the UK in other countries, especially those with lower sales volumes like Greece, Poland, and Israel.
![20 countries](https://github.com/user-attachments/assets/9efd4916-a77a-4baa-9c51-4e0cd8f8ec66)

The graph below shows sales of days in whole complete months. This shows sales fluctuate throughout the months, with multiple peaks and troughs. The shaded area around the line suggests consistent variability in sales, indicating a predictable pattern of sales fluctuations. It's notable also sales tend to decline towards the end of the month, which could be due to budget constraints or reduced consumer activity. Some great actionable insights from this graph can be focus marketing efforts around mid-month to capitalize on higher sales volumes, and considering running promotions during low-sales days to boost activity and smooth out fluctuations.
![Busiest days by all month in terms of sales](https://github.com/user-attachments/assets/f5a74254-6891-4e9a-8690-6584dd12e196)


### Approach
In my online retail project, I began by installing and loading essential Python packages such as matplotlib, pandas, numpy, and seaborn to facilitate data analysis and visualization. then I imported the datasets using pandas and proceeded with data cleaning and validation, addressing missing values, removing duplicates, and ensuring data consistency. Through exploratory data analysis (EDA), we utilized pandas and seaborn to generate descriptive statistics and visualizations, uncovering patterns, trends, and anomalies. This process significantly improved data quality and reliability, leading to insightful visualizations that highlighted key findings. The actionable insights derived from EDA informed strategic decisions, ultimately enhancing data-driven decision-making and contributing to better business outcomes.


### Conclusion 
my online retail project demonstrated the power of data analytics and visualization in driving business success. By installing and utilizing essential Python packages, cleaning and validating data, and conducting thorough exploratory data analysis, I able to uncover valuable insights that informed strategic decisions. This comprehensive approach not only improved operational efficiency and customer satisfaction but also positioned the business for sustained growth and success in the competitive online retail market.
