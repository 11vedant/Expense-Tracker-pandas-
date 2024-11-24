# Expense-Tracker-pandas-
# Expense Tracker

## Description
This **Python program** is a simple command-line-based **Expense Tracker** that allows users to:
1. **Add new expenses** with details such as date, category, description, and amount.
2. **View all recorded expenses** in a tabular format.
3. **Generate a summarized expense report** grouped by categories, displaying total expenses for each category and overall expenditure.

The data is stored in a CSV file named `expenses.csv` for persistence, so expenses are retained across program sessions.

---

## Features
- **Add Expenses**: Enter expense details, and the program saves them to the CSV file.
- **View Expenses**: Displays all recorded expenses in tabular format.
- **Generate Report**: Summarizes total expenses by category and calculates overall expenses.
- **Persistent Storage**: Stores expenses in a CSV file (`expenses.csv`) for future use.

---

## Requirements
### Prerequisites
1. **Python**: Version 3.x or above.
2. **Pandas Library**: Install it using:
   ```bash
   pip install pandas
   ```

---

## How to Use
1. **Clone or download the script**:
   Save the code in a file, e.g., `expense_tracker.py`.

2. **Run the Program**:
   - Open a terminal or command prompt.
   - Navigate to the directory where the file is located.
   - Run the program using:
     ```bash
     python expense_tracker.py
     ```

3. **Follow the Menu Options**:
   - The program will display a menu with the following options:
     ```
     Expense Tracker
     1. Add Expense
     2. View Expenses
     3. Generate Report
     4. Exit
     ```
   - Choose the appropriate option by entering its number (e.g., `1` to add an expense).

4. **Exit the Program**:
   - Select option `4` to exit.

---

## File Structure
### `expenses.csv`
- The program creates or loads a CSV file named `expenses.csv` to store the data.
- **Columns**:
  - `Date`: The date of the expense in the format `YYYY-MM-DD`.
  - `Category`: The category of the expense (e.g., Food, Transport, Utilities).
  - `Description`: A brief description of the expense.
  - `Amount`: The amount spent (numeric).

---

## Example Usage
### Adding an Expense:
```
Enter the date (YYYY-MM-DD): 2024-11-25
Enter the category (e.g., Food, Transport, Utilities): Food
Enter a brief description: Dinner
Enter the amount: 20
Expense added successfully!
```

### Viewing Expenses:
```
All Expenses:
         Date    Category Description  Amount
0  2024-11-25        Food      Dinner   20.00
```

### Generating a Report:
```
Expense Report:
     Category  Total Amount
0        Food          20.0

Total Expenses: 20.0
```

---

## Customization
- **File Path**: The default file is `expenses.csv`. Modify the `file_path` variable in the code to use a custom file name or path.
- **Add New Categories**: Categories can be any string provided by the user when adding expenses.

---

## Error Handling
- The program creates the CSV file if it doesn't exist.
- Invalid inputs (e.g., non-numeric amounts) will cause the program to prompt the user again.

---

## Known Issues
- Ensure valid dates are entered in the `YYYY-MM-DD` format; otherwise, the program won't validate them.

---

## License
This program is open-source and can be used or modified for personal or educational purposes.

---

Let me know if you need any further assistance!
