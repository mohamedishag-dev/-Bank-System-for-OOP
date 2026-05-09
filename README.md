# Bank Management System (OOP)

A professional-grade **Bank Management System** featuring a multi-user environment with an integrated **Permissions System**.
This application allows administrators to manage clients and bank staff (users) with specific access levels, ensuring secure financial operations.

---
## 🌟 Key Features

- 👤 **Manage Users**
    - Show Users
   - Add
   - Delete
   - Update
   - Find 
- 👤 **Manage Clients**
   - Show Clients
   - Add
   - Delete
   - Update
   - Find 
- 💰 **Transactions** 
   - Deposit
   - Withdraw
   - Total Balances
   - Transfar
   - Transfar Log
- 🔑 **User Authentication** 
- 📂 **File Persistence**
- 🛡️ **Role-based Permissions**

  
---
## 📁 Project Structure
```
-Bank-System-for-OOP/
│
├── 📁 src          # Source code files
│   ├── main.cpp        # Entry point of the program
│   ├── 📁 logic        # Core banking logic
│   │    ├── clsUser.h
│   │    ├── clsPerson.h 
│   │    └── clsBankClient.h     
│   └── 📁 Models       # Account and client models
│
├── 📁 data                # Data storage
│   ├── Users.txt          # File storing client information
│   ├── Clients.txt        # File storing User information
│   ├── Currencies.txt     # File storing Currency information
│   ├── TransferLog.txt    # File storing Transfer information
│   └── LoginRegister.txt  # File storing Login Register information
│ 
├── 📁 docs              # Documentation
│   ├── flowcharts.pdf    # Visual diagrams of system workflow 
│   └──📁 screenshots    # File storing screenshots
│
├── 📁 tests            # Unit tests and validation
│
├── .gitignore          # Ignore temporary files
├── LICENSE             # License information
└── README.md           # Project documentation
```
---

## 🛠️ Installation & Usage 

```bash
# Clone repository
git clone https://github.com/mohamedishag-dev/-Bank-System-for-OOP.git
```
```bash
# Compile
g++ src/main.cpp -o bank_system
```
```bash
# Run
./bank_system
```
