# sing box config

* singbox Official Website [https://sing-box.sagernet.org](https://sing-box.sagernet.org)

* [singbox config](https://sing-box.sagernet.org/configuration)

### install hysteria2

```bash
wget -N --no-check-certificate https://raw.githubusercontent.com/flame1ce/hysteria2-install/main/hysteria2-install-main/hy2/hysteria.sh && bash hysteria.sh

```

```bash
systemctl start hysteria-server.service    # 启动 hysteria 服务
systemctl enable hysteria-server.service   # 设置 hysteria 服务 开机自启
systemctl restart hysteria-server.service  # 重启 hysteria 服务
systemctl stop hysteria-server.service     # 停止 hysteria 服务
systemctl status hysteria-server.service   # 查看 hysteria 服务 状态
```

### hysteria2 reference

* [hysteria2-config-example.json](./hysteria2-config-example.json)

* Configure the following information

```json
{
  "tag": "proxy",
  "type": "hysteria2",
  "server": "Server IP",
  "server_port": "Server Proxy PORT",
  "up_mbps": 100,
  "down_mbps": 500,
  "password": "Proxy Password",
  "tls": {
    "enabled": true,
    "server_name": "www.bing.com",
    "insecure": true
  }
}
```
