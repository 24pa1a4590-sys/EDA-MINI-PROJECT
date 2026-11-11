
# Housing Prices Regression Analysis & EDA

## Project Overview
This project focuses on Exploratory Data Analysis (EDA) and data cleaning of a Housing Prices dataset using Python. It explores housing features, identifies missing values, handles duplicates, cleans inconsistent data, and visualizes relationships between different variables.

## Objectives
- Understand the housing dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Identify and handle outliers.
- Explore relationships between housing features.
- Visualize important patterns and trends.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

## Dataset
Dataset file: `housing_prices_regression.csv`

Important columns:
- `sale_price` – Sale price of the house.
- `size_sqft` – House size in square feet.
- `num_bedrooms` – Number of bedrooms.
- `num_bathrooms` – Number of bathrooms.
- `year_built` – Year the house was built.
- `has_garage` – Garage availability.
- `has_garden` – Garden availability.
- `zipcode` – Property ZIP code.

## Project Workflow

### 1. Data Loading
- Imported required Python libraries.
- Loaded the CSV dataset.
- Displayed the first and last records.
- Checked dataset shape and data types.

### 2. Data Inspection
- Checked missing values.
- Calculated missing-value percentages.
- Identified duplicate records.
- Generated descriptive statistics.

### 3. Data Cleaning
- Removed duplicate records.
- Handled missing numerical values using median.
- Handled missing categorical values.
- Removed unnecessary ID columns.
- Converted columns to appropriate data types.
- Standardized categorical values.
- Removed redundant columns.
- Identified and handled unusual house-size values.

### 4. Exploratory Data Analysis (EDA)

The following visualizations were created:

1. Sale Price Distribution Histogram
2. Number of Bedrooms Bar Chart
3. Garage Availability Count Plot
4. Garage Availability Pie Chart
5. Sale Price Box Plot
6. House Size vs Sale Price Scatter Plot
7. Year Built vs Sale Price Line Plot
8. Correlation Heatmap
9. Pairplot of Numerical Features
10. Sale Price by Bedroom Count Violin Plot

## How to Run the Project

### Step 1: Clone the Repository
```bash
git clone <your-repository-url>
```

### Step 2: Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Open Jupyter Notebook
```bash
jupyter notebook
```

### Step 4: Run the Notebook
Open `eda_int.ipynb` and execute all cells.

Make sure `housing_prices_regression.csv` is available in the working directory. If running in Google Colab, upload the dataset when prompted.

## Expected Outcome
- Cleaned housing dataset.
- Identification of missing values and duplicates.
- Better understanding of housing price distributions.
- Insights into relationships between house features and sale prices.
- Visual representation of important housing trends.

## Future Improvements
- Feature engineering.
- Encoding categorical variables.
- Train-test splitting.
- Implement Linear Regression.
- Implement Random Forest Regression.
- Model evaluation using MAE, RMSE, and R².

## Author
Add your name here.

