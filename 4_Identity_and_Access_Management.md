# Identity & Access Management (IAM)  
### Governance of Subjects and Objects  

---

## 📌 Overview
This module covers how access to systems is controlled, how identities are verified, and how actions are monitored within secure environments.

It includes:
- IAM core processes
- Authentication mechanisms
- Multi-Factor Authentication (MFA)
- Kerberos authentication model
- Password attack techniques & defenses

---

## 🧠 Subjects vs Objects

### 👤 Subjects
Entities that request access:
- Users
- Devices
- Processes

### 🗄️ Objects
Resources being accessed:
- Files
- Databases
- Servers
- Networks

> Access control systems define how subjects interact with objects.

---

## 🔐 The Four Core IAM Processes

- **Identification**  
  Assigning a unique identity to a subject  

- **Authentication**  
  Verifying identity using credentials  

- **Authorization**  
  Defining permissions and access rights  

- **Accounting (Auditing)**  
  Tracking actions and detecting anomalies  

---

## 🔑 Authentication Factors

![Authentication Factors](https://rublon.com/wp-content/uploads/2021/12/three-auth-factors-1024x754.png)

- **Something You Know** → Passwords / PINs  
- **Something You Have** → Tokens / Smart Cards  
- **Something You Are** → Biometrics  

---

## 🔐 Multi-Factor Authentication (MFA)

- Combines multiple authentication factors  
- **2FA:** Knowledge + Possession  
- **3FA:** Knowledge + Possession + Biometrics  

---

## 🔓 Single Sign-On (SSO)

- Authenticate once, access multiple systems  
- Reduces credential fatigue  
- Commonly implemented using **Kerberos**

---

## 🧠 Kerberos Authentication Model

![Kerberos Flow](https://miro.medium.com/1*B_XxW3GzF2y3HmlCtjeeeig.jpeg)

- Uses a trusted third party: **Key Distribution Center (KDC)**  
- Operates on **Port 88 (TCP/UDP)**  
- Components:
  - Authentication Server (AS)
  - Ticket Granting Server (TGS)

### 🔁 Authentication Flow

1. Client requests Ticket Granting Ticket (TGT)  
2. AS verifies identity using stored credentials  
3. TGT + Session Key are issued  
4. Client uses TGT to request services from TGS  

---

## 🔓 Password Attack Vectors

- **Plaintext Attacks**  
  Exploit insecure protocols (HTTP, FTP, Telnet)

- **Online Attacks**  
  Try passwords directly on login systems

- **Offline Attacks**  
  Crack stolen password hashes locally  

---

## ⚔️ Password Cracking Techniques

![Password Strength Chart](https://images.squarespace-cdn.com/content/v1/5ffe234606e5ec7bfc57a7a3/1745873102132-XQU3946KFHS7I18QV876/2025+Hive+Systems+Password+Table)

### Brute Force
- Tries all combinations  
- 🔒 Defense: Long passwords + account lockout  

### Dictionary Attack
- Uses common word lists  
- 🔒 Defense: Strong complexity rules  

### Rainbow Table
- Uses precomputed hashes  
- 🔒 Defense: Salting  

### Hybrid Attack
- Mix of dictionary + variations  
- 🔒 Defense: MFA  

---

## 🛡️ Security Insight

Strong IAM implementation is the foundation of any secure system.  
Most real-world breaches occur due to weak authentication or poor access control policies.

---

## 🙌 Conclusion
Understanding IAM is essential for securing systems, preventing unauthorized access, and detecting malicious behavior early.
