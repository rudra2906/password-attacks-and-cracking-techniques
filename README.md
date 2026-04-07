# 🔐 Password Attacks & Cracking Techniques

A hands-on cybersecurity lab project focused on understanding common password attack methods and cracking techniques.

---

## 📌 Objective

To understand how attackers exploit weak passwords and how security professionals assess password strength in a controlled lab environment.

---

## 🧠 Topics Covered

* Brute Force Attack
* Dictionary Attack
* Credential Stuffing
* Password Spraying
* Rainbow Table Attack

---

## 🔐 Hashing Algorithms

* MD5
* SHA-1
* bcrypt

---

## 🛠️ Tools Used

* THC Hydra
* John the Ripper
* Hashcat

---

## 🔬 Practical Work

### Hydra

```bash
hydra -l msfadmin -P wordlists/small.txt 192.168.145.82 ftp
```

### John the Ripper

```bash
john --format=raw-md5 --wordlist=wordlists/small.txt hashes/hash.txt
```

### Hashcat

```bash
hashcat -m 0 hashes/hash.txt wordlists/small.txt
```

---

## 📂 Project Structure

```text
hashes/
screenshots/
wordlists/
README.md
```

---

## 📸 Screenshots

Execution screenshots are available inside the `screenshots` folder.

---

## 📊 Key Learnings

* Importance of strong password policies
* Risks of weak passwords
* Practical password auditing
* Hash cracking techniques

---

## ⚠️ Disclaimer

This project was performed in a controlled lab environment for educational purposes only.
