## 免费开源Http、Https抓包工具，支持Windows、Mac、Android、IOS,  全平台系统

**Mac首次打开会提示已损坏，需要到系统偏好设置-安全性与隐私-允许任何来源。**

国内下载地址：https://gitee.com/wanghongenpin/network-proxy-flutter/releases/tag/0.0.1

>  ios先没有上架AppStore, 后面在处理。

- Mac先点左上角关闭按钮退出，直接Command+q可能不会清理系统代理。如果退出上不了网，请检查系统代理设置，清除即可。

- [ ] 接下来会完善功能体验，JSON格式化展示，URL解码，UI优化。
- [ ] IOS上架app Store。
- [ ] 后面桌面端和手机端整合，扫码连接啥的，不用手动配置Wifi代理，包括配置同步。
- [ ] 支持安卓微信小程序抓包，安卓分为系统证书和用户证书，下载的自签名根证书安装都是用户证书，微信不信任用户证书，不Root导致Https抓不了了, 目前市场上所有抓包软件抓不了微信的包，后面单独做个运行空间插件，动态反编译修改配置，信任用户证书来解决。


<img alt="image"  width="600px" height="400px" src="https://github.com/wanghongenpin/network-proxy-flutter/assets/24794200/67a2feb1-f1c3-4c0c-8737-5abe62c34794">.    <img alt="image"   height="500px" src="https://github.com/wanghongenpin/network_proxy_flutter/assets/24794200/1bb4b1ec-ec5c-44a7-add7-f0f94c8765b9">


