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
sudo chmod -R 755 /usr/share/nginx/html  */ this command allows to set user premission for the home directory/*
sudo chown -R "$USER":www-data /usr/share/nginx/html */ this command allows premission for the root folder/*
sudo systemctl restart nginx */ in order the changes to apply the server need to be restarted
```
```

chown --help
sudo systemctl restart nginx
 ```
