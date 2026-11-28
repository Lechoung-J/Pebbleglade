# macOS 预览版 · 0.1.0-preview.7

[下载 Apple Silicon DMG](https://github.com/Lechoung-J/Pebbleglade/releases/download/v0.1.0-preview.7/Pebbleglade-0.1.0-preview.7-arm64.dmg) · [查看 Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.7)

## 当前范围

- 适用机型：Apple Silicon Mac（M 系列），macOS 12 或更新版本。
- 产品定位：免费使用的闭源桌面预览。
- 新画布文件：`.pebb`。
- 旧文件：可打开 `.kanvaz` 并另存副本。
- 连接方式：应用内生成指令，交给本地 MCP Harness 配置。

Intel Mac、Windows 和 Linux 版本暂未发布。

## 安装

1. 保存并退出正在使用的旧版。
2. 下载并打开 DMG。
3. 将 Pebbleglade 拖到 Applications。
4. 从 Applications 启动。

也可解压 ZIP，将其中的应用放入 Applications。
DMG 与 ZIP 包含同一版本，通常选一种安装方式即可。

本版转用 Developer ID 签名。
应用与 DMG 均已通过 Apple 公证并附加票据。
Apple 公证不等同于 App Store 审核。

新 Mac 可直接下载安装，无需安装证书或关闭 Gatekeeper。
首次打开时，macOS 仍可能询问是否打开从互联网下载的应用。
确认应用名称和来源后，按系统提示打开即可。
跨机首次安装体验仍待新 Mac 实测。

## Agent 与备注

在「连接 Agent」中选择 Harness，复制指令到对应聊天窗口。
接入完成后，应用显示真实连接状态。
内置运行文件，不要求另装 Node。

图片和分组备注直接显示在画布上，可编辑、拖动和调整宽高。
空白处右键可添加独立文本框，再选择关联为图片或分组备注。
Agent 可通过 MCP 读写同一份备注。

## 文件与数据

旧 `.kanvaz` 首次保存时需另存为 `.pebb`。
重要画布请保留自己的备份。
应用数据和最近列表保存在本机，使用独立的 Pebbleglade 数据目录。

## 更新

Preview 3–6 用户都需手动覆盖安装 Preview 7 一次。
Preview 7 更换了签名证书。
旧版内置更新器会拒绝这次跨证书更新，Preview 6 也需手动安装。

保存并退出旧应用，把本版拖入 Applications 并选择替换即可。
不用卸载，也不用删除画布、设置或本地数据。
重要画布请先备份。
跨机和不同系统的升级体验仍待验证。

Release 同时附带更新 ZIP、blockmap、通道清单和 SHA-256 校验和。
这些是下载和更新所需资料，日常安装只需 DMG 或 ZIP。
