# 听花语 · Flower NFC Music Project

> 用音乐读懂花朵的秘密 🌸

## 项目简介

「听花语」是一个结合 NFC 技术的文创项目。每一张花朵卡片都内置 NFC 标签，用户用手机触碰卡片，即可自动打开对应的花朵页面，聆听专属的花语音乐。

### ✨ 特色功能

- 📱 **NFC 触发**：手机碰一下，自动打开花朵页面
- 🎵 **音乐陪伴**：每朵花都有专属的背景音乐
- 📖 **花语故事**：了解花朵的文化寓意和美丽传说
- 🎨 **精美设计**：适配手机的优雅界面

---

## 项目结构

```
flower-nfc/
├── index.html              # 首页（花朵列表）
├── flower/                 # 花朵详情页
│   ├── lotus.html         # 荷花
│   ├── osmanthus.html     # 桂花
│   └── plum.html          # 梅花
├── css/
│   └── style.css          # 全局样式
├── js/                     # JavaScript（待扩展）
├── assets/                 # 音乐文件、图片等资源
└── README.md              # 项目说明
```

---

## 支持的花朵

| 花朵 | 寓意 | 音乐风格 |
|------|------|---------|
| 🪷 荷花 | 出淤泥而不染 | 禅意钢琴 |
| 🌼 桂花 | 十里桂花香 | 民谣吉他 |
| 🌸 梅花 | 凌寒独自开 | 古琴独奏 |

---

## 部署指南

### 方式一：Cloudflare Pages（推荐）

1. 注册 [Cloudflare](https://cloudflare.com) 账号
2. 进入 `Pages` → `Create a project`
3. 连接 GitHub 仓库
4. 部署设置：
   - Build command: **留空**
   - Build output directory: `/`
5. 点击 `Deploy`

**部署完成后，绑定自定义域名：**
- 在 Cloudflare Pages 项目设置中添加自定义域名
- 修改 Namecheap 的 DNS 记录

---

### 方式二：GitHub Pages（免费）

1. 在 GitHub 仓库设置中开启 `GitHub Pages`
2. 选择 `main` 分支作为源
3. 访问 `你的用户名.github.io/flower-nfc`

---

### 方式三：本地测试

直接用浏览器打开 `index.html` 即可预览

---

## NFC 配置

### 写入 NFC 标签

使用 NFC 写入工具（如 iOS 的「快捷指令」或 Android 的 `NFC Tools`）：

1. 购买 NTAG213 NFC 标签（约 ¥0.5/个）
2. 写入对应花朵的 URL，例如：
   - 荷花：`https://你的域名.com/flower/lotus.html`
   - 桂花：`https://你的域名.com/flower/osmanthus.html`
   - 梅花：`https://你的域名.com/flower/plum.html`
3. 将 NFC 标签贴在卡片背面

---

## 音乐版权

⚠️ **重要提醒**：

本项目使用的音乐需确保版权合规：

- ✅ 使用免版权音乐（推荐）：[Pixabay Music](https://pixabay.com/music/)、[FMA](https://freemusicarchive.org/)
- ✅ 联系独立音乐人授权
- ✅ 定制原创音乐
- ❌ 禁止使用未经授权的流行歌曲

---

## 后续开发计划

- [ ] 添加更多花朵（牡丹、樱花、薰衣草等）
- [ ] 实现真实的音乐播放功能
- [ ] 添加微信小程序版本
- [ ] 用户收藏功能
- [ ] 社区分享功能
- [ ] 多语言支持

---

## 技术栈

- HTML5
- CSS3
- JavaScript (Vanilla)
- NFC Web API

---

## 贡献指南

欢迎提交 Issue 和 Pull Request！

---

## 许可证

MIT License

---

## 联系方式

- 项目作者：Panchi Art
- 域名：[panchiart.com](http://panchiart.com)
- 邮箱：（待补充）

---

**用心聆听，每一朵花都在唱歌 🎵**