# GPT 图像助手 · 安装包与更新

本仓库用于公开分发 GPT 图像助手的 Windows 安装包与更新说明。开发源码保存在独立私密仓库，本仓库不包含开发历史。安装包包含插件运行所需的客户端代码。

[下载最新安装包](https://github.com/Zeevway/photoshop-gpt-assistant-releases/releases/latest)

安装条件：Windows、Photoshop 2026 / 27.0 或以上，以及 Creative Cloud Desktop 提供的 Adobe UPIA 安装组件。PS 2018 不兼容。先保存文档并退出 Photoshop，再运行 Setup.exe；系统管理员权限提示需要确认。安装器目前未签署商业代码签名证书。

0.5.0 起可在插件 **key → 插件更新** 中检查后续正式版本，下载进度以百分比显示；安装包通过大小与 SHA-256 校验后才启动安装器。打开安装器后仍须退出 PS；如提示正在运行，退出后点击“重试”。不会强制关闭 PS。旧版首次升级到 0.5.0 需要手动安装一次。

完整安装器已包括插件及基础本机图片引擎，无需单独安装 Node.js 或 UXP 开发工具；不包含 Photoshop、Creative Cloud 或可选大型模型。AI API Key 需在每台电脑自行配置。更新不需要 GitHub 登录，不使用 AI Key，也不要求本机图片引擎在线。

安装包中的第三方组件许可证随包附带。用户 Key、聊天记录、本机模型配置及用户图片不会作为发布内容上传。GitHub 自动提供的 Source code 压缩包仅含本仓库的说明文件，请下载以 `-Setup.exe` 结尾的安装器。
