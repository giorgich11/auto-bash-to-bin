
# 🚀 Auto-Bash-to-Bin by giorgich11

The ultimate tool to **auto-compile bash scripts into binaries**. No more messing with manual `shc` commands or cleaning up leftover C files. 

## 🛠 Features
- **Interactive Flow:** Just enter the name and paste your script.
- **Auto-Cleanup:** Automatically removes `.x.c` files.
- **Dual Output:** Generates both a `.sh` source and a protected `.bin` executable.
- **Lightweight:** Zero bloat, just pure efficiency.

tutorial video is at: https://www.youtube.com/watch?v=AM9DyUcPCj8

## 📦 Installation & Usage
1. **Clone the repo:**
   ```bash
  git clone https://github.com/giorgich11/auto-bash-to-bin.git
   cd auto-bash-to-bin
   chmod +x factory.sh
   ./factory.sh

requirements: 

1. Ubuntu, Debian, Kali, and Mint
sudo apt update && sudo apt install shc zenity -y

2.Fedora, RHEL, and CentOS
sudo dnf install shc zenity -y

3.Arch Linux and Manjaro
sudo pacman -S shc zenity --noconfirm
if shc isnt in main repo use "yay -S shc"

4.openSUSE
sudo zypper install shc zenity

5.Alpine Linux
apk add shc zenity

other information: coming to MAC-Os soon.update will release when repo hits 200 views
