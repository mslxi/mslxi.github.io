---
title: OneGbps是什么？
date: 2022-03-14 13:46:22
id: introduce
tags:
       - Azure
       - 微软云  
       - CloudFlare
---
## OneGbps的介绍和作用
<!-- more -->
OneGbps是由微软云服务器+CloudFloud组成的公益中转节点

CloudFlare优点是除了大陆电信用户，对于别的网络都很友好，特别是在Azure的商宽上面

CloudFlare的CDN节点数量众多，可以把除了大陆的全球服务器线路拉平

Azure香港云服务器对于大陆南方用户非常友好

利用CloudFlare和Azure的特性，也就组成了OneGbps公益中转节点

由用户先访问Azure，Azure再把流量转发到CloudFlare，最终CloudFlare把流量转发到落地机，这就是OneGbps公益中转节点的作用。

如果多线程测速原版节点就能跑满，那么OneGbps可以大大提升单线程速度，还有真实google ping值也会大幅度优化！
