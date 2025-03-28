# Machine Learning Preprocessing Pipeline

## Overview
A robust scikit-learn preprocessing pipeline for handling mixed data types (numerical and categorical) with integrated data cleaning and transformation techniques.

## Key Features
- Automated missing value imputation
- Standardization of numerical features
- One-hot encoding for categorical variables
- Seamless integration with machine learning models

## Project Structure
- Handles both numerical and categorical data preprocessing
- Uses scikit-learn's Pipeline and ColumnTransformer
- Supports mean imputation for numerical features
- Supports mode imputation for categorical features

## Technical Components

### Numerical Pipeline
- Missing value imputation using mean strategy
- Feature standardization using StandardScaler
- Handles numerical columns like 'age' and 'weight'

### Categorical Pipeline
- Missing value imputation using most frequent strategy
- One-hot encoding with unknown category handling
- Processes categorical columns like 'gender' and 'colour'

## Dependencies
- pandas
- numpy
- scikit-learn

## Key Preprocessing Steps
1. Numerical Feature Processing
   - Mean imputation for missing values
   - Standardization to normalize feature scales

2. Categorical Feature Processing
   - Mode imputation for missing values
   - One-hot encoding to convert categorical variables

## Advantages
- Automated data cleaning
- Handles mixed data types
- Reduces manual preprocessing efforts
- Integrates seamlessly with machine learning workflows

## Potential Improvements
- Add more advanced imputation strategies
- Implement feature selection techniques
- Support for more complex encoding methods

## License
Open-source project. Use and modify with attribution.

## Contribution
Contributions, issues, and feature requests are welcome!
