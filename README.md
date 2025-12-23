# Linux OS Fundamentals - Lab Exercises

[![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)](https://www.kali.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![VirtualBox](https://img.shields.io/badge/VirtualBox-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)](https://www.virtualbox.org/)

This repository contains comprehensive lab exercises for learning fundamental Linux operating system concepts and commands, based on hands-on practice with Kali Linux.

## 📋 Table of Contents
- [Overview](#-labs-overview)
- [Labs Breakdown](#-lab-breakdown)
- [Tools and Resources](#️-tools-and-resources)
- [Getting Started](#️-getting-started)
- [Prerequisites](#-prerequisites)
- [Learning Outcomes](#-learning-outcomes)
- [Usage](#-usage)
- [Contributing](#-contributing)
- [License](#-license)

## 🧪 Labs Overview

This series of labs provides a structured approach to learning Linux fundamentals through practical exercises. Each lab builds upon the previous one, creating a comprehensive learning path from basic system navigation to advanced network and security concepts.

## 📚 Lab Breakdown

### **Lab 1: Investigate Kali Linux**
**Objective:** Familiarize with Kali Linux GUI and shell, understand basic file/directory operations, and learn about file permissions.

**Topics Covered:**
- Kali Linux GUI familiarization and customization
- Shell navigation and command documentation (`man`)
- Basic file and directory operations (`pwd`, `cd`, `ls`, `mkdir`, `rmdir`)
- File manipulation commands (`cp`, `mv`, `rm`, `cat`)
- Understanding file system structure

### **Lab 2: Installing Packages and Applications**
**Objective:** Learn to manage packages using APT (Advanced Package Tool) in Kali Linux.

**Topics Covered:**
- Updating package lists (`sudo apt update`)
- Installing and removing packages (`sudo apt install/remove`)
- Upgrading packages (`sudo apt upgrade`)
- Searching for packages (`apt search`)
- Managing software repositories (`/etc/apt/sources.list`)
- Package verification and version checking

### **Lab 3: Network Commands**
**Objective:** Use basic and advanced networking commands to configure, diagnose, and monitor network traffic.

**Topics Covered:**
- Network interface configuration (`ip addr show`, `ip route show`)
- Connectivity testing (`ping`, `traceroute`)
- Manual interface configuration (`ifconfig`, `ip addr add`)
- Network traffic monitoring (`tcpdump`)
- Network manager CLI (`nmcli`)
- Firewall status checking (`ufw`)

### **Lab 4: Linux File Permissions and Ownership**
**Objective:** Understand and modify Linux file permissions and ownership.

**Topics Covered:**
- Viewing file permissions (`ls -l`)
- Modifying permissions with octal notation (`chmod`)
- Changing file ownership (`chown`, `chgrp`)
- Understanding permission types (read, write, execute)
- User and group management (`adduser`)
- Practical permission exercises

## 🛠️ Tools and Resources

**Essential Software:**
- **Kali Linux** - Penetration testing and security assessment platform
- **Oracle VirtualBox** - Virtualization software for running Kali Linux VM
- **Terminal/Shell** - Built-in command-line interface

**Requirements:**
- Stable internet connection for package management
- Minimum 4GB RAM (8GB recommended)
- 20GB free disk space

## ⚙️ Getting Started

### Step 1: Environment Setup
1. Download and install [VirtualBox](https://www.virtualbox.org/)
2. Download the [Kali Linux ISO](https://www.kali.org/get-kali/)
3. Create a new VM in VirtualBox with:
   - At least 2GB RAM
   - 20GB disk space
   - Network adapter set to NAT or Bridged

### Step 2: Repository Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/linux-os-fundamentals.git

# Navigate to the project directory
cd linux-os-fundamentals

# Explore the lab materials
ls -la
