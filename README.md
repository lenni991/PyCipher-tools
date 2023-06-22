# PyCipher

PyCipher is a Python script that provides a graphical user interface (GUI) for encrypting and decrypting text using popular ciphers. The tool supports three different ciphers: Caesar cipher, monoalphabetic cipher, and Vigenere cipher. With PyCipher, you can easily experiment with various ciphers and observe the results in real-time.

## Features

- Encrypt or decrypt text using Caesar cipher, monoalphabetic cipher, or Vigenere cipher.
- User-friendly GUI for a seamless experience.
- Real-time display of the encrypted or decrypted text.
- Adjustable key input for each cipher algorithm.
- Supports both uppercase and lowercase letters.
- Robust error handling for invalid inputs.

## Installation

To use PyCipher, follow the steps below:

1. Clone the repository to your local machine or download the source code as a ZIP file.
2. Ensure you have Python 3.x installed on your system.
3. Install the required dependencies by running the following command:

   ```
   pip install tkinter ttkthemes
   ```

4. Once the dependencies are installed, navigate to the project directory.
5. Run the following command to start the PyCipher application:

   ```
   python cipher_tool.py
   ```

## Usage

Upon launching the PyCipher application, you will be presented with the following options:

- **Cipher**: Select the desired cipher algorithm from the dropdown menu. Choose between Caesar cipher, monoalphabetic cipher, or Vigenere cipher.
- **Operation**: Select whether you want to encrypt or decrypt the text.
- **Key**: Enter the key required for encryption or decryption. The key should be provided based on the selected cipher algorithm.
- **Input text**: Enter the text that you want to encrypt or decrypt. You can input multiple lines of text.
- **Output text**: The encrypted or decrypted text will be displayed in this area.

To perform encryption or decryption, follow these steps:

1. Select the cipher algorithm from the "Cipher" dropdown menu.
2. Choose the operation mode (encrypt or decrypt) from the "Operation" dropdown menu.
3. Enter the corresponding key for the selected cipher algorithm in the "Key" input field.
4. Input the text you want to encrypt or decrypt in the "Input text" area.
5. Click the "Encrypt/Decrypt" button to see the result in the "Output text" area.

## Examples

Here are a few examples to demonstrate the usage of PyCipher:

### Example 1: Caesar Cipher Encryption

- Cipher: Caesar
- Operation: Encrypt
- Key: 3
- Input text: Hello, World!

Output text: Khoor, Zruog!

### Example 2: Monoalphabetic Cipher Decryption

- Cipher: Monoalphabetic
- Operation: Decrypt
- Key: qazwsxedcrfvtgbyhnujmikolp

Input text: Myb mxbyz

Output text: You there

### Example 3: Vigenere Cipher Encryption

- Cipher: Vigenere
- Operation: Encrypt
- Key: lemon
- Input text: Attack at dawn!

Output text: Lxfopv ef rnhr!

Feel free to explore and experiment with different keys, texts, and cipher algorithms using PyCipher!
