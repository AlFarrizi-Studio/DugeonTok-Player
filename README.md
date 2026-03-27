<p align="center">
  <img src="https://raw.githubusercontent.com/AlFarrizi-Studio/DugeonTok-Player/refs/heads/main/Images/Icon.ico" width="200" />
</p>

<h1 align="center">DugeonTok Player</h1>

<p align="center">
  <a href="https://github.com/AlFarrizi-Studio/DugeonTok-Player/releases/tag/v2.12.9">
    <img src="https://img.shields.io/badge/version-2.12.9-blue" />
  </a>
  
  <img src="https://img.shields.io/badge/status-active-success" />
  
  <a href="https://github.com/AlFarrizi-Studio/DugeonTok-Player/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/license-Al%20Farrizi%202026-red" />
  </a>
  
  <a href="https://github.com/AlFarrizi-Studio/DugeonTok-Player/releases/download/v2.12.7/DugeonTok-Player-Installer_v2.12.9.exe">
    <img src="https://img.shields.io/badge/platform-Windows-lightgrey?logo=windows" />
  </a>
  
  <img src="https://img.shields.io/badge/build-stable-brightgreen" />
</p>

<p align="center">
  <a href="https://www.virustotal.com/gui/file/46a733a5b1bfb9240d773b3fb9d2e5688643b8b4c0a82fef8bc6c1d28e9fa24c/detection">
    <img src="https://img.shields.io/badge/VirusTotal-2%2F67%20(False%20Positive)-blue?logo=virustotal" />
  </a>
</p>

<p align="center">
  <b>Panel Kontrol Musik Modern untuk Streamer</b><br>
  Kelola request lagu, antrian, dan overlay streaming secara real-time dengan mudah dan profesional.
</p>

---

## 🖼️ Preview

<p align="center">
  <img src="https://raw.githubusercontent.com/AlFarrizi-Studio/DugeonTok-Player/refs/heads/main/Images/image-1.png" width="100%" />
  <br><br>
  <img src="https://raw.githubusercontent.com/AlFarrizi-Studio/DugeonTok-Player/refs/heads/main/Images/image-2.png" width="100%" />
  <br><br>
  <img src="https://raw.githubusercontent.com/AlFarrizi-Studio/DugeonTok-Player/refs/heads/main/Images/image-3.png" width="100%" />
  <br><br>
  <img src="https://raw.githubusercontent.com/AlFarrizi-Studio/DugeonTok-Player/refs/heads/main/Images/overlay.png" width="100%" />
</p>

---

## ✨ Pendahuluan

**DugeonTok Player** merupakan sebuah panel kontrol modern yang dirancang khusus untuk membantu streamer dalam mengelola pemutaran musik, menerima request lagu dari audiens, serta menampilkan overlay streaming secara **real-time**.

Aplikasi ini dikembangkan dengan tujuan untuk memberikan pengalaman streaming yang **lebih terstruktur, responsif, dan profesional**, dengan mengintegrasikan seluruh kebutuhan kontrol musik ke dalam satu sistem yang efisien.

Melalui DugeonTok Player, pengguna tidak perlu lagi berpindah-pindah aplikasi untuk mengatur musik selama live streaming. Seluruh proses mulai dari **request lagu, pengelolaan antrian, kontrol pemutaran, hingga sinkronisasi tampilan overlay** dapat dilakukan dalam satu panel terpadu.

Selain itu, aplikasi ini juga mendukung integrasi dengan **TikTok Live Chat**, sehingga penonton dapat berinteraksi secara langsung dengan mengirimkan request lagu yang akan diproses secara otomatis oleh sistem.

---

## 🎯 Tujuan Pengembangan

DugeonTok Player dikembangkan dengan beberapa tujuan utama:

- Menyediakan **sistem kontrol musik terpusat** untuk kebutuhan live streaming  
- Meningkatkan **interaksi real-time antara streamer dan audiens**  
- Menjaga **konsistensi tampilan overlay** agar terlihat profesional  
- Mengurangi kompleksitas workflow selama siaran langsung  
- Meningkatkan **pengalaman dan engagement penonton**  

---

## 🚀 Fitur Utama

### 🎶 Sistem Request Lagu Otomatis
- Mendukung request lagu dari:
  - YouTube  
  - Deezer  
- Pemrosesan link dan pencarian lagu secara otomatis  
- Integrasi langsung ke dalam sistem antrian  

### 📋 Manajemen Antrian (Queue)
- Sistem antrian dinamis dan real-time  
- Pengaturan urutan lagu secara fleksibel  
- Fitur skip, prioritas, dan auto-play  

### 🖥️ Engine Overlay Real-Time
- Menggunakan sistem berbasis Browser Source  
- Sinkronisasi otomatis dengan lagu yang sedang diputar  
- Tampilan overlay yang dapat dikustomisasi sepenuhnya  

### 💬 Integrasi TikTok Live Chat
- Deteksi request lagu langsung dari chat  
- Sistem berbasis keyword (command)  
- Otomatis masuk ke dalam queue tanpa intervensi manual  

### 🎛️ Kontrol Pemutaran Lengkap
- Play / Pause / Skip  
- Monitoring status lagu secara real-time  
- Kontrol langsung tanpa mengganggu jalannya live  

### 🔊 Dukungan Multi-Device Audio
- Kompatibel dengan:
  - Virtual Audio Cable  
  - Sound card eksternal  
  - Multi-output audio system  

---

## 🧩 Arsitektur Sistem

DugeonTok Player dirancang dengan pendekatan modular untuk memastikan stabilitas dan fleksibilitas:

- **Control Panel (Frontend)**  
  Antarmuka utama untuk interaksi pengguna  

- **Playback Engine (Backend / Local)**  
  Bertanggung jawab atas pemrosesan dan pemutaran audio  

- **Overlay Renderer**  
  Menampilkan informasi lagu secara visual di OBS / Streamlabs  

- **Chat Integration Module**  
  Mengelola input dari live chat (TikTok)  

Arsitektur ini memungkinkan aplikasi berjalan dengan **stabil, scalable, dan mudah dikembangkan** di masa depan.

---

## ⚙️ Instalasi & Penggunaan

### Persyaratan Sistem
- Sistem Operasi Windows 10/11 
- OBS Studio atau Streamlabs  
- Koneksi internet stabil  

### Langkah Instalasi

1. **Jalankan Aplikasi**  
   Buka DugeonTok Player dan akses panel kontrol utama  

2. **Konfigurasi Audio**  
   Pilih perangkat output audio yang sesuai  

3. **Pasang Overlay ke OBS**
   - Salin link overlay  
   - Tambahkan sebagai Browser Source  
   - Atur ukuran dan posisi  

4. **Aktifkan Integrasi Chat**
   - Hubungkan dengan TikTok Live  
   - Atur command jika diperlukan  

5. **Mulai Streaming**
   - Jalankan musik  
   - Pantau antrian dan request  

---

## 🎨 Kustomisasi Overlay

Overlay dapat disesuaikan sepenuhnya sesuai kebutuhan:

- Warna teks dan font  
- Background dan transparansi  
- Shadow dan border  
- Posisi dan ukuran  
- Animasi (jika tersedia)  

Hal ini memungkinkan streamer menyesuaikan tampilan dengan **branding dan identitas visual** masing-masing.

---

## ⚙️ Konfigurasi Audio

Untuk hasil terbaik:

- Gunakan output device yang sesuai  
- Gunakan Virtual Audio Cable jika diperlukan  
- Lakukan testing sebelum live  
- Pastikan OBS menangkap sumber audio yang benar  

---

## 📜 Ketentuan Penggunaan (Terms of Service)

Dengan menggunakan aplikasi ini, pengguna menyetujui bahwa:

- Penggunaan harus sesuai dengan kebijakan platform streaming  
- Konten musik berasal dari layanan pihak ketiga  
- Pengguna bertanggung jawab atas penggunaan konten selama live  
- Fitur dapat berubah mengikuti kebijakan layanan eksternal  

---

## 🔒 Kebijakan Privasi (Privacy Policy)

Kami berkomitmen menjaga privasi pengguna:

- Tidak mengumpulkan data sensitif tanpa izin  
- Data hanya digunakan untuk kebutuhan aplikasi  
- Pengguna disarankan tidak membagikan data pribadi di chat publik  
- Data terbatas pada konfigurasi, antrian, dan overlay  

---

## 📄 Lisensi

This project is licensed under the **Al Farrizi License © 2026**.
See the LICENSE file for details.

---

## 🤝 Kontribusi

Saat ini, proyek ini tidak dibuka untuk kontribusi publik.  
Untuk kerja sama atau kolaborasi, silakan hubungi pengembang secara langsung.

---

## 📌 Roadmap Pengembangan

Pengembangan selanjutnya akan mencakup:

- Peningkatan stabilitas integrasi YouTube  
- Animasi overlay yang lebih advanced  
- Sistem moderasi request  
- Dukungan multi-platform chat  
- Versi web panel kontrol  

---

## ⚠️ Disclaimer

Perangkat lunak ini disediakan “sebagaimana adanya” tanpa jaminan apa pun.  
Pengembang tidak bertanggung jawab atas kerusakan, kehilangan data, atau gangguan layanan.

---

## ⭐ Dukungan

Jika proyek ini membantu Anda:

- ⭐ Berikan star di repository  
- 📢 Bagikan ke sesama streamer  
- 💬 Berikan feedback untuk pengembangan  

---

## 🧠 Catatan Akhir

DugeonTok Player dikembangkan untuk menyederhanakan workflow streaming sekaligus meningkatkan kualitas produksi siaran.

Pengembangan akan terus dilakukan untuk memastikan aplikasi tetap stabil, relevan, dan memberikan pengalaman terbaik bagi pengguna.
