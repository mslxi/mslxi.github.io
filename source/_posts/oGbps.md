---
title: 节点部署+OneGbps公益中转
date: 2022-03-14 10:54:25
id: oGbps
tags:
       - Azure
       - 微软云  
---

## 节点部署+使用OneGbps中转保姆级教程！
<!-- more -->
### 准备工作
1. 到[CloudFlare](https://dash.cloudflare.com/)解析一个域名到你的服务器,先不要勾选小云朵（代理状态）！
![Alt description](https://user-images.githubusercontent.com/56199297/158095785-7d000926-2106-4f31-bc7f-07bd71452b64.png)
2. 连接你的服务器
3. 执行命令
``` wget https://raw.githubusercontent.com/mack-a/v2ray-agent/master/install.sh -O /usr/bin/vasma && chmod +x /usr/bin/vasma && vasma```
![Alt description](https://user-images.githubusercontent.com/56199297/158097773-cc887e73-3f15-4798-8dac-fe79fb0dae27.png)

4. 选择2，任意组合安装，之后选择1，Xray-core,之后选择123，然后输入你刚刚解析的域名，之后一路回车
5. 安装好之后随意复制一个节点导入v2ray等软件测试是否可用
6. 如果可用，去[CloudFlare](https://dash.cloudflare.com/)勾选小云朵
![Alt description](https://user-images.githubusercontent.com/56199297/158096455-c96ca0a1-b05a-497c-8064-7c05e6edca05.png)
7. 节点部署完成！[到OneGbps频道](https://t.me/oGbps)获取中转ip
8. 打开V2ray等软件把获取到的ip和端口更换到你节点的ip和端口，伪装域名不要动！