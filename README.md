# Working with Pandas

This repository contains a Jupyter notebook file that covers the basics of working with the pandas library in Python for data analysis. It covers various topics such as loading and saving data, data manipulation, data visualization and more.

## Topics Covered
- Introduction to the pandas library
- Loading and saving data with `pd.read_csv()` and `pd.to_csv()`
- Data manipulation with DataFrame and Series objects
- Data visualization with `matplotlib` and `seaborn`
- Handling missing data
- Groupby and Aggregation
- Merging and joining data

## Getting Started
To use the notebooks in this repository, you will need to have a working installation of Python and Jupyter Notebook. You can download the latest version of Python from the official website (https://www.python.org/) and install Jupyter Notebook by running `pip install jupyter`. You will also need to install pandas library by running `pip install pandas`, matplotlib and seaborn library if you want to use it for visualization.

Once you have the necessary software installed, you can clone or download this repository to your local machine. Then, open a terminal or command prompt and navigate to the directory where you downloaded the repository. Run the command `jupyter notebook` to launch the Jupyter Notebook application.

In the Jupyter Notebook interface, navigate to the Working with Pandas repository and open the notebook files to begin working through the tutorials.

## Examples
Here's an example of how you can use the pandas library to load a CSV file:
```python
import pandas as pd

# Load the CSV file
df = pd.read_csv("italy-covid-daywise.csv")

# Print the first 5 rows
print(df.head())
