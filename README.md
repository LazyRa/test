# surge


Surge 是基于 iOS 9 的新特性 Network Extension 开发的一款网络调试工具，工作原理是使用 Packet Tunnel Provider 给系统套上一个代理，Surge 有两个主要组件：Surge 代理服务器和 Surge TUN 接口。程序运行之后，Surge 会将自身设置为默认的 HTTP/HTTPS 代理服务器来处理所有的 HTTP/HTTPS 流量。针对一些不服从系统代理设置（如 Mail.app ）的应用程序 ，将由 Surge 的 TUN 接口来进行处理。


看完了？还是不知道这是什么，好吧 <a href="https://medium.com/@scomper/surge-%E9%85%8D%E7%BD%AE%E6%96%87%E4%BB%B6-a1533c10e80b#.t8ft6niyv">那就点我吧</a>，看完你就知道了。
