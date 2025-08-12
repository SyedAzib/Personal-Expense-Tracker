# 💰 Personal Expense Tracker

A simple **Python-based expense tracking tool** that allows you to log daily expenses, store them in a CSV file, and visualize your spending trends.  
This project uses **Pandas**, **Matplotlib**, and **Seaborn** for data handling and visualizations.

---

## 📌 Features
- Add new expenses with date, category, amount, and notes.
- Store data in a CSV file (`expenses.csv`) for persistence.
- View **total spending** and **category-wise breakdown**.
- Display **monthly spending trends**.
- Generate **bar charts** and **pie charts** for visual analysis.

---

## 📂 Project Structure
```
├── project_2.ipynb      # Main Jupyter Notebook
├── expenses.csv         # Data file (created after first run)
└── README.md            # Project documentation
```

---

## 🛠️ Installation & Setup
1. **Clone the repository** (or download the files):
   ```bash
   git clone https://github.com/yourusername/personal-expense-tracker.git
   cd personal-expense-tracker
   ```

2. **Install dependencies**:
   ```bash
   pip install pandas matplotlib seaborn
   ```

3. **Open the notebook**:
   ```bash
   jupyter notebook project_2.ipynb
   ```

---

## ▶️ Usage
### 1. Add a New Expense
Run the cell containing:
```python
add_expense()
```
You’ll be prompted to:
- Enter **date** (leave blank for today)
- Enter **category** (e.g., Food, Transport, Shopping)
- Enter **amount spent**
- Optionally add **notes**

The expense will be saved in `expenses.csv`.

### 2. View Summary
Run:
```python
df = pd.read_csv("expenses.csv")
```
You’ll get:
- Total records
- Total amount spent
- Spending by category
- Monthly spending trend

### 3. Visualizations
- **Category Bar Chart**
- **Pie Chart of Spending by Category**

---

## 📊 Example Output
**Category-wise Spending:**
```
Food       2500
Transport  1200
Shopping    800
```

**Monthly Spending Trend:**
```
2025-06    3000
2025-07    1500
```

---

## 🚀 Future Improvements
- Add filtering by date range.
- Add interactive dashboard with **Streamlit**.
- Export reports as PDF.

---

## 📜 License
This project is licensed under the MIT License.
