# GPT 图像助手 · 安装包与更新

Photoshop 插件的公开下载与更新源。源码仓库保持私密；这里只发布安装器及校验文本。安装包包含可提取的客户端代码，不是源码保密措施。

## 最新版本：0.8.28

[下载 Windows 完整安装器](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.28/GPT-Photoshop-Assistant-0.8.28-Setup.exe) · [查看更新说明](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/tag/v0.8.28) · [SHA-256](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/download/v0.8.28/GPT-Photoshop-Assistant-0.8.28-Setup-SHA256.txt)

0.8.28 交付三项交互可靠性修复：审核允许的最终生成结果可从结果卡手动置入，不同字节的对比原图在存储边界保持阻断、不能借用最终结果的审核；输入框随内容和面板尺寸同步高度，返回运行页时重新测量；标注画布支持以指针为中心的 25%–800% 滚轮缩放及中键临时平移，缩放平移后可继续绘制、保存与重新打开。置入按钮与提示明确绑定"审核后结果"，即使正在查看原图也不会误置入。

1,941 项自动测试、4 个浏览器回归套件及 39 项安装器自检全部通过。本机已安装 0.8.28；91 个插件文件与 CCX、24 个引擎文件与引擎包逐项一致，升级前后 12 个配置及安全存储文件未变。

本轮构建、测试和安装没有调用用户 Key 或付费图片接口。Photoshop 原生实机交互验收因 Photoshop 2026 丢弃自动化合成键盘输入而以自动化证据替代；真实模型输出与原生交互仍建议在实际素材上确认。

完整安装器大小为 68,326,400 字节，SHA-256 为 `02D39FA786F8359D736E149CB53ECD2ECC31E58740FE4415E689CD448C0C20A0`。

## 安装与更新

需要 Windows x64、Photoshop 2026（27.0）或更新版本，以及管理员安装权限和 Adobe Creative Cloud 提供的安装组件。先保存文档并退出 Photoshop，再运行完整安装器。更新保留已保存的 API 配置，但会释放当前会话素材。

安装包内含本机高清引擎和 Real-ESRGAN 基础模型。API 功能需要自行配置服务商 Key 和可用接口；可选模型需要另外安装，硬件要求随模型而异。包内不包含作者的 Key、配置、聊天或图片。

已支持更新的插件可在「设置 → 插件更新」检查并下载安装；下载更新无需访问私密源码仓库或提供 GitHub Token。
