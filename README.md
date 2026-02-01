## Power Bi Amazon Laptop Sales Dashboard
Developed an interactive Power BI dashboard analyzing Amazon laptop sales, starting with data cleaning and transformation in Power Query to handle missing values, standardize brands, and ensure data quality. The dashboard identifies top-performing brands, high-revenue product segments, and sales to stock demand.

Source: Kaggle Dataset
File name: amazon-product-sales.pbix
Tools: Power BI (Power Query and M language)

## Data Cleaning and Transformation:
- Inconsistent naming and capitalization – standardized brand and model names.
- Numeric conversion – transformed columns such as RAM, price, and screen size into numeric values by removing units.
- Handling null values – replaced missing numeric entries with 0.
- Filtered empty model cells 
- Conditional columns – added a Price Range column to segment products into low, medium, and high price tiers.

## Data Visuals and Analytics:
_KPIs_
- Total Sales
- Number of products sold
- Top selling model
- Top selling brand

_Charts_
- Pie charts for segmentation of price (low, medium, high).
- Bar chart for model sales.
- Pie chart for brand sales.
