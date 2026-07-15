# Ubuntu-install
A Full guideline of uduntu install 

# PuTTY Installation Guide

![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-blue)
![Tool](https://img.shields.io/badge/Tool-PuTTY-green)
![License](https://img.shields.io/badge/License-Free-lightgrey)
![Maintained](https://img.shields.io/badge/Maintained-Yes-brightgreen)

---

## Overview

**PuTTY** is a free and lightweight SSH and Telnet client used to securely connect to remote servers. It is widely used by system administrators, developers, and cybersecurity students.

---

## Install PuTTY on Windows

### Step 1: Download

Download PuTTY from the official website:
https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html

* Choose: `putty-64bit-installer.msi` (recommended)

---

### Step 2: Run Installer

* Double-click the downloaded `.msi` file
* Click **Next**

---

### Step 3: Choose Installation Location

* Keep default location (recommended)
* Click **Next**

---

### Step 4: Select Components

Make sure all components are selected:

* PuTTY (SSH client)
* PuTTYgen (key generator)
* PSCP (file transfer)
* Pageant (authentication agent)

Click **Next**

---

### Step 5: Install

* Click **Install**
* Wait until installation completes

---

### Step 6: Finish

* Click **Finish**
* PuTTY is now installed 

---

## How to Use PuTTY (SSH Connection)

1. Open **PuTTY**
2. Enter:

   * **Host Name (IP address)** → your server IP
   * **Port** → `22`
   * **Connection Type** → SSH
3. Click **Open**
4. Login with username & password

---

##  Install PuTTY on Linux (Ubuntu)

```bash
sudo apt update
sudo apt install putty -y
```

Run PuTTY:

```bash
putty
```

---

## Install PuTTY on macOS

Install using Homebrew:

```bash
brew install putty
```

---

##  Common Issues & Fixes

| Problem            | Solution                  |
| ------------------ | ------------------------- |
| Connection refused | Check server is running   |
| Network error      | Verify IP address         |
| Timeout            | Check firewall / internet |
| Access denied      | Wrong username/password   |

---

## Important Tips

* Default SSH Port: **22**
* Use **PuTTYgen** for SSH key generation
* Always verify server IP before connecting
* Keep your credentials secure

---

##  Use Cases

* Remote Linux server access
* Cloud server management (AWS, Azure, etc.)
* Cybersecurity labs (TryHackMe, HackTheBox)
* Network administration

---





