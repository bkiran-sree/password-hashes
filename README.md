# Cracking Passwords with Hashes

This project demonstrates how to crack password hashes using **dictionary attacks** and **brute-force attacks** in Python, focusing on MD5 hashes.

## Overview

- Learn the basics of password hashing and cracking techniques.
- Generate sample MD5 password hashes.
- Perform dictionary attacks using a user-uploaded wordlist.
- Perform brute-force attacks on short passwords.
- Test cracking multiple password hashes with the dictionary method.

## Features

- Uses Python's built-in `hashlib` for hashing.
- Supports uploading custom wordlists (e.g., subsets of `rockyou.txt`).
- Implements dictionary attack by matching hash with wordlist entries.
- Implements brute-force attack with configurable password length and charset.
- Provides easy-to-follow steps and sample hashes for demonstration.

## Usage

1. Run the script/notebook in an environment supporting file uploads (e.g., Google Colab).
2. Upload a wordlist file when prompted.
3. The script will generate sample MD5 hashes for known passwords.
4. Use the dictionary attack to crack one or multiple password hashes.
5. Optionally, try brute-force attack on short, simple passwords.

## Dependencies

- Python 3.x
- `hashlib` (standard library)
- `itertools` (standard library)
- `string` (standard library)
- For file upload: works best on Google Colab or similar environments

## Notes

- MD5 is used here for educational purposes; it is not secure for real-world applications.
- Brute force attack is limited to short passwords due to combinatorial explosion.
- Use a small wordlist for quicker dictionary attack demonstrations.

