## 🦊About

Local GitLab

## 🐋Deploy

### 1 set the .env

Please refar the .env_sample

```.env
GITLAB_HOME="./volumes"     # specifying the directory where GitLab will store its data.
SERVER_IP="XXX.XXX.XXX.XXX" # the server's IP address. Replace "XXX.XXX.XXX.XXX" with the actual local IP address.
HTTP_PORT="58080"           # specifying the port number for HTTP connections.
SSH_PORT="52424"            # specifying the port number for SSH connections.
```

### 2 docker compose

```
docker compose up -d
```

#### 3 login as root

```
username: root
password: check file of .volumes/config/trusted-certs/initial_root_password
```
