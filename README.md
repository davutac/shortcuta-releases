# ShortCuta

Turn Twitch VODs into YouTube Shorts. Let AI pick the best moments. ShortCuta captions and frames each one, then schedules them for you.

This repository hosts ShortCuta's release builds. The source code isn't public. More at [shortcuta.com](https://shortcuta.com).

## Download

| Platform | Download |
| --- | --- |
| macOS (Apple silicon) | [ShortCuta.dmg](https://github.com/davutac/shortcuta-releases/releases/latest/download/ShortCuta.dmg) |
| Windows | [ShortCuta-Setup.exe](https://github.com/davutac/shortcuta-releases/releases/latest/download/ShortCuta-Setup.exe) |

These links always point to the latest version. Older versions are on the [Releases](https://github.com/davutac/shortcuta-releases/releases) page.

## Install

### macOS

The app isn't notarized yet, so macOS says it's damaged after downloading it.

1. Open `ShortCuta.dmg` and drag ShortCuta into Applications.
2. Run this once in Terminal:

   ```sh
   xattr -cr /Applications/ShortCuta.app
   ```

### Windows

The installer isn't signed yet. When SmartScreen stops it, choose **More info → Run anyway**.

## Requirements

- **macOS:** a Mac with Apple silicon (M1 or newer).
- **Windows:** an NVIDIA GPU from the RTX 20 or GTX 16 series or newer, with a driver for CUDA 13 (580 or newer), transcribes on the GPU. Without one, ShortCuta runs on the processor, which is much slower.
- **ffmpeg, yt-dlp and uv.** On first start, ShortCuta checks for them and shows the command to install each one that's missing (Homebrew on a Mac, winget on Windows).

ShortCuta needs a license key, which you enter on first start.

## Support

Email [hi@shortcuta.com](mailto:hi@shortcuta.com).
