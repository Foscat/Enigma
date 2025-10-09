# 🧩 Caesar's Enigma

**Caesar’s Enigma** is a modern reimagining of the classic Caesar cipher — a simple yet powerful web-based encryption tool built with HTML, CSS, and JavaScript.  
It lets users **encrypt and decrypt text**, **copy or paste messages**, and **learn how it all works** through an accessible, built-in guide.

🔗 **Live Demo:** [https://foscat.github.io/Enigma/](https://foscat.github.io/Enigma/)

---

## ⚙️ Overview

This project takes inspiration from the ancient Caesar cipher — one of the earliest known encryption techniques — and expands on it with a **universal alphabet system** that supports:

- Letters, numbers, punctuation, and symbols.
- Modern UTF-8 characters.
- Full bidirectional (encrypt/decrypt) message handling.

It’s a clean, interactive, front-end application with no server dependencies, designed for **educational use, secure local testing, and lightweight message encoding.**

---

## ✨ Features

✅ **Modified Caesar Cipher Logic**  
A more flexible algorithm that can handle multi-byte characters (like emojis) and full UTF-8 input.

✅ **Universal Alphabet Support**  
Encrypts nearly any character a user can type — including emojis, punctuation, and whitespace.

✅ **Dual Mode Operation**  
Automatically detects and decrypts tagged messages or encrypts new input.

✅ **Clipboard Integration**  
Easily copy encrypted messages or paste text directly from your clipboard.

✅ **Accessible UI/UX**  
A clean, dark-blue themed interface with high-contrast design, keyboard navigation, and a modal help guide accessible via an info icon.

✅ **Responsive Design**  
Fully responsive layout, ideal for both desktop and mobile users.

---

## 🧠 How It Works

1. **Input your text** in the provided textarea.
2. **Encrypt** the message using the "Encrypt" button.  
   - The cipher shifts characters within a predefined alphabet, wrapping around seamlessly.  
   - Each character maps to another within the universal set.
3. **Decrypt** an encrypted message using the "Decrypt" button.  
   - The algorithm reverses the shift and restores your original text.
4. **Double-click** the input box to auto-detect and process the message (encrypt or decrypt automatically).
5. **Copy** or **Paste** using the clipboard buttons for quick sharing.
