# InitializeVPS
自用初始化VPS相关脚本

- 修改SSH登录端口、配置秘钥登录
- 新建用户，禁止root登录
- 安装并配置fail2ban
- 设置swap
- 防火墙配置

确保安装了curl 
```bash
apt install curl -y
```
一键执行
```bash

bash <(curl -sL https://raw.githubusercontent.com/AmamiyaHotaru/InitializeVPS/refs/heads/main/init.sh)
```
