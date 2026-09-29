# Hero Video

The profile hero video is here:

```text
assets/profile/hero.webm
```

The profile README already links the banner preview to this path.

Recommended export:

- Format: WebM
- Codec: VP8 / VP9
- Resolution: 1920 x 1080
- Duration: 12-15 seconds
- Audio: none
- File size target: under 10 MB if possible

If you later prefer MP4, export a replacement named:

```text
assets/profile/hero.mp4
```

If you export from a GIF with FFmpeg:

```bash
ffmpeg -i assets/profile/hero-animatic-preview.gif -movflags faststart -pix_fmt yuv420p assets/profile/hero.mp4
```
