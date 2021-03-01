# Mariadb-NoteText

### 1.Installation
```
sudo dnf -y install mariadb-server
```
### 2.Basic Configuration
```
sudo mysql_install_db --user=mysql
```
### 3.Start the systemd service
```
sudo systemctl start mariadb.service
```

## 4.Security harden
```
sudo mysql_secure_installation
```
