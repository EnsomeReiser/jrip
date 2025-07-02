# Jrip

> **JRIP** is a minimal Rust desktop utility for ripping audio from `.mkv` files using `ffmpeg`, with a lightweight GUI built on [`iced`](https://github.com/iced-rs/iced).  
>  
> Designed for speed, clarity, and minimalism. Nothing more, nothing less.

---

## ⚙️ Features

- ✅ File explorer for local directories  
- ✅ Detect and display `.mkv` files  
- ✅ One-click audio extraction via `ffmpeg`  
- ✅ Clean UI with zero distractions  
- ✅ No Electron, no bloated web wrappers — pure native Rust

---

## 🧱 Requirements

Make sure your system meets the following requirements **before building**:

- Rust (edition 2021 or newer)  
- `ffmpeg` installed and available in your system's `$PATH`

To verify:

```bash
ffmpeg -version
```

If that fails — stop here and install `ffmpeg`.

---

## 🛠️ Build Instructions

```bash
git clone https://github.com/your-username/jrip.git
cd jrip
cargo run --release
```

Once launched, you can:

- Navigate directories using the **Up** button  
- Click **Jrip** next to any `.mkv` to extract audio  
- Output is saved as `output.mp3` in the same folder as the video