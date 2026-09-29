# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里仅发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.7.7

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.7.7/GPT-Photoshop-Assistant-0.7.7-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.7.7) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.7.7/GPT-Photoshop-Assistant-0.7.7-Setup-SHA256.txt)

0.7.7 修复蒙版诊断跨 Photoshop 异常边界丢失，恢复返回图预览；对于符合严格条件的近灰度蒙版，提供本地去偏色与对齐候选。候选需查看并确认边缘，原图像素保持不变，不会自动发起新的 AI 请求。明显彩色、透明彩照及缺少有效黑白区域的结果仍不能走这条恢复路径。

1058 项自动测试、260/320 px 卡片浏览器检查和 30 项安装器核心检查通过。本机安装文件及配置保留已核验；真实 Photoshop 交互和 AI 蒙版效果仍需复测。统计条件不能保证主体识别正确。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限。先保存文档并退出 Photoshop，再运行完整安装器。更新不会清空已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在“设置 → 插件更新”检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
