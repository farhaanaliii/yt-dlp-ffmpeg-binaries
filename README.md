# yt-dlp-ffmpeg-binaries

This repo hosts **precompiled Windows builds of `ffmpeg.exe`** for use with [yt-dlp](https://github.com/yt-dlp/yt-dlp).

✅ Currently included:

* Windows 64-bit static build (GPL)
* Downloaded from the official [yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds/releases/tag/latest) repository.

---

## 📥 Download

Head to the [Releases page](https://github.com/farhaanaliii/yt-dlp-ffmpeg-binaries/releases/latest) and grab the latest `ffmpeg.exe`.

---

## 🚀 Usage with yt-dlp

1. Download `ffmpeg.exe` from this repo’s releases.
2. Place it:

   * In the same folder as `yt-dlp.exe`, **or**
   * Somewhere in your system `PATH`.

Example command:

```bash
yt-dlp -f best https://youtube.com/watch?v=...
```

yt-dlp will automatically detect `ffmpeg.exe` and use it for merging and post-processing.

---

## ⚖️ License

FFmpeg is licensed under the GNU General Public License v3.
See [LICENSE](./LICENSE) for full terms.

Source code and other builds are available at the official repo:
➡️ [yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds)
