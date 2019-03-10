# Server Config

### NGinx Installation

```
sudo apt update
sudo apt install nginx
```

The following command updates Ubuntu server.
```
yum update -y
```


The following 2 commands allow to set user permission for the home directory and change, always chmod rather than using sudo su command which enables you to work directly from the root folder, but it can complicate your future work as you might modify files that do not requir to be modified. Now you permission level access then you need to specify the group file by using the colon (:) and the file path. Restart the system to apply the changes.
```
```
sudo chmod -R 755 /usr/share/nginx/html 
```
```
sudo chown -R "$USER":www-data /usr/share/nginx/html

```
```
sudo systemctl restart nginx 

```
```


