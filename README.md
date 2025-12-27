# MissavSubtitleFinder

[![Tampermonkey](https://img.shields.io/badge/Tampermonkey-v5.3.3%2B-blue?logo=tampermonkey&logoColor=white)](https://www.tampermonkey.net/)
[![TypeScript](https://img.shields.io/badge/TypeScript-blue?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

[missav](https://missav.ws/dm194/cn)字幕搜索脚本（油猴/Tampermonkey）。主要提供：在线字幕（sub-dog）、字幕评论、字幕校准等能力。
![preview](https://github.com/lilymark6868-stack/MissavSubtitleFinder/blob/main/3.png)

## 功能说明

### M3U8链接嗅探
- 自动嗅探m3u8播放链接
- 点击复制链接
- 点击跳转到[字幕狗](https://player.sub-dog.top/)播放
<img width="329" alt="image" src="https://github.com/lilymark6868-stack/MissavSubtitleFinder/blob/main/1.png" />

### 在线字幕（sub-dog）

在播放器控制栏提供“字幕组(C)”入口（快捷键 `C`），支持：

- 站内登录/注册（弹窗）
- 字幕开关（显示/隐藏）
- 多字幕变体切换，付费字幕会显示“👑”
- 卡密充值：兑换后解锁更多付费字幕
- 3万+字幕自动匹配：根据115网盘文件名中的番号自动匹配
- 字幕来源展示：
  - `sub-dog`：后端字幕服务
  - `115网盘`：来自 115 网盘的字幕文件
- 记住每个视频的字幕选择偏好（下次打开自动恢复）

### 播放器增强

- 🎨 `Ultra` 画质
- 👁 视频缩略图
- 🤖 在线外挂字幕
- 🖼 画中画
- ⌚ 播放列表展示
- ⌨️ 快捷键
- 🎨 视频调色

### 网盘文件列表增强（首页/文件列表）

- 视频封面预览增强（列表模式下）
- 使用 `115master` 播放页打开
- 使用 115 原生播放页打开

## 脚本使用介绍

### 1) 进入播放页

- 在 115 网盘文件列表中：点击“master播放”，会跳转到 `master` 播放页
- 如果你已在 `master` 播放页：脚本会自动加载增强播放器与控件

### 2) 使用字幕组（在线字幕）

1. 在播放器控制栏点击字幕图标（提示“字幕组(C)”）
2. 未登录时：菜单第一行显示“登录/注册”，点击后在弹窗内完成登录/注册/重置密码
3. 登录后：菜单会列出可用字幕（含来源与是否付费标识）
4. 选择字幕后即可显示；按 `C` 可快速显示/隐藏字幕
5. 遇到付费字幕（带“👑”）：
   - 点击会弹出“账户升级”弹窗
   - 可点击“前往购买卡密”购买后，在弹窗内输入卡密兑换
   - 也可点击“前往字幕狗”打开字幕站：`https://player.sub-dog.top/`

## 使用安装

1. 选择浏览器 `Chrome 130+` 或 `115Browser 35+`。

2. 安装 [Tampermonkey v5.3.3+](https://www.tampermonkey.net/)。

3. 开启 [浏览器扩展开发者模式](https://www.tampermonkey.net/faq.php#Q209)。

4. 点击 [115master.user.js](https://raw.githubusercontent.com/lilymark6868-stack/115SubtitleAssistant/v2.0/115master.user.js) 安装 【115Master】脚本。

5. 在油猴面板勾选启动 【115Master】脚本并刷新 115 主页开始使用。

6. 安装完成后如果没有看到文件列表中有【master播放】的按钮，请检查有没有其他脚本导致冲突或重启浏览器。

<img width="329" alt="image" src="https://github.com/user-attachments/assets/189ac578-0592-43bd-ab75-b62cbe6f5170" />

👆上面一通操作后，还是无法使用的话请提交 [Issues](https://github.com/lilymark6868-stack/115SubtitleAssistant/issues)。

## 常见问题

### 为什么脚本没有生效？

- 确认 Tampermonkey 中脚本已启用
- 尝试强制刷新页面（`Ctrl+F5`）

### 为什么没有匹配到字幕？
- 检查文件名中是否含有番号
- 字幕狗后端未更新该番号的字幕：前往[字幕狗主站](https://player.sub-dog.top/)，使用心愿单功能


