# Amazon Sales Data Analysis Project

## Objective

The objective of this project is to analyze Amazon sales data to identify trends, key performance metrics, and actionable insights that can enhance 
business decision-making. The goal is to optimize sales performance and improve customer satisfaction.

## Data Overview

### Dataset Description

- **Source**: Kaggle
- **Columns**:
  - **Category**: Type of product (String)
  - **Size**: Size of the product (String)
  - **Date**: Date of the sale (Date)
  - **Status**: Status of the sale (String)
  - **Fulfilment**: Method of fulfilment (String)
  - **Style**: Style of the product (String)
  - **SKU**: Stock Keeping Unit (String)
  - **ASIN**: Amazon Standard Identification Number (String)
  - **Courier Status**: Status of the courier (String)
  - **Qty**: Quantity of the product (Integer)
  - **Amount**: Amount of the sale (Float)
  - **B2B**: Business to business sale (Boolean)
  - **Currency**: The currency used for the sale (String)

### Known Issues

- Missing values in some columns.
- Duplicates found in a few rows.
- Certain product categories have higher cancellation rates.

## Insights and Recommendations

### Sales and Order Trends

- **Low-Price Products**: Most orders are in the lower price range, showing a preference for affordable products.
- **High-Value Purchases**: High-value purchases are relatively rare, suggesting that premium pricing strategies may need improvement.
- **Single-Unit Purchases**: A large number of orders consist of single-unit purchases, indicating that bulk-buying is not very common.

### Order Cancellations and Returns

- Certain product categories have higher cancellation rates, possibly due to stock unavailability, pricing concerns, or unclear product descriptions.
- Orders fulfilled by third-party sellers have more cancellations and returns compared to Amazon-fulfilled orders, pointing to logistics or service issues.

### Fulfillment and Logistics

- Amazon-fulfilled orders account for a large share of total sales, reinforcing customer trust in Amazon’s logistics network.
- Merchant-fulfilled orders show a higher rate of delays and cancellations, suggesting inefficiencies in third-party fulfillment processes.

## Suggested Improvements

### Pricing Strategies

- Adjust pricing for high-value products by testing discounts, bundles, or loyalty rewards.
- Use demand-based pricing models to maximize conversions.

### Inventory Management

- Improve stock forecasting to ensure availability for high-demand products.
- Reduce cancellations by keeping real-time track of stock levels.

### Fulfillment Processes

- Encourage sellers to opt for Fulfilled by Amazon (FBA) for better delivery efficiency and customer satisfaction.
- Provide third-party merchants with guidelines and resources to improve their fulfillment operations.

## Conclusion

### Key Takeaways

- Most sales come from lower-priced products, while high-end items have limited traction.
- Merchant-fulfilled orders tend to have more cancellations, affecting overall customer satisfaction.
- Amazon’s fulfillment system remains the preferred option due to its reliability and efficiency.

### Future Scope of Analysis

- Segment customers based on buying patterns to personalize recommendations and marketing strategies.
- Analyze how discounts and promotions influence repeat purchases and customer retention.
- Study how product ratings and reviews correlate with return rates to identify potential quality issues.

### Potential Areas of Further Study

- Use A/B testing to measure how price changes impact conversions.
- Analyze seasonal trends to improve inventory planning.
- Develop predictive models to identify orders with a high cancellation risk before they happen.

## References & Appendix

### Data Sources

- The dataset used for this analysis was sourced from Kaggle: **Amazon Sale Report Dataset**.

### Additional Resources and Tools Used

- **Python libraries**: Pandas, NumPy, Matplotlib, Seaborn.
- **Jupyter Notebook** for data analysis and visualization.

### Additional Resources

- Amazon Seller Central documentation
- Kaggle forums
  
