# Online-Retail-Project

### Project scenario

In this project, I'll be working with transactional data from an online retail store. An online retail company is looking to interpret its data to help make key business decisions. I want you to use exploratory data analysis on their transactional data, which contains information about customer purchases, including product details, quantities, prices, and timestamps. I'll explore and analyze this dataset to gain insights into the store's sales trends, customer behavior, and popular products in order to help data drive business decisions.

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
As the main objective of this Online Retail Project is to interpret real world data to make a key business decision, I proceeded with data cleaning and validation, addressing missing values, removing duplicates, and ensuring data consistency. For example, more than 5268 duplicate rows, so we must remove all the duplicate value from the data set. Before removing I had 541909 rows, but after removing the duplicates 536641 rows left. This process significantly improved data quality and reliability, leading to insightful visualizations that highlighted key findings include actionable insights derived from EDA informed strategic decisions.

### Screenshots
This is Bivariate distribution of UnitPrice and Quantity. This a higher concentration of data points at lower UnitPrices, suggesting that items with lower prices tend to have higher quantities sold or available. This shows the distribution of data points is not uniform across different price ranges, showing variability in how Quantity relates to UnitPrice. On the other hand, the Quantity tends to decrease as the UnitPrice increases. This indicates that fewer units are sold or available at higher prices, which is a common trend in many markets.
![Bivariate distribution of UnitPrice and Quantity](https://github.com/user-attachments/assets/bb3a87c7-23f5-4518-a753-30f295f56d4a)

![Heat map](https://github.com/user-attachments/assets/1d18ed60-a1b5-4a85-a849-0974206bb286)

From the graph below, UK has the highest sales volume by a significant margin. Investigate the factors contributing to this success, such as marketing strategies, product preferences, and distribution channels. lower sales countries can be improved by identifing and replicating successful strategies from the UK in other countries, especially those with lower sales volumes like Greece, Poland, and Israel.
![20 countries](https://github.com/user-attachments/assets/9efd4916-a77a-4baa-9c51-4e0cd8f8ec66)

The graph below shows sales of days in whole complete months. This shows sales fluctuate throughout the months, with multiple peaks and troughs. The shaded area around the line suggests consistent variability in sales, indicating a predictable pattern of sales fluctuations. It's notable also sales tend to decline towards the end of the month, which could be due to budget constraints or reduced consumer activity. Some great actionable insights from this graph can be focus marketing efforts around mid-month to capitalize on higher sales volumes, and considering running promotions during low-sales days to boost activity and smooth out fluctuations.
![Busiest days by all month in terms of sales](https://github.com/user-attachments/assets/f5a74254-6891-4e9a-8690-6584dd12e196)

![Sales trend over the year](https://github.com/user-attachments/assets/40344dd2-bf46-4c43-83ba-4759cd6aa408)

From the graph below, there are noticeable peaks and troughs in sales for different countries, indicating seasonal trends. For example, some countries might experience higher sales during certain months, possibly due to holidays or seasonal demand. No single country consistently outperforms others throughout all months which shows that the market dynamics vary significantly across regions. In addition, there is similar sales which can be seen the dense overlapping of lines in the middle section of the graph, this indicates that many countries have similar sales figures during certain months which could imply a common market trend or external factor affecting multiple regions simultaneously. Lastly, some countries show sharp increases or decreases in sales during specific months. These could be due to promotional activities, economic events, or other significant factors impacting sales.
![Sales trend of countries by month](https://github.com/user-attachments/assets/2c4f5e1d-2e89-4042-a960-0b146246694d)

### Approach
In my online retail project, I began by installing and loading essential Python packages such as matplotlib, pandas, numpy, and seaborn to facilitate data analysis and visualization. Then I imported the datasets using pandas and proceeded with data cleaning and validation, addressing missing values, removing duplicates, and ensuring data consistency. Through exploratory data analysis (EDA), we utilized pandas and seaborn to generate descriptive statistics and visualizations, uncovering patterns, trends, and anomalies. For instance, most of the colums have zero missing values except Description and CustomerID variables. 0.27% and 25% of rows are missing value both columns respectively. To handle this issue, there is two options, either dropping or filling the missing entries. I used drop method for Description column to handle missing value because the data type of this variable is object which is suitable to fill, and the number missing values are small compared to the length of the data. The case of CustomerID column, this column gives special meaning in the data. The missing values may be are non-registered customer considering new customers. It's also important to not forget the fact that this column can be used to classify customer loyalty. I'll not fill the missing values in this column also not drop because of mass missing values (135037 rows are missing). So I'll mask the missing values in this column and data for further exploring. This significantly improved data quality and reliability, leading to insightful visualizations that highlighted key findings. The actionable insights derived from EDA informed strategic decisions, ultimately enhancing data-driven decision-making and contributing to better business outcomes.


### Conclusion 
my online retail project demonstrated the power of data analytics and visualization in driving business success. By installing and utilizing essential Python packages, cleaning and validating data, and conducting thorough exploratory data analysis, I able to uncover valuable insights that informed strategic decisions. This comprehensive approach not only improved operational efficiency and customer satisfaction but also positioned the business for sustained growth and success in the competitive online retail market.
