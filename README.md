# CreditLens: Credit Card Usage & Analysis Dashboard

This Power BI Dashboard provides insights into credit card usage, customer spending behavior, and transaction patterns. The dashboard helps businesses understand customer segments, track key performance metrics, and make data-driven decisions.

## Key Features

- **Transaction Overview**: Visual representation of total transactions, transaction volume, and average transaction size.
- **Customer Segmentation**: Breakdown of customer segments based on spending patterns, credit limits, and usage frequency.
- **Spending Behavior**: Analysis of transaction types (e.g., retail, online, utilities) and spending trends over time.
- **Risk Analysis**: Identifies high-risk accounts based on unusual spending behavior, late payments, or over-limit transactions.
- **Credit Utilization**: Visualization of credit utilization rates across different customer segments.
- **Geographical Analysis**: Insights into spending trends based on regions or locations.

## Data Sources

- **Credit Card Transactions**: Historical transaction data for credit card accounts.
- **Customer Demographics**: Age, gender, income, and location data of credit card holders.
- **Account Information**: Data on credit limits, balances, and account statuses.
- **Risk Factors**: Late payments, over-limit accounts, and fraud risk indicators.

## Technologies Used

- **Power BI**: Main tool for creating interactive visualizations and reports.
- **SQL**: Used to clean and transform raw data for analysis.
- **Excel/CSV**: Data files used as inputs for the dashboard.

## Installation and Setup

### Prerequisites

- Install Power BI Desktop. You can download it [here](https://powerbi.microsoft.com/).
- Ensure you have access to the necessary data files (e.g., transaction data, customer data).

### Clone the Repository

```sh
git clone https://github.com/SakshamAggarwal101002/CreditLens.git
cd credit-card-analysis-dashboard
```

### Open the Dashboard

- Open the `.pbix` file in Power BI Desktop:
  
  ```sh
  open CreditLens.pbix
  ```

### Data Import

- Ensure that the dataset paths are correct.
- Refresh the data sources in Power BI to load the latest data into the dashboard.

### Customize

- Adjust filters and visuals according to the analysis you want to perform.

## Usage

- **Transaction Overview**: View total transactions, monthly trends, and top transaction categories.
- **Customer Segmentation**: Analyze different customer groups based on credit usage and spending frequency.
- **Spending Patterns**: Track spending behavior, including top merchants, spending by category, and average transaction size.
- **Risk Monitoring**: Visualize accounts with high risk, including late payments and over-limit warnings.
- **Geographical Trends**: Analyze credit card usage by region, city, or specific merchant locations.

## Dashboard Walkthrough

- **Main Page**: High-level summary of key metrics, including total transaction volume and spending categories.
- **Segmentation Page**: Visualizes customer segmentation based on spending patterns and credit utilization rates.
- **Risk Analysis Page**: Identifies risky accounts based on late payments, over-limit usage, and unusual spending.
- **Geographical Insights**: Displays a map of spending by region, highlighting key areas of activity.

## Future Enhancements

- Integrate real-time data for live updates on transactions.
- Add predictive analytics to forecast credit card usage and potential risks.
- Implement machine learning models to predict customer churn or fraud.

---

Feel free to contribute or suggest improvements by submitting a pull request!

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
