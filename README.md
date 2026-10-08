# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.6

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.6/GPT-Photoshop-Assistant-0.8.6-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.6) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.6/GPT-Photoshop-Assistant-0.8.6-Setup-SHA256.txt)

0.8.6 在「设置 → 用户反馈」增加图片附件。可以主动添加 PNG、JPG 或 JPEG 截图，检查缩略图并逐张移除，再与反馈文字一起提交。最多 3 张，单张 5 MiB、合计 10 MiB；界面以 MB 显示。取消或提交失败保留草稿，复制反馈只复制文字，重试保持原请求编号。

图片保留原始字节，不自动遮挡敏感信息或移除内部元数据；请先处理截图中的 Key、账号等信息。上传使用通用文件名，不发送原文件名和本地路径。添加图片不会读取 Photoshop 画布或聊天附件，也不会调用 AI 或自动发送。

1232 项自动测试、语法和 manifest 检查、3 组浏览器回归及 30 项安装器自检通过。2026-10-08 本机已安装 0.8.6；74 个插件文件与 24 个引擎文件和安装包核验一致，升级前后 8 个配置及安全存储文件未变。

线上服务已部署 Apps Script 代码版本 3，并通过不发信的匿名附件能力检查。本轮未进行真实 POST、未发送测试邮件、未核对收件箱，Photoshop 原生选图与显示仍待验收。成功发信回执也不代表邮件已进入收件箱或作者已阅读。

完整安装器大小为 68206592 字节，SHA-256 为 `F34607047D87700CA95299EA2E2017EB80221F2AC310C093098FE9FF7ED87E63`。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需要自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在「设置 → 插件更新」检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
