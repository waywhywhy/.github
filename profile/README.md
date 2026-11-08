<p align="center">
  <img src="https://raw.githubusercontent.com/waywhywhy/waydlp-desktop-rust/main/assets/icons/waydlp-512.png" width="96" alt="waydlp logo">
</p>

<h1 align="center">waydlp</h1>

<p align="center"><b>Your media, your format, your way.</b><br>
A free, open-source media downloader for Windows, Linux and Android, powered by
<a href="https://github.com/yt-dlp/yt-dlp">yt-dlp</a> and <a href="https://ffmpeg.org">FFmpeg</a>.</p>

---

Paste a link, see the real title, thumbnail and qualities, pick a format and download. It works with every website yt-dlp supports, which is thousands of them.

* 🎬 **Video:** MP4, MKV, WebM, MOV or the original file, from 144p up to 4K and 8K when available.
* 🎧 **Audio:** MP3, M4A, Opus, FLAC, WAV, OGG or the original stream, with optional loudness normalisation.
* 📃 **Playlists and batches:** preview, pick items and queue many links at once.
* ⏯ **Download manager:** real progress, pause/resume, retries and searchable history.
* 🔒 **Privacy:** no accounts, no ads, no telemetry. Everything runs on your device.
* 🖤 One AMOLED-black and purple design across desktop, Android and the website.

## Repositories

| Repository | What | Stack |
|---|---|---|
| [waydlp-desktop-rust](https://github.com/waywhywhy/waydlp-desktop-rust) | Windows & Linux app, CLI, graphical and CLI installers, packages (setup.exe, MSI, portable, AppImage, deb, rpm, Flatpak, Arch) | Rust, egui |
| [waydlp-mobile-dart](https://github.com/waywhywhy/waydlp-mobile-dart) | Android app with on-device yt-dlp/FFmpeg | Dart, Flutter, Kotlin |
| [waywhy-website](https://github.com/waywhywhy/waywhy-website) | Website, downloads and documentation | Next.js, TypeScript |
| [.github](https://github.com/waywhywhy/.github) | This profile and shared community files | — |

## Install

waydlp is in early development. [Desktop 0.1.0 builds](https://github.com/waywhywhy/waydlp-desktop-rust/releases/tag/v0.1.0) and signed [Android 0.1.0 APKs](https://github.com/waywhywhy/waydlp-mobile-dart/releases/tag/v0.1.0) are available with SHA-256 checksums. For source builds, follow the "Building from source" sections in the repository READMEs.

Install the latest stable desktop app and CLI from your terminal. Both installers detect x64/ARM64, verify SHA-256 checksums and install for your user without administrator access.

**Windows (PowerShell):**

```powershell
& ([scriptblock]::Create((irm 'https://github.com/waywhywhy/waydlp-desktop-rust/releases/latest/download/install.ps1')))
```

**Linux (requires curl and sha256sum):**

```sh
curl -fsSL https://github.com/waywhywhy/waydlp-desktop-rust/releases/latest/download/install.sh -o install-waydlp.sh && sh install-waydlp.sh
```

The scripts print launch, CLI, verification and uninstall commands. Run the same command again to upgrade. See the [installation guide](https://github.com/waywhywhy/waydlp-desktop-rust#command-line-installer) for custom folders and pinned versions.

## Contributing

Contributions are welcome: bug reports, documentation, testing on your distribution or device, and code. Start with the [contributing guide](https://github.com/waywhywhy/.github/blob/main/CONTRIBUTING.md) and the [code of conduct](https://github.com/waywhywhy/.github/blob/main/CODE_OF_CONDUCT.md). Report security issues privately; see the [security policy](https://github.com/waywhywhy/.github/blob/main/SECURITY.md).

## License

The apps are licensed under GPL-3.0-or-later. The website and these community files are MIT.

<sub>Only download media you have the right to access. waydlp does not circumvent DRM.</sub>
