# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.0

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.0/GPT-Photoshop-Assistant-0.8.0-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.0) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.0/GPT-Photoshop-Assistant-0.8.0-Setup-SHA256.txt)

0.8.0 增加原生通道抠图、选区和蒙版工具及调整层。图片生成/编辑可关闭、按需调用或始终允许，网页搜索独立控制；关闭图片能力后仍可使用已接入的 PS 操作。抠图和精准修改任务卡新增效果检查，只评价结果，视觉检查由用户主动发起并使用对话 API。

1119 项自动测试、30 项安装器检查及浏览器布局检查通过，69 个插件文件和 24 个引擎文件与构建包一致。真实 Photoshop 文档操作和真实模型视觉质量尚需验收。原生通道自动选择依据明暗对比，复杂背景和发丝仍可能需要修整；当前限 RGB 8 位、1600 万像素以内。效果检查不会自动比较多个方案，也不保证最优结果。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在“设置 → 插件更新”检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
