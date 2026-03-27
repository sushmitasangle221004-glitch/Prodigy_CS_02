# 🔐 Prodigy_cs_02

## 📌 Task 2 : Pixel Manipulation for Image Encryption

## 📖 Overview

This project is a Python-based Image Encryption Tool that uses pixel manipulation techniques to secure images. It applies a simple XOR (Exclusive OR) operation on each pixel using a secret key (`0x55`) to convert the image into an encrypted format.

The same process is used for decryption, making it **reversible and lossless**.

---

## ✨ Features

* 🔒 Encrypt images using XOR operation
* 🔓 Decrypt images using the same key
* 🔑 Fixed key encryption (`0x55`)
* ⚡ Fast processing using NumPy
* 🖼 Supports JPG and PNG formats
* 💻 Simple command-line interface

---

## ⚙️ Tech Stack

* Python 3
* NumPy
* Pillow

---

## 🧠 How It Works

### 🔐 Encryption

* Load image
* Convert to RGB
* Convert into NumPy array
* Apply XOR with key
* Save as `_encrypted` image

### 🔓 Decryption

* Load encrypted image
* Apply XOR with same key
* Restore original image
* Save as `_decrypted` image

📌 XOR Logic:

```
Original ⊕ Key = Encrypted  
Encrypted ⊕ Key = Original  
```

---

## 📦 Installation

```bash
pip install numpy pillow
```

---

## ▶️ Usage

```bash
python "Task 2.py"
```

### Steps:

1. Choose option:

   * `1` → Encrypt Image
   * `2` → Decrypt Image
2. Enter image path
3. Output will be saved automatically

---

## 📂 Output Example

* `image.jpg` → `image_encrypted.jpg`
* `image_encrypted.jpg` → `image_decrypted.jpg`

---

## 👩‍💻 Author

**Sushmita Suryakant Sangle**
📌 Prodigy InfoTech Internship – Task 2 Completed

---



