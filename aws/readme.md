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


The following 2 commands allows to set user premission for the home directory and change, always chmod rather than using ___sudo su___ command which enables you to work direct from the _root folder_, but it can complicate your future work as you might modify files that does not required to be modified.
Now you premission level access then you need to specify the group file by using the __colon (:)__ and the file path.
Restart the system to apply the changes.
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


