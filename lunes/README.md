# 1.Hysteria2在Nodejs或Python部署

* Node.js/Python运行环境一键极简部署Hysteria2节点，可自定义端口

* 必须在一键脚本末尾添加自定义端口

```
curl -Ls https://raw.githubusercontent.com/LiangLliu/vpn-client-config/refs/heads/master/lunes/hy2.sh | sed 's/\r$//' | bash -s -- PROT
```
