<p align="right"><a href="guide.md">English</a> · <a href="guide.zh-CN.md">简体中文</a></p>

# FoilPage 安装与使用指南

[返回首页](../README.zh-CN.md) · [下载最新版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) · [反馈问题](https://github.com/Ansel-Poiesis/FoilPage-releases/issues)

## 安装与开始使用

1. 从官方发行页下载最新版 **FoilPage-Setup** 并安装。支持 64 位 Windows 10 1809 及以上版本、Windows 11。
2. 打开 FoilPage，在「准备」中完成邮箱验证码登录、环境检测、保存目录设置和本地模型下载。
3. 粘贴支持的视频链接，或导入本地视频、音频。
4. 在「任务」查看进度，到「文本库」阅读原稿并编辑整理稿。

CPU 转写可用。NVIDIA GPU 加速包为可选项，版本需与桌面端匹配。

## 校验安装包

当前安装包尚未使用 Windows Authenticode 签名，首次启动时 SmartScreen 可能提示风险。

1. 确认安装包来自 FoilPage 官方发行页。
2. 下载同一版本的 **SHA256SUMS.txt**。
3. 在 PowerShell 中运行 **Get-FileHash -Algorithm SHA256**，将安装包计算结果与该版本校验文件逐字比对。
4. 来源和哈希一致后，若 SmartScreen 仍提示，可选择「更多信息 → 仍要运行」。若不一致，请重新下载。

SHA-256 用于检查文件完整性，不等同于代码签名。

## 本地与云端处理

邮箱验证码用于识别账户，无需设置密码。本地转写在电脑上完成，不消耗云端积分。

托管文字整理与标题优化为可选功能。开启后，该次操作所需的文本会发送到所选服务。使用前请查看应用内当前报价。自带 API 按服务商规则计费。

## 配对浏览器扩展

1. 打开 FoilPage 的「浏览器」页，选择「打开扩展目录」。
2. 在 Chrome 或 Edge 扩展管理页启用开发者模式。
3. 选择「加载已解压的扩展」，选中 FoilPage 打开的目录。
4. 返回 FoilPage 点击「允许连接」，并在两分钟内从扩展完成配对。
5. 打开支持的视频页面，通过扩展提交到桌面端。

默认目录为 **%LOCALAPPDATA%\Programs\FoilPage\browser-extension**。旧安装可能仍使用 **%LOCALAPPDATA%\Programs\VideoToArticle\browser-extension**。请以 FoilPage 实际打开的目录为准，不要手动移动已安装扩展。

## 连接 Agent

在「设置 → Agent 控制」复制完整或只读 MCP 配置。随附 CLI 可管理文稿、任务和队列。连接期间请保持 FoilPage 运行。

## 本地资料与更新

媒体和文稿保存在当前本机资料目录。切换邮箱不会移动这些文件。默认目录为 **%LOCALAPPDATA%\FoilPage**；旧版可能从 **VideoToArticle** 迁移。请以当前应用显示的路径为准。

更新后找不到文稿时，先核对资料目录、筛选条件和归档状态。重要文件请自行备份。

FoilPage 默认跟随正式版。当前安装包和更新说明以[最新发行页](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest)为准。

## 内容使用与支持

请只使用你有权访问和处理的内容，并遵守来源平台条款及所在地法律。

反馈问题时，请在 [Issues](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) 中附上 FoilPage 版本、Windows 版本和复现步骤。截图或日志中请移除私人文稿、账户信息、验证码和带签名的媒体链接。
