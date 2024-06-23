# <center> Marketing Analysis and RFM Rates with Correlation Metrics </center>

## Please use here to navigate Tableau Public to experience the dashboard in real-time. Also it is important to use it yourself since the outcomes below are samples.
<a href="https://public.tableau.com/app/profile/baris.yalcin6208/viz/MarketingDashboardandRFMRatesAnalysis/MarketingAnalysis"> Marketing Analysis and RFM Rates Tableau Dashboard </a>

### Objective
The objective of this project is to enhance our marketing strategies by conducting a comprehensive marketing analysis and calculating Recency, Frequency, and Monetary (RFM) rates. By leveraging SQL, Snowflake, Python, and Tableau, we aim to gain deep insights into customer behavior and segment our customers effectively to drive targeted marketing campaigns and increase overall business revenue.

The first page of the dashboard is designed to analyze the required data to determined the total number of customers, demographics of customers, total spent, income type and RFM analysis.

![Marketing Analysis](https://github.com/borisyalcin/marketing-rfm-analysis/assets/155834534/bbc42578-9554-46df-8a6e-e6480972e39a)

### Tools and Technologies
* SQL: Used for data extraction, transformation, and loading (ETL) processes.
* Snowflake: Serves as the cloud data warehousing solution to store and manage large datasets.
* Tableau: Used for data visualization, enabling interactive dashboards and reports.

### Outcomes
![Marketing Analysis (1)](https://github.com/borisyalcin/marketing-rfm-analysis/assets/155834534/32ff7252-c709-4dd3-a00c-1f48a4d9557a)

#### Education:
Customers are mostly graduated by Bachelors degree and following degrees are PHD and Masters. High School graduates size the least.
#### Maritial Status:
High majority of customers are Married followed by number of people who are Together and Single. There are very less people who are either divorced and widow.
#### Income vs Purchase:
Income and Store Purchases are postively corelated.(More income leads to more store purchases).
#### Kids:
People without children tend to have higher salaries than those with children, which contradicts the general assumption that more kids require more money and people want to make more money. Additionally, as the number of children increases, people tend to earn less income; for example, those with one child typically make more than those with two or three.
#### Kids vs Income:
A negative correlation is seen between income, total expenditure, and the number of children; those with no children tend to earn more and spend more, while expenses decrease as people begin having kids. This is evidenced by the fact that those with three children spend much less than those with zero or one child.
#### Kids vs Deals:
It is intriguing to observe that individuals with no children tend to purchase fewer deals despite earning more and spending more. Conversely, people with one or two kids, who earn less and spend less, tend to take advantage of deals. Lastly, those with three or more children make less money, spend much less, and consequently, buy fewer deals.
