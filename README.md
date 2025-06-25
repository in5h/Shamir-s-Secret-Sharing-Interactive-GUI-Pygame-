
---

# 🔐 Shamir's Secret Sharing – Interactive GUI (Pygame)

A Python-based graphical simulator for **Shamir’s Secret Sharing** using **Pygame**. This interactive application visually demonstrates how secrets are split into shares and reconstructed using Lagrange interpolation, with step-by-step explanations of every calculation involved.

---

## 🎯 Features

* 🧮 **Generate Shares** from a secret using a threshold-based polynomial
* 🔓 **Reconstruct Secret** from a subset of shares
* 📜 **Step-by-step visualization** of both generation and reconstruction
* 👨‍🏫 **Educational interface** for learning modular arithmetic, Lagrange interpolation, and polynomial operations
* 🖱️ **Interactive GUI** with scrollable steps and error validation

---

## 🧰 Requirements

```bash
pip install pygame
```

---

## 🚀 How to Run

1. Save the script as `shamir_gui.py` (or any name you prefer).
2. Run:

```bash
python shamir_gui.py
```

---

## 📌 How It Works

* **Input Parameters**:

  * Secret
  * Prime modulus `p`
  * Number of participants `n`
  * Threshold `t`

* **Outputs**:

  * A list of generated `(x, y)` shares
  * A detailed explanation of polynomial creation
  * Reconstruction process using Lagrange basis with modular inverse calculations

---

## 📸 Interface Overview

* 🎨 GUI built with **Pygame**
* Tabs to switch between:

  * **Generation Steps**
  * **Reconstruction Steps**
* Scroll to navigate through long calculations
* Real-time validation and visual feedback

---

## 📚 Educational Value

This tool is ideal for:

* Cryptography students and educators
* Demonstrations of threshold schemes
* Learning modular inverses and interpolation under a finite field

---

## 📄 License

MIT License – feel free to use, modify, and share.

---

## 👨‍💻 Author

**Insharah Aman**
Cybersecurity Student | Designer | Developer
https://www.linkedin.com/in/insharah-aman/

---

