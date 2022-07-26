## CTIPFS

CTIPFS 代表着内容到IPFS的网络中来，我们希望未来越来越多应用能够使用IPFS网络的优势
用户可以很容易访问查找存储在IPFS的内容，而不需要了解IPFS的技术，当然用户希望Web 3.0的方式来存取数据。

```
例如：
1. 用户想查找存在IPFS上的某个文件是否包含“XXX” 内容，而不想下载该文件再查找，就像使用google搜索一样。
2. 用户想观看某个视频，而不需要知道某个视频的名字对应的是一个CID。
```    

## 为什么要做CTIPFS
web3.0 在不断的发展，人们对数据的隐私及权利越来越重视。
广大开发者和社区对用 web3.0 方式存储、管理、维护和使用数据的需求也会越来越大，
有必要通过将 web2.0 和 web3.0 解决方案混合在一起来提供服务以帮忙他们迁移应用程序的服务以及开发新的应用程序。


## 关于CTIPF的计划？
根据上面的设想：我们计划采用以下几个步骤来实现这个计划，当然这个roadmap也是比较简陋。

```
第一、把用户非常感兴趣的内容储存到IPFS，并提供Web2.0的查询服务，让用户能够感受更高效和便捷的体验。
	     * 这也是我们本次Hackathon切入的一点。
	     
第二、 提供标准的服务或者SDK，开发者社区可以容易集成。
第三、 开放标准的协议，希望以区块链和去中心的思路来发展这个项目。
```


## 关于本次Hackathon
	
|  表头   | 表头  |
|  ----  | ----  |
| 1. 很容易的将磁力链对应的内容转存到IPFS上去。       | 【已完成】 |
| 2. 将热点的内容存储到IPFS上去，并建立响应的数据索引    | 【进行中】|
| 3. 为社区和开发者提供高效查询服务。  | 【规划中】|
| 4. 为更多普通内容建立索引    | 【规划中】|

##  视频Demo

![avatar](https://github.com/JiesonWu/CTIPFS/blob/main/Result.png)

##  CTIPFS 源码使用样例

## Build from source

```
go build bt2ipfs.go
```

## Usage

示例：将磁力链(magnet:?xt=urn:btih:KRWPCX3SJUM4IMM4YF5RPHL6ANPYTQPU）对应的文件存储到IPFS上（127.0.0.1:5001）


```
# ./bt2ipfs magnet:?xt=urn:btih:KRWPCX3SJUM4IMM4YF5RPHL6ANPYTQPU 127.0.0.1:5001
Waiting info of magnet:?xt=urn:btih:KRWPCX3SJUM4IMM4YF5RPHL6ANPYTQPU
Filename: ubuntu-14.04.2-desktop-amd64.iso
Size: 1044381696
[##################################################] 1044381696/1044381696
IPFS hash: QmaZnCNKzkkqMvNhsrw3zHhVTnUy6P1tK9dbPmLBBXLN7D
```
