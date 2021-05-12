# Sales-Forecasting-Using-LSTM

Introduction to the Problem :
 
Data Source : It was a sample dataset from ERP & CRM. Then we merged and transformed the data using business data integration logic. The idea was to come at daily level dataset for the booking which was captured in Sales Amount Column.

Once we have developed the dataset, it was ranging from 2016 to 2018. It in the Beginning there were 23 columns and 387032 rows. Below is summary/list of the important columns

Table from other docx

We have many categorical variables as well for e.g. geography which is continent based, and nation based. Forecasting at the aggregated level( for all the regions) would not make sense. Because, forecasting at aggregated would give less context to the sales amount column, we wanted to be for specific to our forecasting problem

So, Idea is to use LSTM deep Learning model to forecast at a region-based level. 
