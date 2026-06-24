# Linux-basics-and-System-Administration-Lab


## Description

This project documents my hands-on practice with Linux fundamentals while working through the TCM Security training course. I installed Ubuntu in a virtual machine and explored Linux navigation, file management, user privileges, file permissions, and the Linux file system hierarchy.

## Lab Environment

* Ubuntu Linux
* Oracle VirtualBox
* Linux Terminal

## Skills Demonstrated

* Linux Installation
* Virtual Machine Management
* Terminal Navigation
* File and Directory Management
* Linux File System Hierarchy
* User Privileges and Sudo
* Linux File Permissions

---

## Task 1: Installing Ubuntu

### Objective

Install Ubuntu Linux in a virtual machine environment.

### Actions Performed

* Downloaded the latest Ubuntu ISO.
* Created a new virtual machine in VirtualBox.
* Attached the Ubuntu ISO.
* Installed Ubuntu Linux successfully.

### Screenshots

![Ubuntu Download](https://files.catbox.moe/uih2c7.png)

![Ubuntu Desktop](https://files.catbox.moe/ny8fk0.png)
![Ubuntu Desktop](https://files.catbox.moe/ovtyd5.png)

---

## Task 2: Creating a Virtual Machine Snapshot

### Objective

Create a recovery point before making system changes.

### Actions Performed

* Created a VirtualBox snapshot.
* Verified the snapshot was available for rollback purposes.

### Screenshot

![Snapshot](https://files.catbox.moe/x3ytvn.png)

---

## Task 3: Linux Terminal Basics

### Video Demonstration

https://github.com/user-attachments/assets/148dac3b-512d-4f74-a596-716b04e6adab


### Commands Practiced

```bash
pwd
ls
cd
mkdir
touch
cat
man
exit
```

### Skills Learned

* Navigating directories
* Creating files and folders
* Viewing file contents
* Accessing command help pages

---

## Task 4: Linux User Levels and Sudo

### Objective

Understand the difference between standard users and administrative users.

### Concepts Covered

* Standard User
* Root User
* sudo Privileges

### Skills Learned

* Running commands with elevated privileges
* Understanding Linux user permissions
  
### Video Demonstration

https://github.com/user-attachments/assets/d9d30892-790c-4089-823e-1ad05ea5d7fb


---

## Task 5: Linux File System Hierarchy

### Video Demonstration

https://github.com/user-attachments/assets/09fc8108-b41e-4f6b-a961-431b11a6e9cc




### **Essential System Directories:**

| **Directory** | **Purpose** | **What's Inside** |
| --- | --- | --- | 
| **`/bin`** | **Essential binaries** | Basic commands everyone needs: `ls`, `cp`, `cat`, `bash` |
| **`/sbin`** | **System binaries** | Admin commands: `fdisk`, `ifconfig`, `iptables`, `shutdown` |
| **`/home`** | **User home directories** | Your personal files: `/home/rohan/`, `/home/user2/` |
| **`/tmp`** | **Temporary files** | Files deleted on reboot, world-writable |
| **`/etc`** | **Configuration files** | System config: `/etc/passwd`, `/etc/hosts`, network settings |
| **`/var`** | **Variable data** | Logs, databases, emails: `/var/log/`, `/var/www/` |
| **`/usr`** | **User programs** | Applications: `/usr/bin/`, `/usr/lib/`, `/usr/share/` |
| **`/opt`** | **Optional software** | Manually installed apps: Google Chrome, IDEs |
| **`/boot`** | **Boot files** | Kernel, initramfs, bootloader |
| **`/dev`** | **Device files** | Hardware devices: `/dev/sda` (disk), `/dev/tty` (terminal) |
| **`/proc`** | **Process information** | Virtual filesystem showing running processes |
| **`/root`** | **Root user's home** | Administrator's personal directory |
<img align="" src="https://files.catbox.moe/60vbe9.png" >

### Skills Learned

* Understanding Linux directory structure
* Navigating critical system folders

---

## Task 6: Linux File Permissions

### Video Demonstration
https://github.com/user-attachments/assets/9e985431-5fca-4c09-be07-f16ecf61fea4


![Ubuntu Desktop](https://files.catbox.moe/20thpa.png)

### Commands Practiced

```bash
ls -l
chmod 660 test.txt
sudo chown root test.txt
sudo chgrp root test.txt
cat test.txt
```

### Skills Learned

* Viewing permissions
* Modifying permissions
* Changing file ownership
* Managing file groups




https://github.com/user-attachments/assets/4177576b-a16e-4c85-9446-6a09bd919e7e

















