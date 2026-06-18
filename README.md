Caesar Cipher Encryption and Decryption in Python

Prodigy InfoTech Cyber Security Internship – Task 01

Description

This project demonstrates the implementation of the Caesar Cipher algorithm using Python. The program allows users to encrypt and decrypt text by specifying a shift value, providing a simple introduction to classical cryptography.

Features

- Encrypts plaintext using a user-defined shift value.
- Decrypts ciphertext back to the original message.
- Supports both uppercase and lowercase alphabetic characters.
- Preserves spaces, numbers, and special characters without modification.
- Simple and user-friendly command-line interface.

How It Works

- The "encrypt()" function shifts each alphabetic character forward by the specified number of positions.
- The "decrypt()" function reverses the process by shifting the characters backward using the same shift value.
- Uppercase and lowercase letters are processed separately to maintain their original case.
- Non-alphabetic characters remain unchanged throughout the encryption and decryption process.

Code Explanation

- "ord(char)" converts a character into its corresponding ASCII value.
- "% 26" ensures the alphabet wraps around correctly (e.g., Z → A and z → a).
- "chr()" converts the modified ASCII value back into its corresponding character.

Technologies Used

- Python 3

How to Run

python caesar_cipher.py

Example

Input

Enter message: Maheswaricse
Enter shift value: 2

Output

Encrypted Text: Ocjguyctkeug
Decrypted Text: Maheswaricse
