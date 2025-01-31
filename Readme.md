# E-commerce Data Analysis and Customer Intelligence Project

This repository contains a comprehensive data analysis project focused on e-commerce transaction data, encompassing customer behavior analysis, 
lookalike modeling, and customer segmentation. The project leverages advanced analytics and machine learning techniques to derive actionable business insights.

## Project Structure

### Task 1: Exploratory Data Analysis (EDA) & Business Insights
- Performed detailed analysis of customer transactions, product preferences, and sales patterns
- Created comprehensive visualizations using seaborn and matplotlib
- Identified key business insights covering:
  - Seasonal sales patterns and growth trends
  - Category performance and revenue distribution
  - Customer purchase behavior analysis
  - Regional market dynamics
  - Customer value concentration and lifetime value analysis

### Task 2: Lookalike Customer Modeling
Implemented two distinct approaches for customer similarity:
1. **Traditional Approach**
   - Utilized feature engineering for customer profile creation
   - Implemented cosine similarity for customer matching
   - Generated top-3 similar customer recommendations

2. **FAISS Implementation**
   - Leveraged Facebook AI Similarity Search (FAISS) for efficient similarity search
   - Optimized for high-dimensional feature spaces
   - Achieved faster query times for large-scale customer base

### Task 3: Customer Segmentation
- Implemented K-Nearest Neighbors (KNN) clustering
- Performed feature engineering to capture customer behavior
- Analyzed key metrics:
  - Purchase frequency
  - Average order value
  - Total spend
  - Category preferences
- Visualized cluster characteristics and distributions

## Repository Contents
  - `EDA.ipynb`: Exploratory Data Analysis
  - `Lookalike_Model.ipynb`: Customer similarity modeling
  - `Clustering.ipynb`: Clustering analysis
  - Three CSV files and one pdf

## Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn
- FAISS
- Seaborn & Matplotlib
- Jupyter Notebook

## Key Findings
The analysis revealed significant insights into customer behavior, sales patterns, and market dynamics. 
Detailed findings can be found in the respective notebook files and the final report (EDA report)

## Usage
1. Clone the repository
2. Install required dependencies
3. Run the Jupyter notebooks in sequence

## Requirements
```python
pandas
numpy
scikit-learn
faiss-cpu
seaborn
matplotlib
jupyter
