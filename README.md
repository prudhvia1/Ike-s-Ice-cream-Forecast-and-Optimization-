Project: Ordering and Stocking Optimization for Ike’s Ice Cream

Overview:

This project aims to optimize the inventory management system of Ike's Ice Cream, a franchisee located in Texas. Ike’s Ice Cream faces challenges such as frequent stockouts of certain flavors, especially seasonal ones, and limited freezer space, which leads to lost sales and customer dissatisfaction. The goal of this project is to develop a forecasting model and an order optimization tool to better manage inventory, minimize stockouts, and enhance customer satisfaction.

Project Objectives:

Develop a Forecasting Model:
Predict future demand for each ice cream flavor using various forecasting methods, including moving averages, linear regression, and exponential smoothing.
Tailor the forecasting approach to each flavor based on its sales pattern and accuracy metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared values.
Optimize Inventory Management:

Use the Excel Solver tool to create an optimal ordering strategy that minimizes the number of tubs in the freezer when a new order arrives while reducing the frequency of stockouts.
Develop an optimization model that considers freezer capacity, minimum order sizes, and forecasted customer demand to determine the ideal quantity of each flavor to order.

Methodology:

Data Preparation:
Analyze and clean sales data from 2021-2023 to remove any outliers or inaccuracies.
Format the data using R and Microsoft Excel, transforming it into long format and removing seasonal flavors for better analysis.
Replace missing data points using linear regression in Python.

Forecasting:
Test different forecasting methods (moving averages, linear regression, exponential smoothing) to determine the best model for each flavor.
Utilize historical sales data to forecast future demand for both non-seasonal and seasonal flavors.

Inventory Optimization:
Formulate an optimization strategy using the Excel Solver tool.
Set constraints based on freezer capacity (320-350 tubs), minimum order size (72 boxes), and forecasted demand.
Aim to minimize variance in the number of days to stock out while maximizing the number of boxes ordered per shipment.

Assumptions:
Sales data manually tracked is assumed to be accurate.
Non-seasonal flavors are always available for ordering.
Approximately 10-15% of the product may go to waste.
Future demand patterns are consistent with historical trends.
There are 5 seasonal flavors, subject to change.

Data:
Non-Seasonal Flavors: 21 flavors available year-round.
Seasonal Flavors: 5 flavors, with availability depending on the season.
Sales Data: Weekly sales data from March 2021 to the present.
Starting Inventory: Provided for current inventory levels of each flavor.
Waste Percentage: Estimated at 10-15%.

Deliverables:
Forecasting Model: Tailored predictions for each flavor's future demand.
Order Optimization Tool: An Excel-based solution that provides optimal order quantities for each flavor, considering constraints and objectives.

Technologies Used:
R: Data preparation, transformation, and cleaning.
Python: Handling missing data using linear regression and performing additional data analysis.
Microsoft Excel: Forecasting, data formatting, and inventory optimization using the Solver tool.

How to Run the Project:

Data Setup:
Ensure that all required datasets (2021-2023 weekly sales data) are correctly formatted and available in the designated folder.
Running the Forecasting Model:

Open the forecasting script in Python or R and run it to generate demand predictions for each flavor.
Optimization Model:

Open the Excel file with the optimization model.
Input the starting inventory and forecasted demand.
Run the Solver tool to get the optimal order quantities for each flavor.

Contributions:
This project was developed to support Ike's Ice Cream in improving its inventory management, reducing stockouts, and enhancing customer satisfaction. The project involves collaborative efforts in data analysis, forecasting, and optimization.
