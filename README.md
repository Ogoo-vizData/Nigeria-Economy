# Nigeria-Economy
### An Overview of Nigeria major Economic sectors
This project is based on a dataset gotten from World bank data base. During this project different tools were used on to archive the analytical insight and dashboard.

## Data Sources
The primary dataset used for this project is "World development indicators" this contains data about Nigeria from 1990-2020

## Tools
Dax queries, Excel - Data cleaning.
Power BI - Data transformation and visualization.

## Data Cleaning/Preparation
This data required a lot of data cleaning as the raw data set wasn't workable with out critical modifications and cleaning.
In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection: this involves a quick scroll through the data while marking necessary changes and modifications to be done on excel.
- Data cleaning and formatting: unnecessary columns were deleted along side with empty column and duplicates
- Data transposition: The rows of the data was converted into column using the transpose 

## Exploratory Data Analysis(EDA)
- In power bi we used the transform data provision to extract the month from the date using 'MonthName = FORMAT('Table'[DateColumn], "MMMM")', then sorted it by the month number column.
- Most columns were adjusted to remove decimal places, as there were no significant numbers after the decimal point.
- The dataset was moved to Power BI for further data transformation and visualization.
- Using charts and graphs, various insights were visualized, such as the neighborhoods with the External total debt, total foreign investment, inflation, GDP e.t.c 

## Observations
- External Debt Analysis: At $98,335,333,958.00, 2022 had the highest External debt stocks and was 193.90% higher than 1990, which had the lowest Average of External debt stocks at 33,458,483,418.00.
- Population Growth: ﻿Across all 11 DATE, Average of Population, total ranged from 95,214,257.00 to 218,541,212.00 in 2022.
- Foreign Investment Trends: Foreign investment fell drastically to $186,792,429 compared to it's highest point at 2014 with $574,183,763,412.
- Inflation Rates: Inflation was at the highest in 2000 at 22.67%.
- Immigration rate: Inflation went continuously downhill, with the lowest being 2014.

## Conclusion
The project successfully utilized advanced data analysis and visualization techniques to provide a comprehensive overview of Nigeria's economic trends over three decades. The insights gained can inform policy decisions and strategic planning for economic development.
