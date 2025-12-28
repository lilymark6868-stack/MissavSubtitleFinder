# MissavSubtitleFinder

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-v5.3.3%2B-blue?logo=tampermonkey&logoColor=white)](https://www.tampermonkey.net/)
[![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

MissavSubtitleFinder字幕搜索脚本（油猴/Tampermonkey）。独家提供：[Missav](https://missav.ws/dm194/cn)自动嗅探m3u8视频链接、在线字幕（sub-dog）、多清晰度播放等能力。
![preview](https://github.com/lilymark6868-stack/MissavSubtitleFinder/blob/main/3.png)

## 功能说明

### M3U8链接嗅探
- 🎨 自动嗅探m3u8播放链接
- ⌨️ 点击复制链接
- 👁 点击跳转到[字幕狗](https://player.sub-dog.top/)播放
<img width="329" alt="image" src="https://github.com/lilymark6868-stack/MissavSubtitleFinder/blob/main/1.png" />

- 🖼 点击"multi"项。进入多清晰度播放
- 🤖 手机端/PC端/Pad多端支持

## 脚本使用介绍

### 1) 进入播放页

- 使用油猴安装此脚本
- 刷新网页，检测到m3u8链接后会自动出现在页面右上角位置，点击播放即可跳转到字幕狗网站
- 在视频播放页，有时需要先点击视频播放，才能检测到M3U8链接，若弹出广告页，请关闭广告页，回到视频播放页

## 使用安装

### PC端安装

1. 选择浏览器 `Chrome 130+`。

2. 安装 [Tampermonkey v5.3.3+](https://www.tampermonkey.net/)插件。

3. 开启 [浏览器扩展开发者模式](https://www.tampermonkey.net/faq.php#Q209)。

4. 点击 [dog-catch-mobile.user.js](https://raw.githubusercontent.com/lilymark6868-stack/MissavSubtitleFinder/v2.0/dog-catch-mobile.user.js) 安装 【115Master】脚本。

5. 在油猴面板勾选启动 【m3u8视频侦测字幕搜索器】脚本并刷新[Missav](https://missav.ws/dm194/cn)主页开始使用。

👆上面一通操作后，还是无法使用的话请提交 [Issues](https://github.com/lilymark6868-stack/MissavSubtitleFinder/issues)。

### iphone端安装

1.苹果商店搜索并安装Stay应用程序

## 常见问题

### 为什么脚本没有生效？

- 确认 Tampermonkey 中脚本已启用
- 尝试强制刷新页面（`Ctrl+F5`）

### 为什么没有匹配到字幕？
- 检查文件名中是否含有番号
- 字幕狗后端未更新该番号的字幕：前往[字幕狗主站](https://player.sub-dog.top/)，使用心愿单功能


