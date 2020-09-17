- :smile: [简体中文](https://github.com/hongwenjun/vps_setup/blob/master/README.md) 　:cry: [English](https://git.io/vps.english)


- 欢迎加入编程语言群 Telegram 电报群：https://t.me/codeblocks
- [![](https://raw.githubusercontent.com/hongwenjun/vps_setup/master/img/youtube.png)频道](https://www.youtube.com/sRGB18/videos) &nbsp;&nbsp;www.youtube.com/sRGB18 &nbsp;&nbsp;(https://paypal.me/sRGB18)&nbsp;&nbsp;https://paypal.me/sRGB18
----

- :gift: 项目: https://git.io/vps.us 　　 https://git.io/winkcp 　　 https://git.io/vps.english
- :bomb: 脚本: https://git.io/vps.sh 　　 https://git.io/wgmtu 　　 https://git.io/v2ray.ss
- :anger: 防火墙脚本: https://git.io/fhUSe 　　 路由器脚本: https://git.io/sskcp.sh
- English Script: https://git.io/vps.setup 　　 https://git.io/wireguard.sh 　　 https://git.io/v2ray_ss.sh


---
### :heart_eyes:Linux 简单命令工具和简易脚本


  
### 安装工具 tmux 和 fish 等

```
apt install tmux fish  -y
```

### 在Android手机上安装Termux应用，测试学习10个秘密和酷命令!

```
1) apt install sl
     sl
2) factor "Any Number" 
3) apt install fish
     fish
4) apt install figlet
     figlet "Any Text" 
5) apt install cmatrix
     cmatrix
6) apt install fortune
     fortune 
7) apt install toilet
     toilet "Any Text" 
     toilet -f mono12 -F gay "Any Text" 
8) apt install w3m
     w3m "any websites" 
     example:- w3m google.com
9) ifconfig
10) apt install cowsay
      cowsay "Any Text"
```

### [acme协议从letsencrypt生成免费的证书](http://srgb.vicp.net/2018/11/05/acme_sh/) 

```
#!/usr/bin/env sh

# https://github.com/Neilpang/acme.sh/wiki/说明

# 安装ssl依赖 和 acme.sh工具
apt-get install socat netcat -y
curl  https://get.acme.sh | sh

# 设置域名
DOMAIN=ssl.srgb888.ga

# 生成域名ssl证书
~/.acme.sh/acme.sh  --issue -d ${DOMAIN}  --webroot  /var/www/html --standalone -k ec-256 --force

```

### 如果你用的nginx服务器，以后可以使用一行命令更新证书
```
~/.acme.sh/acme.sh  --issue -d ssl.srgb888.ga  --nginx  --standalone -k ec-256 --force
```

</details>

### Debian 10 Buster 管理员手册  [在线阅读](https://debian-handbook.info/browse/zh-CN/stable/)

- Debian 开发者和 Debian 手册作者 Raphaël Hertzog 宣布面向 Debian 10 的最新版本 Debian 管理员手册已上线。
### 网友视频和白话文档

- 白话文档: [OpenWRT配置](https://git.io/wrt.wg) 　 [Nginx反代V2ray原理](https://git.io/v2ray.nginx) 　 [rclone使用教程](https://github.com/hongwenjun/vps_setup/blob/master/rclone/README.md) 　 [Debian 安装Transmission教程和一键脚本](https://github.com/hongwenjun/vps_setup/blob/master/rclone/transmission.md)
- 网友视频: [三剑客](https://youtu.be/BHZhU8wxf9A) 　 [PC_MAC_手机客户端](https://youtu.be/dkXWicxak3w)

---

