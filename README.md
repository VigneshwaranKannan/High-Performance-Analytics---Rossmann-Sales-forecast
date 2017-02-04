Rossmann operates over 3,000 drug stores in 7 European countries. For such a vast organization, the volume of sales data is immense which opens up great opportunities to analyze and forecast the sales. Rossmann’s dataset contains sales data and stores information from 1,115 stores across Germany.
Store sales are influenced by several factors, including promotions, competition, school and state holidays, seasonality, and locality. Sales forecasting will help the organization to perform better in the near future and work on their shortcomings in a particular area. By analyzing the customer data, we can forecast sales and take decisions to improve customer experience which is also a critical factor to focus on as an organization. Reliable sales forecasts enable store managers to create effective staff schedules that increase productivity and motivation.
Our analysis includes the below points:
•	We explored the data set and did basic preprocessing disregarding few data fields as they were not helpful in predicting the target.
•	Created attribute view and analytic view using SAP HANA Modeler.
•	As part of the detailed analysis, we came up with four different hypothesis using different measures with the dataset and verified the same.
•	To forecast sales for a set of Rossmaan stores we used SAP Predictive Analytics and partitioned the date as per the below criterion:
  o	Training: 50%
  o	Validation: 30%
  o	Testing: 20%
•	We used Multiple Linear Regression and generated the regression equation which indicated which variable contributes more to the sales and which is negatively related.
•	Based on the store ID, the predicted sales for a particular store can be found. These results indicate whether a particular store can remain open or should be closed to avoid loss.
