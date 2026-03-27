# Prodigy_CS_02
🔐 Pixel Manipulation for Image Encryption Tool (Python)

A simple Python-based tool to encrypt and decrypt images using the XOR operation. This project demonstrates basic image processing and encryption concepts using Pillow and NumPy.

📌 Features
🔒 Encrypt images using XOR encryption
🔓 Decrypt images using the same key
🖼 Supports common image formats (JPG, PNG, etc.)
⚡ Fast processing using NumPy arrays
📁 Automatically generates output file names
🛠️ Technologies Used
Python 3.x
NumPy
Pillow
📂 Project Structure
Image-Encryption-Tool/
│── Task 2.py
│── README.md
⚙️ Installation
Install required libraries:
pip install numpy pillow

💡 Usage
Run the program
Choose an option:
1 → Encrypt Image
2 → Decrypt Image
Enter the image file path
🔑 How It Works
The program converts the image into a NumPy array
Applies XOR operation with a key (default: 0x55)
Saves the processed image

👉 Encryption and decryption use the same logic:

Pixel ^ Key = Encrypted Pixel
Encrypted Pixel ^ Key = Original Pixel

⚠️ Note
Use the same key for encryption and decryption
This is a basic encryption method and not suitable for real-world security applications

👨‍💻 Author
Created by : Sushmmita Suryakant Sangle
Task 2 : Pixel Manipulation for Image Encryption - Completed
