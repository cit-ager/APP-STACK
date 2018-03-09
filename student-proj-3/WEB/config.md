### 1. Copy zip and configure following
Edit rdportal/js/config.js 
Modify the IP address of your server (Piblic IP)

### 2. Update mod-jk.conf file
Add the following line in /etc/httpd/conf.d/mod-jk.conf
```
JkMount /rdp-api* worker1
```


### 3. Restart web server
