# 💰 Personal Expense Tracker

A simple Python-based expense tracking program that stores spending data in a CSV file and visualizes trends using Pandas, Matplotlib, and Seaborn.

## Features
- 📝 Add expenses with date, category, amount, and optional notes.
- 📂 Stores data in `expenses.csv` for easy access.
- 📊 Displays total spending, category-wise breakdown, and monthly trends.
- 🎨 Generates bar charts and pie charts for visual insights.
- 💡 Beginner-friendly Python data analysis project.

## How It Works
1. User enters expense details (date, category, amount, notes).
2. Data is saved to `expenses.csv`.
3. Program reads the CSV and calculates:
   - Total spending
   - Category-wise spending
   - Monthly spending trends
4. Generates visual charts to help analyze spending habits.

## Requirements
- Python 3.x  
- Pandas  
- Matplotlib  
- Seaborn  

Install dependencies:
```bash
pip install pandas matplotlib seaborn
```

## How to Run
1. Download or clone the repository.
2. Open the project folder in Jupyter Notebook or any Python IDE.
3. Run:
   ```bash
   jupyter notebook personal-expense-tracker.ipynb
   ```
4. Follow on-screen prompts to add expenses or view reports.

## Example Output
```
📅 Total Records: 15
💰 Total Spent: Rs. 7,500

📂 Spending by Category:
Food        3,500
Transport   2,000
Shopping    2,000
```

**Category Bar Chart:**  
_(Shows spending distribution per category)_

**Pie Chart:**  
_(Displays percentage breakdown of each category)_

## Future Improvements
- Add filters for specific date ranges.
- Export summary reports as PDF.
- Create an interactive dashboard with Streamlit.
- Include recurring expense tracking.

## 👤 Author
**Made by Syed Azib Waseem**