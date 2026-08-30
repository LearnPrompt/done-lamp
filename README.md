<p align="center">
  <img src="assets/app-icon.png" width="132" alt="done灯 图标">
</p>

<h1 align="center">done灯</h1>

<p align="center">
  <strong>Agent 干得更快了，“做完了”的感觉却不见了。</strong><br>
  done灯 就负责把这一下按回来。<br>
  给每天并行跑 Agent 的 P 人。你不用先列清单，也能爽到像顶级 J 人刚清空一整页待办。
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

## 我为什么想做这盏灯

进入 Agent 时代后，我一天能做的事真的翻了四五倍。我没有夸张。

我的一天也变得很碎。发一个需求，等半小时。切去做别的，又被 Agent 的回复叫回来。几个 Agent 一起跑，额度窗口和重置时间还在旁边催着。看着点，别浪费。

以前做完一件事，至少会关掉一个页面，或者划掉一个待办。现在很多结果只需要扫一眼、点一下、继续跑。事情确实结束了，我的脑子却没收到那个“好了，这件做完了”的信号。

有天晚上，我看着已经结束的几个任务，脑子里只剩一个问题。**今天到底干了什么？**

这个槽点后来变成了 done灯。

我不想再做一套需要认真维护的效率系统。P 人已经够忙了，别为了记待办，再给“记待办”建一个待办。

我只想要一个很小的动作。Agent 交付了，按一下。灯亮一下，响一声。好，这件事结束。然后继续去跑下一个。

> 这个“按一下”的仪式，我想从 Agent 手里抢回来。

我喜欢 Agent 带来的速度。done灯 只补上被速度挤掉的那个动作，让我在继续跑下一个任务之前，知道上一件已经结束。

## 它不催你规划，只在你做完时亮一下

- **没写进 Todo 也算。** 做完再按。突然处理掉的事、Agent 临时跑出来的结果，都配拥有一个勾。
- **识别还在跑，你先爽到。** 声音和表情不会等 AI，完成感先到，文字稍后再补。
- 到了晚上十一点，日报会把散在各个窗口里的交付放回同一张时间线上。终于不用猜自己今天干过什么。

## 用起来真的只有三步

1. **有结果了。** Agent 交付，或者你自己终于做完一件事。不用提前写进清单。
2. **按一下。** done灯 响一声、亮一下，这件事落进“今天”。按错了？长按约 2 秒撤销。
3. **晚上看一眼。** 日报会把散在不同 Agent、不同窗口里的推进收回来。原来今天真的做了不少。

<p align="center">
  <img src="assets/today.png" width="48%" alt="done灯 今天页面">
  <img src="assets/report.png" width="39%" alt="done灯 完成日报页面">
</p>

<p align="center"><sub>今天做过的事，终于不用全靠脑子硬记。</sub></p>

## 记录多少，你说了算

| 模式 | 按下后会发生什么 | 画面去哪儿 | 适合这种时候 |
| --- | --- | --- | --- |
| 仅记录 | 只记下时间，内容之后自己补 | 不截图 | 今天不想折腾任何模型 |
| 本地模型 | 按下时截一次，交给本机 Ollama 猜你做完了什么 | 留在本机 | 想自动一点，也想尽量留在本机 |
| Codex Agent（在线） | 按下时截一次，交给 Codex Agent | 在线处理 | 已经在用 Codex，想少配点东西 |
| 模型 API | 按下时截一次，交给你配置的模型 | 你选择的模型服务 | 想自己决定用哪个模型 |

不想用 AI，直接选“仅记录”。以后想换，设置里随时换，不用第一次打开就把所有东西配置明白。

“屏幕录制权限”这个名字容易吓人。macOS 把截图也放在这个权限里。done灯 不会从早到晚盯着你，只在你按下的那一刻截一次。截图范围可以选“智能单窗”或“当前显示器”。

## 关于隐私，直说

一个会截图的 App，得先把这件事讲明白。

- 选“仅记录”，就不截图、不请求屏幕录制权限，也不调用模型。
- 只有你主动选择识别模式后，done灯 才会向 macOS 申请截图需要的权限。
- 截图留多久由你设置。想清空，点一下就能删除本机上的全部截图。
- 权限没开、模型挂了、识别失败，都不会把这次完成一起弄丢。时间先记下来，内容之后还能补。
- 来 GitHub 反馈问题时，别上传私人截图、窗口标题、完整日志或 API Key。真的，先保护好自己。

## 先装上，别给自己再加一个待办

1. 下载并双击 [`done-lamp-0.3.4.dmg`](https://github.com/LearnPrompt/done-lamp-releases/releases/download/v0.3.4/done-lamp-0.3.4.dmg)。
2. 在弹出的窗口里，把 `done灯.app` 拖到“应用程序”。
3. 从“应用程序”打开 done灯。只想先试试感觉，就选“仅记录”；模型以后再配也完全来得及。

## 你现在下载到的是什么

| 项目 | 信息 |
| --- | --- |
| 版本 | `0.3.4 (8)` · 初代公测版 |
| 能装在哪 | macOS 14.0 或更高版本 |
| 支持的 Mac | Apple Silicon 与 Intel，一个安装包都能用 |
| 签名与公证 | Developer ID 签名，已通过 Apple 公证并装订凭据 |
| 下载文件 | `done-lamp-0.3.4.dmg` · 约 42.7 MB |
| SHA-256 | `8066c77b74f9709432e01423ed0000be3efb51bfde6c17cb45b72010e208413b` |

这版具体改了什么，可以看 [0.3.4 Release Notes](https://github.com/LearnPrompt/done-lamp-releases/releases/tag/v0.3.4) 和 [CHANGELOG](CHANGELOG.md)。

## 你可能会问

### 非得用 AI 吗？

完全不用。选“仅记录”，done灯 就只保存完成时间和你自己填写的内容。先把“按一下”的感觉用起来，比先研究半天模型重要。

### 屏幕录制权限，是不是代表它会一直录？

不会一直录。这个名字是 macOS 起的，截图也归它管。done灯 只在你主动按下时截一次。

### 它会替我管理待办吗？

done灯 只管“已经做完”。“接下来要做什么”留给你决定，它不会再拿一张列表来催你。

### 用坏了怎么办？

先看看 [有没有人遇到同一个问题](https://github.com/LearnPrompt/done-lamp-releases/issues)。没有的话，直接告诉我。

- [它哪里坏了](https://github.com/LearnPrompt/done-lamp-releases/issues/new?template=bug_report.yml)
- [你希望它以后变成什么样](https://github.com/LearnPrompt/done-lamp-releases/issues/new?template=feature_request.yml)

## 最后，这个仓库是干什么的

先把边界讲清楚。done灯 的应用源码没有放在这里。

这个仓库放经过签名和 Apple 公证的安装包，也记着每一版改了什么。你遇到问题，可以直接在这里告诉我。想下载新版，也可以随时回来看看。
