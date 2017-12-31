# 使用介绍

### 简介

    将surge规则分割，只添加自己想要的部份路由，为 kitsunebi 定制自定义规则

---
* 在 <从指定 url 导入规则> 中输入对应地址导入对应规则

e.g：输入 https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/proxy/Top_blocked_sites.conf

则导入 Top_blocked_sites.conf 文件中的规则。 注：当前导入的规则不会覆盖前一次导入规则。
<!--
[^_^]:
![](https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/image/home_url-1.PNG)
![](https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/image/home_url-2.PNG)
-->

<div align="center">
<img src="https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/image/home_url-1.PNG" High="378" Width="213" alt="image1" >
<img src="https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/image/home_url-2.PNG" High="378" Width="213" alt="image2" >
</div>

### 规则目录说明与地址“前缀” 

#### 注：规则内容有部分重复,建议只增加 proxy 中的规则，ads 中的规则请谨慎添加，以免造成网址、视频、app加载内容缓慢的问题。（当然也许是dns的锅）

* ads————广告相关  

	* 前缀 https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/ads/

* direct————直连相关
		
	* 前缀 https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/direct/

* proxy————代理相关

	* 前缀 https://raw.githubusercontent.com/q158073378252010/Surge/new2017.12.29.08.30/kitsunebi/proxy/
