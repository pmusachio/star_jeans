# Star Jeans
![logo.png](https://raw.githubusercontent.com/pmusachio/star_jeans/main/logo.png)

Star Jeans is an E-commerce that is entering the American men's jeans market, its strategy will be to keep the operating cost low and scale as they gain customers.

However, even with the entry product and the defined public, star jeans lacks experience in this fashion market and still does not know how to define things like price, type of pants and material for making each piece.

## Business Problem
- What is the best selling price for the pants?
- How many types of pants and their colors for the initial product?
- What are the raw materials needed to make the pants?

## Business Assumptions
- Pricing strategy can be defined based on the price of leading companies
- H&M and Macys are reference companys in the market

## Solution Strategy
- **What is the best selling price for the pants?**
    - Use of webscraping to extract data related to the product using competitors websites as a benchmark ['H&M'](https://www2.hm.com/en_us/men/products/jeans.html) and ['Macys'](https://www.macys.com/shop/mens-clothing/mens-jeans?id=11221&edge=hybrid)
    - Mount a database containing: id | product_name | product_type | product_color | product_price | exposure_days
    - Defines the schema and storage infrastructure ( SQLITE3 )
    - Build ETL and Script Scheduling Planning
    - Calculate the median price of competing sites by product, type and color in the last 30 days
    - Create Bar Chart with the median price of competitors products, by type and color
    - Deploy on Streamlit


- **How many types of pants and their colors for the initial product?**


- **What are the raw materials needed to make the pants?**


## Top Insights


## Business Results


## Conclusion


## Next Steps
