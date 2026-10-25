# WhisperPal

Local-first transcription, meeting notes and dictation for macOS.

[whisperpal.app](https://whisperpal.app) · [Releases](https://github.com/HanryYu/whisperpal-releases/releases)

## Download

| Platform | Download |
| --- | --- |
| macOS 12+, Apple silicon | [WhisperPal_macos_arm64.dmg](https://github.com/HanryYu/whisperpal-releases/releases/latest/download/WhisperPal_macos_arm64.dmg) |

Open the disk image and drag WhisperPal to Applications. Installed copies update themselves from **WhisperPal → Check for Updates…**.

Beta builds are published as pre-releases. To receive them in the app, choose **Settings → General → Update channel → Beta**.

## Verify a download

Each release includes `SHA256SUMS_macos_<arch>.txt`:

```bash
shasum -a 256 -c SHA256SUMS_macos_arm64.txt --ignore-missing
```

## 下载

从 [最新版本](https://github.com/HanryYu/whisperpal-releases/releases/latest) 下载 `WhisperPal_macos_arm64.dmg`，打开后将 WhisperPal 拖入“应用程序”。已安装的 WhisperPal 可通过“WhisperPal → 检查更新…”自动更新；在“设置 → 通用 → 更新渠道”中选择“测试版”即可接收预发布版本。

---

This repository hosts release binaries and update manifests only. `updates/<channel>.json` is read by the app; do not edit it by hand.
