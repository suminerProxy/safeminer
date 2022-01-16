# Safeminer矿池助手
# 全网第一款本地连接矿池加密软件，可直接在矿机上运行，无需中转服务器。全国连接矿池延时50以内，隐藏挖矿ip、加密数据包、流量混淆，可实现防止被检测挖矿的目的，GO语言开发，功能强大！

## 更新日志
```bigquery
2022-01-15 19:24    2.2.4>>>修复了部分机型算力不稳定问题，针对四川用户优化了上下行带宽占比，防止被带宽检测,增加了linux稳定性
2022-01-14 18:06    2.2.3>>>修复了部分Windows机型无法正常连接矿池，建议无法连接用户全部更换
2022-01-13 04:12    2.3.2>>>稳如老狗版，实现本地转发、ip隐藏、流量混淆，已完成稳定性测试

```

如需服务器抽水软件，可查看我的另一软件[https://github.com/suminerProxy/suminerProxy]     开发费为全网最低：0.2%
# windows安装


### 1、下载safeminer_linux.exe软件到矿机
### 2、打开挖矿软件
### 3、双击运行矿池助手
### 4、修改矿池地址到本地端口
  ```
	127.0.0.1:8901
  ```
### 5、开始运行
### 注意，部分机型在启动挖矿软件后本软件会被意外关闭，重新双击启动即可，攻城狮正在加紧定位解决！


# OS系统安装


### 1、在控制端执行一键安装指令
E池：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 1 helloworld&
```
鱼池：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 2 helloworld&
```
风池：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 3 helloworld&
```
蚂蚁：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 4 helloworld&
```
币印：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 5 helloworld&
```
欧易：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 6 helloworld&
```
HIVE：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 7 helloworld&
```
币安：
```
git clone https://e.coding.net/suminer/suminer/ssafeminer.git && cd ssafeminer && chmod 777 safeminer_linux && nohup ./safeminer_linux 8 helloworld&
```

### 2、执行成功后将矿池地址改成本地端口即可连接矿池
  ```
	127.0.0.1:8901
  ```


### 注意，不要重启矿机，重启矿机后执行下列指令重启软件
```
cd ssafeminer && nohup ./safeminer_linux &
```

## 重要说明

```bigquery
本软件开销极小，可挂在各类挖矿主机上运行
目前仅支持ETH，后续币种正在开发中
目前开发者固定费用为0.2%，可屏蔽内核抽取的算力
需要技术服务请添加技术支持qq：1514953259
或者加入电报群：https://t.me/+1hnMqBXqxsAyMGRl
```

