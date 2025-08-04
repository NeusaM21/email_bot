![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat-square)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

![Capa do Projeto](capa_nova.png)

# 📧 Bot de E-mails Automáticos com Python

Automatize o envio de e-mails personalizados usando Python e planilhas Excel.  
Ideal para cobranças, notificações, lembretes e mensagens recorrentes — tudo de forma rápida, segura e personalizável.

---

## 🚀 Funcionalidades

- 📊 Leitura automática de planilha com dados dos destinatários  
- ✍️ Geração de mensagens personalizadas com nome, valor e vencimento  
- 📬 Envio automático via Gmail com autenticação segura  
- 🔐 Armazenamento seguro de credenciais usando `.env`  
- 🧩 Código limpo, comentado e fácil de adaptar a novos cenários  

---

## 🛠️ Requisitos

- Python 3.x  
- Bibliotecas Python:  
  - `pandas`  
  - `openpyxl`  
  - `schedule`  
  - `python-dotenv`

---

## ⚙️ Como Usar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/NeusaM21/email_bot.git
   cd email_bot
   ```


---

## 🧾 Exemplo da planilha `clientes.xlsx`:

| Nome  | Email           | Valor | Vencimento  |
|-------|------------------|--------|--------------|
| João  | joao@email.com   | 150.0  | 01/07/2025   |
| Maria | maria@email.com  | 200.0  | 03/07/2025   |
| Pedro | pedro@email.com  | 300.0  | 05/07/2025   |

---

## 🔒 Segurança com `.env`

Este projeto usa um arquivo `.env` para armazenar dados sensíveis (como seu e-mail e senha de app).  
Esse arquivo está no `.gitignore` e **não será enviado ao GitHub** por segurança.

---

### Exemplo de `.env`:

```env
EMAIL_REMETENTE=seuemail@gmail.com
SENHA_DO_APP=sua_senha_de_aplicativo
```


⚠️ *Nunca compartilhe ou faça upload do seu `.env`. Ele contém informações sensíveis!*

---

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais informações.

---

## 👩‍💻 Autora

Feito com 💙 por [NeusaM21](https://github.com/NeusaM21)

---

## 📬 Fale Comigo

Quer trocar uma ideia ou precisa de uma automação personalizada?

📧 E-mail: [contact.neusam21@gmail.com](mailto:contact.neusam21@gmail.com)  
🌐 GitHub: [github.com/NeusaM21](https://github.com/NeusaM21)

---


