# Auto Installer VPS Oleh SSH Sedang

apt update && apt upgrade -y && update-grub && sleep 2 && reboot

rm -rf setup.sh && apt install curl && wget https://raw.githubusercontent.com/SSHSEDANG4/gaspoll/main/setup.sh && apt update && apt install dos2unix && dos2unix setup.sh && chmod +x setup.sh && ./setup.sh
