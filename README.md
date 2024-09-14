# Business-Analytics-Project

This project involves analyzing the 2019 transactional data of a electronics store to identify key trends, patterns, and opportunities to improve sales performance. The analysis includes product performance, seasonality in sales, and geographical insights into delivery patterns.

## Project Overview

### Objective
The primary goal of this project is to design and deliver a comprehensive business intelligence solution. We aimed to analyze the store's sales data from 2019 and answer critical business questions, uncover opportunities to drive sales, and improve operational efficiency.

### Business Questions Addressed:
1. **Total Revenue Generated**: How much money did we make this year?
2. **Seasonality in Sales**: Can we identify any sales seasonality throughout the year?
3. **Product Performance**: What are our best and worst-selling products?
4. **Sales Trends**: How do sales compare across months or weeks?
5. **Geographical Insights**: Which cities received the most deliveries?
6. **Product Category Performance**: How do product categories compare in revenue and quantity sold?

## Dataset

The dataset consists of sales transactions recorded throughout 2019. The data was split into two halves:
1. **First Half (Jan-Jun)**: Provided as CSV files.
2. **Second Half (Jul-Dec)**: Extracted from an SQL database.

The dataset includes the following columns:
- **Order_ID**: Unique identifier for each transaction.
- **Product**: Name of the product sold.
- **Quantity_Ordered**: Quantity of the product ordered.
- **Price_Each**: Price per unit of the product.
- **Order_Date**: Date and time of the transaction.
- **Purchase_Address**: Address where the product was delivered.

## Project Structure

The project follows the typical CRISP-DM methodology:
1. **Business Understanding**: Define the objectives and questions to be answered.
2. **Data Understanding**: Inspect the data, assess quality, and prepare it for analysis.
3. **Data Preparation**: Clean the data (handle missing values, data type conversion, and deduplication).
4. **Exploratory Data Analysis (EDA)**: Identify key trends and patterns in sales, product performance, and customer demographics.
5. **Hypothesis Testing**: Use ANOVA to identify significant factors influencing sales.
6. **Findings and Insights**: Provide actionable insights based on the analysis.

## Analysis Highlights

### 1. **Total Revenue**
- The total revenue generated in 2019 was **$34,465,537.94**.

### 2. **Seasonality in Sales**
- Sales exhibit clear seasonality, peaking in **Q2 (April - June)** and **Q4 (October - December)**. There is a notable dip during **Q3 (July - September)**, likely due to the summer vacation season.
- Product categories like **Home Appliances** and **Batteries** display smoother trends, while categories like **Phones** experience sharper fluctuations.

### 3. **Best and Worst-Selling Products**
- **Best-Selling**: MacBook Pro Laptop and Google Phone were the top revenue-generating products.
- **Worst-Selling**: AAA Batteries and USB-C Charging Cables were among the least profitable, despite being sold in high quantities.

### 4. **Sales Trends**
- Sales consistently rise towards April, dip during the summer, and pick up significantly during the holiday season (December).

### 5. **Geographical Insights**
- Cities like **San Francisco**, **Los Angeles**, and **New York** contributed the most to sales. These regions have higher purchasing power, correlating with the higher sales volumes.

### 6. **Product Category Performance**
- **Laptops** and **Phones** generated the most revenue despite lower quantities sold. Conversely, **Cables** and **Batteries** sold in higher quantities but contributed less to total sales.
  
### 7. **Significant Factors (ANOVA)**
- The ANOVA analysis revealed that **Product Category**, **Price**, and **Quantity Ordered** are significant factors affecting total sales, while the city of purchase was not statistically significant.

## Technologies Used

- **Python**: For data cleaning, exploration, and analysis.
- **Pandas**: Data manipulation and preparation.
- **Matplotlib & Seaborn**: Data visualization.
- **PyODBC & SQL**: Database connection and data extraction.
- **Power BI**: Business intelligence and interactive dashboard creation.

## Installation

To run the analysis:
1. Clone the repository:  
   `git clone https://github.com/briansiaw5/business-analytics-project.git`
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook or Python script provided.

## Future Improvements

- Implement more advanced machine learning techniques to forecast future sales and identify customer buying patterns.
- Incorporate external factors (e.g., promotions, weather data) to better understand fluctuations in sales.
- Enhance the visualizations to include interactive dashboards using Power BI or Tableau.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

This project was completed by **Team Namibia** as part of a Power BI Dashboard project. Special thanks to all contributors and supporters of this initiative.

