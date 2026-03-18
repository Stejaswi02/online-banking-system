# online-banking-system
# 🏦 Banking Management System (Python + MySQL + Email OTP)

## 📌 Description
This project is a **Banking Management System** developed using Python.  
It allows users to perform basic banking operations like account creation, deposit, withdrawal, PIN generation, and more.

The system also includes **Email OTP Verification** and **Greeting Email Feature**, making it more secure and interactive.

---

## 🚀 Features
- 🆕 Account Creation with OTP verification
- 💰 Deposit and Withdrawal
- 🔐 PIN Generation & Change PIN
- 📄 Mini Statement
- 📊 View All Account Details (Admin)
- 📧 Email OTP Authentication
- 🎉 Send Greetings via Email
- 🗂️ Data stored using MySQL Database

---

## 🛠️ Technologies Used
- Python 🐍
- MySQL 🗄️
- pymysql (Database Connectivity)
- smtplib (Email Sending)
- MIME (Email Formatting)
- Regular Expressions (Validation)

---

## ▶️ How to Run

1. Install required libraries:
```bash
pip install pymysql
```

2. Setup MySQL Database:
```sql
CREATE DATABASE banking;

USE banking;

CREATE TABLE accounts (
    acc_num INT PRIMARY KEY,
    name VARCHAR(50),
    email VARCHAR(50),
    balance FLOAT,
    pin INT
);
```

3. Clone the repository:
```bash
git clone https://github.com/your-username/banking-system.git
```

4. Navigate to the project folder:
```bash
cd banking-system
```

5. Run the program:
```bash
python banking.py
```

---

## 🔐 OTP Verification
- OTP is sent to the user's email
- Valid for secure authentication
- Required for:
  - Account Creation
  - PIN Generation

---

## 🎮 Functional Modules
1. Account Creation  
2. Deposit  
3. Withdrawal  
4. Mini Statement  
5. PIN Generation  
6. Get All Details (Admin Only)  
7. Change PIN  
8. Send Greetings  
9. Exit  

---

## 📂 Project Structure
```
banking-system/
│── banking.py
│── README.md
│── details.txt   # Generated file for admin
```

---

## ⚠️ Important Notes
- Enable **Less Secure Apps / App Password** in Gmail for sending emails
- Replace email credentials with your own
- Ensure MySQL server is running

---

## 💡 Future Improvements
- Add GUI interface 🖥️
- Encrypt PIN for better security 🔐
- Add transaction history 📜
- Integrate mobile OTP 📱
- Add user login system

---

## 👩‍💻 Author
**Tejaswi**

---

## 📜 License
This project is open-source and available under the MIT License.
