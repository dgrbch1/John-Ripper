# John-Ripper
# Password Hash Cracking with John the Ripper

This project demonstrates the process of cracking password hashes using [John the Ripper](https://www.openwall.com/john/), a popular password cracking tool. The workflow includes generating password hashes, storing them in a file, and using a wordlist to attempt cracking the hash.

---

## Features
- **Password Hashing:** Generate secure password hashes using OpenSSL.
- **Cracking Passwords:** Leverage `John the Ripper` to crack hashes with a wordlist.
- **Educational Demonstration:** Learn how password cracking works in a controlled environment.


## Prerequisites
- [WSL (Windows Subsystem for Linux)](https://learn.microsoft.com/en-us/windows/wsl/) or a Linux environment.
- [John the Ripper](https://www.openwall.com/john/).
- A wordlist such as `rockyou.txt`.

---

## Usage Instructions

1. **Hash a Password**  
   Use OpenSSL to generate a password hash:
   ```bash
   echo -n "mypassword123" | openssl passwd -6 > hash.txt
   Verify the has.txt file has it
   cat hash.txt

2. **JohnRipper**
   john hash.txt --wordlist=rockyou.txt
3. **Finish the command should run until it can crack the code**

## Examples

![Google Social Engineering](https://github.com/user-attachments/assets/af97bdc9-acef-48c6-8282-9d88b66f18b2)


![PasswordManger2](https://github.com/user-attachments/assets/f32fd310-5f30-4d6b-8f45-bd3bc5b4dd7e)



