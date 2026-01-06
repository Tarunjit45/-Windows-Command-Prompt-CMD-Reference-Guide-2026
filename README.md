# 📂 Windows Command Prompt (CMD) Reference Guide 2026

A comprehensive collection of essential and interesting Windows Command Prompt commands for navigation, system management, and customization.

---

## 🎨 Visuals & Customization
Use these to change the look and feel of your terminal.

| Command | Description | Example |
| :--- | :--- | :--- |
| `color` | Changes text and background color. | `color 0a` (Hacker Green) |
| `title` | Renames the CMD window title. | `title My Workspace` |
| `prompt` | Customizes the command prompt text. | `prompt Hello $G` |
| `cls` | Clears the screen. | `cls` |

---

## 📂 Navigation & Directory Management
Commands for moving through your files and managing folders.

* **`cd`**: Change directory. Use `cd ..` to go back one level.
* **`dir`**: List files and subdirectories in the current folder.
* **`mkdir`** / **`md`**: Create a new directory.
* **`rmdir`** / **`rd`**: Remove an empty directory. Use `/s` to remove folders with files.
* **`tree`**: Display a graphical tree structure of your directories.
* **`pushd`** / **`popd`**: Save a current directory path to memory to navigate back to it later.

---

## 📄 File Operations
Manipulate and manage individual files.

* **`copy`**: Copy files to another location.
* **`move`**: Move or rename files.
* **`del`** / **`erase`**: Delete one or more files.
* **`type`**: View the contents of a text file directly in CMD.
* **`ren`**: Rename a file.
* **`fc`**: Compare two files and display the differences.
* **`attrib`**: View or change file attributes (Hidden, Read-only, etc.).
* **`robocopy`**: Advanced "Robust Copy" for large data migrations and backups.

---

## 🌐 Network Configuration & Diagnostics
Tools for troubleshooting internet and network issues.

* **`ipconfig`**: View IP settings. Use `ipconfig /flushdns` to clear DNS cache.
* **`ping`**: Test connectivity to a website or server.
* **`tracert`**: Trace the path data takes to reach a destination.
* **`nslookup`**: Find the IP address of a domain name.
* **`netstat`**: View all active network connections and ports.
* **`netsh`**: Advanced configuration for network interfaces, firewall, and Wi-Fi.
* **`getmac`**: Display the MAC address of your network adapters.

---

## 🛠️ System Info & Troubleshooting
Deep system diagnostics and repair tools.

* **`systeminfo`**: Generates a detailed report of system specs and OS version.
* **`tasklist`**: List all currently running processes.
* **`taskkill`**: Force close a program (e.g., `taskkill /f /im chrome.exe`).
* **`sfc /scannow`**: Scans and repairs corrupted Windows system files.
* **`powercfg /batteryreport`**: Generates an HTML report of your laptop's battery health.
* **`chkdsk`**: Checks a disk for errors and repairs them.
* **`dism`**: Repair the Windows system image (used if SFC fails).
* **`driverquery`**: Lists all installed device drivers.

---

## 🔐 Disk & User Management
Administrative tools for hardware and accounts.

* **`diskpart`**: Interactive disk partitioning utility.
* **`net user`**: View, add, or delete user accounts on the computer.
* **`cipher /w:C:`**: Securely wipes free space on a drive to make deleted files unrecoverable.
* **`format`**: Formats a disk or partition.

---

## ⚡ Productivity Shortcuts

| Key/Command | Action |
| :--- | :--- |
| **F7** | Opens a pop-up window of your command history. |
| **\| clip** | Pipes the output of any command to the clipboard (e.g., `dir \| clip`). |
| **CTRL + C** | Aborts a running command immediately. |
| **TAB** | Auto-completes file or folder names as you type. |

> [!IMPORTANT]  
> Some commands require **Administrative Privileges**. Right-click CMD and select **"Run as Administrator"** to access them.
