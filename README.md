# Loka Clip Desktop

Aplikasi desktop untuk membuat short-form video viral dari video YouTube panjang.

## Download

Download installer terbaru dari [Releases](https://github.com/Rafi718/Loka-Clip-Desktop/releases).

## Fitur

- **Auto-Update**: Aplikasi otomatis mengecek dan menginstall update terbaru
- **AI Highlight Detection**: Deteksi momen viral menggunakan AI
- **Reframe Otomatis**: Konversi video horizontal ke vertikal (9:16)
- **Caption TikTok Style**: Subtitle dengan style viral TikTok
- **Hardware Acceleration**: Support GPU NVIDIA, Intel, AMD
- **Multi-Clip Rendering**: Render beberapa klip sekaligus

## Sistem Operasi

- Windows 10/11 (64-bit)

## Teknologi

- **Framework**: Tauri v2 + React + Rust
- **Video Processing**: FFmpeg + yt-dlp
- **AI Services**: Cloud LLM untuk highlight detection
- **Auto-Update**: Tauri Updater Plugin dengan signing verification

## Development

```bash
# Install dependencies
pnpm install

# Run development
pnpm tauri dev

# Build production
pnpm tauri build
```

## License

Proprietary. All rights reserved.
