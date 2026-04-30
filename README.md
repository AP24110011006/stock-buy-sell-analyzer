Stock Buy-Sell Analyzer
Greedy & Dynamic Programming Approach
 Project Description

The Stock Buy-Sell Analyzer is a Python-based project that determines the maximum profit from stock price data using two algorithmic approaches:

Greedy Algorithm (efficient and simple)
Dynamic Programming (DP) (optimal and flexible)

This project demonstrates how different algorithmic strategies solve the same problem and compares their efficiency and results.

 Objectives
Analyze stock prices to maximize profit
Implement and compare Greedy and DP approaches
Display buy/sell transactions clearly
Understand time complexity differences
 Technologies Used
Python 3
VS Code (or any IDE)
Git & GitHub
📂 Project Structure
stock-buy-sell-analyzer/
│── main.py        # Entry point of the program
│── greedy.py      # Greedy algorithm implementation
│── dp.py          # Dynamic Programming implementation
│── utils.py       # Helper functions (printing transactions)
│── README.md      # Project documentation
 Algorithms Used
 1. Greedy Algorithm
Strategy: Buy when price increases the next day
Makes local optimal decisions
Works efficiently for unlimited transactions

Time Complexity: O(n)

 2. Dynamic Programming
Considers all possible buy/sell combinations
Ensures global optimal solution
Useful for more complex constraints

Time Complexity: O(n²)

How to Run the Project:
Step 1: Clone Repository
git clone https://github.com/your-username/stock-buy-sell-analyzer.git
cd stock-buy-sell-analyzer
Step 2: Run Program
python main.py
Step 3: Enter Input
Enter stock prices (space separated): 7 1 5 3 6 4
Sample Input:
7 1 5 3 6 4
Sample Output:
--- Results ---
Greedy Profit: 7
Buy on day 1 at price 1, Sell on day 2 at price 5
Buy on day 3 at price 3, Sell on day 4 at price 6

DP Profit: 7
🔍 Explanation
The program identifies profitable buy/sell points
Greedy captures every increasing sequence
DP validates the maximum achievable profit

 Comparison of Algorithms:
| Feature     | Greedy        | Dynamic Programming |
| ----------- | ------------- | ------------------- |
| Approach    | Local Optimum | Global Optimum      |
| Complexity  | O(n)          | O(n²)               |
| Efficiency  | High          | Moderate            |
| Flexibility | Limited       | High                |

 Future Enhancements:
Add graph visualization of stock prices
Build a web interface (React/HTML)
Support real-time stock data
Add constraints like transaction limits / cooldown

TEAM MEMBERS:
1) AP24110011006
2) AP24110010997
3) AP24110010982
4) AP24110011034
5) AP24110010936
