# Secure-International-Payment-System-for-Banking-Operations

**Description:**  
The **Secure International Payment System** is a web-based application designed to facilitate secure and seamless international payments for customers of an international bank. The system includes two portals:  

1️⃣ **Customer Portal**  
   - Enables customers to securely register, log in, and initiate international payments.  
   - Provides options to select payment amounts, currencies, and providers (e.g., SWIFT).  
   - Ensures all sensitive customer data is encrypted, validated, and securely stored.  

2️⃣ **Employee Portal**  
   - Accessible only to pre-registered employees.  
   - Allows employees to verify transactions by checking the payee's account information and SWIFT codes.  
   - Provides functionality to forward transactions to the SWIFT system upon verification.  

**Key Features:**  

### 🛡️ Security  
- **Password Security:** Implements hashing and salting to protect user passwords.  
- **Input Validation:** Whitelists inputs using regular expressions (RegEx) to prevent invalid or malicious data entries.  
- **Data Protection in Transit:** Uses **SSL/TLS** to encrypt traffic and ensure secure communication.  
- **Protection Against Attacks:** Implements measures against common vulnerabilities, including:  
  - Session Jacking  
  - Clickjacking  
  - SQL Injection  
  - Cross-Site Scripting (XSS)  
  - Man-in-the-Middle (MitM)  
  - Distributed Denial of Service (DDoS)  

### 🌐 Customer Portal  
- **Customer Registration:**  
  Allows customers to register by providing personal information like full name, ID number, account number, and password.  
- **Customer Login:**  
  Customers log in using their username, account number, and password.  
- **Dashboard:**  
  Displays a personalized greeting and enables users to initiate payments.  
- **Payment Workflow:**  
  Guides customers through entering recipient account details, SWIFT codes, payment amounts, and selecting payment providers.  

### 💼 Employee Portal  
- **Employee Login:**  
  Employees securely log in to access customer transactions.  
- **Transaction Verification:**  
  Employees review and validate customer transaction details, ensuring the correctness of account and SWIFT codes.  
- **Submit to SWIFT:**  
  Verified transactions are forwarded to SWIFT for processing.  

### 🔧 Technical Specifications  
- **Frontend:** React/Angular for a responsive and dynamic user interface.  
- **Backend:** Node.js with Express for secure and efficient API implementation.  
- **Database:** Secure storage of sensitive data using hashing, salting, and encryption mechanisms.  
- **CI/CD Pipeline:** GitHub repository integrated with **CircleCI** to run automated **SonarQube** scans for hotspots and code smells.  

**How It Works:**  
1. Customers register and log in to initiate payments.  
2. Payments are securely stored in a database and displayed on the employee portal.  
3. Employees log in, verify the transactions, and forward them to SWIFT upon approval.  

**Why This Project?**  
This project highlights the integration of robust security practices and efficient workflows for financial applications. It serves as a comprehensive solution to meet the needs of customers and employees while maintaining the highest security standards.  

**Technologies Used:**  
- **Frontend:** React/Angular  
- **Backend:** Node.js with Express  
- **Database:** MongoDB/PostgreSQL (with encryption)  
- **Security:** SSL/TLS, hashing, salting, input validation  
- **CI/CD:** CircleCI with SonarQube for quality assurance  

This project demonstrates proficiency in **web development**, **secure coding practices**, and **financial system workflows**.
