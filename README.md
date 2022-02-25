# Some screenshots of the project
![exp](https://user-images.githubusercontent.com/50864725/155724097-bc9e10da-a822-4770-9aca-9636b64b0a79.PNG)
![med](https://user-images.githubusercontent.com/50864725/155724114-0973dadd-74f6-4175-a82e-14d75925c546.PNG)
![avg](https://user-images.githubusercontent.com/50864725/155724150-7c0b1597-5cb0-41e5-b127-10669bc24ab8.PNG)
![available](https://user-images.githubusercontent.com/50864725/155724161-3b45bb3e-2bae-4ba2-8a4b-c7132cce3425.PNG)

# Prerequisites:
- Python 3.x
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook (or any IDE that accepts .ipynb files)

# How to run:
It should be noted that the project can be viewed by simply clicking the .ipynb file in the repo. But should you wish to run it:
- Download the repo and unzip the data folder into the same folder as the .ipynb file
- Run all cells

# Description of the data:
Data includes country, locality, market, goods purchased, price & currency used, quantity exchanged, and month/year of purchase.

- adm0_id: country id

- adm0_name: country name
- adm1_id: locality id
- adm1_name: locality name


- mkt_id: market id
- mkt_name: market name
- cm_id: commodity purchase id
- cm_name: commodity purchased
- cur_id: currency id
- cur_name: name of currency
- pt_id: market type id
- pt_name: market type (Retail/Wholesale/Producer/Farm Gate)
- um_id: measurement id
- um_name: unit of goods measurement
- mp_month: month recorded
- mpyear: year recorded
- mpprice: price paid
- mp_commoditysource: Source supplying price information

# Food-EDA
Exploratory Data Analysis and Data Visualization was carried out on Global Food Data from Kaggle in order to gather insights. The various questions answered were as follows:
- What were the top 20 commodities sold globally over the years?
- What was the average price of all commodities sold in Kenya every year from 2006 to 2021?
- Has there been an increase or decrease in this price over the years?
- What was the median price of all commodities sold in Kenya every year?

# Insights
This is what was discovered from the data:
- The top 3 commodities sold globally were Millet, Imported Rice and Maize, respectively.
- The average price of all commodities sold in Kenya has doubled from the year 2006 to 2019. This could be attributed to a number of factors such as: inflation, an increased demand in the products or even higher production, storage and transportation costs.  
- The average price of all commodities sold in Kenya saw a sharp decline from the year 2019 to 2021. This could be because of reduced importation of more expensive commodities to mitigate losses brought about by the pandemic. Or there could also just be less data in the latter years. 
- The median prices of all Kenyan commodities by year are very close to the 1st Quartile (Q1). There are also numerous outliers each year that tend to have a much higher price compared to the median. This shows us that some commodities are much more expensive that others. 
