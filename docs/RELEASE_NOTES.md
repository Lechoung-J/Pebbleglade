# 0.1.0-preview.7

[下载与安装](DOWNLOAD_PREVIEW.md) · [GitHub Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.7)

本版将 macOS 分发签名切换为 Developer ID。

## 本版调整

- 转用 Developer ID 签名。
- 应用与 DMG 均已通过 Apple 公证并附加票据。
- Preview 3–6 用户需手动覆盖安装一次，完成签名证书迁移。
- 新 Mac 可直接下载安装，无需安装证书或关闭 Gatekeeper。

## 验证状态

应用与 DMG 的签名、公证票据及本机系统评估均已通过。
最终 ZIP 已完成隔离启动、画布保存和 51 个 MCP 工具检查。
跨机首次下载和安装体验仍待新 Mac 实测。
Apple 公证不等同于 App Store 审核。

## 当前范围

适用于 Apple Silicon Mac（M 系列），macOS 12 或更新版本。
Intel Mac、Windows 与 Linux 版本暂未发布。
旧版内置更新器会拒绝跨证书更新，Preview 6 也需手动安装。
保存并退出旧版，将新应用拖入 Applications 并选择替换。
画布、设置和本地数据无需删除，重要画布请先备份。

---

## 0.1.0-preview.6（历史版本）

[下载与安装](DOWNLOAD_PREVIEW.md) · [GitHub Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.6)

本版将画布滚轮操作统一为缩放。

## 本版调整

- 在画布内直接滚动滚轮即可围绕指针缩放，不再上下平移。
- 按住鼠标中键拖动，继续用于平移画布。
- 保留空格或 Alt 加拖动、触控板捏合和输入框原生滚动。
- 旧的滚动平移选项已移除，升级后直接采用新行为。
- 沿用 Preview 5 的固定签名身份，可从应用内检查更新。

## 当前功能

- 在同一画布放置图片、视频、GIF 和 3D 参考。
- 按项目保存画布，整理分组并写下参考判断。
- 连接 Agent 后，通过 MCP 读取和编辑画布。
- 图片和分组备注常驻画布，可原地修改与调整尺寸。
- 空白处右键可添加独立文本框，并关联为单图或整组备注。
- 新画布使用 `.pebb`，兼容读取旧 `.kanvaz`。
- 原生应用名、菜单、图标和安装窗口使用 Pebbleglade 品牌。

## 本版验证

安装包已完成滚轮方向、指针锚点、文字区域、中键拖动及 MCP 检查。
Preview 5 到 Preview 6 的同证书测试版本完成了原生替换和重启。
安装前未保存文字与设置均保留。
DMG 与 ZIP 中的应用文件一致。

## 已知范围

当前仅发布 Apple Silicon macOS 版本。
采用固定自签名，尚未完成 Developer ID 签名和 Apple 公证。
Preview 5 可从应用内更新；旧临时签名 Preview 3 / 4 仍需手动安装一次。
本机验证不等于所有系统和跨机安装已验收。

公开展示图使用合成示例素材。
本仓库用于介绍和分发，专有源码在私有仓库管理。

## 第三方

画布基于 Kanvaz（MIT，P4inz Interactive Labs）派生。
第三方许可保留于 [许可说明](../THIRD_PARTY_NOTICES.md)及安装包。
