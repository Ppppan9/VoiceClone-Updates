# v1.0.3 更新说明

本次更新把分发方式升级成了 Windows 一键安装包。用户只需要安装一次，之后直接打开 After Effects，就可以自动加载面板并启动本地服务。

## 本次改动
- 新增 Windows 安装包 `ElevenLabs-Voice-Panel-Setup-v1.0.3.exe`
- 安装包会自动把运行文件部署到 CEP 目录下，并自动执行面板安装
- 发布包内置托管默认配置 `.env.defaults`，当前版本已锁定内置 ElevenLabs API Key
- 后续如果内置 API 或发布配置变更，会跟随新版本包一起更新
- 面板启动时会自动检测并拉起本地服务，使用时不再要求手动运行 `start-panel.cmd`

## 首次使用
- 下载并运行安装包
- 安装完成后重启 After Effects
- 之后直接打开 AE 即可使用面板

## 发布文件
- ElevenLabs-Voice-Panel-v1.0.3-win-x64.zip
- ElevenLabs-Voice-Panel-Setup-v1.0.3.exe

## Runtime ZIP SHA256
- 1fff73ebeaf203b47ff70f146e81e66f8aa8adda0abe323761a6792accd80728

## Installer SHA256
- 41c26f053c91ea3a6f4ba6db3a0cf002ff9359eeed01dc70a3ff03ed0cc54e51

## 下载地址
- https://github.com/Ppppan9/VoiceClone-Updates/releases/download/v1.0.3/ElevenLabs-Voice-Panel-v1.0.3-win-x64.zip
- https://github.com/Ppppan9/VoiceClone-Updates/releases/download/v1.0.3/ElevenLabs-Voice-Panel-Setup-v1.0.3.exe
