# ATM
ATM Machine Mechanism (TypeScript Simulation)

This project is a simulation of an Automated Teller Machine (ATM) built using TypeScript, designed to mimic the core functionalities of an ATM including user authentication, balance inquiry, deposits, and withdrawals. The purpose is to demonstrate how modern JavaScript/TypeScript features can be applied in simulating a real-world banking scenario with clean, modular code.


---

🚀 Features

User Login Simulation
Mimics ATM card authentication using predefined account data.

Balance Inquiry
Users can view their current account balance.

Cash Deposit
Functionality to simulate depositing money into an account.

Cash Withdrawal
Handles fund withdrawals with validations (e.g., insufficient balance).

Transaction History (optional based on extension)
Can be extended to show recent transactions.

Modular Codebase
Built using TypeScript's strong typing and modular approach for better maintainability and scalability.



---

🧰 Tech Stack

TypeScript – Main language for logic and structure.

Node.js – Execution environment.

npm – Dependency manager for TypeScript and related packages.



---

📁 Project Structure

ATM-Machine-Mechanism-main/
│
├── ATM.ts                # Main TypeScript logic for the ATM system
├── ATM.js                # Transpiled JavaScript from TypeScript
├── package.json          # Project metadata and dependencies
├── tsconfig.json         # TypeScript configuration
├── README.md             # Project overview and usage
└── .gitignore            # Node and TypeScript artifacts ignored by Git


---

🛠️ Setup & Run

# Clone the repository
git clone https://github.com/yourusername/ATM-Machine-Mechanism.git
cd ATM-Machine-Mechanism

# Install dependencies
npm install

# Compile TypeScript to JavaScript
npx tsc

# Run the program
node ATM.js


---

📚 How It Works

Users interact with a CLI-based ATM.

Accounts are defined with balances and PINs in the code (simulating a database).

Input is taken through the console to perform different ATM operations.

TypeScript ensures proper data types, better IDE support, and cleaner error handling.



---

📌 Future Enhancements

Integrate with a file-based or database-backed system for persistent account storage.

Add UI using Electron or a web frontend.

Add internationalization and multi-language support.

Extend transaction logs and implement receipts.



---

👨‍💻 Author

Muzammil Khan
Computer Science Student | Backend & Systems Enthusiast
LinkedIn • GitHub

