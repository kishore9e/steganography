#  Secure Data Hiding in Images Using Steganography

A Python-based project that hides secret messages inside images. This ensures secure and undetectable communication.


## Features
*Invisible Communication** – Embeds data in images without noticeable changes.  
**Passcode Protection** – Messages can only be extracted with the correct passcode.  
*Fast & Lightweight** – Minimal computational overhead.  
*Cross-Platform Support** – Works on Windows, Linux, and macOS.  
*User-Friendly** – Simple encoding and decoding process.  

---

## Technologies Used
**Python**
**OpenCV (`cv2`)** – Image processing  
**OS (`os`)** – File handling  
**String Manipulation** – Character encoding  

---

## Installation

### 1.Install Python (if not installed)
   - [Download Python](https://www.python.org/downloads/) and install it.

### 2.Install Dependencies
   Open a terminal or command prompt and run:
   ```sh
   pip install opencv-python
#How It Works?
1.Encoding (Hiding Data)
The script loads an image.
A secret message is entered by the user.
The message is embedded into the image.
The modified image is saved as encryptedImage.jpg
2.Decoding (Extracting Data)
The user provides the encryptedImage.jpg
If the correct passcode is entered, the hidden message is revealed.
#Usage
-Run the Script
python stego.py
-Encoding Example
Enter secret message: This is a hidden message!
Enter a passcode: 1234
[+] Message encoded successfully in 'encryptedImage.jpg'
-Decoding Example
Enter passcode for decryption: 1234
Decryption message: This is a hidden message!
