OVERWALL
===

使用 docker-compose 部署翻墙服务，现在支持：

- v2ray：vmess+tls+ws 模式
- shadowsocks：tls+ws

## 配置方法

0. 将域名指向对应的服务器。

1. 填写 `.proxy.env` 中的配置：

```conf
#  v2ray ID
V2RAY_UUID=
# v2ray 域名
V2RAY_DOMAIN=
# 邮箱
DOMAIN_EMAIL=
# ss 域名
SHADOWSOCKS_DOMAIN=
# ss 密码
SHADOWSOCKS_PASSWORD=

```

2. 运行 `sudo ./start.sh` 脚本即可。
