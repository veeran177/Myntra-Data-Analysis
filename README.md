# Myntra-Data-Analysis
This project performs an end-to-end data analysis on a dataset of Myntra jeans products. It showcases skills in data cleaning, exploratory data analysis (EDA), and data visualization using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn

1. Introduction
This project demonstrates a complete data science workflow, from raw data to actionable insights. Using a dataset of over 52,000 jeans products scraped from Myntra, this analysis covers key steps: data cleaning, feature engineering, and exploratory data analysis (EDA). The entire project is conducted using Python, with a focus on libraries like Pandas, NumPy, Matplotlib, and Seaborn.

2. Project Goal
The primary objective of this project is to showcase an end-to-end data science process by:

Identifying and cleaning data inconsistencies.

Uncovering key trends and patterns in product pricing, ratings, and discounts.

Visualizing findings to tell a compelling story about the data.

Providing a foundational analysis that can be extended with more advanced techniques.

3. Dataset Overview
The dataset, myntra_dataset_ByScraping.csv, contains the following columns:

brand_name: The brand of the product.

pants_description: A brief description of the product (e.g., "Men Slim Fit Jeans").

price: The current selling price of the product.

MRP: The original Marked Retail Price.

discount_percent: The percentage discount applied.

ratings: The average user rating of the product.

number_of_ratings: The total number of ratings a product has received.

4. Technical Skills Demonstrated
Python Programming: Foundational coding for data manipulation and analysis.

Pandas & NumPy: Loading, cleaning, and transforming data; handling missing values and data type conversions.

Matplotlib & Seaborn: Creating a wide range of visualizations, including histograms, bar plots, and scatter plots, to communicate findings effectively.

5. Key Findings
Through comprehensive EDA, several interesting insights were discovered:

Pricing Trends: The majority of jeans products on Myntra are priced between ₹1000 and ₹2000. The distribution of prices is heavily skewed towards the lower end.

Brand Popularity: Brands like Roadster, Urbano Fashion, and HERE&NOW have the highest total number of ratings, indicating their popularity and high sales volume.

Discounts and Price Tiers:

There is a clear positive correlation between a product's original price (MRP) and the absolute discount amount it receives in Rupees.

Brands such as WROGN and Levis consistently offer the highest average percentage discounts.

Ratings and Discounts: The analysis revealed no strong correlation between a product's ratings and its discount percentage. High ratings were observed across all discount ranges.

6. Repository Structure
myntra_dataset_ByScraping.csv: The original raw data file.

myntra_data_analysis.ipynb: The Jupyter Notebook containing all the code for data cleaning, analysis, and visualization.

README.md: This project summary and guide.
