# experinment-11
EXP 11: Dataset creation

Theory

Dataset Creation using Pandas A dataset is a structured collection of data organized in rows and columns. In Python, the Pandas library provides an efficient way to create datasets using the DataFrame structure. A DataFrame allows storing data in tabular form with labeled rows and columns, making it easy to analyze and manipulate data.

Creating DataFrame from Dictionary Pandas allows creating a dataset using a dictionary where keys represent column names and values represent data entries. This method is simple and widely used for creating small datasets.

Saving Dataset using to_csv() The to_csv() function is used to store a dataset into a CSV (Comma Separated Values) file. This allows data to be saved permanently and used later for analysis or sharing.

Loading Dataset using read_csv() The read_csv() function is used to load data from a CSV file into a Pandas DataFrame. It is one of the most commonly used functions for importing datasets.

Viewing Data (head(), tail(), sample()) Pandas provides functions to view data easily. The head() function shows the first few rows, tail() shows the last few rows, and sample() displays random rows from the dataset.

Dataset Information (info()) The info() function provides details about the dataset such as column names, data types, and non-null values. It helps in understanding the structure of the dataset.

Statistical Summary (describe()) The describe() function generates statistical information such as mean, median, standard deviation, minimum, and maximum values for numerical columns.

Shape and Size of Dataset The shape attribute returns the number of rows and columns in the dataset, while size gives the total number of elements present.

Checking Missing Values (isnull()) The isnull() function is used to detect missing values in the dataset. Handling missing data is important for accurate analysis.

Checking Duplicate Values (duplicated()) The duplicated() function identifies duplicate rows in the dataset, which helps in cleaning the data.

Counting Unique Values (nunique()) The nunique() function returns the number of unique values in each column, which is useful for understanding data diversity.

Conclusion

Thus, dataset creation and analysis using the Pandas library were studied and implemented successfully. Various methods for creating, storing, loading, and analyzing datasets were explored. The experiment demonstrated how Pandas simplifies data handling and improves efficiency in data analysis.
