# graphic-network

## 概念

网络: 由若干**节点**和连接这些节点的**链路**组成

计算机网络: 一些**相互连接**、**自治**的计算机的**集合**

- 公用网
- 专用网

> ISP(Internet Service Provider, 因特网服务提供者)

交换方式: 

- 电路交换: 建立连接 -> 通话 -> 释放连接
- 报文交换
- 分组交换

计算机网络的性能指标:

- 速率（比特率）
- 宽带
- 吞吐量
- 时延
  - 发送时延
  - 传播时延
  - 处理时延
- 时延带宽积
- 往返时间（RTT）
- 利用率
- 丢包率

## 协议

协议: 控制两个**对等实体**进行逻辑通信的规则集合

协议数据单元（PDU）: 对等层次之间传送的数据包

> OSI开放系统互联参考模型和分层思想

TCP/IP协议族模型:

- 应用层

  - HTTP
  
  - SMTP

  - DNS
  
  - DHCP

  - TELNET

  - FTP

```sh
ping www.baidu.com

nslookup 

```

> 全世界总共13台根域名解析服务器

同源策略相关的响应头:

- `Access-Control-Allow-Origin`
- `Access-Control-Allow-Headers`
- `Access-Control-Allow-Credentials`
- `Access-Control-Allow-Methods`
- `Access-Control-Max-Age`
- `Access-Control-Expose-Headers`

缓存控制相关的请求和响应头标识:

- `Cacche-Control`
- `Date`
- `Expires`
- `Etag`
- `Last-Modified`
- `Pragma`

浏览器强制缓存: 内存缓存(from memory cache)和硬盘缓存(from disk cache)

> 简单请求和非简单请求（预检请求）

[fetch规范](https://fetch.spec.whatwg.org/)


- 运输层

  - TCP（报文段）
  
  - UDP（用户数据报）

```sh
netstat /?

```

- 网际层

  - IP（数据报）

> 静态IP和动态IP

```sh
ipconfig


```

- 网络接口层（帧）

**MAC地址**

传输媒体接口特性:

- 机械特性
- 电气特性
- 功能特性
- 过程特性

数据通信工作模式: 单工通信、半双工通信和全双工通信

> 曼彻斯特编码

传输媒体:

- 导向型：双绞线、同轴电缆、电力线和光缆等

- 非导向型：微波、红外线和无线电波等

## 设备

主机之间的通信方式:

- 客户-服务器方式（C/S）

- 对等方式（P2P）

### 交换机

- 电话交换机

- 分组交换机(路由器)：缓存转发分组

> 报文、控制首部和分组

### 调制解调器

数字信号和模拟信号

### 集线器


## 标准

> 因特网协会ISOC
