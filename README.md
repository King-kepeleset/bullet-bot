<div align="center">

# 🚀 APK Builder — Unified Workflow

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=2500&pause=800&color=00C2FF&center=true&vCenter=true&width=650&lines=Build+APK+Otomatis.;Web2APK+%7C+Flutter+%7C+Native.;100%25+Auto-Fix.+100%25+Berhasil.;Cukup+Klik%2C+APK+Jadi." alt="Typing SVG" />

<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white" />
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white" />
</p>

<p>
  <img src="https://img.shields.io/badge/version-2.0.0-00C2FF?style=flat-square" />
  <img src="https://img.shields.io/badge/status-stable-success?style=flat-square" />
  <img src="https://img.shields.io/badge/build-passing-brightgreen?style=flat-square" />
  <img src="https://img.shields.io/badge/license-cwooloXD-ff69b4?style=flat-square" />
  <img src="https://img.shields.io/badge/made_with-%E2%9D%A4%EF%B8%8F_by_Zyvarno1-red?style=flat-square" />
</p>

**Build APK dari URL website, project Flutter, atau project Android native — cukup satu klik, langsung jadi. Tanpa install SDK, tanpa ribet.**

[🚀 Quick Start](#-quick-start) · [📦 Fitur](#-fitur-utama) · [⚙️ Konfigurasi](#️-konfigurasi) · [📖 Cara Pakai](#-cara-pakai) · [🧠 Auto-Fix](#-auto-fix-engine) · [📊 Workflow](#-workflow-diagram) · [🐛 Troubleshooting](#-troubleshooting) · [❓ FAQ](#-faq) · [📜 Lisensi](#-lisensi)

</div>

---

## 📌 Daftar Isi

- [✨ Fitur Utama](#-fitur-utama)
- [🎯 Quick Start](#-quick-start)
- [📋 Persyaratan](#-persyaratan)
- [⚙️ Konfigurasi](#️-konfigurasi)
- [📖 Cara Pakai](#-cara-pakai)
  - [🌐 Web2APK](#-web2apk--website-jadi-apk)
  - [🎯 Flutter](#-flutter--build-apk-dari-zip)
  - [⚙️ Native](#️-native--build-project-android-kamu)
- [🧠 Auto-Fix Engine](#-auto-fix-engine)
- [📊 Workflow Diagram](#-workflow-diagram)
- [🔐 Signing & Keamanan](#-signing--keamanan)
- [📲 Notifikasi Telegram](#-notifikasi-telegram)
- [📦 Struktur Output](#-struktur-output)
- [🐛 Troubleshooting](#-troubleshooting)
- [❓ FAQ](#-faq)
- [🛠️ Development](#️-development)
- [🤝 Kontribusi](#-kontribusi)
- [📜 Lisensi](#-lisensi)
- [🙏 Kredit](#-kredit)

---

## ✨ Fitur Utama

<table>
<tr>
<td width="50%">

### 🧩 Multi-Project Support
- 🌐 **Web2APK** — ubah URL website jadi APK
- 🎯 **Flutter** — build project Flutter dari `.zip`
- ⚙️ **Native** — build project Android existing

### 🤖 Auto-Fix Engine
- 🔁 **Retry hingga 5×** otomatis
- 📉 Turunkan versi dependency otomatis
- 🔧 Perbaiki `pubspec.yaml` tanpa sentuh manual
- 🎯 Deteksi versi Flutter dari constraint Dart
- 🧹 Auto-clean `.dart_tool`, `build/`, `pubspec.lock`

### 🎨 Kustomisasi
- 🏷️ Nama aplikasi custom
- 📦 Package name custom
- 🔢 Version name & version code
- 🖼️ Icon otomatis di-resize ke 5 density

</td>
<td width="50%">

### 🔐 Signing & Release
- 🛡️ Keystore otomatis dibuat per-run
- 📝 Sign APK release via `apksigner`
- ✅ Verifikasi signature built-in
- 🔒 Mendukung debug & release build

### 📲 Notifikasi & Distribusi
- 💬 Kirim ke **Telegram** (opsional)
- 📦 Upload ke **GitHub Artifacts** (30 hari)
- 🏷️ Rename APK dengan nama & versi custom
- 📊 Notifikasi sukses / gagal

### ⚡ Reliability
- 🎯 `set -e` untuk fail-fast
- 🛡️ `|| true` selektif untuk non-critical
- 📝 Log lengkap dengan `--stacktrace`
- 🚫 Gagal eksplisit jika APK tidak dihasilkan

</td>
</tr>
</table>

---

## 🎯 Quick Start

### 1️⃣ Cara Manual (UI)
