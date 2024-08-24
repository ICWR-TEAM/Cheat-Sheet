# Install nginx
```bash
sudo apt install php nginx mysql-server phpmyadmin
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
