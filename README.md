# 罗马地名回声 iPhone 版

这是可安装到 iPhone 主屏幕的 PWA 版本。

## 安装

1. 将整个 `roman-globe-ios` 目录发布到 HTTPS 网站。
2. 用 iPhone Safari 打开发布后的网址。
3. 点击 Safari 的分享按钮。
4. 选择“添加到主屏幕”。
5. 从主屏幕打开后会以独立窗口运行。

首次打开需要联网完成缓存，之后即使断网也可以继续使用。

## 文件

- `index.html`：完整游戏，包含地图、故事、题库和离线数据。
- `manifest.webmanifest`：应用名称、图标和独立窗口配置。
- `sw.js`：离线缓存。
- `icons/`：iPhone 主屏幕和网页图标。

## 限制

这是网页应用，不是 App Store 原生应用。上架 App Store 仍需要 macOS、Xcode、Apple Developer 账号、签名和审核。
