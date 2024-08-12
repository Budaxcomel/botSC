# Free Open Source Admin Bot Panel
Copas code ke VPS:
```
apt update && apt upgrade
apt install python3 python3-pip git
git clone https://github.com/Budaxcomel/botSC.git
unzip botSC/botmin.zip
nano adminbot/var.txt # Isi bot token, ID telegram, & domain VPS
pip3 install -r adminbot/requirements.txt
pip3 install pillow
mv adminbot/adminbot.service /etc/systemd/system/
systemctl start adminbot && systemctl enable adminbot
```
- Buka Bot, ketik .menu
- kendala / error?, Lapor di <a href="https://t.me/immanvpnDC">sini</a>
