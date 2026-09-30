# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.5

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.5/GPT-Photoshop-Assistant-0.8.5-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.5) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.5/GPT-Photoshop-Assistant-0.8.5-Setup-SHA256.txt)

0.8.5 修正 Apple 风格界面在 Photoshop 原生控件中的显示差异：折叠标题与展开按钮分开，导航更紧凑，输入框限制在面板宽度内并去除多余外框。能力定位、已保存配置及未保存草稿保留。

1195 项自动测试、30 项安装器检查和窄面板浏览器检查通过，72 个插件文件与 24 个引擎文件核验一致。真实 Photoshop 原生显示仍须复核；本次界面修正不代表模型或抠图效果提高。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需要自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在「设置 → 插件更新」检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
