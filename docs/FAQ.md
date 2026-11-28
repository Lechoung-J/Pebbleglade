# 常见问题

## Pebbleglade 是什么？

一块给设计师和 Agent 共用的情绪板。
你可以在同一张画布上收集参考、按项目整理，并留下自己的风格判断。
Agent 通过一份读得懂的摘要，看到你的选择。

## Agent 怎么读到我的情绪板？

产品会把参考、组名和你的判断，整理成一份 Agent 可读的风格摘要。
摘要包含关键词、色彩、构图、质感等方向。
它让 Agent 从你的参考开始工作，而不是从一句空泛的 prompt 开始。

## 我需要先接哪个 Agent？

支持本地 stdio MCP 的 Harness 可以连接。
引导页提供 DeepSeek Harness、Claude Code、Codex 和其他客户端入口。
复制连接指令到所选 Harness 的聊天窗口，再按 Agent 的提示完成配置。
应用显示打勾后，就可以让 Agent 读取画布。

## 我的参考会被上传吗？

情绪板和参考默认保存在本机。
只有你主动把摘要交给 Agent 时，内容才会离开你的设备。
如果使用外部 AI 服务，传输范围取决于该服务的设置。

## 它和普通素材库有什么不同？

素材库帮你保存文件。
Pebbleglade 还保存你的取舍：为什么留这张、这组参考叫什么、整体要往哪个方向走。
这些判断会进入 Agent 读到的摘要。

## 适合哪些人？

UI、交互和图形界面设计师，可以用它整理界面风格和状态参考。
AIGC 和视觉创作者，可以用它整理氛围、光线、材质和构图。
不接 Agent 时，它也可以作为一块普通的情绪板使用。

## 现在可以下载吗？

Preview 7 面向 Apple Silicon Mac（M 系列），需要 macOS 12 或更新版本。
下载入口见 [macOS 预览版 Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.7)。
本版转用 Developer ID 签名。
应用与 DMG 均已通过 Apple 公证并附加票据。
Apple 公证不等同于 App Store 审核。
安装方式和已知范围见 [下载说明](DOWNLOAD_PREVIEW.md)。

## 如何更新？

Preview 3–6 用户都需手动覆盖安装 Preview 7 一次。
Preview 7 更换了签名证书，旧版内置更新器会拒绝跨证书更新。
保存并退出旧版，把新应用拖入 Applications，选择替换即可。
不用卸载，也不用删除画布、设置或本地数据。

## 新 Mac 首次安装要做什么？

下载并打开 DMG，把 Pebbleglade 拖入 Applications，再从那里启动。
无需安装证书或关闭 Gatekeeper。
macOS 可能询问是否打开从互联网下载的应用。
确认应用名称和来源后，按系统提示打开即可。
跨机首次安装体验仍待新 Mac 实测。
