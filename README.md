# Lan
ShadowsocksR C# 版本4.7.0

BitTorrent Sync：BHS55LP54SO7A434QBB5Z2O6B7A45B2BX
主页：https://breakwa11.github.io/
Wiki：https://github.com/breakwa11/shadowsocks-rss/wiki
ZeroNet主页：shadowsocksr.bit
ShadowsocksR主要分支：SSR C#, SSR python manyuser, SSR-libev
Android APP: SSR-android
iOS APP： Shadowrocket, Potatso2, Cross
MAC APP：ShadowsocksX-NG, ShadowsocksX-R
其它跨平台分支：avege, electron-ssr
Docker: https://hub.docker.com/r/breakwa11/shadowsocksr/

推荐使用ZeroNet地址，或BitTorrent Sync免翻自动更新，最及时自动获取最新版本
注意发布压缩包内有一个以sig后缀的签名文件（如果没有签名文件，即文件已经被修改过），您应该使用GPG进行校验
公钥地址 https://github.com/breakwa11/pubkey
Key ID: 175F58E4
Fingerping: A39E EB81 2880 75A8 A383 7D2E 211B 66B7 175F 58E4
Key ID: F82FA47C
Fingerping: DD98 A7DF DDCD B5AD D6F6 A17B 602A 81C9 F82F A47C
尽量在此处下载，以避免使用被篡改的版本。如果为了图方便在其它公开网络或下载站下载的，记得要做签名校验，签名是唯一凭证。

版本特点

全能代理，同一端口支持socks4/socks4a/socks5/http
节点统计，包括延迟、连接数、当前下载速度、最高速度、出错率等等
连接管理，随时断开指定节点的连接，或修改节点后自动断开
协议转换，把UDP包封装于TCP里发送
多重代理，通过设置前置socks5/http代理，可达到任意重代理
协议插件，支持自定义协议和协议混淆，详见ShadowsocksR插件文档 <<== 要了解插件的点这里看
你要是有兴趣和我联系的话，特别是编程技术上的支持，那就到
Twitter: @breakwa11
聊天室: https://gitter.im/breakwa11/shadowsocksr
Riot: #ssr:matrix.org
社区: ShadowsocksR
Blogger: https://breakwa11.blogspot.com
Google Group: ShadowsocksR
TOX: D211FF64C848E03161700E74714A2100D363757AED4982F35486CC0713577C2F356B7DD84CAB

更新记录：

版本4.7.0 2017-07-27
1.增加协议auth_chain_b，具体特性参见协议文档
2.修正部分内存泄露
3.修正系统代理设置错误

版本4.6.1 2017-06-29
1.删除默认订阅
2.编辑服务器的一些小BUG修正
