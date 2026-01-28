# PyPass-Gen
A lightweight, secure password generator built in Python. This tool leverages the secrets module to ensure cryptographically strong output, making it ideal for security-conscious users.

# Features
• Cryptographically Secure: Uses Python’s secrets module for high-quality randomness.

• Customizable Modes: Choose between alphanumeric, digits-only, or special characters.

• Batch Generation: Generate multiple passwords at once using Python generators.

# How to Use
Prerequisites: Ensure you have Python 3.x installed.

# Run the Script:

bash
python password_gen.py

# Code Preview
The core logic uses a dictionary-based source selection:

'all': Letters, digits, and punctuation.

'l': Letters only.

'd': Digits only.

's': Special characters only.
