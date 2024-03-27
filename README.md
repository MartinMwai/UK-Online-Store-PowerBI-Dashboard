# UK-Online-Store-Dashboard
### Dashboard Link : [https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection](https://app.powerbi.com/links/2lrFu1KnpM?ctid=6ac7a1f4-5fb1-4153-bb4f-12d2020a1f7d&pbi_source=linkShare)

## Problem Statement
This dashboard helps the store to track their KPI on Total value, Avg Value per order and customer number. It also helps the store to see the months and days with high orders for proper planning and expectation on workload. From the dashboard the store can also see the different trend pattern from the different countries and the most common items odered.

The dashboard clearly shows the trend of different countries and can be used to plan on the expansion strategy.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & added a new calculated column "Value" by multiplying the "UnitPrice" and "Quantity" column
- Step 3 : Changed column types for "Value" and "InvoiceDate" column.
- Step 4 : It was observed that none of the columns had an errors but the description column had some blanks and I filtered out all the blanks.
- Step 5 : Duplicated the "InvoiceDate" and converted the date to a Day of week name.
- Step 6 : Duplicated the "InvoiceDate" and converted the date to a Day of week number to be used for sorting.
- Step 7 : From the clearned up data, created the report 

  


# Snapshot of Dashboard (Power BI Service)

<img width="931" alt="PowerBI Service Screenshot" src="https://github.com/MartinMwai/UK-Online-Store-PowerBI-Dashboard/assets/93153299/c51d1214-6bad-48ce-9863-aac0cd04cf73">

 
 # Report Snapshot (Power BI DESKTOP)

 
<img width="869" alt="PowerBI Desktop Screenshot" src="https://github.com/MartinMwai/UK-Online-Store-PowerBI-Dashboard/assets/93153299/f5253e64-d8d4-4bcf-afd8-97b2fe60ac4b">

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Total sales value = $9.75M

   Average sales value per order = $376.36 (2010- $369.86, 2011- $376.91)

   Total Order = 25.9k (2010-2.025k, 2011- 23.88K)

   Total Customers = 4.373k (2010-949, 2011- 4.245k)

   


           Across all the KPIs the store shows a growth in 2011 compared to 2010.
           
### [2] Country Value % Contribution

    1. United Kingdom - 84.0%
    2. Nertherlands   - 2.9%
    3. Eire           - 2.7%
    4. Germany        - 2.3%
    5. France         - 2.0%
    6. Australia      - 1.4%
    7. Switzerland    - 0.6%
    8. Spain          - 0.6%
    9. Belgium        - 0.4%
    10. Sweden        - 0.4%
    
  
  When getting this numbers I noticed that top 10 coutries by value contribution are all from Europe yet the store is suppling in America and Asia. With UK been their base country 84% of thier sales are in UK but there is potential  to grow to other courties to avoid over dependancy on one country.   
  
  ### [3] Country Customer count

  
    1. United Kingdom - 3951
    2. Germany        - 95
    3. France         - 88
    4. Spain          - 31
    5. Belgium        - 25
    6. Switzerland    - 22
    7. Portugal       - 20
    8. Italy          - 15
    9. Finland        - 12
    10. Austria       - 11
    
Interesting observation on this is Nertherlands and Eire appear in top 3 countries by value but are not in top 10 coutries by number of customers

 ### [4] Some other insights
 
 ### Oder by Month
 
 <img width="355" alt="Oder By Month" src="https://github.com/MartinMwai/UK-Online-Store-PowerBI-Dashboard/assets/93153299/8dd1ab1a-4871-43e9-baae-e8d3de92b310">
 
         From the chart, November show as the best selling month but note 2011 data was only till 10th Dec. Generaly Q4 the store gets more sells. 
 
 ### Order by Day
 
 <img width="330" alt="Order by Day" src="https://github.com/MartinMwai/UK-Online-Store-PowerBI-Dashboard/assets/93153299/deefb45f-b961-4ab2-b664-6590b05c786f">
 
         On Average Thursday & Tuesday are the best selling days with Saturday getting the least orders.
        
