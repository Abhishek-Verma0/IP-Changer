# 🔄 Tor IP Changer Script

- This Bash script automates the process of changing your public IP address using the Tor network. It supports most major Linux distributions and includes installation, setup, and dynamic IP rotation with customizable intervals.

---

## ⚙️ Features

- 🧪 Automatically installs `curl` and `tor` if not present

- 📦 Supports:

  - `apt` (Debian, Ubuntu)

  - `yum` (Fedora, CentOS, RHEL, Amazon Linux)

  - `pacman` (Arch Linux)

- 🔄 Automatically starts and reloads Tor service

- ⏱️ Set a fixed interval or use random (5–30 sec) between IP changes

- 🔁 Choose between finite or infinite number of IP changes

- 🌐 Retrieves and displays current IP through Tor exit node

---

## 🚀 How to Use

###  Make the script executable

```bash
chmod +x IP-Changer.sh
```
### Run script as root 
```
sudo ./IP.Changer.sh
```
