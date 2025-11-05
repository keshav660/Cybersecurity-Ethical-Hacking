# Installed on Kali Linux using:
sudo apt update
sudo apt install apache2 mysql-server php libapache2-mod-php
git clone https://github.com/digininja/DVWA.git
sudo cp -r DVWA /var/www/html/
sudo chmod -R 755 /var/www/html/DVWA