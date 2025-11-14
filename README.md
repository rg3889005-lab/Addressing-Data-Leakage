# 🛡️ Addressing Data Leakage – Interactive Detection & Prevention Console

This project is a **web-based interactive console** designed to detect, analyze, and prevent **data leakage** across cloud collaboration environments.  
It simulates real-world auditing scenarios, detects sensitive information, and visualizes risk levels using modern UI components.

---

## 🚀 Features

### ✅ **1. Secure Login System**
- Separate access for **Admin** and **Standard Users**
- Admin credentials:  
  **Username:** `admin`  
  **Password:** `admin123`
- Tracks active sessions with simulated unique IDs

### 🔍 **2. Real-Time Data Leak Detection**
Automatically scans input text for sensitive patterns including:
- API Keys  
- Emails  
- Credit Card Numbers  
- Internal Memos  
- Social Security Numbers  
- Insecure Database / Backup Links  

Each detection is categorized by **Critical** or **High** severity.

### 📊 **3. Risk Visualization**
- A dynamic **Chart.js doughnut chart** displays:
  - Critical vulnerabilities
  - High-risk vulnerabilities

### 💬 **4. Team Communication Module**
- Live chat feature for collaboration among auditors
- Time-stamped messages
- Admin view includes full chat log

### 📝 **5. Admin Panel**
- Displays active sessions  
- Shows complete scan history for all users  
- Accordion-style logs with timestamps  
- Designed for real auditing workflows

### 🛡️ **6. Prevention Strategy Dashboard**
Three Security Pillars:
- **Governance Protocols**  
- **Infrastructure Tools**  
- **Personnel Training**

Each module contains actionable guidelines to mitigate data leaks.

---

## 📂 Project Structure

