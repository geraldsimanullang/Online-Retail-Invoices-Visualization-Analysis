# Visualization and Analysis of an Online Retail Invoices Dataset
In this project I conducted **visualization** and **analysis** on an online retail transaction dataset. 

The data I used is sourced from **UC Irvine Machine Learning Repository** and is referred to as the "**Online-retail**" dataset.  
You can access this dataset here --> [Data Source](https://archive.ics.uci.edu/dataset/352/online+retail)  
The analysis was performed using **Jupyter Notebook**. To view the complete code, please click here --> [Complete Code](https://github.com/geraldsimanullang/Online-Retail-Invoices-Visualization-Analysis/blob/main/Online%20Retail%20Invoices%20Analysis.ipynb)

Now, let's begin.

## Dataset Information
**InvoiceNo**: Invoice number, a 6-digit integral number uniquely assigned to each transaction.  
**StockCode**: Product (item), a 5-digit integral number uniquely assigned to each distinct product.  
**Description**: Product (item) name.  
**Quantity**: The quantities of each product (item) per transaction.  
**InvoiceDate**: Invoice Date and time, the day and time when each transaction was generated.  
**UnitPrice**: Unit price, Product price per unit in sterling.  
**CustomerID**: Customer number, a 5-digit integral number uniquely assigned to each customer.  
**Country**: Country name, the name of the country where each customer resides. 

## Data Preprocessing
Before performing visualization and analysis, this dataset needs to be preprocessed first. The preprocessing processes include:  
1. Handling non-positive value in Quantity and Unitprice value
2. Handling Description ambiguity for every StockCode
3. Converting InvoiceDate data type

## Visualization & Analysis  
### Sales Analysis
**How is average gross sale by day of the week?**

![average gross sales by day of the week](https://github.com/geraldsimanullang/Visualization-and-analysis-of-an-online-retail-invoices-dataset/assets/154493278/70b37889-a3a6-4589-a4a0-745e20880601)

**How many items is sold each month?**
![items sold each month](https://github.com/geraldsimanullang/Visualization-and-analysis-of-an-online-retail-invoices-dataset/assets/154493278/8aadcfae-0437-408e-abf2-404812934b94)


**Then how is monthly gross sales?**
![monthly gross sales](https://github.com/geraldsimanullang/Visualization-and-analysis-of-an-online-retail-invoices-dataset/assets/154493278/d6610f86-49f2-405b-8933-71897b245d72)

### Product Analysis
![top product on sept to nov](https://github.com/geraldsimanullang/Visualization-and-analysis-of-an-online-retail-invoices-dataset/assets/154493278/f30e3edd-924d-4007-9c45-e402955a469e)
