# safeminer矿池助手
# 全网第一款本地连接矿池加密软件，隐藏本地ip、加密数据包、流量混淆，可实现防止被检测挖矿的目的

## 更新日志
```bigquery

2022-01-13 04:12    2.3.2>>>稳如老狗版，实现本地转发、ip隐藏、流量混淆，已完成稳定性测试

```



# windows安装


## 下载safeminer_linux.exe软件到矿机
## 打开挖矿软件
## 双击运行矿池助手
## 修改矿池地址到本地端口
···bash
E池：127.0.0.1:8901
鱼池：127.0.0.1:8902
风池：127.0.0.1:8903
蚂蚁：127.0.0.1:8904
币印：127.0.0.1:8905
···
## 开始运行
### 注意，部分机型在启动挖矿软件后本软件会被意外关闭，重新双击启动即可，攻城狮正在加紧定位解决！


# OS系统安装


## 在控制端执行一键安装指令
···

···


### 查看运行情况
```bash
screen -r minerProxy
```
### 退出查看运行情况 键盘键入
```
ctrl + a + d
```
## Linux手动安装
```bash
# 运行3.0.3稳定版
mkdir minerProxy303
cd minerProxy303
wget https://raw.githubusercontent.com/Char1esOrz/minerProxy/master/release/v3.0.3/minerProxy_web
chmod 777 minerProxy_web
./minerProxy_web
# 运行4.0.0测试版
mkdir minerProxy
cd minerProxy
wget https://raw.githubusercontent.com/Char1esOrz/minerProxy/master/release/v4.0.0T6/minerProxy_v4.0.0T6_linux_amd64
chmod 777 minerProxy_v4.0.0T6_linux_amd64
./minerProxy_v4.0.0T6_linux_amd64
```

### 后台运行（注意后面的&）运行完再敲几下回车

```bash
# 运行3.0.3稳定版
nohup ./minerProxy_web &
# 运行4.0.0测试版
nohup ./minerProxy_v4.0.0T6_linux_amd64 &
# 运行之后查看webtoken
tail -f nohup.out
```

### 后台运行时关闭

```bash
killall minerProxy
```
### 后台运行时查看
```bash
tail -f nohup.out
```
## 重要说明

```bigquery
推荐使用腾讯云香港节点,flexpool和ethermine都可以到50ms左右,延迟率在0.5%-0.9%之间
该软件系统占用极小,开最便宜的云服务器即可（不要使用轻量服务器,轻量网络极差）
tg交流群
https://t.me/minerProxyGroup
```

![img_2.png](img/img_2.png)
