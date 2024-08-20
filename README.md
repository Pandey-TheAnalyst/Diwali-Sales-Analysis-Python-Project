### Project Summary: Diwali Sales Data Analytics

#### **Objective**
The goal of this project was to perform a comprehensive analysis of Diwali sales data to derive actionable insights on customer behavior and sales patterns. The analysis focused on understanding key factors such as gender, age, marital status, state, occupation, and product category that influence sales during the Diwali period.

#### **Data Overview**
The dataset contains 11,251 records and 15 columns, including user information, product details, and sales metrics. Key columns include:
- `User_ID`, `Cust_name`, `Product_ID`
- `Gender`, `Age Group`, `Age`, `Marital_Status`
- `State`, `Zone`, `Occupation`, `Product_Category`
- `Orders`, `Amount`

#### **Data Cleaning and Preparation**
- **Initial Inspection:** The dataset had 15 columns, with `Status` and `unnamed1` containing only null values, which were removed.
- **Handling Missing Values:** 12 missing values in the `Amount` column were dropped.
- **Data Type Conversion:** The `Amount` column was converted from float to integer for consistency.
- **Column Renaming:** The column `Marital_Status` was renamed to `Shaadi` for better readability.

#### **Exploratory Data Analysis (EDA)**
1. **General Statistics:**
   - The average age of customers is approximately 35 years.
   - The average number of orders per customer is around 2.5, with an average purchase amount of ₹9,453.

2. **Sales by Gender:**
   - Females contributed significantly more to sales compared to males.
   - Visualizations showed that females had a higher purchasing power than males.

3. **Sales by Age Group:**
   - The age group of 26-35 years is the most significant in terms of sales.
   - The majority of buyers in this age group are female.

4. **Sales by State:**
   - Uttar Pradesh, Maharashtra, and Karnataka were the top states in terms of both order volume and total sales amount.
   - Visualizations highlighted the prominence of these states in contributing to overall sales.

5. **Sales by Marital Status:**
   - Married individuals, particularly women, showed higher purchasing power.
   - Married customers contributed more to total sales compared to single individuals.

6. **Sales by Occupation:**
   - Customers working in the IT, Healthcare, and Aviation sectors were prominent buyers.
   - The sales analysis identified these occupations as significant contributors to sales.

7. **Sales by Product Category:**
   - The most purchased product categories were Food, Clothing, and Electronics.
   - Insights from the data suggest these categories are the most popular among customers.

8. **Top Products by Orders:**
   - The analysis identified the top products based on the number of orders, helping to understand customer preferences.

#### **Key Insights**
- **Demographics:** Female customers, particularly those aged 26-35, and married individuals, demonstrated higher purchasing power.
- **Geographical Trends:** Uttar Pradesh, Maharashtra, and Karnataka are key regions driving sales.
- **Occupation Influence:** Customers in IT, Healthcare, and Aviation sectors have higher spending patterns.
- **Product Preferences:** Food, Clothing, and Electronics are the leading product categories.

#### **Conclusion**
The analysis provided valuable insights into customer behavior during Diwali sales. It highlighted key demographic and regional trends that can be leveraged for targeted marketing and inventory management. The findings suggest focusing on the top-performing regions, product categories, and customer segments to optimize sales strategies for future campaigns.

#### **Next Steps**
- **Marketing Strategies:** Develop targeted marketing campaigns based on identified customer demographics and regional preferences.
- **Inventory Management:** Adjust inventory levels based on popular product categories and top-selling regions.
- **Further Analysis:** Explore additional factors such as seasonal trends and customer feedback to refine sales strategies.
