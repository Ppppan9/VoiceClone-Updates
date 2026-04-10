# v1.0.4 更新说明

本次更新修复了安装包版本中“面板一直停在 Checking local service...”的问题。现在安装完成后，打开 After Effects 即可稳定自动加载面板并启动本地服务。

## 本次修复
- 修复运行包服务端构建方式，避免自动启动时因缺少依赖或模块格式不兼容而启动失败
- 服务端运行入口改为稳定的 `server.cjs`
- 保持 Windows 一键安装包分发方式不变，首次安装后仍然只需要直接打开 AE

## 首次使用
- 下载并运行安装包
- 安装完成后重启 After Effects
- 之后直接打开 AE 即可使用面板

## 发布文件
- ElevenLabs-Voice-Panel-v1.0.4-win-x64.zip
- ElevenLabs-Voice-Panel-Setup-v1.0.4.exe

## Runtime ZIP SHA256
- 3a0605825d81e5fe3d990c15885368551b3f5a5b4032d1ca2b7b9eed4d9a5cd1

## Installer SHA256
- 93330936f73d95eda629a8bd9d269b527c3b58cce54795b93c2cf0f93aaee024

## 下载地址
- https://github.com/Ppppan9/VoiceClone-Updates/releases/download/v1.0.4/ElevenLabs-Voice-Panel-v1.0.4-win-x64.zip
- https://github.com/Ppppan9/VoiceClone-Updates/releases/download/v1.0.4/ElevenLabs-Voice-Panel-Setup-v1.0.4.exe
