# Linux Administration Cheat Sheet

A quick reference for essential Linux commands and their functions.
## 🧠 System Identification
| Command | Description |
|----------|--------------|
| hostname | Displays the network name of the current Linux system. |
| whoami | Shows the username of the logged‑in user. |
| pwd | Prints the current working directory path. |
| uname -a | Displays system and kernel details. |
| uptime | Shows how long the system has been running. |
## 📂 Filesystem and Resources
| Command | Description |
|----------|--------------|
| ls -la | Lists all files, including hidden ones, with details. |
| df -h | Reports disk space usage in human‑readable format. |
| free -h | Displays memory and swap usage. |
| du -sh * | Summarizes directory sizes. |
## ⚙️ Process and Service Management
| Command | Description |
|----------|--------------|
| ps aux | Lists all running processes. |
| top | Displays real‑time CPU and memory usage. |
| sudo apt update | Refreshes package repository metadata. |
| sudo apt install <package> | Installs a software package. |
| systemctl status nginx | Checks service status. |
| systemctl start/stop/restart nginx | Controls service lifecycle. |
| journalctl -u nginx | Views logs for a specific service. |
## 🌐 Networking and Environment
| Command | Description |
|----------|--------------|
| curl http://localhost | Tests local web server response. |
| export VAR=value | Sets a temporary environment variable. |
| echo $VAR | Displays the value of an environment variable. |
