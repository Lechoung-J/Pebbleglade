# macOS 预览版 · 0.1.0-preview.5

[下载 Apple Silicon DMG](https://github.com/Lechoung-J/Pebbleglade/releases/download/v0.1.0-preview.5/Pebbleglade-0.1.0-preview.5-arm64.dmg) · [查看 Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.5)

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

本预览采用固定自签名证书，尚无 Developer ID 签名和 Apple 公证。
从网络下载后，macOS 可能显示验证提示。
可按系统提供的打开选项操作；系统放行体验仍需跨机验证。

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

Preview 3 / 4 用户需要先手动覆盖安装本版一次。
保存并退出旧应用，把本版拖入 Applications 并选择替换即可。
不用卸载，也不用删除画布、设置或本地数据。

本版建立固定证书基线，后续同证书版本可使用应用内更新。
本机已实测检查、下载、原生校验、保存后替换和重启。
测试使用同一签名身份与独立测试标识，不影响当前安装版。
跨机和后续公开版本的升级体验仍需继续验证。

Release 同时附带更新 ZIP、blockmap、通道清单和 SHA-256 校验和。
这些是下载和更新所需资料，日常安装只需 DMG 或 ZIP。
