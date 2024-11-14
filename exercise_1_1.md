# Exercise 1: Monthly Summary Table from Transaction Files

## Objective

Create a script to read multiple partitioned files from a directory and generate a summary table with monthly totals across categories.

## Instructions

1. **Directory Structure:** You are provided with a folder named `transactions` containing multiple CSV files. Each file represents a partition of a larger table with detailed transaction records.
  
2. **Data Format:** Each CSV file contains columns similar to:
   - `date`: Transaction date in the format `YYYY-MM-DD`
   - `category`: The category of the transaction (e.g., Groceries, Electronics, Clothing, etc.)
   - `amount`: The transaction amount as a numeric value.

3. **Summary Table Requirements:**
   - **Rows:** Each row should represent a month.
   - **Columns:** Each column should represent a category.
   - **Values:** Populate each cell with the total transaction amount for that month and category.
   - Add an additional "Total" column that shows the sum across all categories for each month.

4. **Deliverable:**
   - Produce a CSV file named `monthly_summary.csv` containing the summary table.
   - Each month should be represented as a row, with each category in a separate column.
   - The table should look similar to the following:

     | Month   | Groceries | Electronics | Clothing | Entertainment | Utilities | Total    |
     |---------|-----------|-------------|----------|---------------|-----------|----------|
     | January | $1,200    | $2,000      | $850     | $1,300        | $950      | $6,300   |
     | February| $1,100    | $1,800      | $900     | $1,500        | $1,100    | $6,400   |
     | March   | $1,250    | $2,100      | $1,000   | $1,400        | $1,050    | $6,800   |

5. **Additional Notes:**
   - Pay attention to data aggregation and ensure accuracy in the calculations.
   - You are welcome to use any Python libraries you find useful.
   - Extra points for any relevant finding on the data, comment, report or chart that might be useful.

## Evaluation Criteria

Your submission will be evaluated based on:
- Correctness of the calculations.
- Code readability and organization.
- Efficiency of the solution.

Good luck, and feel free to reach out if you have any questions!