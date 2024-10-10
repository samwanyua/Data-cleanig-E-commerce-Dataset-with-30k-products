# E-commerce Dataset with 30K Products - Data Cleaning

This repository contains a project focused on data cleaning and analysis using an **E-commerce Dataset** consisting of 30,000 women's fashion products. Categories covered in this dataset include western wear, Indian wear, perfumes, fragrances, watches, and nightwear.

## Dataset Overview

The dataset is ideal for applying data cleaning, visualization, and analytical skills. It includes the following columns:

- **BrandName**: Mentions the brand of the product.
- **Details**: Details about the product.
- **Size**: Sizes available.
- **MRP**: The maximum retail price of the product.
- **SellPrice**: The price of the product after discounts.
- **Category**: The category of the product (e.g., western wear, Indian wear, etc.).

## Data Cleaning Steps

1. **Handling Missing Values**:
   - Missing values were handled by filling them with appropriate values where possible or dropping rows with critical missing data to maintain data quality.

2. **Removing Duplicates**:
   - Duplicates were checked and removed to ensure consistency and avoid skewed analysis.

3. **Ensuring Data Integrity**:
   - Data types were corrected (e.g., converting prices to numerical formats).
   - Outliers were handled to avoid distortions in analysis.

## Next Steps

- **Data Visualization**: Visualize trends in product pricing, sales, and categories.
- **Exploratory Data Analysis (EDA)**: Identify patterns and insights within the dataset to assist in decision-making for retail and marketing strategies.

## Usage

To clean the data, follow the steps in the provided Jupyter notebook or Python script. You will need the following libraries:
```bash
pandas
numpy
matplotlib
seaborn
