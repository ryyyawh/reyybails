# reyybails - the baileys support all base

![rey](https://ar-hosting.pages.dev/1747015064481.jpg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Node.js](https://img.shields.io/badge/Node.js-18.x-green)  
![Baileys](https://img.shields.io/badge/Baileys-Custom-orange)
> Custom WhatsApp Multi-Device Bot based on [@whiskeysockets/baileys](https://github.com/WhiskeySockets/Baileys), built for automation, bug tools, and Telegram integration.

---

## 📌 Features

- 💬 WhatsApp Multi-Device support via custom Baileys
- 🤖 Modular Command System (SC-Based)
- 📦 Telegram Bot integration for remote control
- 🐞 WhatsApp Bug Tools (Relay & Interactive Bug Methods)
- 🔐 GitHub Token-based Session & Number Verification
- 🧠 Memory/Session Management
- 🧱 Clean, Customizable Folder Structure
- ⚙️ Plugin-ready architecture (`func/`, `system/`, etc.)

---

## ⚙️ Requirements

- Node.js `>=18.x`
- Git
- WhatsApp Number (paired with device)
- Telegram Bot Token (if Telegram interface is used)

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/ryyyawh/reyybails
cd reyybails

# Install dependencies
npm install

# Start the bot
node main.js


---

💡 How to Use

1. Pair WhatsApp Device

Upon starting main.js, follow terminal instructions to pair a WhatsApp device using the 6-digit code method.

Session will be saved in sessions/<token>.json.


2. Telegram Bot Commands

If using Telegram control, create a bot at BotFather, get the token, and configure it in telegram/main.js. Some commands:

/sendwa <token> <number> <message>     → Send message from session
/xtrashevryy <token> <number>          → Execute bug relay attack
/addwa <number>                        → Add verified WhatsApp number

3. Bug Tools (func/)

Functions like:

sendOPInteractiveStatus

protocolnew

Delaying

ligthnêt

xneverdie


Can be called from Telegram or CLI using format:

bugFunction(bot, target)
and all other functions (support all)

---

🛠️ Customization

Modify or add your bug tools inside func/

Commands are handled modularly from Telegram & WhatsApp

You can integrate GitHub API to fetch/store verified numbers dynamically



---

📜 License

This project is licensed under the MIT License.
Feel free to fork, modify, and use for educational or testing purposes.


---

👤 Author

github: @ryyyawh
telegram: @conquerryy

---

⭐ Star This Repo

If you find this useful, please consider giving it a ⭐ to support future development!
