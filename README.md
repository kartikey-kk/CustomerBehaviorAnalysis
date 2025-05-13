# Customer Behavior Analysis

This project analyzes a dataset containing customer behavior data, including total spending, average purchase value, visit frequency, and buyer type classification.

## Dataset Columns
- **total_spent**: Total amount of money a customer has spent.
- **avg_purchase_value**: Average value of each purchase.
- **visits_per_month**: Number of visits per month.
- **buyer_type**: Category of buyer (e.g., 'bargain_hunter', 'premium_buyer').

## Analysis Performed
1. Summary Statistics
2. Correlation Matrix
3. Visualizations:
   - Distribution Plots for all numerical variables
   - Box Plots grouped by `buyer_type`
   - Scatter Plot of Total Spent vs Visits per Month

## Outputs
- `summary_statistics.csv`
- `correlation_matrix.csv`
- `distribution_plots.png`
- `boxplots_by_buyer_type.png`
- `scatter_plot_total_spent_vs_visits.png`

## Requirements
- Python 3.x
- pandas
- seaborn
- matplotlib
