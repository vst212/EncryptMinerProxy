<h2 align="center">蜜罐加密代理-平头哥</h2>
<h4 align="center">市面上第一款也是唯一一款加密代理抽水软件</h4>

<p align="center">
  <a>
    <img src="https://img.shields.io/badge/Release-v1.0.0-orgin.svg" alt="travis">
  </a>
  <a>
    <img src="https://img.shields.io/badge/Last_Update-2022_02_17-orgin.svg" alt="travis">
  </a>
</p>

<p align="center">
  <a href="https://t.me/+Q0u6PCLXZoZhMjRl">Telegram 群</a> •
  <a href="https://jq.qq.com/?_wv=1027&k=6Hkn0cla">QQ 群</a> 
</p>


## :sparkles: 特性

- 💾 安全稳定：客户端服务端模式(也可单独服务端模式)，加密混淆
- :cloud: 目前支持ETH-GPU，后续支持BTC-ASIC等机型币种
- :zap: 性能强劲，CPU占用低
- 💻 可以自定义抽水比例
- 📚 可以自定义抽水算法
- :outbox_tray: WEB管理，清晰明了
- :rocket: 开箱即用：All-In-One 打包，一键搭建运行
- :family_woman_girl_boy: 支持Liunx Windows

## 流量侦别原理
发现很多人不太理解为啥运营商可以侦别SSL流量，明明已经用了SSL(非常安全，数据几乎无法被破解)，但是为啥运营商还是能够识别你的流量呢，其实下图就是原理，中心词就是两个字：特征。对于大数据训练的模型无需知道流量内容，通过大量数据训练之后，流量对外呈现某种特征类型，就可以识别流量了，无需知道明文。
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E6%B5%81%E9%87%8F%E4%BE%A6%E5%88%AB.jpg" width="350"/>
</h1>
知道原理了，那么可以针对该原理，使用自定义加密的算法，并且对数据进行混淆操作，甚至模拟访问正常网页访问，尽可能抹去特征，这样运营商就无法识别。

## 普通代理方案

<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E6%99%AE%E9%80%9A%E4%BB%A3%E7%90%86%E6%96%B9%E6%A1%88.jpg" width="800"/>
</h1>

## 蜜罐平头哥部署模式
### 部署方案1-同普通代理方案

<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E9%83%A8%E7%BD%B2%E6%96%B9%E6%A1%881.jpg" width="800"/>
</h1>

### 部署方案2

<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E9%83%A8%E7%BD%B2%E6%96%B9%E6%A1%882.jpg" width="800"/>
</h1>

### 部署方案3

<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E9%83%A8%E7%BD%B2%E6%96%B9%E6%A1%883.jpg" width="800"/>
</h1>


## 加解密报文
### 蜜罐平头哥客户端加密混淆
Windows 双击运行即可
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E5%AE%A2%E6%88%B7%E7%AB%AF%E5%8A%A0%E5%AF%86%E6%95%B0%E6%8D%AE.jpg" width="800"/>
</h1>

### 蜜罐平头哥服务端解密转发
Windows 双击运行即可
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/%E6%9C%8D%E5%8A%A1%E7%AB%AF%E8%A7%A3%E5%AF%86%E6%95%B0%E6%8D%AE.jpg" width="800"/>
</h1>

### 蜜罐平头哥WEB界面-客户端
Windows 双击运行即可
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/Web%E7%95%8C%E9%9D%A2-%E5%AE%A2%E6%88%B7%E7%AB%AF.jpg" width="800"/>
</h1>

### 蜜罐平头哥WEB界面-服务端
Windows 双击运行即可
<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/ryu0007/EncryptMinerProxy/main/Web%E7%95%8C%E9%9D%A2.jpg" width="800"/>
</h1>

## :hammer_and_wrench: 运行
### Windows
在对应的机器商双击运行以下脚本(脚本比较简陋，后续完善)，按照提示运行：

Win服务端代理一键安装脚本.bat

Win客户端代理一键安装脚本.bat

### Linux
还未编译Linux版本，待编译之后补充


## 其他说明
待补充

