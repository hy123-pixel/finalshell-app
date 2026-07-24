# FinalShell App

一个基于 Tauri 2 + Vue 3 的跨平台 SSH 终端管理工具。

## 功能

- SSH 终端：xterm.js 渲染，多标签，支持密码/私钥认证
- SFTP 文件管理：目录浏览、文件编辑（语法高亮）、上传下载
- 服务器监控：CPU / 内存 / 磁盘 / 网络实时监控
- AI 助手：Chat / Agent 双模式，支持自定义 API 地址和 Key
- 端口转发：本地端口转发（SSH 隧道）
- 网络工具：Ping / Traceroute 实时输出
- 系统托盘、深色/浅色主题、8 种终端配色方案

## 下载

请前往 [Releases](../../releases) 页面下载最新版本。

| 平台 | 安装包 |
|------|--------|
| macOS | `.dmg` |
| Windows | `.msi` / `.exe` |

## 技术栈

- 前端：Vue 3 + TypeScript + Tailwind CSS + CodeMirror 6
- 后端：Tauri 2 (Rust) + russh
- 构建：Vite

## 支持项目

如果 FinalShell App 对你有帮助，欢迎扫码打赏支持项目持续维护。

<p align="center">
  <strong>支付宝</strong><br>
  <img src="docs/images/donate-alipay.jpg" alt="支付宝打赏码" width="320">
</p>

<p align="center">
  <strong>微信支付</strong><br>
  <img src="docs/images/donate-wechat.png" alt="微信打赏码" width="320">
</p>

## 联系与交流

扫描下方二维码添加微信，或加入 FinalShell 群聊交流使用心得和问题。

<p align="center">
  <strong>添加微信</strong><br>
  <img src="docs/images/wechat-contact.jpg" alt="微信好友二维码" width="320">
</p>

<p align="center">
  <strong>加入群聊</strong><br>
  <img src="docs/images/wechat-group.jpg" alt="FinalShell 微信群二维码" width="320">
</p>

> 群聊二维码有有效期；如二维码已失效，请先添加微信并备注“FinalShell”。

## 许可证

MIT
