# 0.1.0-preview.3

[下载与安装](DOWNLOAD_PREVIEW.md) · [GitHub Release](https://github.com/Lechoung-J/Pebbleglade/releases/tag/v0.1.0-preview.3)

这是首个公开的 macOS Apple Silicon 预览版。

## 当前功能

- 在同一画布放置图片、视频、GIF 和 3D 参考。
- 按项目保存画布，整理分组并写下参考判断。
- 连接 Agent 后，通过 MCP 读取和编辑画布。
- 图片和分组备注常驻画布，可原地修改与调整尺寸。
- 空白处右键可添加独立文本框，并关联为单图或整组备注。
- 新画布使用 `.pebb`，兼容读取旧 `.kanvaz`。
- 原生应用名、菜单、图标和安装窗口使用 Pebbleglade 品牌。

## 本版验证

安装包已完成隔离启动、画布写入、MCP 连接及包完整性检查。
DMG 与 ZIP 中的应用文件一致。

## 已知范围

当前仅发布 Apple Silicon macOS 版本。
采用 ad-hoc 本地签名，尚未完成 Developer ID 签名和 Apple 公证。
建议手动下载更新，正式签名版本之间的自动替换仍待验收。

公开展示图使用合成示例素材。
本仓库用于介绍和分发，专有源码在私有仓库管理。

## 第三方

画布基于 Kanvaz（MIT，P4inz Interactive Labs）派生。
第三方许可保留于 [许可说明](../THIRD_PARTY_NOTICES.md)及安装包。
