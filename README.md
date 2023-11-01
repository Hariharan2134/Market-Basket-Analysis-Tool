# AI_Market_Basket_Insight-813821205049
# Market Basket Analysis - README

## Project Overview
This project is focused on conducting a Market Basket Analysis using the Apriori algorithm to discover associations and patterns in customer purchase behavior. It involves extracting meaningful insights from a provided dataset.

## Team Members
- J. ARUN KUMAR
- C. MURUGANANTHAN
- T. SRIHARIHARAN
- S. VENGADASHAN
- S. VISHWA

## Code Description
The code provided in this project performs the following tasks:

1. *Data Loading*: It loads the dataset from a CSV file, using the specified separator.

2. *Data Preprocessing*:
   - Removes duplicate rows from the dataset.
   - Removes rows with missing or invalid values.

3. *Column Selection*: Selects the relevant columns 'BillNo' and 'Itemname' for the analysis.

4. *One-Hot Encoding*: Converts the data into a one-hot encoded format suitable for association analysis.

5. *Frequent Itemset Mining*: Uses the Apriori algorithm to find frequent itemsets based on a minimum support threshold.

6. *Association Rule Generation*: Generates association rules based on a minimum lift threshold.

7. *Interpretation*: The code allows for the interpretation of the discovered association rules based on specific project requirements.

## How to Run
To run the code, follow these steps:
1. Ensure you have Python and the required libraries (e.g., Pandas, mlxtend) installed.
2. Download the dataset ('Assignment-1_Data.csv') from the provided link.
3. Place the dataset in the same directory as the code file.
4. Run the code using a Python interpreter.

## Dependencies
- Python 3.x
- Pandas
- mlxtend

## Dataset
The dataset used for this project can be found at the following link:
[Dataset Link](https://www.kaggle.com/datasets/aslanahmedov/market-basket-analysis)

The dataset contains transaction data that is used for market basket analysis.

## Output
The code generates output in the form of frequent item sets and association rules, which are printed to the console.

## Additional Notes
- Make sure to tailor the code to your specific dataset if necessary.
- The interpretation of association rules should be based on your project's domain knowledge and requirements.

Please feel free to reach out to any of the team members listed above if you have questions or need further assistance with the project.

Happy coding!
