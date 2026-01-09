# Caesar Cipher 🛡️

A simple Python implementation of the **Caesar Cipher** that allows users to
encrypt and decrypt messages using a shift-based substitution technique.

## Features
- Encode (encrypt) messages
- Decode (decrypt) messages
- Preserves numbers, symbols, and spaces
- Supports large shift values using modulo arithmetic
- Option to restart the program multiple times
- Displays a logo at startup

## How It Works
The Caesar Cipher shifts each letter in the message by a fixed number of
positions in the alphabet. Non-alphabet characters remain unchanged.

## Example
Input:
Type 'encode' to encrypt, type 'decode' to decrypt:
encode
Type your message:
Claude Shannon@%$&

Type the shift number:
5
Output:
hqfzij xmfssts@%$&

## Requirements
- Python 3.x

## How to Run
```bash
python caesar_cipher.py
