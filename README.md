<p align="right"><a href="#user-content-home-en">English</a> · <a href="#user-content-home-zh">简体中文</a></p>

<details name="foilpage-language" open>
<summary><strong>English</strong></summary>

<a id="home-en"></a>

<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/hero-en-dark-v4.svg"><img src="assets/home/hero-en-light-v4.svg" alt="FoilPage — Turn video into text you can revisit." width="1000"></picture></p>

<h1 align="center">FoilPage</h1>
<p align="center"><strong>Turn video into text you can revisit.</strong><br>Video download, local transcription, and an editable library for Windows.</p>
<p align="center"><a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-download-en-dark-v3.svg"><img src="assets/home/action-download-en-light-v3.svg" alt="Download for Windows" height="44"></picture></a> &nbsp; <a href="docs/guide.md"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-guide-en-dark-v3.svg"><img src="assets/home/action-guide-en-light-v3.svg" alt="Setup guide" height="44"></picture></a> &nbsp; <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-releases-en-dark-v3.svg"><img src="assets/home/action-releases-en-light-v3.svg" alt="Release notes" height="44"></picture></a> &nbsp; <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/issues"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-feedback-en-dark-v3.svg"><img src="assets/home/action-feedback-en-light-v3.svg" alt="Feedback" height="44"></picture></a></p>


<p align="center">Windows 10 / 11 · Local CPU transcription · Optional NVIDIA acceleration<br>Keep the transcript. Refine a draft. Return to the source.</p>
<p align="center"><a href="#features">Features</a> · <a href="#two-appearances">Light &amp; dark</a> · <a href="#your-workflow">Workflow</a> · <a href="#quick-start">Quick start</a> · <a href="#questions">FAQ</a></p>

## A workspace for what you want to keep

A lecture is easier to revisit when you can read it. An interview becomes more useful when its original words and your edited notes stay together. Your own recordings deserve a place in that same library.

FoilPage brings **download, transcription, reading, and editing** into one Windows workspace. Local models handle transcription on your computer. Text cleanup and title refinement are separate choices, so you can keep the original transcript and continue with a more readable draft when you want one.

<a id="features"></a>

## What you can do

| Bring content in | Keep working with it |
| :--- | :--- |
| **Video links** — start from a supported Douyin, Bilibili, or YouTube link. Browser pairing helps with sources that need a browser session. | **A readable library** — search documents, filter by tags, and return to earlier transcripts without finding the video again. |
| **Local video and audio** — import recordings or existing media files. Queue several items and follow their progress in Tasks. | **Transcript and draft** — keep the source text, open the edited draft, and continue reading, editing, copying, or exporting. |
| **On-device transcription** — use a downloaded model on CPU; choose the matching NVIDIA GPU pack when you want hardware acceleration. | **Optional text processing** — configure draft cleanup and title refinement independently, using hosted services or your own API. |
| **A browser companion** — send a video page to the desktop app through a paired Chrome or Edge extension. | **Agent access** — connect MCP or CLI to work with documents, tasks, and queues while keeping the desktop app in the loop. |

Source-site changes, sign-in requirements, and network conditions can affect downloads. Use content you are entitled to download and process.

<a id="two-appearances"></a>

## Two appearances. The same workspace.

The homepage uses FoilPage's own sage, forest, and jade palette. Both views below are shown together so you can compare them without changing your GitHub theme.

### Light · White Rock

Soft sage surfaces, dark forest text, and a quiet reading area.

<img src="assets/home/workspace-en-light-v3.png" alt="FoilPage Light · White Rock: English navigation, sample documents, and an edited draft in the library." width="1000">

### Dark

Forest surfaces, pale text, and a muted jade accent for longer sessions.

<img src="assets/home/workspace-en-dark-v3.png" alt="FoilPage Dark: the same English library and sample draft using the dark appearance." width="1000">

<sub>Screenshots use fictional sample content and the current development interface. The English interface switch has been added to source; it is not included in the existing 1.3.10 installer. Check future release notes for availability.</sub>

<a id="your-workflow"></a>

## From a link to a document you can use

**01 · Bring it in.** Paste a supported link, submit the current video page from the browser extension, or import local media. Choose the route that fits the source.

**02 · Let the queue work.** Follow download and transcription as separate stages in Tasks. Download a local model during setup; CPU is supported, and a matching GPU pack is optional.

**03 · Read before you refine.** Open the transcript in Library. Turn on draft cleanup or title refinement only when it helps; original text and a refined draft remain distinct.

**04 · Make it useful again.** Add tags, search the library, edit the draft, copy a passage, or export the text. Return to the source when a detail needs context.

## Local work, optional online services

Local transcription does not use hosted cloud credits and does not require a separate software-unlock payment. Account sign-in uses an email verification code. First-time setup, model downloads, and account verification need a network connection.

| Route | Processing location | What to expect |
| :--- | :--- | :--- |
| **Local transcription** | Your computer | Audio is transcribed by the installed local model. This step does not upload your media or transcript. |
| **Hosted text cleanup / title refinement** | Hosted model service | Relevant text and prompts are sent to the service. Access follows the current in-app plan and credit permissions. |
| **Your own API** | Your configured provider | Relevant content goes to that provider and is billed under its terms. Optional visual processing can also send selected frames. |

Cloud credits are purchased separately when needed; there is no automatic renewal. Review the active settings and data-processing notices before using an online model. Account switching does not move local media or documents between folders.

## Work from the browser

Keep a video in view and let the extension hand it to FoilPage.

1. In **Browser**, open the extension folder supplied by your installation.
2. In Chrome or Edge, enable Developer mode and choose **Load unpacked**.
3. Back in FoilPage, allow a connection; complete pairing from the extension during the displayed window.
4. Submit the current video page. Keep FoilPage running while the desktop queue processes it.

Desktop updates refresh the extension files in the same installation folder. Older installations may still use the original `VideoToArticle` path. Use the folder the application opens rather than moving it manually. [Full browser setup →](docs/guide.md)

## Continue with your agent

**Settings → Agent control** offers full-access and read-only MCP configurations. The installer also includes a CLI. A connected agent can manage documents, tasks, queues, model settings, and prompt profiles within the access you choose.

FoilPage must remain running; a tray-resident instance can still accept connections. Edits made through the control interface are reflected in the app. Choose read-only access when you only need inspection or retrieval.

## Language and appearance

The development interface now provides **Settings → Appearance → Interface language**, with **English** and **简体中文**. This setting is saved independently of the speech-recognition language: changing the interface does not translate your documents, rename your tags, or change the language used for transcription.

The default appearances are named **Dark** and **Light · White Rock** in English. Additional built-in palettes remain available in Appearance. Detailed legal and source documents retain their own original language.

<a id="quick-start"></a>

## Install and make your first transcript

| Requirement | Details |
| :--- | :--- |
| System | 64-bit Windows 10 version 1809 or later, or Windows 11 |
| Runtime | The installer includes the CPU runtime; Python and Node.js are not required |
| Local model | Download a model during setup before local transcription |
| GPU | Optional NVIDIA pack; its version must match the desktop app |
| Account | Email verification code; no password to create |

1. Download the **FoilPage-Setup** installer from the [latest stable release](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest).
2. Open **Setup**, sign in, check the environment, choose your folders, and download a local model.
3. Add a link or import a local recording. Follow it in **Tasks**, then open **Library** to read the result.

The installer is currently unsigned. Verify the official source and the matching `SHA256SUMS.txt` before continuing past a SmartScreen prompt. In PowerShell, use `Get-FileHash -Algorithm SHA256 "path-to-installer.exe"` and compare the result with the release checksums. [Installation guide →](docs/guide.md)

<a id="questions"></a>

## Questions before you start

<details><summary><strong>Can I use FoilPage without an NVIDIA GPU?</strong></summary>

Yes. CPU transcription is included. Download the optional GPU pack only when you have a compatible NVIDIA setup, and use the pack that matches your desktop version.

</details>

<details><summary><strong>Do I need to buy cloud credits for local transcription?</strong></summary>

No. Local transcription is available after sign-in and does not consume hosted cloud credits. Online cleanup, title refinement, or your own API follow their separate service terms and costs.

</details>

<details><summary><strong>Will changing the interface language change my documents?</strong></summary>

No. The interface setting changes application labels. Document titles, tags, prompts, and body text retain the language and content you supplied. Speech-recognition language is a separate setting. The new interface switch is currently in development source, awaiting a desktop release.

</details>

<details><summary><strong>Why do some video links need the browser extension?</strong></summary>

Some sources depend on a browser session or information available on the video page. Pair the extension with your own browser session, then submit from the page. Pairing does not guarantee that every platform or video can be downloaded.

</details>

<details><summary><strong>What happens to local documents when I switch accounts or update?</strong></summary>

Local documents belong to the current data folder. Account changes affect online entitlements, not the location of local files. If documents appear missing, check the active folder, filters, and archive state before changing or deleting anything. Keep backups of important material.

</details>

<details><summary><strong>Is this an open-source repository?</strong></summary>

No. Source code is maintained privately. This is the official Windows distribution, documentation, and feedback repository. Installers and GPU packs are provided through Releases.

</details>

## Releases, documentation, and support

The stable update channel follows the latest formal release. Preview builds require an explicit choice. Historical release notes describe their own versions; they are not a promise about the current installation.

| You want to… | Start here |
| :--- | :--- |
| Install or update FoilPage | [Latest stable release](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) |
| Read installation and pairing steps | [Setup guide](docs/guide.md) |
| Read all published changes | [Release history](https://github.com/Ansel-Poiesis/FoilPage-releases/releases) |
| Report a problem or suggest an improvement | [Issues](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) |

Include the FoilPage version, Windows version, and reproducible steps in a report. Remove email addresses, keys, login codes, private text, and signed media URLs from shared screenshots or logs.

Download and process only content you are entitled to use, and follow the source platforms' terms. FoilPage software and installers are © 2026 Ansel-Poiesis. Do not redistribute or bundle the installers without permission.


</details>

<details name="foilpage-language">
<summary><strong>简体中文</strong></summary>

<a id="home-zh"></a>

<p align="right"><a href="#user-content-home-en">English</a> · <a href="#user-content-home-zh">简体中文</a></p>
<p align="center"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/hero-zh-dark-v4.svg"><img src="assets/home/hero-zh-light-v4.svg" alt="FoilPage — 把视频折进文字平面，再展开阅读。" width="1000"></picture></p>

<h1 align="center">FoilPage</h1>
<p align="center"><strong>把视频折进文字平面，再展开阅读。</strong><br>Windows 上的视频下载、本地转写与可编辑文本库。</p>
<p align="center"><a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-download-zh-dark-v3.svg"><img src="assets/home/action-download-zh-light-v3.svg" alt="下载 Windows 版" height="44"></picture></a> &nbsp; <a href="docs/guide.zh-CN.md"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-guide-zh-dark-v3.svg"><img src="assets/home/action-guide-zh-light-v3.svg" alt="安装与使用" height="44"></picture></a> &nbsp; <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/releases"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-releases-zh-dark-v3.svg"><img src="assets/home/action-releases-zh-light-v3.svg" alt="更新记录" height="44"></picture></a> &nbsp; <a href="https://github.com/Ansel-Poiesis/FoilPage-releases/issues"><picture><source media="(prefers-color-scheme: dark)" srcset="assets/home/action-feedback-zh-dark-v3.svg"><img src="assets/home/action-feedback-zh-light-v3.svg" alt="问题反馈" height="44"></picture></a></p>


<p align="center">Windows 10 / 11 · 本地 CPU 转写 · 可选 NVIDIA 加速<br>保留原稿，整理成稿，随时回到来源。</p>
<p align="center"><a href="#中文功能">功能一览</a> · <a href="#中文主题">亮色与暗色</a> · <a href="#中文流程">使用流程</a> · <a href="#中文开始">快速开始</a> · <a href="#中文问答">常见问题</a></p>

## 留下内容，也留下继续使用它的空间

一堂课变成文字，才更容易回看；一段访谈留下原话与自己的笔记，才方便再次思考。自己的会议录音、长谈和创作素材，也可以放进同一个文本库。

FoilPage 把**下载、转写、阅读与编辑**放在一个 Windows 工作区中。本地模型在电脑上完成转写；正文整理和标题优化分别控制。保留原稿，需要时再继续整理，让一段内容有机会成为可以反复使用的文稿。

<a id="中文功能"></a>

## 它能帮您做什么

| 把内容收进来 | 继续阅读和使用 |
| :--- | :--- |
| **视频链接**：支持抖音、B 站、YouTube；需要浏览器会话的来源，可通过配对扩展提交。 | **可检索的文本库**：搜索文稿，按标签筛选，再次阅读时不必先找到原视频。 |
| **本地视频与音频**：导入自己的录音或已有文件，加入队列后在任务页查看进度。 | **原稿与整理稿分开保留**：切换文本版本，继续阅读、编辑、复制或导出。 |
| **在本机转写**：下载本地模型后使用 CPU；需要时安装与桌面版本匹配的 NVIDIA GPU 包。 | **按需整理**：正文整理、标题优化分别开启，使用托管服务或自己的 API。 |
| **浏览器伴侣**：从配对的 Chrome / Edge 视频页，把内容提交到桌面队列。 | **连接 Agent**：通过 MCP / CLI 管理文稿、任务和队列，操作与应用同步。 |

平台下载能力受来源站点、登录状态与网络条件影响。请只下载和处理自己有权使用的内容。

<a id="中文主题"></a>

## 两种外观，同一个工作区

主页沿用软件的灰绿、森林绿与玉绿。亮色和暗色在这里同时展示，不需要切换 GitHub 主题才能比较。

### 亮色 · 白岩 / Light · White Rock

浅灰绿的层次、深色文字和安静的阅读区域。

<img src="assets/home/workspace-en-light-v3.png" alt="FoilPage 亮色白岩主题，展示真实英文界面与示例文稿。" width="1000">

### 暗色 / Dark

森林绿的界面、浅色文字与低饱和玉绿强调。

<img src="assets/home/workspace-en-dark-v3.png" alt="FoilPage 暗色主题，展示同一套英文文本库与示例文稿。" width="1000">

<sub>截图使用虚构示例内容与当前开发界面。英文切换已加入源码，现有 1.3.10 安装包尚不包含该入口，实际可用版本以之后的发行说明为准。</sub>

<a id="中文流程"></a>

## 从一段内容，到一篇可以继续使用的文稿

**01 · 收进来。** 粘贴支持的视频链接，从浏览器扩展提交当前视频页，或导入本地媒体。不同来源使用适合它的入口。

**02 · 交给队列。** 在任务页分别查看下载和转写阶段。准备时先下载本地模型；CPU 可以使用，GPU 包按需安装。

**03 · 先读，再决定怎么整理。** 在文本库打开原稿，判断是否需要正文整理或标题优化。原话和整理稿分别保留，避免把两者混在一起。

**04 · 再次使用。** 加上标签，搜索旧文稿，继续编辑、复制片段或导出文本。引用细节前，也可以重新核对来源和语境。

## 本地处理，与按需选择的在线服务

本地转写登录后即可使用，不消耗托管云端积分，也不收取独立软件解锁费。账户使用邮箱验证码登录；首次准备、模型下载和账户验证需要网络。

| 处理方式 | 在哪里处理 | 需要了解的事 |
| :--- | :--- | :--- |
| **本地转写** | 当前电脑 | 由本地模型处理音频；这一步不会把媒体或转写正文上传。 |
| **托管正文整理、标题优化** | 托管模型服务 | 相关文字与提示词会交给服务处理，按当前套餐和积分权限使用。 |
| **自带 API** | 您配置的服务商 | 相关内容交给对应服务商并按其规则计费；开启视觉功能时还可能发送所选画面。 |

云端积分按需单独购买，不自动续费。启用在线模型前，请确认当前设置、数据处理说明与费用。切换账户不会移动本机媒体和文稿。

## 从浏览器继续收集

保留眼前的视频页，让扩展把它交给 FoilPage。

1. 在「浏览器」页打开当前安装附带的扩展目录。
2. 在 Chrome / Edge 扩展管理页启用开发者模式，选择「加载已解压的扩展」。
3. 回到 FoilPage 允许连接，在显示的时间窗口内从扩展完成配对。
4. 在视频页提交任务，让运行中的桌面队列继续处理。

桌面升级会更新同一目录的扩展文件。旧安装可能仍使用 `VideoToArticle` 目录，以软件打开的路径为准，不需要手动搬迁。[完整扩展步骤 →](docs/guide.zh-CN.md)

## 与您的 Agent 接着工作

「设置 → Agent 控制」提供完整访问与只读 MCP 配置；安装包也附带 CLI。连接后，可以在所选权限内管理文稿、任务、队列、模型设置与提示词。

FoilPage 需要保持运行，驻留托盘时也可接受连接。通过控制接口完成的编辑会同步到应用。仅需查询和读取时，使用只读配置。

## 界面语言与主题名称

当前开发界面新增「设置 → 界面 → 界面语言」，可保存 **English / 简体中文**。它与转写识别语言独立：切换界面不会翻译文稿、改写标题或标签，也不会更改转写的语言配置。

默认主题的英文名称为 **Dark** 与 **Light · White Rock**；其他内置配色仍可从主题列表选择。详细法律与来源文档保留各自原文语言。

<a id="中文开始"></a>

## 安装并完成第一次转写

| 项目 | 要求与说明 |
| :--- | :--- |
| 系统 | Windows 10 1809 及以上，或 Windows 11，64 位 |
| 运行组件 | 安装包包含 CPU 运行组件，无需安装 Python 或 Node.js |
| 本地模型 | 在准备阶段下载完整模型，再开始本地转写 |
| GPU | NVIDIA 加速包可选，必须与桌面版本匹配 |
| 账户 | 邮箱验证码登录，无需创建密码 |

1. 从 [最新正式版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) 下载 **FoilPage-Setup** 安装器。
2. 打开「准备」，依次登录、检查环境、设置目录并下载本地模型。
3. 添加链接或本地录音。在「任务」查看进度，再到「文本库」阅读结果。

安装包当前未配置 Windows 代码签名。遇到 SmartScreen 提示前，请核对官方来源与同版本 `SHA256SUMS.txt`。可用 PowerShell 的 `Get-FileHash -Algorithm SHA256 "安装包路径.exe"` 比较校验值。[完整安装指南 →](docs/guide.zh-CN.md)

<a id="中文问答"></a>

## 开始前，您可能关心这些

<details><summary><strong>没有 NVIDIA 显卡也能使用吗？</strong></summary>

可以，安装包包含 CPU 转写组件。GPU 包是可选项，需要兼容的 NVIDIA 环境，且必须与桌面版本匹配。

</details>

<details><summary><strong>本地转写需要购买云端积分吗？</strong></summary>

不需要。本地转写登录后即可使用，不扣托管云端积分。在线整理、标题优化和自带 API 各自遵循对应服务与费用说明。

</details>

<details><summary><strong>切换英文界面会更改文稿吗？</strong></summary>

不会。界面设置只改变应用标签，不更改用户标题、标签、提示词或正文。转写识别语言也保持独立。该入口已加入开发源码，尚待新桌面版本发行。

</details>

<details><summary><strong>为什么部分链接需要浏览器扩展？</strong></summary>

部分来源依赖浏览器会话或视频页中的信息。使用自己的浏览器配对，再从视频页提交。配对成功不等于所有平台和视频均可下载。

</details>

<details><summary><strong>更新或切换账户，会移动本地文稿吗？</strong></summary>

本地文稿属于当前资料目录。切换账户影响在线权益，不改变文件所在目录。如果内容未显示，请先核对当前目录、筛选与归档状态，不要直接删除数据库或覆盖设置。重要内容建议保留备份。

</details>

<details><summary><strong>这是开源仓库吗？</strong></summary>

不是。源码在私有仓库维护，这里是官方 Windows 发行、使用文档与反馈入口。安装器和 GPU 包通过 Releases 提供。

</details>

## 版本、文档与反馈

默认更新跟随最新正式版，测试版需要主动选择。历史发行说明只描述各自版本，不代表当前安装实例的状态。

| 我想…… | 从这里开始 |
| :--- | :--- |
| 安装或更新 FoilPage | [最新正式版](https://github.com/Ansel-Poiesis/FoilPage-releases/releases/latest) |
| 查看安装与浏览器配对步骤 | [安装指南](docs/guide.zh-CN.md) |
| 查看所有版本变化 | [发行记录](https://github.com/Ansel-Poiesis/FoilPage-releases/releases) |
| 反馈问题、提出建议 | [Issues](https://github.com/Ansel-Poiesis/FoilPage-releases/issues) |

反馈时请提供 FoilPage 版本、Windows 版本与复现步骤。分享截图或日志前，先移除邮箱、密钥、验证码、私人正文和带签名的媒体链接。

请只处理自己有权使用的内容，并遵守来源平台条款。FoilPage 软件及安装包 © 2026 Ansel-Poiesis。未经允许，请勿再分发或捆绑分发安装器。

<p align="center"><sub>@玩家川行出品</sub></p>


</details>
