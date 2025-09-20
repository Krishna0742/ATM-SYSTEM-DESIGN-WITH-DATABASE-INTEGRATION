README - Banking/ATM Project (C in Console)

=================================================
1. Project Overview
=================================================
This is a Banking/ATM Simulation project in C that allows users to manage bank accounts through a console menu system.

- Language: C (Console Application)
- Features: Account creation, deposit, withdrawal, transfer, balance enquiry, account update, transaction history, and more.
- Data Storage: CSV files (Bank_Details.csv, transaction logs)

=================================================
2. Flow of the Project
=================================================

Entry Point: main.c

1. main.c
   - Starts program execution.
   - Calls Print_Menu() to display available options.

2. Print_Menu.c
   - Displays user menu options.
   - Routes user choice to respective modules.

3. Functional Modules
   - Create_Account.c: Creates new bank account and stores in Bank_Details.csv.
   - Deposit.c: Deposits money into selected account.
   - Withdraw.c: Withdraws money from an account.
   - Transfer_Money.c: Transfers money between accounts.
   - Balance_Enquery.c: Displays balance for a given account.
   - Update_Account.c: Updates account details (like name, address, etc.).
   - History.c: Maintains transaction history.
   - Display_All_Accounts.c: Shows details of all accounts.
   - Find_Specific_Account.c: Search for a specific account by ID.

4. Supporting Modules
   - Verify_PIN.c: Validates PIN for authentication.
   - Compare_Aadhar.c: Compares Aadhaar information for verification.
   - Verify_RFID.c: Handles RFID-based authentication (if enabled).
   - Save_To_File.c: Saves account information to Bank_Details.csv.
   - Sync_From_File.c: Loads account information from Bank_Details.csv.

5. Data Files
   - Bank_Details.csv: Stores account records (ID, name, balance, etc.).
   - Transaction history CSV files: Store transaction logs.

=================================================
3. Compilation & Execution
=================================================
1. Navigate to project folder:
   $ cd Projectt/Cminiproject

2. Compile using the makefile provided:
   $ make

3. Run the executable:
   $ ./a.out

4. Follow on-screen instructions to perform banking operations.

=================================================
4. Notes
=================================================
- Ensure Bank_Details.csv exists before running.
- PIN, Aadhaar, and RFID verification are simulated.
- Transaction history is maintained in CSV logs for record-keeping.

=================================================
5. Authors 
=================================================
ch.Anantha Krishna Nookaraju Developed as part of a Banking/ATM simulation project in C.
