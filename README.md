# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.3

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.3/GPT-Photoshop-Assistant-0.8.3-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.3) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.3/GPT-Photoshop-Assistant-0.8.3-Setup-SHA256.txt)

0.8.3 汇总三版修补：能力导航默认收起，API 页签名称更清楚，操作记录单独查看；Photoshop 人物抠图采用主体定位结合通道柔边；AI 蒙版轻微偏色和小幅比例误差可在本地生成待确认预览，不自动追加图片请求。本版修正稀疏偏色蒙版被单点色差门槛拒绝的问题，仍需检查人物位置和发丝边缘后采用。

1177 项自动测试、30 项安装器检查和窄面板浏览器检查通过，70 个插件文件与 24 个引擎文件核验一致。真实 Photoshop 文档与模型视觉质量仍须验收；统计校验不能证明人物识别准确。Photoshop 主体定位遵循其设备/云端设置，不是纯通道算法，也不保证最佳抠图效果。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需要自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在“设置 → 插件更新”检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
