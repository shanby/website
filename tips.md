此页面最近一次更新时间：2020.04.20               
[返回到首页](https://clashopenwrt.github.io/website/)            

【IT奶爸的视频教程系列】：           
* 第01期：[三分钟上手](https://youtu.be/6qqWEPK9ODs)             
* 第02期：暂无                 
【其他】：               
* 如果全新写盘报错的话，临时解决办法：先刷一个其他的openwrt固件，然后上传升级本固件(不保留配置升级)，升级到本固件后再重置一次固件即可(至于解决写盘出错问题，这得等官方openwrt解决)                    
* [openclash官方说明](https://github.com/vernesong/OpenClash/blob/master/README.md)             
* 挂载着硬盘等外接存储设备的固件，更新前一定要先拔出来，再更新固件，否则总有一天你就哭吧       
* 修改LAN的IP命令：ifconfig br-lan         
* 大多数问题都可以重启一次固件解决，请牢记！IT界真理：重启！             
* 有些主题兼容性不好，在使用个别的luci插件时会出不显示错显示等bug,不想遇到这些问题请使用默认的主题(bootstrap类主题)                    
* “旁路由”模式下，无法访问国内网络，在防火墙自定义规则添加：           
iptables -t nat -I POSTROUTING -j MASQUERADE                                 
* 不保留配置升级：[图文](./upgrade.md)                        
* 如果出现YouTube等一些网站的页面上的特定内容错误显示，比如广告区域加载失败，只有框框没有图片，大概率是你的系统（不是固件！）的负责域名快速解析的HOSTS文件在作妖，解决办法是删除HOSTS文件里的所有规则（# 号注释掉的内容可以不管，其他的都删掉）    
* 始终无法连接到软路由网络、始终无网络：[可能解决办法](./winproxy.md)                          
* 单线or双线，最简单的iptv内网融合教程，需要懂一点基础：[教程](https://github.com/luckyyyyy/blog/issues/44)         

  
     

