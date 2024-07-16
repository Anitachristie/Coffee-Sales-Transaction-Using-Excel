# Coffee Sales Analysis Using Excel
#### A sales transaction project carried out in Microsoft Excel on data cleaning and gathering, use of Excel functions (such as IF, VLOOKUP,INDEX,MATCH), Pivot tables, Pivot charts and a dashboard

## Table of Content
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Excel Utilization for Data Management and Visualization](#excel-utilization-for-data-management-and-visualization)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)

### Project Overview
This sales analysis project aims to provide insights into the sales performance of a coffee shop from 2019-2022. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendation and gain a deeper understanding of the company's performance.

### Data Source
The primary dataset used for thisanalysis is the "CoffeeOrdersData" file, containing detailed information about eac sale made by the company.

### Tools
- Excel

### Excel Utilization for Data Management and Visualization
We utilized Excel for:
1. Table population using functions such as IF, VLOOKUP, INDEX, and MATCH functions.
2. Date and Currency formatting.
3. Removing duplicates or blank cells.
4. Generating pivot tables and pivot charts to visualize our findings.
5. Compiling all charts and filters into a cohesive dashboard.

### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:
- What is the overall sales trend?
- Which customers are top 5?
- What are the sales per country?

### Data Analysis
```Excel
=VLOOKUP(C2,customers!$A$2:$B$1001,2,FALSE)
=INDEX(products!$A$1:$G$49,MATCH($D2,products!$A$1:$A$49,0),MATCH(I$1,products!$A$1:$G$1,0))
```


