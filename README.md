## wangcb.com上的小壁虎们

### 主用配置(ss):

```
ss://Y2hhY2hhMjA6Q1RZREREREREQlVH@ss.wangcb.com:8080#ss.wangcb.com
```

使用方法：将上面这串URL导入到客户端内

若主用配置无法使用，请去[备用配置](#%E5%A4%87%E7%94%A8%E9%85%8D%E7%BD%AE)。

### ss客户端下载:

- Windows
  - [https://github.com/shadowsocks/shadowsocks-windows/releases](https://github.com/shadowsocks/shadowsocks-windows/releases)
- Android
  - [https://github.com/shadowsocks/shadowsocks-android/releases](https://github.com/shadowsocks/shadowsocks-android/releases)
- OS X
  - [https://github.com/shadowsocks/ShadowsocksX-NG/releases](https://github.com/shadowsocks/ShadowsocksX-NG/releases)
- iOS
  - [Outline](https://itunes.apple.com/app/outline-app/id1356177741) or [Wingy(App Store)](https://itunes.apple.com/us/app/wingy-http-s-socks5-proxy-utility/id1178584911)

### 备用配置:

所有备用配置使用[v2ray软件](https://www.v2ray.com/)作为代理软件。使用此软件，通常通过配置文件连接。

- 1 静态tcp端口vmess协议的备用配置。
  - 配置文件: [client_tcp.json](./client_tcp.json)
- 4 动态tcp端口vmess协议的备用配置。
  - 配置文件: [client_Dtcp.json](./client_Dtcp.json)
- 3 基于[mKCP](https://www.v2ray.com/chapter_02/transport/mkcp.html)底层传输的备用配置，此配置可以将网络流量伪装成微信视频聊天。
  - 配置文件: [client_mkcp.json](./client_mkcp.json)
- 4 基于WebSocket底层传输的备用配置。
  - 配置文件: [client_ws.json](./client_ws.json)
- 5 伪装为http的备用配置。
  - 配置文件: [client_http.json](./client_http.json)
- ~~6 在heroku上部署的基于TLS加密+WebSocket(wss)底层传输并使用Domain Fronting技术绕过Censorship的备用配置。~~
  - ~~配置文件: [v2ray-heroku.json](./v2ray-heroku.json)~~
- 7 基于http2底层传输的备用配置。
  - 配置文件: [client_h2.json](./client_h2.json)
- 8 基于http2底层传输，并通过Cloudflare CDN隧穿的备用配置。
  - 配置文件: [client_h2_cf.json](./client_h2_cf.json)

### v2ray客户端下载:

- Windows, Linux, OS X
  - [官方v2ray-core](https://github.com/v2ray/v2ray-core/releases)
- Android
  - [v2rayNG](https://github.com/2dust/v2rayNG/releases) or [BifrostV](https://play.google.com/store/apps/details?id=com.github.dawndiy.bifrostv)
- iOS
  - [Shadowrocket(App Store, 付费软件$2.99)](https://itunes.apple.com/us/app/shadowrocket/id932747118?mt=8)
