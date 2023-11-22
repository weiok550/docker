# docker
本仓库仅用来存放个人搭建开发环境相关的docker配置以及一些软件的配置文件

# 认证配置
```
  ~/.ssh/config

  Host github.com
    Hostname ssh.github.com
    Port 443
    User git
  Host *
    AddKeysToAgent yes
    UseKeychain yes
    IdentityFile ~\.ssh\id_rsa
    ServerAliveInterval 30
  ```
