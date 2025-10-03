# Techfest 2025-26: Algorithmic Trading Competition

This repository contains the project for the Techfest Algorithmic Trading Competition. The objective is to design, implement, and backtest a rule-based equity trading strategy for the Nifty 500 universe.

## 🚀 Project Objective

To develop a robust and profitable quantitative trading algorithm based on historical data analysis and validate its performance through comprehensive backtesting.

## 📂 Repository Structure

```
.
├── notebooks/
│   └── backtest_notebook.ipynb  <-- Main notebook for Round 3
├── round-2-strategy/
│   └── strategy_ideation.md     <-- Your strategy logic and flowchart
├── src/
│   └── strategy.py              <-- Your strategy implementation
├── .gitignore
├── README.md
└── requirements.txt
```

## 🛠️ Setup and Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url>
    cd <your-repo-name>
    ```

2.  **Create and activate a Python virtual environment:**
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## 📈 How to Run the Backtest

1.  Implement your trading logic in `src/strategy.py`.
2.  Open the Jupyter Notebook: `jupyter lab notebooks/backtest_notebook.ipynb`.
3.  Run the cells to fetch data, execute the backtest, and analyze the results.
4.  Export the final notebook as a PDF for submission.
