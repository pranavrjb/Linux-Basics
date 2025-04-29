# 📘 Linux Week 1 Notes – DevOps Beginner Journey

Welcome! This file contains my personal notes from my first week learning Linux as part of my DevOps journey.  
I practiced commands on an Ubuntu VM and explored key concepts. 🚀

---

## 📂 Linux Directory Structure

- `/` → Root of the file system (top-level directory)
- `/root` → Home directory for the root user (administrator)
- `/bin` → Essential system commands (like `ls`, `cp`, etc.)
- `/sbin` → System commands for root/admin (e.g., `shutdown`)
- `/etc` → Configuration files for system and apps
- `/dev` → Files representing devices (e.g., `/dev/sda`)
- `/usr` → User programs, libraries, and docs

---

## 💻 Basic Commands

- `ls` – List files and folders
- `pwd` – Show current working directory
- `cd` – Change directory
- `mkdir` – Make a new directory
- `touch` – Create a new file
- `clear` – Clear the terminal screen

---

## 📝 File Editors & Viewers

- `vim filename` – Open and edit a file (Vim editor)
- `cat filename` – View contents of a file
- `more`, `less` – View long files page by page
- `/searchterm` – Search inside `less`

---

## 🔍 File & Text Search

- `find / -name filename` – Find a file by name
- `locate filename` – Quickly find a file (uses a database)
- `grep "text" filename` – Search for text inside files

---

## 📁 Paths

- **Absolute Path**: Full path from `/` (e.g., `/home/user/docs`)
- **Relative Path**: From current location (e.g., `../docs`)

---

## 📑 Useful System Commands

- `history` – View command history
- `df -h` – View disk space usage
- `cut -d: -f1 /etc/passwd` – Cut specific text fields
- `awk -F: '{ print $1 }' /etc/passwd` – Print first column (usernames)
- `sed 's/old/new/' filename` – Replace text in file

---

## 🛜 Networking (SSH)

- `sudo systemctl status ssh` – Check if SSH is running
- `sudo systemctl start ssh` – Start SSH service
- `ip addr show` – Show network IP info

---

## ✍️ Notes & Reflections

- The command line felt tricky at first, but repetition helps.
- Vim is hard at first but powerful. I’m getting used to it.
- `grep`, `cut`, and `find` are super helpful for large files.
- Understanding paths and file structures made navigation easier.

---

## ✅ Next Up (Week 2 Goals)

- Linux users & permissions
- Shell scripting basics
- Advanced `grep`, `awk`, and `sed`

---

> 🌐 I also wrote a blog about this journey! Check it out:  
> [📖 Read on Hashnode](https://starting-linux-as-a-devops-beginner.hashnode.dev/learning-linux-basics-for-devops-my-first-week-experience)
