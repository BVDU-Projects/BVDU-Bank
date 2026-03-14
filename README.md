# 🏦 BVDU-Bank — Banking & Trading Management System (C)

<p align="center">
  <img src="bvdu_bank_logo.png" alt="BVDU Bank Logo" width="180"/>
</p>

**Banking Vision for Development & Unity (BVDU)** — a complete **Banking + Trading simulation** written in **C language** using **file handling**.  
It allows users to manage accounts, perform UPI transfers, pay bills, and trade in stocks, crypto, and forex — all in one text-based ecosystem.

---

[![License: MIT](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Language: C](https://img.shields.io/badge/language-C-blue.svg)](bvdu_bank.c)

---

## 🧩 Features

✅ Create and manage multiple bank accounts  
✅ Automatic account number generation  
✅ Unique and secure UPI IDs (`name@bvdu`)  
✅ Deposit, withdraw, and transfer money  
✅ UPI transfers only within registered users  
✅ Built-in trading for Stocks, Crypto, and Forex  
✅ Real-time random market price updates  
✅ Portfolio tracking with colored P/L display  
✅ Admin dashboard (PIN: **0013**)  
✅ Account freeze after 3 failed PIN attempts  
✅ Admin audit log and notifications system  
✅ FX conversion for USD and EUR markets  
✅ Time-based market open/close simulation  
✅ File-based data persistence — no database required  

---

## ⚙️ Requirements

- **Compiler:** GCC / MinGW / any C99 compatible compiler  
- **Platform:** Windows / Linux / macOS (terminal based)  
- **Editor (recommended):** VS Code  

---

## 📂 Files Included

| File | Description |
|------|--------------|
| `bvdu_bank.c` | Main C source code |
| `accounts.txt` | Account data file |
| `holdings.txt` | Portfolio holdings |
| `prices.txt` | Market prices (stocks/crypto) |
| `transactions.txt` | Transaction logs |
| `fx_rates.txt` | Exchange rate data |
| `admin_audit.txt` | Admin audit log |
| `notifications.txt` | Account notifications |
| `README.md` | Project documentation |
| `LICENSE` | MIT License |
| `AUTHORS.md` | Author and credits |

---

## 🏗️ How to Build & Run

### 🖥️ Compile
```bash
# Windows (MinGW)
gcc bvdu_bank.c -o bvdu_bank.exe

# Linux / macOS
gcc bvdu_bank.c -o bvdu_bank
```

### ▶️ Run
```bash
# Windows
.vdu_bank.exe

# Linux / macOS
./bvdu_bank
```

---

## 🧮 Demo Walkthrough

1. **Create Account** → Choose account type (Savings / Current)  
2. **Deposit** → Add money to your account  
3. **Transfer / UPI** → Send money only within BVDU accounts  
4. **Trading App** → Buy/Sell stocks, crypto, or forex assets  
5. **Admin Login (PIN: 0013)** → Apply interest, update rates, audit logs  
6. **Portfolio View** → Check performance in color-coded P/L  
7. **Account Freeze** → After 3 wrong PIN attempts, admin must unfreeze  

---

## 📊 Example Data Format

**accounts.txt**
```
1001|Adarsh|Savings|1234|5000.00|0.00|1|0|0|adarsh@bvdu|2025-10-15 10:23:00
```

**prices.txt**
```
AAPL|Apple Inc|190.00|0.02|US|2025-10-15 12:00:00|9|17
INFY|Infosys Ltd|1500.00|0.01|IN|2025-10-15 12:00:00|9|15
BTC|Bitcoin|35000.00|0.05|US|2025-10-15 12:00:00|0|24
```

---

## 🧠 Project Structure

```
BVDU-Bank/
├── bvdu_bank.c
├── accounts.txt
├── holdings.txt
├── prices.txt
├── transactions.txt
├── notifications.txt
├── admin_audit.txt
├── fx_rates.txt
├── README.md
├── AUTHORS.md
├── CONTRIBUTORS.md
├── LICENSE
└── bvdu_bank_logo.png
```

---

## 💡 Notes

- All data is stored in plain text files — ideal for learning file handling.  
- No SQL or external libraries required.  
- The market updates dynamically using volatility-based randomization.  
- Account and portfolio data persist between sessions.  

---

## 👥 Contributors

Lead Developer  
- **Adarsh Satyajit Adhikary** — System Architecture, Core Development, and Project Maintenance

Contributors  
- **Achyut Nayak** — Testing, Debugging, and Code Review  
- **Ayush Shashibhushan Tripathi** — Feature Feedback and System Testing  
- **Aabir Nilu Das** — Documentation Support and UI Suggestions

---

## 📜 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it with credit.  
See [LICENSE](LICENSE) for details.
