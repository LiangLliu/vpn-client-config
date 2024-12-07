# sing box config

* singbox Official Website [https://sing-box.sagernet.org](https://sing-box.sagernet.org)

* [singbox config](https://sing-box.sagernet.org/configuration)


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
