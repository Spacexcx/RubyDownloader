# Ruby Downloader

<p align="center">
  <img src="https://github.com/user-attachments/assets/5d2c587c-eb1b-4a8f-b775-7cba9bb72f2f" alt="Ruby Downloader" width="200" height="200" />
</p>

<p align="center">
  <a href="https://discord.gg/FkRsbQrX9v"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/Spacexcx/RubyDownloader/releases/latest"><img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Windows" /></a>
  <a href="https://github.com/Spacexcx/RubyDownloader/releases/latest"><img src="https://img.shields.io/badge/Version-1.7.0-red?style=for-the-badge" alt="Version" /></a>
</p>

<p align="center">
  Ruby Downloader is a lightweight, modern, and high-performance desktop media downloader designed for fast, watermark-free video and audio extraction from YouTube, TikTok, and Instagram.
</p>

---

## Features

### Multi-Platform Media Extraction
* **YouTube:** Full resolution downloads from 360p up to 1080p Full HD, 1440p (2K), and 2160p (4K Ultra HD) at 60 FPS.
* **YouTube Playlists:** Complete playlist detection with one-click batch addition to the download queue.
* **TikTok:** Clean, watermark-free video downloads and direct high-quality audio extraction.
* **Instagram:** Reels, video posts, audio tracks, and original full-resolution photos.

### High-Fidelity Audio Extraction & ID3 Tagging
* Multiple audio output formats:
  * MP3 (320 kbps High Quality & 192 kbps Standard)
  * M4A / AAC (Original stream copy)
  * FLAC (Lossless)
  * WAV (Uncompressed studio quality)
* Automatic ID3 metadata tagging: Embeds cover art, artist name, and title directly into downloaded audio files.

### Advanced YouTube Engine & 4K Reliability
* **SABR Experiment Bypass:** Utilizes an intelligent client fallback chain (`web_embedded`, `visionos`, `default`) on the first attempt to prevent YouTube SABR stream restrictions from stripping high-resolution formats.
* **Strict Resolution Matching:** Employs precise format sorting to guarantee the selected resolution (4K, 2K, 1080p, 720p) is downloaded without silent degradation.
* **TLS Session Stabilization:** Mitigates Windows OpenSSL session handshake errors for reliable downloads on any connection.

### Multi-Download Queue Manager
* Concurrent download management with customizable concurrency limits.
* Real-time progress tracking displaying download speed, percentage, and time remaining (ETA).
* Individual download controls with pause, retry, and cancellation capabilities.

### Dedicated Session Authentication (cookies.txt)
* Built-in Netscape `cookies.txt` support for accessing age-restricted videos and member-only content.
* Isolated session cookie processing avoids SQLite database locks and Windows DPAPI browser encryption hurdles.

### Potato PC Mode & Performance Tuning
* Hardware-accelerated glassmorphic desktop interface.
* **Potato PC Mode:** Dedicated performance profile that turns off background canvas animations, particle effects, and backdrop blur to minimize CPU and RAM usage on low-end systems.

### Theme & Audio Customization
* Per-platform color themes (Ruby Red, Sapphire Blue, Topaz Yellow).
* Customizable Matrix rain background with adjustable speed and custom character input.
* Interactive audio feedback (SFX) for queue additions, completion, and notifications with volume control.

### Smart Clipboard Monitor
* Automatically detects valid YouTube, TikTok, and Instagram links copied to the Windows clipboard for instant one-click analysis.

### Multi-Language Localization
* Native interface translations for 6 languages:
  * English
  * Turkish (Türkçe)
  * German (Deutsch)
  * Spanish (Español)
  * French (Français)
  * Russian (Русский)

---

## Security, Privacy & Update Transparency

Ruby Downloader is committed to open, user-first security practices:

### 1. 100% User-Controlled Updates
* **No Silent Background Installs:** The application will never install updates without your explicit consent.
* **Transparent Changelogs:** When an update is available, you receive a side-by-side version comparison and detailed changelog before deciding to proceed.

### 2. Direct GitHub Integration
* Update verifications and installer downloads communicate directly with the official GitHub Releases API via secure HTTPS.
* No middleman proxies, tracking endpoints, or external routing servers.

### 3. Zero Telemetry & Local Storage
* Zero tracking: No analytics, query logs, IP logging, or telemetry data collection.
* All configuration settings, session cookies, and download history remain entirely on your local computer.

### 4. Digitally Signed Binaries
* Application executables and setup packages are cryptographically signed (`CN=Spacexcx`) to guarantee file integrity and protect against unauthorized tampering.

---

## Download & Installation

1. Go to the **[Latest Release](https://github.com/Spacexcx/RubyDownloader/releases/latest)** page.
2. Download `RubyDownloader_Setup.exe`.
3. Run the installer and launch Ruby Downloader.

Future version notices can be checked and applied directly from the in-app Settings menu.

---

## How to Use

1. Launch **Ruby Downloader**.
2. Select your platform (YouTube, TikTok, or Instagram).
3. Paste the media or playlist URL into the search box and click **Search**.
4. Choose your desired video resolution (e.g., 4K, 1080p) or audio format (e.g., MP3 320 kbps).
5. Click **Download** or add to queue.
6. When complete, click **Open File** or **Show in Folder** to access your downloaded media.

---

## Community & Support

Join the official Discord community for technical assistance, feature requests, announcements, and direct developer feedback:

<p align="center">
  <a href="https://discord.gg/FkRsbQrX9v"><img src="https://img.shields.io/badge/Discord-Join%20our%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Server" /></a>
</p>

---

## System Requirements

* **Operating System:** Windows 10 or Windows 11 (64-bit)
* **Processor:** 1.0 GHz or faster
* **Memory (RAM):** 512 MB minimum (Potato PC Mode recommended for low-spec systems)
* **Storage:**
  * **Installer Download Size:** ~137 MB
  * **Installed Disk Space:** ~670 MB free space
* **Network:** Active broadband Internet connection

---

## Disclaimer & Terms of Use

Ruby Downloader is intended for personal, educational, and backup purposes only. Users are responsible for complying with the terms of service of the third-party platforms from which media is retrieved, as well as all applicable intellectual property and copyright regulations in their jurisdiction.

---

## Author

Developed and maintained by **Spacexcx**.
