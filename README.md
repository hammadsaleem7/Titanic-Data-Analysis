# Titanic Dataset Exploration and Analysis

This notebook explores and analyzes the Titanic dataset, aiming to understand the factors that influenced passenger survival.

## Dataset Overview

The Titanic dataset contains information about passengers who were aboard the RMS Titanic, including demographics, ticket details, and survival status.

## Data Exploration

1. **Loading and Initial Inspection:**
   - The dataset is loaded using Pandas.
   - Basic information about the dataset is gathered using `.info()` and `.head()`.

2. **Missing Data Handling:**
   - Missing values in 'Age' are filled with the mean age.
   - Missing values in 'Cabin' are filled with randomly generated cabin numbers (e.g., 'A123').

3. **Exploratory Data Analysis:**
   - **Survival Counts:** Visualizations are created to analyze the number of survivors and non-survivors.
   - **Survival by Sex:** Analyze the impact of gender on survival rates using a countplot.
   - **Survival by Passenger Class:** Analyze the impact of passenger class on survival rates using a countplot.
   - **Descriptive Statistics:** Summary statistics are generated for the numerical features.


## Further Analysis (Possible Steps)

- Feature engineering: Create new features, such as family size or title from passenger names.
- Data visualization: Explore relationships between different features (e.g., survival rate vs. age)
- Predictive modeling: Build a model to predict passenger survival using machine learning techniques.


## Tools and Libraries

- Pandas
- Seaborn

