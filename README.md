# Secure-AES---256-Utility
An interactive AES-256 encryption and decryption tool built with pure HTML, CSS (Tailwind CSS), and JavaScript using the vetted CryptoJS library.

This utility demonstrates the fundamental use of symmetric-key cryptography, where the same secret key is used for both encrypting and decrypting data.

# ✨ Core Functionality
AES-256 Encryption: Encrypts plaintext into a Base64-encoded ciphertext using a strong, user-provided Secret Key.

Decryption: Reverses the process, converting ciphertext back to the original plaintext, provided the correct Secret Key is used.

Key Visibility Toggle: Allows secure entry by hiding the key, with an option to reveal it for verification.

Responsive Design: Optimized for use on both desktop and mobile devices.

🚀 Live Demo
https://yogeshofficepersonal.github.io/Secure-AES---256-Utility/

View Live Demo on GitHub Pages

# 🚨 Disclaimer
This project is for educational and demonstrative purposes only. It should not be used for encrypting real-world sensitive or financial data. While AES-256 is secure, the implementation's security relies heavily on the user's environment and key management.

# 🛠️ How to Use
Enter a Secret Key: Choose a strong password. This key is vital—you cannot decrypt the message without it.

Input Data: Enter your plaintext to encrypt, or your ciphertext to decrypt.

Click an Action: Select either Encrypt Data or Decrypt Data.

Copy Result: The output area will show the result, which can be copied using the dedicated button.

# ⚙️ Development Stack
Algorithm: AES-256 (via CryptoJS)

Styling: Tailwind CSS (loaded via CDN)

Language: JavaScript (ES6+)

Deployment: GitHub Pages
