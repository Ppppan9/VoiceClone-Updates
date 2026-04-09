# v1.0.2 更新说明

本次更新重点优化了启动体验。安装完成后，不再需要每次手动运行本地服务，正常打开 After Effects 即可自动加载面板并拉起本地运行环境。

## 本次改动
- 新增一键安装入口 `install-panel.cmd`，用于首次安装面板
- 面板支持在启动时自动检测并拉起本地服务，不再要求每次手动运行 `start-panel.cmd`
- 安装脚本会自动写入运行目录配置，并同步扩展版本号
- 更新发布包说明，用户安装流程更精简

## 新的使用方式
- 首次使用：解压后配置 `.env`，运行一次 `install-panel.cmd`
- 后续使用：直接打开 After Effects，面板会自动加载并启动服务

## 发布文件
- ElevenLabs-Voice-Panel-v1.0.2-win-x64.zip

## SHA256
- f1e210c621f2a326d6ebf8f1846018f9d638fe7ca2289951346976fc0cece5bd

## 下载地址
- https://github.com/Ppppan9/VoiceClone-Updates/releases/download/v1.0.2/ElevenLabs-Voice-Panel-v1.0.2-win-x64.zip
