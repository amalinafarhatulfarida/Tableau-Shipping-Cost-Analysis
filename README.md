**Tableau Visualization: Shipping Costs by Product**

**Overview**
This Tableau Public project visualizes the Shipping Costs by Product, comparing two measures:

    1. Shipping Baseline - The actual shipping cost under current conditions.
    2. Shipping What-If - A hypothetical or projected shipping cost based on certain adjustments.

The visualization uses a Combination Chart to present a dual-axis view with:

    1. Bar Chart (Shipping Baseline).
    2. Circle Plot (Shipping What-If).

This combination allows for easy comparison of the two metrics across products.

**Data Sources**
The analysis is based on data from the following CSV files:

    1. fact_sales.csv: Contains transaction-level data including shipping costs.
    2. dim_customers.csv: Includes customer-related information such as order state, postal code, and location coordinates.
    3. dim_products.csv: Holds product-related attributes like description, stock codes, landed costs, and weights.

**Key Features**
1. Dual-Axis Visualization:
    Shipping Baseline (bars) and Shipping What-If (circles) share a common Product Description axis.
    Each axis is scaled appropriately to highlight variances.

2. Interactivity:
    The chart supports dynamic filtering and interaction based on product descriptions.

3. Comparative Analysis:
    The project allows easy evaluation of the difference between baseline and hypothetical shipping costs.
