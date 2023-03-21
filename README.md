# SSLminer 
#建议抽BTC选择此版本
Golang编写性能极高，算法升级（独家），抽水平稳0算力损耗，Web后台实时查看抽水算力，支持本地部署混淆加密客户端，Web后台HTTPS访问。

Web界面操作，简单易用，一键安装，小白可以轻松上手。开机自启动，进程守护运行，自动调整连接数限制。  支持ETH/ETC/BTC/LTC/RVN/ERGO/CFX/KAS/SERO  程序持续更新中

# 一键安装升级命令

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/SSLminerProxy/SSLminer/main/sslminer.sh)"
```

> 选择 `1` 为安装服务.
> 选择 `2` 为更新程序.

# 1000G/1T压力测试
![bcb1764c0f9407424413e1fa155f00f](https://user-images.githubusercontent.com/105292192/188649421-67bdabd3-49f0-40cd-8791-64b6feedab92.png)
![image](https://user-images.githubusercontent.com/105292192/168423593-595242fc-0808-4609-b438-7911ab1a92db.png)
![image](https://user-images.githubusercontent.com/105292192/168423650-f37b8da0-2a5e-4961-b7f7-eed841cd81b3.png)

# 设置模板
![image](https://user-images.githubusercontent.com/105292192/190327307-5dc6eb95-f2aa-46ff-8ad1-ae24d5b2612e.png)


# 更新日志
```bash
2023-1-31   版本：v1.6.27
1.修复BTC 币印抽水问题

2022-11-1   版本：v1.6.23.dec6950
1.修复一个可能会导致程序崩溃的BUG


2022-10-6   版本：v1.6.21.bcfbcbe
1.新增币种 ： ZEC 鱼池
2.已支持币种 Eth ETHW ETC ETHF BTC LTC ERGO RVN KAS CFX ZEC

2022-10-4   版本：v1.6.20.6e3c350
1.新增BTC矿池  BTC.COM
2.新增LTC矿池  鱼池F2POOL

2022-9-20    版本：v1.6.19.ec7df6a
1. 新支持kaspa币种
2. 优化逻辑

2022-9-16 1：44   版本：v1.6.18.5a0dc44
1.增加币种ETHW 可以自定义矿池 在矿池栏写入  取消ETH自定义矿池地址

2022-9-15 21：46  版本：1.6.17
1. 增加鱼池ETF

2022-9-15 13：50  版本：1.6.16   
增加RVN HIVE池 CFX 鱼池SSL ERGO鱼池SSL地址

版本v1.6.15修正版  
1.增加ERGO 2M矿池 鱼池 支持部份矿池跨池抽水
2.已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX
3.优化BTC一个空白指针

版本：v1.6.15
1.优化抽水算法
2.增加币种CFX   已支持币种 Eth Etc Btc Ltc Ergo Rvn CFX
3.优化BTC

版本：v1.6.11
针对BTC 多矿池 进行优化  没有BTC的可以不更新

版本：v1.6.8
强烈建议167版本升至168  修复了167的一个己知BUG

版本：v1.6.7
增加币种Ergo Ltc 支持Eth Etc Btc Ltc Ergo Rvn

版本：v1.5.6
增加芯片机亚米的支持
增加BTC鱼池
程序配置支持备份还原导入导出
增 加币种 RVN支持ETH ETC BTC RVN

版本：v1.4.3
修复一个BUG

版本：v1.4.1
WEB后台支持HTTPS安全访问 矿机证书自定义
```
