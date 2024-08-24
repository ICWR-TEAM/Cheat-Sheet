# Install nginx
```bash
sudo apt install php nginx mysql-server phpmyadmin
```

# Query Create user

Query:

```mysql
CREATE USER 'server'@'localhost' IDENTIFIED BY 'securepassword';
GRANT ALL PRIVILEGES ON *.* TO 'server'@'localhost' WITH GRANT OPTION;
FLUSH PRIVILEGES;
```
