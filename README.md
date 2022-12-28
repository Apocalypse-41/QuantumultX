# Quantumult X
>Quantumult X 是iOS端最好的代理软件！

## 0. 目录
- 节点
- 分流
- 重写 & MitM
- 进阶用法
- 特别感谢

## 1. 节点
自用机场收集，排名不分先后

|                               机场名称                                |                                                 套餐截图                                                 |
|:---------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------:|
| [Texon's LAB](https://texon.io/portal/aff.php?aff=291)</br>（菜市场） | ![Texon's LAB](https://raw.githubusercontent.com/Apocalypse-41/QuantumultX/main/Images/Texon'%20LAB.png) |
|        [AmyTelecom](https://www.amysecure.com)</br>（按摩院）         |  ![AmyTelecom](https://raw.githubusercontent.com/Apocalypse-41/QuantumultX/main/Images/AmyTelecom.png)   |
|             [FlowerCloud](https://flower.yt)</br>（花云）             |  ![FlowerCloud](https://github.com/Apocalypse-41/QuantumultX/blob/main/Images/FlowerCloud.png?raw=true)  |
|   [跨越长城](https://panel.gfwnetwork.com/#/register?code=1EWzhmfM)   | ![CrossGFW](https://raw.githubusercontent.com/Apocalypse-41/QuantumultX/main/Images/CrossGFW.png)                                                                                                         |

## 2. 分流
### GEOIP
[@Hackl0us](https://github.com/Hackl0us/GeoIP2-CN)
- 强烈建议修改代理软件设置中的Geoip为此[优化版](https://github.com/Hackl0us/GeoIP2-CN/raw/release/Country.mmdb)
- 且不要使用类似的国内分流规则，避免冲突

### 全分流规则
[@blackmatrix7](https://github.com/blackmatrix7/ios_rule_script/tree/master/rule/QuantumultX)
- ❤️神仙规则集

### 神机去广告
[@DivineEngine](https://github.com/DivineEngine/Profiles/tree/master/Quantumult/Filter/Guard)
- [广告拦截](https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Advertising.list)
- [隐私保护](https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Privacy.list)
- [运营商劫持](https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Filter/Guard/Hijacking.list)

### Minor Stuff
- [Wechat规则](https://raw.githubusercontent.com/unknowntokyo/surge-list/master/wechat.list)
- [Private Relay](https://raw.githubusercontent.com/VirgilClyne/iRingo/main/Archive/sgmodule/iCloud_Private_Relay_Gateway_for_ACL4SSR.sgmodule)

## 3. 重写 & MitM
### 基础配置
- [神机Google重定向](https://raw.githubusercontent.com/DivineEngine/Profiles/master/Quantumult/Rewrite/General.conf)
- [blackmatrix7去广告](https://raw.githubusercontent.com/blackmatrix7/ios_rule_script/master/rewrite/QuantumultX/AllInOne/AllInOne.conf)

### 🍟 整点薯条
[@VirgilClyne](https://github.com/VirgilClyne)
- [ iRingo](https://github.com/VirgilClyne/iRingo)：解锁完整的Apple功能和集成服务
- [🍿️ DualSubs](https://github.com/DualSubs/DualSubs)：流媒体平台字幕增强及双语模块

### 🧰 BoxJs
<https://raw.githubusercontent.com/chavyleung/scripts/master/box/rewrite/boxjs.rewrite.quanx.conf>
- 使对脚本参数进行进一步配置成为可能
- [使用教程](https://docs.boxjs.app)

### ✅  功能提升
- [Emby Premium](https://raw.githubusercontent.com/qiangxinglin/Emby/main/QuantumultX/emby.conf)
- [Spotify Premium](https://raw.githubusercontent.com/Apocalypse-41/QuantumultX/main/Rewrite/SpotifyPremium.qxrewrite)
- [Testflight 账号管理](https://raw.githubusercontent.com/NobyDa/Script/master/TestFlight/TestFlightAccount.js)

### ⚠️ 去广告
- Pending

## 4. 进阶用法
### **Quantumult X** 网关模式说明

原文：https://github.com/crossutility/Quantumult-X/blob/master/lan-gateway.md

步骤（**M1** 设备为例）：
1. M1设备上开启流量转发：`sudo sysctl -w net.inet.ip.forwarding=1`
2. 其它设备上的Wi-Fi设置，手动设置路由器地址为M1设备的IP 
3. DNS 设置为`198.19.0.3`

## 5. 特别感谢
@erdongchanyo的小白教程，让我在2022年春节从零开始自学上手Quantumult X这个宝藏软件。

**教程系列**：[@w37fhy](https://github.com/w37fhy/QuantumultX)、[@erdongchanyo](https://github.com/erdongchanyo/Rules/blob/main/Quantumult%20X/README.md)  
**图标库**：[@erdongchanyo](https://github.com/erdongchanyo/icon)、[@Orz-3](https://github.com/Orz-3/mini)、[@koolson](https://github.com/Koolson/Qure)  
**JavaScript**：[@KOP-XIAO](https://github.com/KOP-XIAO/QuantumultX)  
**规则与重写**：[@NobyDa](https://github.com/NobyDa/Script)、[@blackmatrix7](https://github.com/blackmatrix7/ios_rule_script)  
