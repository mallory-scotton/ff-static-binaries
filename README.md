# 🎬 FFmpeg & FFprobe Static Binaries

Precompiled **static binaries** of [FFmpeg](https://ffmpeg.org) and [FFprobe](https://ffmpeg.org/ffprobe.html), built for multiple platforms and architectures.
These releases aim to provide developers, video editors, and enthusiasts with **ready-to-use binaries** without the need to build from source.

---

## 🚀 Latest Release

**Version:** `v7.0.2`
📅 Released by [@mallory-scotton](https://github.com/mallory-scotton)

### 🔹 Available Assets

* **macOS**

  * `ffmpeg-darwin-arm64` (47.1 MB)
  * `ffmpeg-darwin-x64` (76.3 MB)
  * `ffprobe-darwin-arm64` (47.9 MB)
  * `ffprobe-darwin-x64` (76.2 MB)

* **Linux**

  * `ffmpeg-linux-amd64` (76.1 MB)
  * `ffmpeg-linux-arm64` (48.8 MB)
  * `ffmpeg-linux-armel` (36.4 MB)
  * `ffmpeg-linux-armhf` (30.3 MB)
  * `ffmpeg-linux-i686` (49.7 MB)
  * `ffprobe-linux-amd64` (76 MB)
  * `ffprobe-linux-arm64` (48.6 MB)
  * `ffprobe-linux-armel` (36.3 MB)
  * `ffprobe-linux-armhf` (30.2 MB)
  * `ffprobe-linux-i686` (49.5 MB)

* **Windows**

  * `ffmpeg-win32-x64.exe` (82.5 MB)
  * `ffprobe-win32-x64.exe` (82.4 MB)

---

## 🛠️ Usage

1. **Download the binary** for your platform from the [Releases](../../releases) page.
2. Place it in a directory included in your system `PATH`.
3. Run from your terminal:

```bash
# Check FFmpeg version
ffmpeg -version

# Convert a video file to MP4
ffmpeg -i input.mkv output.mp4

# Extract audio from video
ffmpeg -i input.mp4 -vn -acodec copy output.aac

# Inspect media metadata
ffprobe input.mp4
```

---

## 🌍 Supported Platforms

| Platform    | Architectures                    | Notes                                       |
| ----------- | -------------------------------- | ------------------------------------------- |
| **macOS**   | arm64, x64                       | Universal support for Apple Silicon & Intel |
| **Linux**   | amd64, arm64, armel, armhf, i686 | Works on most modern distributions          |
| **Windows** | x64                              | Portable `.exe` binaries                    |

---

## 🤝 Contributing

Contributions are welcome!

* Report issues or request new builds via [GitHub Issues](https://github.com/mallory-scotton/ff-static-binaries/issues).
* Submit pull requests to improve documentation, CI/CD, or add support for new targets.

---

## 📝 License

This project provides **prebuilt binaries of FFmpeg/FFprobe**.

* FFmpeg is licensed under the **LGPL/GPL** depending on the enabled features.
* Please refer to the official [FFmpeg License](https://ffmpeg.org/legal.html) for details.

---

## 🙏 Credits

* 🎥 **[FFmpeg Project](https://ffmpeg.org/)** – for creating the world’s most versatile multimedia framework.
* 🛠️ **Static build automation & packaging** – by [Mallory Scotton](https://github.com/mallory-scotton).

---

## 📫 Contact

For questions, feedback, or suggestions:

* ✉️ Email: **[mallory.scotton@epitech.eu](mailto:mscotton.pro@gmail.com)**
* 🐙 GitHub: [@mallory-scotton](https://github.com/mallory-scotton)

---

✨ Enjoy fast, reliable, and portable **FFmpeg builds** on every platform!
