# Superstore Sales Data Analysis

## Project Overview

This project aims to perform an analysis of the Superstore sales data to understand trends and performance. The goal is to provide business insights that can help improve sales strategies.

## Dataset Information

The Superstore sales dataset contains information about sales transactions at a retail store. The data includes attributes such as order date, product category, sales amount, and region.

- **superstore_sales.csv**: The dataset file containing sales data.

## Objectives

- Analyze sales trends over time
- Identify best selling products
- Analyze regional performance

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Contains the Jupyter Notebook with the analysis.
- `README.md`: Project documentation.
- `requirements.txt`: List of required Python libraries.

## How to Run

1. Clone the repository: `git clone https://github.com/yourusername/Superstore_Sales_Analysis.git`
2. Navigate to the project directory: `cd Superstore_Sales_Analysis`
3. Install the required libraries: `pip install -r requirements.txt`
4. Open the Jupyter Notebook: `jupyter notebook notebooks/Sales_Analysis.ipynb`

## Summary of Findings

### Sales Trends Over Time

The summary statistics for sales over time provide several key insights into the sales performance:

- **Count**: The dataset includes sales data for 48 months.
- **Mean**: The average monthly sales amount to $163,231.83.
- **Standard Deviation**: The variability in monthly sales is relatively high, with a standard deviation of $55,285.70.
- **Min and Max**: The lowest monthly sales recorded is $88,803.00, while the highest is $319,829.00.
- **Quartiles**:
  - 25th Percentile (Q1): $122,076.50
  - Median (Q2): $157,070.50
  - 75th Percentile (Q3): $196,361.50

These statistics indicate that while the average monthly sales are substantial, there is significant fluctuation in sales figures, suggesting potential seasonality or external factors influencing sales performance.

### Best Selling Products

The analysis of the top 10 best selling products reveals the following:

1. **Eldon File Cart, Single Width**: $31,319.00
2. **Rogers File Cart, Single Width**: $22,645.00
3. **Tenex File Cart, Single Width**: $20,778.00
4. **Smead File Cart, Single Width**: $20,775.00
5. **Office Star Executive Leather Armchair, Adjustable**: $19,355.00
6. **Fellowes Lockers, Industrial**: $19,172.00
7. **Smead Lockers, Industrial**: $18,648.00
8. **Hewlett Copy Machine, Color**: $16,849.00
9. **Rogers Lockers, Blue**: $16,494.00
10. **Fellowes Lockers, Wire Frame**: $16,470.00

The dominance of file carts and lockers in the top-selling products indicates a high demand for storage solutions among customers. Additionally, high-value items such as executive chairs and copy machines also contribute significantly to sales.

### Regional Performance

The regional performance analysis shows the total sales for each region:

1. **Central**: $1,806,638.00
2. **South**: $1,031,101.00
3. **North**: $790,546.00
4. **Oceania**: $625,382.00
5. **EMEA**: $575,562.00
6. **Africa**: $538,115.00
7. **Southeast Asia**: $532,172.00
8. **North Asia**: $453,686.00
9. **West**: $424,173.00
10. **Central Asia**: $389,506.00
11. **East**: $366,492.00
12. **Caribbean**: $251,441.00
13. **Canada**: $50,314.00

The Central region leads in sales, followed by the South and North regions. This indicates that these regions have a larger customer base or higher demand for the store’s products. The significantly lower sales in regions like the Caribbean and Canada suggest potential areas for growth and market penetration.

### Conclusions

Based on the sales analysis, several key insights can be drawn:

1. **Sales Trends Over Time**:
   - There is considerable variation in monthly sales, indicating potential seasonality or external factors affecting sales performance.
   - The average monthly sales are healthy, but the high standard deviation suggests that sales strategies need to account for these fluctuations.

2. **Best Selling Products**:
   - Storage solutions such as file carts and lockers are the top-selling products, indicating strong demand in this category.
   - High-value items like executive chairs and copy machines also contribute significantly to overall sales, highlighting the importance of offering high-ticket items.

3. **Regional Performance**:
   - The Central, South, and North regions are the top-performing regions, suggesting a well-established customer base and strong market presence.
   - Lower-performing regions like the Caribbean and Canada represent opportunities for targeted marketing and sales strategies to boost performance.

### Business Insights for Improving Sales Strategies

1. **Address Seasonal Fluctuations**:
   - Implement targeted promotions during low sales periods to smooth out fluctuations and maintain a steady revenue stream.

2. **Capitalize on Best Selling Products**:
   - Increase inventory and marketing efforts for top-selling products, especially storage solutions, to maximize sales in these high-demand categories.

3. **Expand Market Penetration**:
   - Develop marketing campaigns and promotional activities aimed at regions with lower sales to increase market share and drive growth in underperforming areas.

By leveraging these insights, the business can optimize its sales strategies, enhance inventory management, and identify new growth opportunities to improve overall performance.

## License

This project is licensed under the MIT License.
