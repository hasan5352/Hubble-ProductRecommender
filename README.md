# Hubble-ProductRecommender
- This project is built on scikit-learn, pandas and nltk libraries of python
### The Data
- The model operates on both numerical, and categorical data. The data contains 9 features, over 500k instances/products with more than 30% having missing values in atleast one feature. The instances are divided into 109 sub categories and 20 main categories of products. 
- The data used is a product sales dataset retrieved from - **[Kaggle](https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset)**   
- After downloading and extracting the dataset, delete the Amazon-products.csv in it and paste the dataset in the same folder as the model file. 

### The Process
1. Transform the datasets into pandas dataframes and clean the data.
2. Employ Univariate Imputation using mean on a subcategory basis to account for potential variations in feature means across different subcategories
- I will be updating this with Multivariate Imputation 
3. Apply CCA for values missing completely at random (MCAR)
4. Normalize numerical data due to skewness and presence of outliers
5. kidld  
