# Release 1.0.8

## 🩹 热修复说明
- 🧰 修复面板内点击“更新脚本”后，`apply-update.ps1` 因参数块位置错误触发的 PowerShell 解析报错。
- 🔧 现在更新脚本会先正确解析 `PackageUrl`、`ExpectedSha256`、`InstallExtensionScript` 等参数，再执行下载和覆盖更新。
- 🚀 这版就是专门用于恢复在线更新链路，方便你直接在 AE 内继续测试自更新。

## 📦 发布内容
- `downloads/ElevenLabs-Voice-Panel-v1.0.8-win-x64.zip`
- `downloads/ElevenLabs-Voice-Panel-Setup-v1.0.8.exe`

## 🔐 SHA256
- ZIP: `3c431c271fe2a86140784eda06445754a2904cdcb3419f9aa83d26701852b549`
- EXE: `2b68ea3b3dae7240206d5f08cd3984f22c89e3dab3499ff3e92e5c86effe78f1`

## ⬇️ 下载地址
- https://raw.githubusercontent.com/Ppppan9/VoiceClone-Updates/main/downloads/ElevenLabs-Voice-Panel-v1.0.8-win-x64.zip
- https://raw.githubusercontent.com/Ppppan9/VoiceClone-Updates/main/downloads/ElevenLabs-Voice-Panel-Setup-v1.0.8.exe
