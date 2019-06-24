# shadowsocks with net-speeder
这是一个Shadowsocks Docker

## 启动方式

```
docker run -d --name ss-with-net-speeder -p 8989:8989 -p 22:22 malaohu/ss-with-net-speeder -s 0.0.0.0 -p 8989 -k RUYO.net -m rc4-md5
```

## Arukas.io 启动

```
镜像 ：liyubaku/ss-with-net-speeder
启动命令(CMD) ：-s 0.0.0.0 -p 9898 -k akuras -m aes-256-gcm
```

## 支持SSH
用户名：root
密  码：password

## SSR镜像
https://github.com/malaohu/ssr-with-net-speeder

## 感谢
lowid/ss-with-net-speeder
