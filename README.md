# Amazon India Product Analysis

## Introduction

In the realm of online shopping, Amazon stands as a giant, offering a vast array of products. This project delves into the analysis of over 1000 different products available on Amazon India. By exploring a diverse dataset encompassing product names, categories, prices, customer ratings, and reviews, the goal is to uncover valuable insights and patterns. Focused on Amazon India, this choice is driven by the availability of a freely accessible dataset on the internet.

The project's significance lies in distilling essential knowledge from a sea of facts, aiding both Amazon and its customers. For Amazon, this analysis acts as a map in a complex market, guiding decisions on pricing, advertising, and understanding product trends. Simultaneously, customers benefit from the project's insights, helping them make informed choices while navigating the vast array of products.

## Data Processing

### Key Dataset Features

- **product_name:** Name of the product
- **category:** Category of the product
- **discounted_price:** Discounted price of the product
- **actual_price:** Actual price of the product
- **discount_percentage:** Percentage of discount for the product
- **rating:** Rating of the product
- **rating_count:** Number of people who voted for the Amazon rating
- **about_product:** Description about the product
- **user_id:** ID of the user who wrote the product review
- **user_name:** Name of the user who wrote the product review
- **review_id:** ID of the product review
- **review_title:** Short review title
- **review_content:** Detailed product review
- **img_link:** Image link of the product
- **product_link:** Official website link of the product

### Data Processing Steps

1. Renamed columns for clarity.
2. Handled missing values in the 'rating_count' column and corrected invalid data in the 'rating' column.
3. Removed less significant columns with missing values.
4. Ensured all numerical columns have the correct data type.
5. Simplified the 'category' column by extracting the main category.

## Exploring the Data Terrain

Visualized single variables using histograms, bar charts, and box plots to understand the distribution of ratings, rating counts, discount percentages, and the number of products in different categories.

## Hypothesis Testing

Conducted a Two-Sample T-Test to determine a significant difference in the mean actual prices of products between the 'Electronics' and 'Home&Kitchen' categories.

## Data Modeling

Trained and evaluated two regression models:
- Linear Regression
- Decision Tree Regression

Evaluated models using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R2) Score.

## Contents

- **Jupyter Notebook:** The detailed analysis and code implementation.
- **Readme.md:** Documentation providing an overview of the project, data processing steps, exploration, hypothesis testing, data modeling, and evaluation metrics.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python packages (can be installed using `pip install -r requirements.txt`):
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn

## Acknowledgement

This project utilizes the [Amazon Sales Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset) available on Kaggle. Special thanks to the dataset creator for making it publicly accessible.

---

*Note: Ensure you have the required Python packages installed before running the Jupyter Notebook.*
