# 💻Payment Management Module

Welcome to the **Payment Management Module** repository for the Object-Oriented Programming (OOP) course. This project involves designing and implementing a system to manage various payment services for a company. Below is a detailed guide on the project's requirements, structure, and implementation.

---

## 📖 Overview
This project simulates a payment management system with three payment service types:
1. **Convenient Card**
2. **EWallet**
3. **Bank Account**

### Key Features:
- Manage payment service accounts.
- Process transactions such as payments and money transfers.
- Handle exceptions and specific transaction requirements.
- Implement interfaces for extensible functionality.

---

## 🗂️ Project Structure

```plaintext
.
├── Input Files
│   ├── IDCard.txt               # Contains ID card information.
│   ├── PaymentInformation.txt   # Details of payment service accounts.
│   ├── TopUpHistory.txt         # History of top-up transactions.
│   ├── Bill.txt                 # Details of payment transactions.
├── Expected Output
│   ├── Req3.txt
│   ├── Req4.txt
│   ├── Req5.txt
│   ├── Req6.txt
│   ├── Req7.txt
│   ├── Req8.txt
│   ├── Req9.txt
├── Source Files
│   ├── TestReq1.java            # Tests for Requirement 1.
│   ├── TestReq2.java            # Tests for Requirement 2.
│   ├── Test.java                # Tests for Requirements 3-9.
│   ├── Bill.java                # Predefined Bill class.
│   ├── CannotCreateCard.java    # Custom exception for card creation.
│   ├── IDCard.java              # IDCard class.
│   ├── IDCardManagement.java    # Manages IDCard objects.
│   ├── ConvenientCard.java      # ConvenientCard class.
│   ├── EWallet.java             # EWallet class.
│   ├── BankAccount.java         # BankAccount class.
│   ├── TransactionProcessing.java # Handles transaction processing.
└── README.md                   # Documentation for the project.
```

---

## 🔧 Setup and Execution

1. **Input Files**
   - Ensure the `input` directory contains the required files: `IDCard.txt`, `PaymentInformation.txt`, `TopUpHistory.txt`, and `Bill.txt`.

2. **Compilation**
   - Use `javac` to compile all `.java` files:
     ```bash
     javac *.java
     ```

3. **Execution**
   - Run the provided test files to validate the implementation of each requirement:
     ```bash
     java TestReq1   # Test Requirement 1
     java TestReq2   # Test Requirement 2
     java Test       # Test Requirements 3-9
     ```

4. **Output Files**
   - Results will be written to the `output` directory for comparison with expected results in the `expected_output` folder.

---

## 📋 Requirements

### **Core Requirements**
1. **ConvenientCard Class Implementation**
   - Define rules for creating cards based on age.
   - Handle `CannotCreateCard` exceptions.

2. **EWallet and BankAccount Transfer Implementation**
   - Implement the `transfer` method for handling money transfers with transaction fees.

3. **File Parsing**
   - Parse `PaymentInformation.txt` to populate payment accounts.

4. **Adult Convenient Cards**
   - Filter and return a list of adult ConvenientCard accounts.

5. **Accounts with All Services**
   - Identify customers who have all three service types.

6. **Top-Up Processing**
   - Process top-up transactions from `TopUpHistory.txt`.

7. **Unsuccessful Transactions**
   - Identify failed transactions from `Bill.txt`.

8. **Largest Bank Payments**
   - Determine accounts with the largest successful bank payments.

9. **Discounted Transactions**
   - Apply discounts to eligible transactions based on customer attributes and purchase details.

---

## 📌 Notes
- Ensure all file paths are relative for compatibility.
- Modify `main` methods in test files for additional debugging if needed.
- Compare output files against `expected_output` for validation.

---

## 📝 Submission Guidelines
1. Submit the following files only:
   - `ConvenientCard.java`
   - `EWallet.java`
   - `BankAccount.java`
   - `IDCard.java`
   - `TransactionProcessing.java`

2. Structure for submission:
   ```plaintext
   MSSV_HoTen.zip
   ├── ConvenientCard.java
   ├── EWallet.java
   ├── BankAccount.java
   ├── IDCard.java
   └── TransactionProcessing.java
   ```

3. Submit the `.zip` file to the ELIT system by **23:59, 04/06/2023**.

---

## ⚖️ Rules and Regulations
- Use **Java 11** or **Java 8**.
- Do not alter method names or signatures.
- Avoid hardcoding file paths.
- Ensure the program compiles and runs using provided `main` methods.
- Any plagiarism or unauthorized assistance will result in disqualification.

---

## 🤝 Acknowledgements
Special thanks to Ton Duc Thang University and the Faculty of Information Technology for providing this comprehensive exercise in Object-Oriented Programming.

---
