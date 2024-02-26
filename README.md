

# Project Title: Retail Sales Analysis 🛒📊

- **Author:** Szymon Swiezy
- **Email:** szymon.swiezy1@gmail.com
- **Website:** www.datascienceportfol.io/szymonswiezy
- **LinkedIn:** www.linkedin.com/in/szymon-świeży


The objective of this project is to analyze sales and promotional data from a sampling of stores over a period of 156 weeks, spanning from January 2009 to December 2011. The data includes various metrics related to sales, promotions, and store characteristics.
The aim of the project is also to demonstrate how Python and various libraries can be utilized for analysis purposes.



## Introduction 📖

In today's competitive retail landscape, understanding sales trends and the effectiveness of promotional strategies is crucial for retailers to optimize their marketing efforts and enhance profitability. This project aims to delve into the sales and promotional data of a selection of stores to uncover insights that can drive strategic decision-making.

By analyzing sales metrics such as total spend, units sold, and average weekly baskets alongside promotional factors like in-store displays and temporary price reductions, we aim to identify patterns and trends that influence consumer purchasing behavior. Additionally, we will explore how store attributes such as store size, location, and store appeal impact sales performance.

Through this analysis, we seek to provide actionable recommendations to retailers on how to optimize their promotional strategies, enhance store performance, and ultimately drive revenue growth.


The entire analysis is available in the [file](https://github.com/SimonAnalyst/Python_project/blob/main/Retail%20Sales%20Analysis.ipynb).



## Data Sources 📂

The data for this project is sourced from three CSV files containing information on various variables:

Store Lookup Table:

- ADDRESS_CITY_NAME: City where the store is located
- ADDRESS_STATE_PROV_CODE: State where the store is located
- AVG_WEEKLY_BASKETS: Average weekly baskets sold in the store
- MSA_CODE: Metropolitan Statistical Area code, representing a geographic region with a high core population density and close economic ties throughout the surrounding areas
- PARKING_SPACE_QTY: Number of parking spaces in the store parking lot
- SALES_AREA_SIZE_NUM: Square footage of the store
- STORE_APPEAL: Retailer's designated store appeal
- STORE_NUM: Store number
- 
Products Lookup Table:

- MANUFACTURER: Manufacturer of the product
- CATEGORY: Category of the product
- DESCRIPTION: Description of the product
- SUB_CATEGORY: Sub-category of the product
- UPC: Universal Product Code, a product-specific identifier
- PRODUCT_SIZE: Package size or quantity of the product

Data Table:

- BASE_PRICE: Base price of the item
- DISPLAY: Indicator if the product was a part of in-store promotional display
- FEATURE: Indicator if the product was in an in-store circular
- HHS: Number of purchasing households
- PRICE: Actual amount charged for the product at shelf
- WEEK_END_DATE: Week ending date
- SPEND: Total spend (i.e., sales)
- TPR_ONLY: Indicator of temporary price reduction only
- UNITS: Units sold
- VISITS: Number of unique purchases (baskets) that included the product


## Conclusions 📋


- Promotions result in a sales surge of **146% to 267%**.
- The selection of a particular promotion matters only for the product **Bag Snacks**, where opting for **in-store promotion** is advisable.
- The largest increase in sales due to promotions was observed for **Frozen Pizza** and **Cold Cereal**.
- The highest sales in terms of both quantity and value were recorded for the **Cold Cereal** product.
- The highest sales per unit were for **Frozen Pizza**.
- The state with the highest sales is **Ohio**.
- For the **Cold Cereal** product, it can be noticed that the subproduct named **"All family"** sells the most, followed by **"Kids"**.
- The top manufacturers in terms of sales are **Private Label**, **General Mills**, and **Kellogg**.
- The stores with the highest sales are **Houston**, **Anderson Towne Center**, and **Middletown**.
- Large stores with an area of over **60,000 square feet** sell twice as much merchandise as small stores with an area up to **35,000 square feet**. This applies to all products.
- **Oral Hygiene Products** and **Frozen Pizza** have the widest price range, with the latter also being the most expensive.
- It is worth investigating why there was a significant drop in sales in **March/April 2010**; further analysis is needed.
- Sales of **Cold Cereal** and **Frozen Pizza** were highly irregular depending on the period, whereas sales of **Bag Snacks** and **Oral Hygiene Products** were more stable.
- The implementation of promotions resulted in approximately a **300% increase** in product sales.

