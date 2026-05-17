# 🔐 MyPass — Password Manager

> A lightweight CLI tool to store, retrieve, and generate passwords — all locally, all yours.

Built in Python as a practical dive into file handling, data structures, and real-world CLI design. No bloat, no cloud dependency — just a fast, simple manager that works from your terminal.

---

## 🎯 What It Does

MyPass lets you save credentials for any service, retrieve them instantly, and copy passwords straight to your clipboard — all from the command line.

---

## ✨ Features

- 🔑 Save credentials (service, email, password) in one command
- 🔍 Retrieve stored passwords instantly by service name
- 📋 Auto-copies password to clipboard via `pyperclip`
- 💾 Persistent local storage using JSON
- ⚡ Minimal CLI — no setup overhead

---

## 🛠 Tech Stack

| | |
|---|---|
| Language | Python 3 |
| Storage | JSON |
| Clipboard | pyperclip |
| Packaging | Poetry |

---

## 📂 Project Structure

```
MyPass/
├── main.py          # Core CLI logic
├── data.json        # Local credential store
├── pyproject.toml   # Dependencies
└── poetry.lock
```

---

## ⚙️ Installation

```bash
# Clone the repo
git clone https://github.com/withaarav/Password-Manager.git
cd Password-Manager

# Install dependencies
pip install pyperclip

# Run
python main.py
```

---

## 💡 How It Works

Credentials are stored in `data.json` as structured entries:

```json
{
  "github": {
    "email": "you@example.com",
    "password": "your_password"
  }
}
```

On retrieval, the password is loaded and copied to your clipboard automatically.

---

## 🧠 What I Learned

- Structuring real-world CLI tools in Python
- Reading and writing persistent data with JSON
- Handling user input and edge cases cleanly
- Using `pyperclip` for clipboard integration

---

## ⚠️ Disclaimer

This is a **learning project** — passwords are stored in plain text locally. Not intended for production use. Encryption is on the roadmap.

---

## 🔮 What's Next

- [ ] Encrypt stored passwords (Fernet / AES)
- [ ] Add a master password with hashed authentication
- [ ] GUI version with Tkinter or PyQt
- [ ] Cloud sync option

---

## 📬 Contact

Made by [Aarav Porwal](https://github.com/withaarav) · with.aarav@gmail.com
