# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.20

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.20/GPT-Photoshop-Assistant-0.8.20-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.20) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.20/GPT-Photoshop-Assistant-0.8.20-Setup-SHA256.txt)

0.8.20 修复 AI 抠图已经生成并通过自动效果检查，却在写入 Photoshop 的最终校验阶段报 `Unsupported layer type（错误码 1）` 的问题。插件现在会隔离新建的结果组并读取文档合成画面完成校验，不再直接读取 Photoshop 组图层；校验结束后恢复原有图层可见性，任何步骤失败仍会回滚，不留下半成品。

1,721 项自动测试、21 组浏览器回归及 39 项安装器自检全部通过。本机已安装 0.8.20；88 个插件文件与 CCX、24 个引擎文件与引擎包逐项一致，升级前后 12 个配置及安全存储文件未变。

本轮构建、测试和安装没有调用用户 Key 或付费图片接口。回归测试覆盖截图中的 `Unsupported layer type` 分支；真实远程蒙版质量与 Photoshop 原生画布结果仍需在实际素材上复测。

完整安装器大小为 68,306,944 字节，SHA-256 为 `9BE5C5DE492FA67A235671961662400083FB0AACA6515B2C342A198D98F161BB`。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需要自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在「设置 → 插件更新」检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
