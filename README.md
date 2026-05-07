# 🔐 Cipher Studio

An interactive encryption & decryption tool built to explore classic cipher techniques — hands-on, visual, and beginner-friendly.

---

## 🌐 Live Demo

[suryanshi-web.github.io/Cipher-Studio](https://suryanshi-web.github.io/Cipher-Studio/)

---

## 💡 About

Cipher Studio lets you experience how classic encryption algorithms actually work — just type a message, pick a cipher, and watch it transform in real time. Built to make cryptography concepts tangible rather than theoretical.

---

## 🔑 Ciphers Included

| Cipher | Type | What it does |
|---|---|---|
| Caesar | Encrypt / Decrypt | Shifts each letter by a fixed number |
| ROT13 | Encode | Rotates each letter by 13 positions |
| Vigenère | Encrypt / Decrypt | Uses a keyword to shift letters |
| Atbash | Encode | Mirrors the alphabet — A↔Z, B↔Y |
| Base64 | Encode / Decode | Encodes text as ASCII-safe format |
| Morse Code | Encode / Decode | Converts text to dots and dashes |
| Steganography | Hide / Reveal | Hides secret text inside an image (LSB method) |

---

## ✨ Features

- Live output as you type
- Encrypt / Decrypt toggle where applicable
- Copy output to clipboard
- Morse Code reference chart
- LSB image steganography via Python/Flask backend
- Responsive — works on mobile too

---

## 🛠 Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)

Frontend in pure HTML, CSS, and JavaScript. Steganography feature uses a Python/Flask backend.

---

## 📂 Structure

```
Cipher-Studio/
├── index.html   — structure & layout
├── style.css    — styling & theme
├── script.js    — all cipher logic & interactions
└── app.py       — Flask backend for steganography
```

---

## ⚙️ Running Locally

The steganography tab requires the Flask server to be running:

```bash
pip install flask flask-cors pillow
python app.py
```

Then open `index.html` in your browser. All other ciphers work without the server.