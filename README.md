<img width="2560" height="1280" alt="FrostCast-GitHub-Hero-Banner-RealUI" src="https://github.com/user-attachments/assets/a3e85464-0e60-45e3-8e21-bad84af6ec40" alt="FrostCast Dock Official Hero Banner" width="100%"  />

<br />

# FrostCast Dock — Live Overlay Studio (`v3.2.9`)

**All-in-One 5-Platform Live Chat, Gift/Donation & Follower Aggregator for OBS Studio & Windows 10/11 (`.ZIP` & `.EXE`)**  
**Penggabung Live Chat, Gift/Donasi & Follower 5 Platform Real-Time untuk OBS Studio & Windows 10/11 (`.ZIP` & `.EXE`)**

[![Release Version](https://img.shields.io/badge/Release-v3.2.9_Official-22D3EE?style=for-the-badge&logo=windows)](./RELEASE_NOTES.md)
[![Platform](https://img.shields.io/badge/Platform-Windows_10%2F11_x64_%7C_OBS_Studio-10B981?style=for-the-badge)](./RELEASE_NOTES.md)
[![Local Engine](https://img.shields.io/badge/Engine-127.0.0.1_Zero_API_Key-38BDF8?style=for-the-badge)](./RELEASE_NOTES.md)
[![Publisher](https://img.shields.io/badge/Publisher-FrostBlue_(@FrostBluefps)-818CF8?style=for-the-badge)](https://github.com)

**[🇮🇩 Dokumentasi Bahasa Indonesia](#-dokumentasi-bahasa-indonesia)** • **[🇬🇧 English Documentation](#-english-documentation)** • **[📦 Unduh Rilis (.ZIP / .EXE)](../../releases)**

</div>

---

## 🇮🇩 Dokumentasi Bahasa Indonesia

### Sekilas Tentang FrostCast Dock (FrostCast Live Overlay)
**FrostCast Dock** adalah aplikasi desktop portabel Windows (`.EXE` & `.ZIP`) dan overlay siaran real-time yang dirancang khusus untuk para kreator konten dan *live streamer* oleh **FrostBlue (`@FrostBluefps`)**. Aplikasi ini menggabungkan komentar live chat, notifikasi **Gift / Donasi / SuperChat / Stars**, serta **Follower / Subscriber Baru** dari **5 platform sekaligus** (**YouTube Live, TikTok Live, Twitch Stream, Kick Live, dan Facebook Gaming**) ke dalam satu layar terpadu yang bersih, ringan, dan bebas *delay*.

Seluruh mesin berjalan **100% secara lokal di komputer Anda (`127.0.0.1:3000`)** tanpa memerlukan kunci API (*Zero API Key*), dilengkapi fitur **Smart Paste URL Live (Otomatis Deteksi)**, **Mode Hemat GPU (50 DOM Cap)**, serta **Mode Zero-Storage (Anti-Bloat)** yang otomatis mereset seluruh riwayat chat maupun kanal kembali ke **`0`** begitu jendela aplikasi ditutup.

---

### ✨ Fitur Utama Sesuai Aplikasi Asli

| Fitur Unggulan | Deskripsi Lengkap |
| :--- | :--- |
| **🌐 Agregator Multi-Chat 5 Platform Resmi** | Menggabungkan live chat, jumlah penonton (*viewer count*), dan *like* dari **YouTube Live**, **TikTok Live**, **Twitch Stream**, **Kick Live**, dan **Facebook Gaming** secara real-time. |
| **🔗 Smart Paste URL Live (Otomatis Deteksi)** | Cukup tempel tautan live streaming atau ketik `@username` kanal Anda; aplikasi otomatis mendeteksi platform dan langsung menghubungkan aliran chat. |
| **🎁 Stage Spotlight: Gift, Donasi & Follower Penuh** | Menampilkan kartu sorotan interaktif untuk **TikTok Gift**, **YouTube SuperChat**, **Twitch Bits/Sub**, **Kick Gifted Subs**, **Facebook Gaming Stars**, dan **Follower Baru** lengkap dengan antrean FIFO dan tombol **Pin ke Layar**. |
| **📱 Mode Portrait 9:16 Mandiri (`430×780`)** | File `FrostCast.Live.Overlay.Portrait.exe` membuka jendela vertikal `430×780` dengan kontrol satu baris (**Semua / Gift**, **Glass 20%**, **Kanal**, **OBS**, **Pengaturan**), sangat ideal untuk layar kedua atau *Custom Browser Dock* OBS. |
| **🖥️ Mode Landscape Studio Mandiri (`1280×820`)** | File `FrostCast.Live.Overlay.Landscape.exe` membuka ruang kerja studio lengkap (**3-Zone Header**, **Toolbar Filter 5 Platform**, **Sidebar Koneksi & Simulator Alert**, serta **Kustomisasi Tema & CSS**). |
| **⚡ Mode Hemat GPU & Zero-Storage (`0 KB DB`)** | Menjaga FPS game kompetitif tetap maksimal dengan pembatasan 50 DOM chat aktif dan otomatis membersihkan seluruh sesi kembali ke `0` saat aplikasi ditutup. |
| **🛡️ Biner Bersih Beridentitas Resmi FrostBlue** | Dilengkapi ikon resmi **FrostBlue (`RT_ICON`)**, metadata **`VS_VERSION_INFO`**, manifes **`asInvoker`**, serta **PE Header CheckSum** resmi dengan ekstraksi aliran biner GZip langsung (bebas error `FromBase64String`). |

---

### 🖼️ Tampilan Asli Aplikasi (1:1 Real UI Showcase)

#### 1. Mode Landscape Studio (`1280×820` — `FrostCast.Live.Overlay.Landscape.exe`)
<div align="center">
<img width="100%" alt="FrostCast Dock Landscape Studio 1280x820 Real UI" src="https://github.com/user-attachments/assets/c319ede0-2ac2-40dd-9b04-70e98626c2c9" />
</div>

#### 2. Mode Portrait 9:16 Vertikal (`430×780` — `FrostCast.Live.Overlay.Portrait.exe`)
<div align="center">
<img width="440" alt="FrostCast Dock Portrait 9:16 Overlay 430x780 Real UI" src="https://github.com/user-attachments/assets/852e6d98-41d6-49eb-9a68-a2a4f507ffa8" />
</div>

---

### 🚀 Cara Mengunduh & Menjalankan Aplikasi Windows (`.ZIP` / `.EXE`)

1. Buka halaman **[GitHub Releases](../../releases)** di sisi kanan repositori ini.
2. Unduh paket **`FrostCast.Live.Overlay.Complete.zip`** (berisi versi *Portrait* + *Landscape* + skrip pembuka bebas SmartScreen) atau pilih varian tunggal sesuai kebutuhan Anda:
   - 📦 `FrostCast.Live.Overlay.Portrait.zip` (Untuk tampilan vertikal `9:16` ukuran `430×780`)
   - 📦 `FrostCast.Live.Overlay.Landscape.zip` (Untuk tampilan studio `16:9` ukuran `1280×820`)
3. **Ekstrak file `.ZIP`** ke folder mana saja di PC Windows 10/11 (64-bit) Anda.
4. Klik 2x **`Buka-Tanpa-SmartScreen.cmd`** (cukup sekali saat pertama kali ekstrak untuk menghapus penanda unduhan internet *Mark-of-the-Web*), atau langsung klik 2x file **`.EXE` berlogo FrostBlue**.
5. Tempel tautan live atau `@username` pada panel **01. Koneksi 5 Platform** (atau tombol **Kanal** di Mode Portrait), dan chat akan langsung mengalir secara real-time!

---

### 🎥 Cara Integrasi dengan OBS Studio

1. **Sebagai Custom Browser Dock di Dalam OBS Studio**:
   - Buka **OBS Studio** $\rightarrow$ menu **Docks** $\rightarrow$ **Custom Browser Docks**.
   - Masukkan Nama Dock: `FrostCast Dock` dan tempel URL lokal:
     ```text
     http://127.0.0.1:3000/?dock=portrait&bg=transparent&opacity=20
     ```
2. **Sebagai Browser Source Transparan di Atas Layar Game/Stream**:
   - Tambahkan **Sources** $\rightarrow$ **Browser** di OBS Studio.
   - Masukkan URL Overlay Transparan:
     ```text
     http://127.0.0.1:3000/?overlay=1&bg=transparent
     ```
   - Atur Lebar (`Width`): `430` dan Tinggi (`Height`): `780`.

---

## 🇬🇧 English Documentation

### Overview
**FrostCast Dock (FrostCast Live Overlay)** is a standalone portable Windows desktop application (`.EXE` & `.ZIP`) and real-time broadcast overlay engineered by **FrostBlue (`@FrostBluefps`)**. It unifies live chat messages, **Gift / SuperChat / Stars / Donation alerts**, and **New Follower / Subscriber notifications** across **5 streaming platforms simultaneously** (**YouTube Live, TikTok Live, Twitch Stream, Kick Live, and Facebook Gaming**) into a single low-latency studio interface.

It runs **100% locally on `127.0.0.1:3000`** with **zero API keys required**, includes **Smart Paste Live URL Auto-Detection**, **Ultra-Low GPU Mode (50 DOM Cap)**, and **Zero-Storage Anti-Bloat Mode** that resets all channels and chat history back to **`0`** the moment you close the window.

### Key Highlights
- **5-Platform Real-Time Chat & Metrics Aggregation**: Connect YouTube Live, TikTok Live, Twitch Stream, Kick Live, and Facebook Gaming simultaneously using just your channel handle or stream URL.
- **Dual Standalone Windows `.EXE` Executables**:
  - `FrostCast.Live.Overlay.Portrait.exe` (`430×780` vertical 9:16 dock with 1-click Glass 20% mode and unclipped Gift & Follower cards).
  - `FrostCast.Live.Overlay.Landscape.exe` (`1280×820` full broadcast studio with 3-Zone Header, 5-Platform Filter Toolbar, Smart Paste Sidebar, and CSS Customizer).
- **Clean Native PE32+ Architecture**: Embedded with official FrostBlue multi-resolution icons (`RT_ICON`), `VS_VERSION_INFO` version metadata, `asInvoker` Windows 10/11 compatibility manifest, and direct binary offset GZip streaming (zero `FromBase64String` heuristics).

---

### 🛠️ Pengembangan Lokal dari Kode Sumber (Build from Source)

```bash
# 1. Clone repositori ini
git clone https://github.com/USERNAME_ANDA/frostcast-live-overlay.git
cd frostcast-live-overlay

# 2. Pasang dependensi paket
npm install

# 3. Jalankan server pengembangan lokal (http://localhost:3000)
npm run dev

# 4. Bangun bundel produksi
npm run build
```

---

<div align="center">
  <sub>Dikembangkan oleh <strong>FrostBlue (@FrostBluefps)</strong> • FrostCast Dock Live Overlay Studio v3.2.9</sub>
</div>
