# 🤖 FLUTTER BUILDER BOT

<p align="center">
  <img src="https://img.shields.io/badge/Telegram-Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Bot">
  <img src="https://img.shields.io/badge/Flutter-3.16.9-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Node.js-20.x-339933?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js">
  <img src="https://img.shields.io/badge/GitHub-Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" alt="GitHub Actions">
</p>

<p align="center">
  <b>Telegram Bot untuk membuild APK dari file ZIP atau Website</b><br>
  <i>Dengan sistem Credit, Antrian, dan Notifikasi Channel</i>
</p>

---

## 📋 Daftar Isi

- [Fitur](#-fitur)
- [Prerequisites](#-prerequisites)
- [Instalasi](#-instalasi)
- [Konfigurasi](#-konfigurasi)
- [Struktur Folder](#-struktur-folder)
- [Command Bot](#-command-bot)
- [Sistem Credit](#-sistem-credit)
- [GitHub Workflow](#-github-workflow)
- [Dashboard Web](#-dashboard-web)
- [Screenshot](#-screenshot)
- [Developer](#-developer)
- [License](#-license)

---

## ✨ Fitur

| Fitur | Deskripsi |
|-------|-----------|
| 🚀 **Build APK dari ZIP** | Upload project Flutter (.zip) → build APK via GitHub Actions |
| 🌐 **Build Web to APK** | Masukkan URL website → build APK dengan WebView |
| 💳 **Sistem Credit** | 7 credit/minggu, ZIP=2 credit, WEB=1 credit |
| 📋 **Sistem Antrian** | Max 3 concurrent build, antrian otomatis |
| 📊 **Status Bot** | Runtime, RAM, CPU, Disk VPS |
| 🐛 **Laporan Bug** | Kirim foto + deskripsi ke Owner |
| 🔔 **Notifikasi Channel** | User baru, Build dimulai, Build selesai |
| 🎨 **Button Berwarna** | Tombol dengan style primary, success, danger, warning |
| ⚙️ **Dashboard Web** | Monitoring build & antrian via web |
| 👑 **Owner Command** | Setup GitHub, Reset Antrian, Add Credit |

---

## 📦 Prerequisites

- **Node.js** v16+ atau v20+
- **GitHub Account** dengan Personal Access Token
- **Repository GitHub** untuk workflow Actions
- **Bot Token** dari [@BotFather](https://t.me/BotFather)
- **3 Channel Telegram** (wajib join)
- **Video Welcome** (opsional, upload ke catbox.moe)

---

## 🚀 Instalasi

### 1. Clone Repository

```bash
git clone https://github.com/username/flutter-builder-bot.git
cd flutter-builder-bot
