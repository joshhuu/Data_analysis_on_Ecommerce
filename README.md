# Sales Data Visualization and Predictive Modeling Project

This project involves data analysis, visualization, and predictive modeling of various sales and expense reports. I utilized Python, along with libraries such as Pandas, NumPy, Matplotlib, Seaborn, and machine learning libraries, to process the data and create insightful visualizations as well as a predictive model for sales forecasting.

## Project Overview

The script reads multiple CSV files containing sales data, warehouse comparisons, expenses, and international sales reports. After cleaning and processing the data, I generate visualizations to highlight trends in total sales over time and analyze sales by category. Additionally, I implemented a predictive model to forecast future sales based on historical data.

## Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating static, animated, and interactive visualizations.
- **Seaborn**: For enhanced statistical data visualization.
- **Scikit-learn**: For building the predictive model.
- **Warnings**: To manage and suppress warnings during execution.

## Data Sources

I processed the following CSV files in this project:

1. **Amazon Sale Report**: Contains sales data from Amazon.
2. **Cloud Warehouse Comparison Chart**: Compares performance metrics of cloud warehouses.
3. **Expense IIGF**: Detailed expense reports.
4. **International Sale Report**: Data related to international sales.
5. **May-2022**: Sales data specifically for May 2022.
6. **P&L March 2021**: Profit and Loss report for March 2021.
7. **Sale Report**: General sales report.

## Data Cleaning Process

In this project, I performed several data cleaning tasks:

- Removed unnecessary columns (e.g., `Unnamed` columns).
- Converted date columns to the datetime format for accurate time-series analysis.

## Visualizations

I created the following visualizations to represent the data:

1. **Total Sales Over Time**: A line plot illustrating total sales amounts grouped by date.
2. **Total Sales by Category**: A horizontal bar chart showcasing total sales amounts by product category.

## Sales Predictive Model

The project includes a sales predictive model that:

- Uses historical sales data to train a machine learning algorithm.
- Predicts future sales based on trends observed in the dataset.
- Outputs sales forecasts that can be used for planning and decision-making.

## How to Use

To run the project:

1. Ensure you have Python installed along with the required libraries. You can install them using:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Place the CSV files in an `archive` folder within the same directory as this script.

3. Execute the script in your Python environment. The visualizations and predictive model outputs will be displayed sequentially.

## Conclusion

This project enabled me to analyze, visualize, and forecast sales performance, providing valuable insights for data-driven decision-making. I look forward to exploring further insights and adapting the project.
