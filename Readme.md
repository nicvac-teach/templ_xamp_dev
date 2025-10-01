# Installazione 
wget https://sourceforge.net/projects/xampp/files/XAMPP%20Linux/8.2.12/xampp-linux-x64-8.2.12-0-installer.run
chmod +x xampp-linux-x64-8.2.12-0-installer.run
sudo ./xampp-linux-x64-8.2.12-0-installer.run --mode unattended

# Servizi
## Start all XAMPP services
sudo /opt/lampp/lampp status
sudo /opt/lampp/lampp start

## Or start specific services:
sudo /opt/lampp/lampp startapache
sudo /opt/lampp/lampp startmysql

# PORT
Su PORTS aggiungi la porta 80

# Apache e phpmyadmin
Click su icona 🌍 in PORTS (Open in Browser)
ti porta su url
https://{codespace}.app.github.dev/dashboard/
Url per aprire phpmyadmin:
https://{codespace}.app.github.dev/phpmyadmin

# Creare un progetto (PHP+html+css+js)
mkdir proj01
sudo ln -sf $PWD/proj01 /opt/lampp/htdocs/dashboard/

Creare ad es. il file hello.php in proj01/

Eseguire il progetto 
https://{codespace}.app.github.dev/dashboard/proj01/hello.php

