# lamp-stack-setup

## 1. Initially i begin with system update

- Ensuring system is up to date

```bash
sudo apt update && sudo apt upgrade -y
```
## 2. Installed the Apache servers
```bash
sudo apt install -y apache2 -y
```
- Checking the apache status, ensuring its running
```bash
sudo systemctl status apache2
```
## 3. Installed MariaDB for databse management
```bash
sudo apt install mysql-server -y
```
- Ensuring a secured root password is properly configured
```bash
sudo mysql_secure_installation
```

## 4. PHP installation with Apache connection
```
sudo apt install php libapache2-mod-php php-mysql -y
```
- I have created a PHP file named Info.php
- add some PHP code content
- Navigating to the this URL on browser the content seems visible

# screenshots
![APache testing](./image/apche.png)
