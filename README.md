# Automated-email-sender
A Python-based automated email sender that allows users to send emails to multiple recipients using **SMTP**. This script supports **attachments, HTML emails, and scheduling**.

---

## **🚀 Features**  
- ✅ **Send emails automatically** using Python  
- ✅ **Supports attachments** (PDF, images, etc.)  
- ✅ **Send emails in bulk** to multiple recipients  
- ✅ **HTML-formatted emails** for better design  
- ✅ **SMTP authentication** for secure sending  
- ✅ **Schedule emails** using Python's `schedule` library  

---

## **🛠️ Tech Stack**  
- **Programming Language:** Python  
- **Email Protocol:** SMTP (Simple Mail Transfer Protocol)  
- **Libraries Used:**  
  - `smtplib` – Sending emails via SMTP  
  - `email` – Formatting emails (attachments, HTML)  
  - `schedule` – Automating email sending  
  - `dotenv` – Managing environment variables securely  

---

## **📂 Installation**  

### 1️⃣ **Clone the repository**  
```sh
git clone https://github.com/your-username/automated-email-sender.git
cd automated-email-sender
```

### 2️⃣ **Create a virtual environment**  
```sh
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

### 3️⃣ **Install dependencies**  
```sh
pip install -r requirements.txt
```

### 4️⃣ **Set up your email credentials**  
- Create a **`.env`** file in the project directory and add:  
  ```env
  EMAIL_HOST=smtp.gmail.com
  EMAIL_PORT=587
  EMAIL_USER=your-email@gmail.com
  EMAIL_PASSWORD=your-password
  ```

🔹 **Important:** If using Gmail, enable **Less Secure Apps** or set up an **App Password**.

---

## **📤 Usage**  

### **1️⃣ Run the script to send an email**  
```sh
python send_email.py
```

### **2️⃣ Schedule emails (Optional)**  
Modify `schedule_email.py` to set **time intervals** and run:  
```sh
python schedule_email.py
```

---

## **📸 Screenshots**  
_Add screenshots of your script in action!_  
```md
![Email Sent Example](path-to-image/email-example.png)
```

---

## **📌 Future Enhancements**  
- Add support for **OAuth authentication** (e.g., Gmail API)  
- Implement **email tracking & analytics**  
- Improve **error handling & logging**  

---

## **🏆 Contributing**  
We welcome contributions! Feel free to submit **issues** or **pull requests**.

---

## **📜 License**  
This project is licensed under the **MIT License**.

---

Would you like help modifying this README for your specific implementation? 🚀😊
