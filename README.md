# 📬 Python Mail Client (Tkinter GUI)

This project is a simple desktop email client built using **Python** and **Tkinter**. It allows users to send emails through Gmail’s SMTP server and view inbox messages using the POP3 protocol.

---

## 🚀 Features

- ✅ Send emails with subject and message body
- 🔁 Reset all input fields
- 📥 Retrieve and display inbox messages (POP3)

---

## 🛠️ Built With

- `Tkinter` – for GUI components  
- `smtplib` – for sending emails via SMTP  
- `poplib` – for fetching emails from the inbox  

---

## 📷 GUI Overview

The interface includes:
- Input fields for:
  - Email
  - Password
  - Recipient’s email
  - Subject
  - Message body
- Buttons for:
  - **Send**
  - **Reset**
  - **Show Inbox**

---

## ⚙️ How to Run

1. **Install Python** (>=3.6)
2. Clone this repo or download the `.ipynb` file
3. Run the notebook using Jupyter or JupyterLab

---

## 📌 Important Notes

- This client uses Gmail’s SMTP (`smtp.gmail.com:587`) and POP3 (`pop.googlemail.com:995`)
- If you're using Gmail:
  - Enable **"Less secure app access"** in your Google Account settings *(not recommended for production use)*
  - Or use an **App Password** if you have 2FA enabled
- **Avoid hardcoding credentials** in production; use environment variables or OAuth

---

## 🧠 Future Improvements

- Use OAuth2 for secure authentication
- Add support for attachments
- Improve inbox rendering with a better GUI layout
- Switch from POP3 to IMAP for more advanced email management

---

## 📝 License

This project is for educational purposes only. Use responsibly.

---

## 🙋‍♂️ Author

Made with ❤️ by [Your Name]
