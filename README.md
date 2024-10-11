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

