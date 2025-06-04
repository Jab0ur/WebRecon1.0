# 🕵️‍♂️ webrecon.sh

Simple Bash script to perform **directory or file brute-force** on web applications using a custom wordlist. Ideal for the initial reconnaissance phase in penetration testing (pentest).

---

## 📂 Description

This script uses `curl` to test the existence of specific paths on an HTTP/HTTPS target based on a wordlist. It checks whether the response returns **HTTP 200 OK**, indicating that the directory or file exists.

---

## 🛠️ Requirements

- `bash`
- `curl`
- A wordlist named `lista2.txt` in the same directory as the script  
  _(You may also use a wordlist from [SecLists](https://github.com/danielmiessler/SecLists) if preferred.)_

---

## ▶️ Usage

```bash
chmod +x webrecon.sh
./webrecon.sh <target-URL> <extension>
```
