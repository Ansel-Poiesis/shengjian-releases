<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/home/hero-dark.png">
    <img src="assets/home/hero-light.png" alt="FoilPage — 把视频，展开成文字。视频下载、本地转写与文稿整理。" width="1000">
  </picture>
</p>

<p align="center">
  <strong>Windows 上的视频下载、本地转写与文稿整理工具。</strong><br>
  把课程、访谈和自己的录音，留下来，读下去，再编辑。
</p>

<p align="center">
  <img src="assets/home/badge-windows.png" alt="Windows 10 / 11 · 64 位" height="26">
  <img src="assets/home/badge-local.png" alt="本地转写 · 登录即用" height="26">
  <img src="assets/home/badge-cloud.png" alt="云端整理 · 按需选用" height="26">
</p>

<p align="center">
  <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest"><img src="assets/home/download.png" alt="下载 Windows 版" width="204" height="44"></a>
  &nbsp;
  <a href="docs/guide.md"><img src="assets/home/guide.png" alt="安装与使用指南" width="176" height="44"></a>
</p>

<p align="center">
  <a href="#先看它能做什么">功能一览</a> ·
  <a href="#三步开始">快速开始</a> ·
  <a href="docs/guide.md#浏览器扩展">浏览器扩展</a> ·
  <a href="docs/guide.md#agent-控制">Agent 控制</a> ·
  <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/issues">问题反馈</a>
</p>

<br>

## 从播放，到阅读

视频适合观看，文字适合回看。FoilPage 把下载、转写和文稿放在同一个工作区：保留原稿，按需整理，在文本库中继续阅读和编辑。

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/home/workspace-dark.png">
  <img src="assets/home/workspace-light.png" alt="FoilPage 文本库：左侧导航、中间文稿列表、右侧原稿与整理稿阅读区。当前界面使用示例内容展示。" width="1000">
</picture>

<p align="center"><sub>当前界面 · 示例内容展示 · 支持深色与纸白主题</sub></p>

## 先看它能做什么

| 留下内容 | 继续使用 |
| :--- | :--- |
| **视频链接与本地媒体**<br>支持抖音、B 站、YouTube 视频链接，也可导入本地视频与音频。 | **原稿与整理稿**<br>在文本库中切换原稿与整理稿，继续阅读、编辑与复制。 |
| **在本机完成转写**<br>下载本地模型后使用 CPU 转写；可选 NVIDIA GPU 加速包。 | **按需整理文字**<br>正文整理与标题优化可分别开启，选择托管云端或自带 API。 |
| **从浏览器收集**<br>配对 Chrome / Edge 扩展，把当前视频页提交给桌面端。 | **让 Agent 接着工作**<br>通过 MCP / CLI 管理文稿、任务和队列，编辑与应用同步。 |

平台下载能力受来源站点、登录状态与网络环境影响。请只处理自己有权使用的内容。

## 本地转写，按需连接云端

**本地模型登录后即可使用，不收取独立软件解锁费，也不消耗云端积分。** 邮箱验证码用于登录和识别账户，无需设置密码。

| 处理方式 | 在哪里处理 | 使用与计费 |
| :--- | :--- | :--- |
| 本地转写 | 本机 | 登录后使用，不耗云端积分 |
| 托管云端整理 / 标题优化 | 云端模型服务 | 按账户套餐和积分权限使用 |
| 自带 API | 您配置的服务商 | 由相应服务商计费 |

本地转写在本机完成，视频和文稿不会因为这一步上传。启用云端整理或自带 API 时，相应文本会交给所选服务处理；请先确认界面中的数据处理与费用说明。[查看使用与费用说明 →](docs/guide.md#本地与云端)

## 三步开始

**01 · 安装桌面端**  
前往 [最新正式版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest)，下载 `FoilPage-Setup-版本号.exe`。支持 Windows 10 1809 及以上、Windows 11 的 64 位系统，无需安装 Python 或 Node.js。

**02 · 完成准备**  
打开「准备」，依次完成邮箱登录、环境检测与目录设置、本地模型下载。CPU 用户无需下载 GPU 加速包。

**03 · 放入一段内容**  
粘贴视频链接，或在「导入媒体」拖入本地文件。到「任务」查看进度，再到「文本库」阅读与编辑文稿。

> 安装包目前未配置 Windows 代码签名，首次运行可能出现 SmartScreen 提示。请先确认下载来源，并按 [安装与文件校验说明](docs/guide.md#安装提示与文件校验) 核对文件。

## 常见问题

<details>
<summary><strong>没有 NVIDIA 显卡，可以使用吗？</strong></summary>

可以。安装包包含 CPU 转写需要的运行组件。NVIDIA GPU 加速是可选项；需要时，从对应版本的发行页下载匹配的 `FoilPage-GPU-Pack-版本号.zip`，再到「准备 → 环境检测 → 安装 GPU 加速包」中安装并重启。

</details>

<details>
<summary><strong>本地转写为什么需要登录？</strong></summary>

登录用于识别 FoilPage 账户与归属云端权益，不要求为本地转写购买云端积分。本地转写仍在本机完成；首次准备和邮箱登录需要网络。

</details>

<details>
<summary><strong>浏览器扩展从哪里安装？</strong></summary>

在 FoilPage 的「浏览器」页点击「打开扩展目录」，然后在 Chrome / Edge 扩展管理页启用开发者模式，选择「加载已解压的扩展」。回到 FoilPage 点击「允许连接」，完成配对。[查看完整步骤 →](docs/guide.md#浏览器扩展)

</details>

<details>
<summary><strong>更新版本或切换账户，会移动本地文稿吗？</strong></summary>

本地资料属于当前资料目录，切换账户不会移动本机视频和文本，云端权益属于对应账户。升级后如发现内容未显示，请先核对当前资料目录与筛选条件；重要资料建议自行备份。[查看资料与更新说明 →](docs/guide.md#本地资料与更新)

</details>

<details>
<summary><strong>这是开源项目吗？</strong></summary>

FoilPage 源码在私有仓库维护。这里是官方 Windows 发行与反馈入口，提供安装包、发行说明和使用文档。[查看使用边界与版权 →](docs/guide.md#使用边界与版权)

</details>

## 文档与反馈

| 我想…… | 从这里开始 |
| :--- | :--- |
| 下载、安装，完成首次转写 | [安装与使用指南](docs/guide.md) |
| 安装扩展，连接 Chrome / Edge | [浏览器扩展](docs/guide.md#浏览器扩展) |
| 连接自己的 Agent | [MCP / CLI 入口](docs/guide.md#agent-控制) |
| 查看版本变化 | [发行记录](https://github.com/Ansel-Poiesis/FoilPage-releases/releases) |
| 反馈问题，提出建议 | [提交 Issue](https://github.com/Ansel-Poiesis/FoilPage-releases/issues/new/choose) |

反馈时请附 FoilPage 版本、Windows 版本和复现步骤；截图或日志请先移除邮箱、密钥、登录码、私人文稿和带签名的视频地址。

---

<p align="center">
  <strong>FoilPage</strong><br>
  <sub>把视频，展开成文字。</sub><br><br>
  <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest">下载最新正式版</a> ·
  <a href="docs/guide.md">阅读使用指南</a><br><br>
  <sub>© 2026 Ansel-Poiesis · 版权所有 · @玩家川行出品</sub>
</p>
