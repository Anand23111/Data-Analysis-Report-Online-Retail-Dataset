
# Data Analysis Report: Online Retail Dataset

This repository contains an analysis of an Online Retail dataset. The goal is to explore key aspects such as basic statistics, distributions, relationships between attributes, and dimensionality reduction techniques. The analysis helps uncover underlying patterns and trends in the data.

## Dataset Overview

The dataset includes transactional data with the following columns:
- **InvoiceNo**: Transaction ID.
- **StockCode**: Product ID.
- **Description**: Product details.
- **Quantity**: Quantity of items purchased.
- **UnitPrice**: Price per unit of the item.
- **CustomerID**: Customer identifier.
- **Country**: Customer's country.

## Key Analysis Steps

1. **Exploratory Data Analysis (EDA)**: 
   - Inspected basic statistics using `describe()`.
   - Explored distributions of **Quantity** and **UnitPrice** through histograms.
   
2. **Outlier Detection**:
   - Used boxplots and scatter plots to identify potential outliers in **Quantity** and **UnitPrice**.

3. **Statistical Measures**:
   - Calculated mean, variance, and covariance to understand the spread and relationships between key attributes.

4. **Dimensionality Reduction**:
   - Applied **PCA** (Principal Component Analysis) and **t-SNE** (t-distributed Stochastic Neighbor Embedding) to reduce the data to 2D for visualization, revealing patterns and relationships.

## Visualizations

- **Histograms**: Visualized the distribution of **Quantity** and **UnitPrice**.
- **Boxplots**: Detected outliers in **Quantity**.
- **Scatter Plots**: Analyzed the relationship between **UnitPrice** and **Quantity**.
- **PCA & t-SNE**: Used to reduce dimensions and uncover data patterns.

## Findings

- **Outliers**: Extreme values in **Quantity** and **UnitPrice** could represent erroneous data or rare purchase behavior.
- **Relationships**: An inverse relationship exists between **UnitPrice** and **Quantity** — higher-priced items tend to have lower quantities purchased.
- **Dimensionality Reduction**: PCA revealed the data's variance, while t-SNE highlighted local groupings.

## Conclusion & Next Steps

- **Outlier Treatment**: Investigate and possibly treat outliers.
- **Segmentation**: Segment data by customer or product categories to reveal more specific trends.
- **Predictive Modeling**: Cleaned data can be used for building predictive models.

## How to Run the Analysis

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/online-retail-analysis.git
