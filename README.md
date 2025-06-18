==============================
🎰 Java Slot Machine Game 🎰
==============================

📌 DESCRIPTION:
---------------
This is a simple command-line Java Slot Machine game. 
The player starts with a balance of $100 and places bets to spin the slot machine. 
Winnings are based on matched symbols. The game continues until the player chooses to quit or runs out of money.

🎯 FEATURES:
------------
✅ User starts with $100
✅ Validates bet amount (no negative or overbalance bets)
✅ Random slot symbols (🍒 🍉 🍋 🍎 🍇)
✅ Win payout based on matching 2 or 3 symbols
✅ Option to play again or quit
✅ Final balance display at end of game

🔧 REQUIREMENTS:
-----------------
- Java Development Kit (JDK) 8 or higher
- Command-line or any Java IDE (e.g., IntelliJ, VS Code, Eclipse)

📂 FILES INCLUDED:
-------------------
- `Main.java`   → The main game source code
- `README.txt`  → This description and guide

💰 PAYOUT RULES:
-----------------
3 Matching Symbols:
🍒 → x3, 🍉 → x4, 🍋 → x5, 🍎 → x10, 🍇 → x20

2 Matching Symbols (adjacent):
🍒 → x2, 🍉 → x3, 🍋 → x4, 🍎 → x5, 🍇 → x10

🔄 GAME FLOW:
--------------
1. Player sees current balance.
2. Enters a bet amount.
3. If valid, balance is deducted.
4. Slot spins and displays 3 symbols.
5. Game checks for matches and pays out accordingly.
6. Player decides whether to continue or exit.

🚀 HOW TO RUN:
--------------
1. Compile:
   javac Main.java

2. Run:
   java Main

