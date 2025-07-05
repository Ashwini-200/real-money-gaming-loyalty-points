# real-money-gaming-loyalty-points

# Real-Money Online Gaming Loyalty Points Analysis

This project analyzes player transaction data for **ABC**, a real-money online gaming company that offers multiplayer games like Ludo.  
The goal is to calculate loyalty points for players based on their activity and suggest a fair way to distribute bonus money to the top loyal players.

---

## 📌 Project Objective

ABC wants to:
- Retain players by rewarding loyalty points.
- Calculate loyalty points for deposits, withdrawals, and games played.
- Rank players monthly and decide bonus payouts.

---

## 📊 Tasks Covered

- Calculate **slot-wise loyalty points** for specific dates:
  - 2nd October, Slot S1 (12 AM - 12 PM)
  - 16th October, Slot S2 (12 PM - 12 AM)
  - 18th October, Slot S1 (12 AM - 12 PM)
  - 26th October, Slot S2 (12 PM - 12 AM)
- Rank players by total loyalty points for October.
- Resolve ties using number of games played.
- Compute:
  - Average deposit amount
  - Average deposit per user
  - Average games played per user
- Suggest a method to split Rs. 50,000 bonus pool for the top 50 players.
- Evaluate fairness of the loyalty point formula and recommend improvements.

---

## ⚙️ Tech Stack

- Python
- Jupyter Notebook
- pandas, numpy (data analysis)

---

## 📂 Project Structure

/ (root folder)
 ├── ABC_Loyalty_Analysis.ipynb   # Main analysis notebook
 ├── Report.pdf                   # Summary of approach and findings
 ├── /data
 │   ├── user.csv
 │   ├── deposit.csv
 │   ├── withdrawal.csv
 ├── /screenshots
 │   ├── slot_calculation.png
 │   ├── leaderboard.png
 └── README.md                    # This file

---

## ✅ How to Use

1. Clone this repo.
2. Open `ABC_Loyalty_Analysis.ipynb` in Jupyter Notebook.
3. Run all cells to see:
   - Slot-wise loyalty point calculations.
   - Monthly rankings.
   - Suggested bonus distribution.
4. Read `Report.pdf` for a clean project summary.

---

## 📌 Key Insights

- Loyalty points are weighted by deposits, withdrawals, and games played.
- Formula balances financial activity with platform engagement.
- Bonus suggestion is fair, proportional, and encourages active users.
- Suggestions provided to make the formula more robust and fraud-proof.

---

## 🔗 Contact

**Prepared by: Asghwini K B  
**LinkedIn: https://www.linkedin.com/in/ashwini-k-b-60a88a218/

---

## 🚀 Next Steps

- [ ] Add visuals or charts for clearer presentation.
- [ ] Polish markdowns and comments in the notebook.
- [ ] Showcase screenshots in the `screenshots` folder.
