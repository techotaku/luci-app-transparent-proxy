LEDE LuCI support for transparent proxy
===

[![Latest release][release_badge]][release_url]     

A LuCI tool, to manage transparent port forwarding (iptables / ipset) rules.    
Compatible with most proxy which accept redirected packets.    
一个用于管理透明端口转发（iptables / ipset）规则的 LuCI 工具。    
与大多数接受数据包转发的代理服务兼容。    

* Shadowsocks (ss-redir)  
* ShadowsocksR (ssr-reidr)  
* V2Ray (dokodemo-door)  
* Redsocks  

Core part is simplified from  [LuCI for Shadowsocks-libev](https://github.com/shadowsocks/luci-app-shadowsocks).    
Follow its license GPLv3.    
核心部分自 [LuCI for Shadowsocks-libev](https://github.com/shadowsocks/luci-app-shadowsocks) 简化而来。    
沿用其开源协议 GPLv3。    
    
    
下图示例中配合使用的 V2Ray 和 SSR [配置文件和启动脚本参考](https://gist.github.com/techotaku/6bd6a8453b266aca1104775c1d5f945d)    

![General](https://user-images.githubusercontent.com/1948179/29064048-5d21de38-7c5a-11e7-8d86-23f5b35d9346.png "General")    
![Access Control](https://user-images.githubusercontent.com/1948179/29064274-0c69f2b8-7c5b-11e7-9669-d37fc874351d.png "Access Control")    
 [release_badge]: https://img.shields.io/github/release/techotaku/luci-app-transparent-proxy.svg
 [release_url]: https://github.com/techotaku/luci-app-transparent-proxy/releases/latest
