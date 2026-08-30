<p align="center">
  <img src="assets/app-icon.png" width="132" alt="done灯 图标">
</p>

<h1 align="center">done灯</h1>

<p align="center">
  <strong>按一下，把“我刚刚完成了什么”留住。</strong><br>
  不用先写 Todo，不用启动计时，也不会持续录屏。
</p>

<p align="center">
  <a href="https://github.com/LearnPrompt/done-lamp-releases/releases/download/v0.3.4/done-lamp-0.3.4.dmg">
    <img src="https://img.shields.io/badge/Download-macOS%200.3.4-F4B400?style=for-the-badge&logo=apple&logoColor=111111" alt="下载 done灯 macOS 0.3.4">
  </a>
  <a href="https://github.com/LearnPrompt/done-lamp-releases/releases/latest">
    <img src="https://img.shields.io/badge/Release-更新内容-FFF4C2?style=for-the-badge&logo=github&logoColor=111111" alt="查看最新 Release">
  </a>
</p>

<p align="center">
  macOS 14.0+ · Apple Silicon + Intel · 已签名并通过 Apple 公证
</p>

<p align="center">
  <img src="assets/done-lamp-demo.gif" width="800" alt="done灯 从桌面宠物到今天记录和完成日报的产品预览">
</p>

完成一件事时轻点桌面上的 done灯，它会先保存这个真实的完成时间点，再根据你选择的记录方式补充内容。截图或识别失败也不会吞掉这次完成。

## 为什么是 done灯

- **完成后才记录**：不要求提前规划，也不推断你花了多长时间。
- **反馈不等 AI**：按下后立即得到视觉和声音反馈，识别在后台进行。
- **看见真实进展**：在“今天”里整理完成记录，每天 23:00 自动生成完成日报。

## 30 秒开始使用

1. 完成一件事后，轻点桌面宠物；长按约 2 秒可以撤销最近一次记录。
2. 在“今天”里查看、补充或修改刚才的完成事项。
3. 打开“日报”，回顾当天真实的完成时间线，并导出 Markdown 或便签图片。

<p align="center">
  <img src="assets/today.png" width="48%" alt="done灯 今天页面">
  <img src="assets/report.png" width="39%" alt="done灯 完成日报页面">
</p>

<p align="center"><sub>真实发布版本渲染：今天记录与完成日报</sub></p>

## 选择适合你的记录方式

| 方式 | 会截图吗 | 内容会去哪里 | 适合谁 |
| --- | --- | --- | --- |
| 仅记录 | 不会 | 只在本机保存完成时间和你填写的内容 | 只想快速留下完成瞬间 |
| 本地模型 | 主动按下时截取一次 | 交给本机 Ollama 识别 | 希望自动识别，同时尽量留在本机 |
| Codex Agent（在线） | 主动按下时截取一次 | 交给在线 Codex Agent 识别 | 已在使用 Codex，希望少配置 |
| 模型 API | 主动按下时截取一次 | 发送到你配置的模型服务 | 希望自己选择在线模型服务 |

识别模式可以选择“智能单窗”或“当前显示器”。done灯 不会持续录屏；只有在你主动按下时才会截取当时的画面。

## 隐私控制

- 选择“仅记录”时，不截图、不需要屏幕录制权限，也不调用模型。
- 只有选择识别模式后，done灯 才会请求 macOS 屏幕录制权限。
- 截图保留期限可以在设置中修改，也可以立即删除本机全部截图。
- 识别、权限或模型失败时，真实完成时间仍会保留并可手动补充。
- 提交公开反馈时，请勿上传私人截图、窗口标题、日志原文、API Key 或其他敏感信息。

## 安装

1. 下载并双击 [`done-lamp-0.3.4.dmg`](https://github.com/LearnPrompt/done-lamp-releases/releases/download/v0.3.4/done-lamp-0.3.4.dmg)。
2. 在弹出的窗口里，把 `done灯.app` 拖到“应用程序”。
3. 从“应用程序”打开 done灯，按引导选择“仅记录”、本地模型或在线识别。

## 当前版本

| 项目 | 信息 |
| --- | --- |
| 版本 | `0.3.4 (8)` · 初代公测版 |
| 系统 | macOS 14.0 或更高版本 |
| 架构 | Apple Silicon 与 Intel 通用安装包 |
| 安全 | Developer ID 签名、Apple 公证并装订凭据 |
| 安装包 | `done-lamp-0.3.4.dmg` · 约 42.7 MB |
| SHA-256 | `8066c77b74f9709432e01423ed0000be3efb51bfde6c17cb45b72010e208413b` |

完整改动见 [0.3.4 Release Notes](https://github.com/LearnPrompt/done-lamp-releases/releases/tag/v0.3.4) 和 [CHANGELOG](CHANGELOG.md)。

## 常见问题

### 不使用 AI 也能用吗？

可以。首次启动时选择“仅记录”，done灯 只保存完成时间和你手动填写的内容。

### 为什么识别模式需要屏幕录制权限？

这是 macOS 对屏幕截图统一使用的系统权限。done灯 只在你主动按下时截取一次，不会持续录屏。

### 遇到问题怎么办？

请先查看 [已有反馈](https://github.com/LearnPrompt/done-lamp-releases/issues)，确认没有重复后再：

- [报告问题](https://github.com/LearnPrompt/done-lamp-releases/issues/new?template=bug_report.yml)
- [提出建议](https://github.com/LearnPrompt/done-lamp-releases/issues/new?template=feature_request.yml)

## 关于这个仓库

这里是 done灯 的公开下载与反馈仓库，用于发布经过签名和 Apple 公证的安装包、更新日志和公开问题，不包含应用源码。
