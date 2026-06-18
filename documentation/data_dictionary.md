# Data Dictionary

This file explains the columns used in the sales performance and demand pattern analysis project.

| Column Name             | Description                                                             |
| ----------------------- | ----------------------------------------------------------------------- |
| Invoice_Date            | Date on which the sales transaction was recorded                        |
| Fiscal_Year             | Financial year mentioned in the original dataset                        |
| Business_Partner_Code   | Unique code assigned to the dealer or business partner                  |
| Business_Partner_Name   | Name of the dealer or business partner involved in the transaction      |
| Transaction_Type        | Type of transaction recorded in the dataset                             |
| Invoice_Number          | Unique invoice number for the sales transaction                         |
| Order_Number            | Order reference number connected to the invoice                         |
| Product_Type            | Type or broad classification of the product                             |
| Product_Code            | Unique code assigned to each product                                    |
| Product_Description     | Description or name of the product sold                                 |
| Total_Quantity_Sold     | Total number of units sold in the transaction                           |
| Total_Sales_Value_(INR) | Total sales value generated from the transaction in Indian Rupees       |
| Sub_Category_Code       | Code representing the product sub-category                              |
| Item_Group              | Product grouping used for classification and analysis                   |
| Branch_Location         | Branch location responsible for the transaction                         |
| State_Region            | State or regional grouping related to the transaction                   |
| Product_Category        | Main category of the product, such as Grinder, Cooker, Mixie, etc.      |
| Product_Variant         | Product variant or specific product type within the category            |
| Month_Name              | Month name derived from the invoice date                                |
| Month_Number            | Month number derived from the invoice date                              |
| Quarter                 | Quarter derived from the invoice date                                   |
| Fiscal_Year_Calc        | Financial year calculated from the invoice date                         |
| Price_Per_Unit          | Sales value per unit, calculated using sales value and quantity         |
| Transaction_Flag        | Classification of transaction type, such as sales or return             |
| FY_Month_Order          | Month order field used for sorting financial year months correctly      |
| State_Full_Name         | Full state name derived from state or region code                       |
| Demand_Classification   | Classification of product demand based on sales performance and pattern |
