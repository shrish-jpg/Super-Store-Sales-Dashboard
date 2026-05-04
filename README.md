<center>

#  🛒 Super Store Sales Full Data Analysed

</center>
____________________________________________________________________________________________________________________________________


## 📌 Project Overview
This project of Super Store Sales Dashboard is made to analyze the performance of sales in USA by per state, this dasahboard is made to know in which state there is more demande for which product and at which quantity. 

The dashboard is designed with an executive-level mindset, focusing on clarity, reduced cognitive load, and actionable insights.
____________________________________________________________________________________________________________________________________

## 🎯 Business Objectives
* To identify which state is having top sales
* To identify the payment is comming through which sengment
* Analysing which month was the best and will be the best
* TO get which is the best performing item in which state

____________________________________________________________________________________________________________________________________
## 📊 Key KPIs
* Total Sales of 1.6 Milion
* Total Profit of 175K
* Average Shipment Days 4
* Quantity 22K

____________________________________________________________________________________________________________________________________

## 📈 Dashboard Highlights
### 1. Sales by Segments
* In this it has been show that it has been purchased by consumer, Corporate or Home office
* In dash board it has been properly shown how much persentage is beeen done by which segment

### 2. Sales by Region
* USA has 4 main reagions which are North, South, East and West
* And in this dashboard it has been properly byfercated each division to show proper date of sales


### 3. Sales by Month and Years
* Every one knows sale which happens it never hapens the same year
* So, in this Dashboard we have made the comparision about the last year and the current years sales data

### 4. Profit by Year and Month
* Profit is never the same in any aspects of business it never depends on the sales but it has different aspest to major
* AND we have properly displayed proper information for 2 years and compared both years profit

### 5. Forecast
* Forecasted upcoming 15 days sales, using past data
* Used past 2 years data to predict next 15 days data to prevent losses and have more knowledge about upcoming sales

## 📸 DashBoard Preview 

### 📊 Power BI dashboard overview

<img width="1372" height="791" alt="image (1)" src="https://github.com/user-attachments/assets/ab9ba480-0329-4f50-b190-fae3f9033dee" />

### 💰 Dashboard of forecast

<img width="1375" height="791" alt="image (2)" src="https://github.com/user-attachments/assets/64c7d0d5-055e-416c-9f06-deed871dfb48" />

## Formulas used in Power BI to get more insites in this project

### * When there are more than 1 order on 1 day then thene it becomes bit diffecult to calculate the total ordered amount then we have to persolally add them so to prevent them I used DAX function hear which gives me an total amount of orders which where made in a single day

Salesforecast = SUMMARIZE('Sheet1', 'Sheet1'[Order Date], " Total Sales", SUM(Sheet1[Sales]))


### * I was willing to show average days took to diliver package and there was no colum in the table which will reprecent or show days to deliver any product then to get those days i make an column which shows days took to deliver the poduct and using thoes days I made average of them and make an key KPI


AvgDelivery = DATEDIFF('Sheet1'[Order Date],'Sheet1'[Ship Date],DAY)

## 👤 Author
### Shrish Mali Aspiring Data Analyst | SQL • Power BI • Data Visualization

