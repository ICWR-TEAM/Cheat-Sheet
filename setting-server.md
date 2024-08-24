# Install Requirements Software
```bash
sudo apt update
sudo apt install php nginx mysql-server phpmyadmin git iptables
```

# Query Create user

Login Command:

```bash
sudo mysql -u root
```

Query:

```mysql
CREATE USER 'server'@'localhost' IDENTIFIED BY 'securepassword';
GRANT ALL PRIVILEGES ON *.* TO 'server'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
```

# Get Source From Github

```bash
cd /var/www/html
git clone https://github.com/0xbillyyy/ExVulnerability
```

# Setting Untuk Mysql Config

Ganti dengan user yang sudah di buat

![image](https://github.com/user-attachments/assets/9c9e4730-8a41-40f4-8ff4-3946eeb3794f)


