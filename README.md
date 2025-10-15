## User & File Management Practical (Linux)

This repository contains my **Individual Practical Task** for Linux user and file management.
The exercise demonstrates how to create users, manage permissions, and install software using the command line.

---

## Objectives

* Create a new user account on Linux
* Manage user and file permissions
* Install and verify a software package using `apt`
* Provide screenshots and explanations for each step

---

## Steps Performed

### 1️⃣ Create a New User

```bash
sudo adduser studentuser
```

Created a new user called `studentuser`, set a password, and added personal details.

---

### 2️⃣ Switch to the New User

```bash
su - studentuser
```

Verified that the user account works correctly.

---

### 3️⃣ Manage Permissions

Created and secured a folder:

```bash
mkdir testfolder
chmod 700 testfolder
```

Restricted access so only the owner can read, write, and execute.

---

### 4️⃣ Install a Software Package

Updated repositories and installed Vim:

```bash
sudo apt update
sudo apt install vim -y
```

Then verified the installation:

```bash
vim --version
```


---

## What I Learned

Through this task I learned how to:

* Create and manage Linux users
* Modify folder permissions with `chmod` and `chown`
* Use `sudo` and `apt` commands to manage software
* Troubleshoot permission errors and use admin privileges properly

---

## Author

**Nokuthula Ngcongo**
*IT Support Student | Linux User Management Exercise*

---

