# yt-dlp-ffmpeg-binaries
This repo hosts precompiled builds of ffmpeg for use with yt-dlp.

This repository provides **precompiled builds of `ffmpeg.exe`** for easy use with [yt-dlp](https://github.com/yt-dlp/yt-dlp).

✅ Currently included:

* Windows 64-bit static build (GPL)
* Downloaded from the official [yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds/releases/tag/latest) repository.

---

## Usage with yt-dlp

Download `ffmpeg.exe` and place it:

* In the same folder as `yt-dlp.exe`, or
* Somewhere in your system `PATH`.

Example:

```bash
yt-dlp -f best https://youtube.com/watch?v=...
```

yt-dlp will automatically detect `ffmpeg.exe` and use it for format merging and post-processing.

---

## License

FFmpeg is licensed under the GNU General Public License v3.
See [LICENSE](./LICENSE) for full terms.

Source code and other builds are available at the official repo:
➡️ [https://github.com/yt-dlp/FFmpeg-Builds](https://github.com/yt-dlp/FFmpeg-Builds)
