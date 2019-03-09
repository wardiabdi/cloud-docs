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

Comment for the following commands
```
```
This command allows to set user premission for the home directory, it is far safer than using ___sudo su___ command which enables you to wok direct from the _root folder_.
Now you premission level access then you need to specify the group file by using the colon and the file path.
Restart the system to apply the changes.

sudo chmod -R 755 /usr/share/nginx/html  
sudo chown -R "$USER":www-data /usr/share/nginx/html 
sudo systemctl restart nginx */ in order the changes to apply the server need to be restarted
```
```

chown --help
sudo systemctl restart nginx
 ```
