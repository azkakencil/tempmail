# 📧 SMARTGADGET Temp Mail - Premium Source Code

Aplikasi Temporary Email (Email Sementara) modern berbasis Web & PWA dengan tampilan profesional, fitur inbox real-time, dan dokumentasi lengkap.

## ✨ Fitur Unggulan

- **Modern UI/UX:** Desain bersih, responsif, dan animasi halus.
- **PWA Ready:** Bisa diinstal menjadi aplikasi native di Android/iOS.
- **Privacy First:** Sistem inbox menggunakan penyimpanan lokal (IndexedDB) & Backend Serverless.
- **Real-time:** Auto-refresh inbox tanpa reload halaman.
- **Dokumentasi Terintegrasi:** Halaman dokumentasi teknis sudah tersedia di dalam web.

## 📁 Struktur foldernya
```bash
SANN404-Temp-Mail/
│
├── api/
│   └── index.js          <-- Backend (Serverless Function)
│
├── public/
│   ├── index.html        <-- Halaman Utama (App)
│   ├── docs.html         <-- Halaman Dokumentasi
│   ├── style.css         <-- File CSS
│   ├── script.js         <-- File JavaScript Logic
│   ├── sw.js             <-- Service Worker (PWA)
│   └── manifest.json     <-- Manifest (PWA)
│
├── .gitignore            <-- (PENTING) Agar file sampah tidak ikut keupload
├── package.json          <-- Daftar library (dependencies)
├── vercel.json           <-- Konfigurasi Deploy Vercel
└── README.md
```          

## 🛠️ Teknologi

- **Frontend:** HTML5, CSS3 (Modern Variables), Vanilla JS (No Framework heavy overhead).
- **Backend:** Node.js (Vercel Serverless Functions).
- **Database:** IndexedDB (Client Side).
- **Library:** Cheerio (untuk scraping engine).

## 🚀 Cara Instalasi & Deploy (Vercel)

Source code ini didesain khusus untuk deployment instan menggunakan **Vercel**.

1. **Persiapan:**
   - Pastikan sudah install Node.js.
   - Buka terminal di folder project, ketik: `npm install`

2. **Test Lokal:**
   - Install Vercel CLI: `npm i -g vercel`
   - Jalankan: `vercel dev`

3. **Deploy ke Production:**
   - Upload folder ini ke GitHub Anda.
   - Buka Dashboard Vercel -> "Add New Project".
   - Import repository GitHub tadi.
   - Klik **Deploy**. Selesai! Tidak perlu konfigurasi server ribet.

## 📂 Struktur File

- `/api` - Logika Backend (Serverless).
- `/public` - Tampilan Frontend dan Aset PWA.

---
**Developed by SANN404**
