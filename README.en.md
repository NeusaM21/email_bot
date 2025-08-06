![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)

![Project Cover](capa_nova.png)

# 📧 Automated Email Bot with Python

📄 This README is also available in [Portuguese 🇧🇷](README.md)

Automate sending personalized emails using Python and Excel spreadsheets.  
Perfect for billing, notifications, reminders, and recurring messages — fast, secure, and fully customizable.

---

## 🎬 Demo

Watch the bot running directly in the terminal:

![Email Bot Demo](email_bot_demo.gif)

---

## 🚀 Features

- 📊 Automatic reading of recipient data from spreadsheets  
- ✍️ Personalized message generation with name, amount, and due date  
- 📬 Automatic sending via Gmail with secure authentication  
- 🔐 Secure credential storage using `.env`  
- 🧩 Clean, commented code, easy to adapt to new scenarios  

---

## 🛠️ Requirements

- Python 3.x  
- Python libraries:  
  - `pandas`  
  - `openpyxl`  
  - `schedule`  
  - `python-dotenv`

---

## ⚙️ How to Use

1. **Clone the repository:**
   
   ```bash
   git clone https://github.com/NeusaM21/email_bot.git
   cd email_bot
   ```

---

## 🧾 Example of clientes.xlsx spreadsheet:

| Nome  | Email            | Valor  | Vencimento   |
|-------|------------------|--------|--------------|
| João  | joao@email.com   | 150.0  | 01/07/2025   |
| Maria | maria@email.com  | 200.0  | 03/07/2025   |
| Pedro | pedro@email.com  | 300.0  | 05/07/2025   |

---

🔒 Security with .env
This project uses a .env file to store sensitive data (like your email and app password).
This file is included in .gitignore and will not be uploaded to GitHub for security reasons.

---

## Example of `.env` file:

```env
EMAIL_SENDER=youremail@gmail.com
APP_PASSWORD=your_app_password
```


⚠️ Never share or upload your .env file. It contains sensitive information!

---

## 👩‍💻 Author

Made with 💙 by [NeusaM21](https://github.com/NeusaM21)

---

## 📬 Contact Me

Want to chat or need a custom automation?

---

## 📬 Contact

📧 Professional Email: [Send Email](mailto:contact.neusam21@gmail.com)  
🛡️ Available for freelance projects and collaborations!

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---




