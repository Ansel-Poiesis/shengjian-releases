# FoilPage 安装与使用指南

[← 返回项目首页](../README.md) · [下载最新正式版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) · [问题反馈](https://github.com/Ansel-Poiesis/FoilPage-releases/issues)

## 安装与首次使用

1. 从官方 [最新正式版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) 下载 `FoilPage-Setup-版本号.exe` 并安装。支持 Windows 10 1809 及以上、Windows 11 的 64 位系统，无需安装 Python 或 Node.js。
2. 打开 FoilPage，在「准备」依次完成邮箱登录、环境检测、保存目录设置与本地模型下载。
3. 完成准备后，可粘贴视频链接，也可在「导入媒体」拖入本地视频或音频。
4. 在「任务」查看进度，到「文本库」阅读、编辑原稿与整理稿。正文整理和标题优化可分别开启；使用云端前先确认费用与数据处理方式。

安装包包含 CPU 转写所需的运行组件。NVIDIA GPU 加速包为独立可选下载：选择与桌面版本匹配的 `FoilPage-GPU-Pack-版本号.zip`，在「准备 → 环境检测 → 安装 GPU 加速包」中选取，完成后重启。CPU 用户无需下载该包。

## 安装提示与文件校验

安装包目前未配置 Windows 代码签名（Authenticode），首次运行时 Microsoft Defender SmartScreen 可能显示「Windows 已保护你的电脑」。

1. 确认文件来自 [Ansel-Poiesis/FoilPage-releases](https://github.com/Ansel-Poiesis/FoilPage-releases/releases)。
2. 下载同一版本的 `SHA256SUMS.txt`，用 PowerShell 计算本机安装包的 SHA-256，并逐字比较：

   ```powershell
   Get-FileHash -Algorithm SHA256 "下载目录\FoilPage-Setup-版本号.exe"
   ```

3. 来源正确且校验一致后，如仍出现 SmartScreen 提示，可点击「更多信息 → 仍要运行」继续。校验不一致时请重新下载，不要继续运行。

SHA-256 校验用于检查文件完整性，不代替代码签名。若后续版本启用代码签名，会在发行说明中注明。

## 本地与云端

登录后即可使用本地模型转写，不收取独立软件解锁费，也不扣云端积分。登录采用邮箱验证码，无需设置密码；邮箱用于接收验证码、标识账户与归属云端权益。

| 方式 | 使用与额度 | 转写并发 |
| :--- | :--- | :--- |
| 本地模型 | 登录后使用，不耗云端积分 | 1 |
| 标准云端积分 | ¥19.80 / 500 积分 / 30 天 | 2 |
| 专业云端积分 | ¥49.80 / 2000 积分 / 30 天 | 4 |

以上为当前公开发行页列示的套餐；实际购买以应用中的当前报价为准。云端积分按需单独购买，不自动续费。自带 API 由对应模型服务商计费。

本地转写在本机完成，视频与文稿不因本地转写上传。使用托管云端整理或自带 API 时，相应文本会交给所选服务处理；请按界面说明确认数据处理与费用。

## 浏览器扩展

1. 打开 FoilPage 的「浏览器」页，点击「打开扩展目录」。
2. 在 Chrome / Edge 的扩展管理页启用开发者模式。
3. 选择「加载已解压的扩展」，加载刚才打开的固定目录。
4. 回到 FoilPage 点击「允许连接」，在两分钟内打开浏览器扩展并完成一键配对。
5. 打开视频页，通过扩展提交给桌面端；平台下载仍受来源站点、登录状态与网络环境影响。

默认目录为 `%LOCALAPPDATA%\Programs\FoilPage\browser-extension`。旧安装原地升级可能仍在 `%LOCALAPPDATA%\Programs\VideoToArticle\browser-extension`；以 FoilPage 打开的目录为准，不要手动搬迁安装目录。

桌面升级会更新同一目录的扩展文件。扩展通常在任务完成且弹窗关闭后空闲重载，已打开的视频页可能需要刷新。若之前加载了另一份扩展副本，请先改用当前安装目录；没有自动重载能力的旧扩展需手动重载一次。此更新方式不依赖 Chrome 商店。

## Agent 控制

「设置 → Agent 控制」提供完整或只读 MCP 配置，可连接自己的 Agent。安装包随附 CLI，可管理文稿、任务与队列，也可配置模型和转写提示词。

保持 FoilPage 运行，驻留托盘时同样可连接；操作结果与应用中的编辑同步。配置步骤与当前实例信息以应用内指南为准。需要限制修改时，选择只读配置。

## 本地资料与更新

本地资料属于当前资料目录，切换邮箱不会移动本机视频和文本。当前默认数据目录为 `%LOCALAPPDATA%\FoilPage`，旧安装从 `VideoToArticle` 自动迁移；自定义路径以当前实例为准。

如升级后未看到文稿，请先检查当前资料目录、页面筛选和归档状态。不要以清空数据库或覆盖设置作为排查步骤；重要资料建议自行备份。

默认更新跟随正式版。测试版需要主动选择，不进入正式版的默认更新通知。最新版本与资源文件以 [正式发行页](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) 为准，历史标签和发行说明保留各自当时的状态。

在「设置 → 关于 → 通知与更新」查看更新记录。遇到问题请到 [Issues](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) 附上版本、系统与复现步骤，截图和日志请先移除私人内容。

## 使用边界与版权

下载与转写面向个人学习、备份和整理自己有权使用的内容。请遵守抖音、B 站、YouTube 等来源平台的服务条款及所在地法律。

FoilPage 软件及安装包版权所有 © 2026 Ansel-Poiesis。源码在私有仓库维护，本仓库为官方发行入口。请勿再分发或捆绑分发安装包；其他事宜可通过 [Issues](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) 联系。
