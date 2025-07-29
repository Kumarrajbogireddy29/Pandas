# Pandas

This project is focused on exploring and analyzing a dataset using Python and the pandas library in a Jupyter Notebook environment. The dataset used here, titled "crime_safety.csv" (or your dataset name), contains information relevant to crime and safety statistics. The goal of this project is to demonstrate how to load data into pandas, perform basic cleaning, and extract insights using common pandas functions.

To get started, I used the pandas library to read the dataset using pd.read_csv(). After loading the data into a DataFrame, I explored the structure of the dataset using methods like .head(), .info(), and .describe() to understand the columns, data types, and summary statistics. This helps identify missing values, data inconsistencies, or outliers.

Once the dataset structure was understood, I performed several operations such as filtering rows, selecting specific columns, sorting values, and checking for nulls using df.isnull().sum(). These steps helped clean the data and prepare it for further analysis. I also included basic visualizations using matplotlib and seaborn (if applicable), such as bar plots or histograms, to represent trends or patterns in the dataset visually.

The notebook used for this analysis is named analysis.ipynb, and it contains all the code and outputs related to data loading, exploration, and analysis. The dataset file crime_safety.csv must be placed in the same directory as the notebook for the code to run without errors.

This small project is a hands-on example of how pandas can be used for real-world data analysis tasks. It is especially helpful for beginners who are learning how to work with data in Python and want to build their confidence by exploring public datasets.
