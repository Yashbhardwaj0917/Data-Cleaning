# Data Cleaning in Pandas

This project focuses on the data cleaning process using Python and the Pandas library. Data cleaning is a crucial step in data analysis and preparation for further analysis or machine learning tasks. We will walk through the steps involved in cleaning and preprocessing a dataset, demonstrating common data cleaning techniques.

## Project Overview

The dataset used in this project is named "Customer Call List.xlsx." The primary goal is to clean and transform the data to ensure its accuracy, consistency, and readiness for analysis. Here's a summary of the main data cleaning steps performed in this project:

1. **Loading the Data:** We start by loading the dataset from an Excel file into a Pandas DataFrame using the `pd.read_excel` function.

2. **Removing Duplicate Rows:** Duplicate rows can distort analysis results, so we use the `drop_duplicates` method to remove them.

3. **Dropping Unnecessary Columns:** We identify and drop a column named "Not_Useful_Column" that is not relevant to our analysis.

4. **Cleaning Text Data:** We perform text data cleaning on the "Last_Name" and "Phone_Number" columns by removing specific characters and patterns.

5. **Splitting Address Information:** To make the data more structured, we split the "Address" column into separate columns for "Street_Address," "State," and "Zip_Code."

6. **Standardizing "Do_Not_Contact" Values:** We standardize values in the "Do_Not_Contact" column by replacing "Yes" with "Y" and "No" with "N."

7. **Handling Missing Values:** We fill any remaining missing values in the dataset with empty strings.

8. **Filtering Rows:** Rows marked with "Do_Not_Contact" as "Y" and rows with empty "Phone_Number" are removed, as they are not relevant for our analysis.

9. **Resetting the Index:** Finally, we reset the DataFrame index to ensure it is sequential and starts from zero.

## Usage

To replicate this data cleaning process:

1. Make sure you have Python and the Pandas library installed on your system.

2. Download the "Customer Call List.xlsx" dataset or replace it with your dataset, and update the file path accordingly in the code.

3. Copy and paste the provided Python code into your preferred Python environment, such as Jupyter Notebook or a code editor.

4. Execute the code step by step to perform each data cleaning operation.

5. Customize the code and data cleaning steps based on your specific dataset and requirements.

## Contributing

Contributions to this project are welcome! If you have suggestions for improving existing data cleaning techniques or adding new ones, please fork the repository, make your changes, and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code as needed.

---

Customize this README file to include specific details about your dataset, data cleaning steps, and any additional information relevant to your project. Once completed, add the README file to your GitHub repository to provide documentation for others who may benefit from your data cleaning work.
