# 听潮软件

把日常需要的工具，慢慢做成顺手的作品。

[作品网站](https://sites.google.com/view/tingchao-software) · [软件下载与发布说明](https://github.com/GMD777/tingchao-apps/releases/latest)

## 开始使用

下载最新发行版中的 **tingchao-launcher-1.1.1.zip**，解压完整文件夹，在 Windows 10/11 64 位电脑上双击“听潮应用库.exe”。需要系统 .NET Framework 4.8。首次打开是空应用库，点击“添加应用”收录自己的软件、网址或文件。

**今汐 · 听潮 1.0.0** 的软件包同在发行版中。聊天和语音需配置自己的接口，公开包不含个人配置、接口密钥或聊天记录。其余作品目前在网站展示，尚未全部加入公开下载。

## 联网更新

启动器已配置以下固定更新地址：

```
https://github.com/GMD777/tingchao-apps/releases/latest/download/feed.json
```

启动器运行时后台检查与下载，关闭需要更新的应用后，由用户点击“安装更新”。原版本入口保留。退出后不检查；启动器本身暂需手动下载新版。

添加今汐听潮时，更新标识填写 `jinhsi-listen`，显示版本填写 `1.0.0`。当前清单中的相同版本不会提示更新，发布更高版本后才会发现新版。

1.1.1 修正 HTTPS 连接兼容问题，已通过真实公网清单读取、软件包下载和 SHA256 校验。请使用 1.1.1 替代 1.1.0。

请在 Releases 下载软件 ZIP；GitHub 自动生成的 Source code 仅是本仓库说明文件快照。
