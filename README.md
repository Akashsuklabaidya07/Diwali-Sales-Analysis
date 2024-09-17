# Diwali Sales Data Analysis

## Project Overview

This project involves analyzing a dataset called **Diwali Sales Data**. The analysis includes several stages such as data cleaning, exploratory data analysis (EDA), feature extraction, and data visualization to gain insights into sales patterns during the Diwali season.

## Dataset

The dataset contains sales information, customer demographics, product categories, and more. Below are the key columns of the dataset:

- `User_ID`: Unique ID for each customer
- `Cust_name`: Name of the customer
- `Product_ID`: Unique ID for each product
- `Gender`: Gender of the customer (M/F)
- `Age Group`: Age group of the customer (e.g., 26-35)
- `Age`: Actual age of the customer
- `Marital_Status`: Whether the customer is married or not (0: Single, 1: Married)
- `State`: The state from which the customer belongs
- `Zone`: Geographical zone (e.g., Western, Northern)
- `Occupation`: Occupation of the customer (e.g., IT, Government, Media)
- `Product_Category`: Category of the product (e.g., Auto, Electronics)
- `Orders`: Number of orders placed by the customer
- `Amount`: Total amount spent by the customer

## Project Workflow

1. **Data Cleaning**:
   - Handled missing values
   - Removed duplicates
   - Ensured consistency in categorical columns like `State`, `Zone`, etc.

2. **Exploratory Data Analysis (EDA)**:
   - Analyzed customer demographics such as age, gender, and occupation.
   - Examined product categories and their contribution to total sales.
   - Studied geographical trends in customer purchases.

3. **Feature Extraction**:
   - Derived new columns such as `Total_Spend` based on `Orders` and `Amount`.
   - Grouped customers by age and gender to assess purchasing patterns.

4. **Data Visualization**:
   - Created visualizations using libraries like **Matplotlib**, **Seaborn**, and **Plotly** to highlight trends and patterns.
   - Visualized total sales across different states, product categories, and occupations.

## Key Insights

- **Sales by Gender**: We observed different spending habits between male and female customers.
- **Age Groups**: Certain age groups, like 26-35, have a higher purchasing power.
- **Occupation-Based Sales**: Customers in certain professions, such as IT and Government sectors, tend to spend more.
- **Geographical Trends**: Western and Southern zones had the highest sales.

## Tools and Technologies

- **Python**: Used for data manipulation and analysis.
- **Pandas**: For data cleaning and feature extraction.
- **Seaborn/Matplotlib/Plotly**: For data visualization.
- **Jupyter Notebook**: For interactive analysis.
- **Git/GitHub**: Version control and project hosting.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/Akashsuklabaidya07/diwali-sales-data-analysis.git
   cd diwali-sales-data-analysis
   ```
2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to execute the analysis
 ```bash
   jupyter notebook Diwali_Sales_Analysis.ipynb
 ```
## Conclusion
This project successfully highlights the key factors that influence sales during the Diwali season, providing useful insights into customer behavior and sales patterns across different demographics.

## License
This project is licensed under the MIT License 
#### Feel free to replace names and details as necessary.
### Akash Sukla Baidya

akashsuklabaidya780@gamil.com
