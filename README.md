**Movies Data Analysis Project**

This project demonstrates data cleaning, transformation, and exploratory data analysis on a movies dataset using Python. To make it easier to understand we have performed Step-by-Step tasks, here is the explanation of all the tasks we have done:

**Dataset**

Used a CSV file named movie_data.csv (assumed to be provided or publicly available).

**Task 1: Reading and Inspecting the Data**

Imported necessary libraries and suppressed warnings.

Loaded the dataset using pd.read_csv().

Inspected the dataset structure:
Checked shape using .shape
Reviewed column data types and non-null counts using .info()
Used .describe() for summary statistics

**Task 2: Data Cleaning**

Checked for null values column-wise and calculated their percentage.

Identified and removed or imputed missing values (based on later steps in the notebook).

Ensured proper data types were used (e.g., converting columns if needed).

**Task 3: Feature Understanding & Transformation**

Analyzed the relevance of each feature (e.g., genre, duration, rating).

Cleaned and transformed specific fields (e.g., splitting or mapping categories if needed).

Standardized column formats for consistency.

**Task 4: Exploratory Data Analysis (EDA)**

Used groupings and aggregations (groupby, value_counts) to understand:
Top-rated movies
Most common genres
Distribution of IMDB scores, movie durations, etc.

Created various visualizations using:
Bar plots for categorical comparisons
Histograms for numeric distribution
Box plots for spread and outlier detection

**Task 5: Project Output & Inference**

Drew meaningful conclusions from the cleaned dataset

Provided insights into patterns such as:
Which genres perform better
Distribution of movie durations and ratings
Trends in movie production

**Dataset**

Used a CSV file named movie_data.csv (assumed to be provided or publicly available).

**Libraries Used:**

**pandas** for data manipulation

**numpy** for numerical operations

**matplotlib.pyplot** and seaborn for data visualization
