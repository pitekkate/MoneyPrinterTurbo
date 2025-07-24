# MoneyPrinterTurbo 💸

[![GitHub stars](https://img.shields.io/github/stars/harry0703/MoneyPrinterTurbo.svg?style=for-the-badge)](https://github.com/harry0703/MoneyPrinterTurbo/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/harry0703/MoneyPrinterTurbo.svg?style=for-the-badge)](https://github.com/harry0703/MoneyPrinterTurbo/issues)
[![GitHub forks](https://img.shields.io/github/forks/harry0703/MoneyPrinterTurbo.svg?style=for-the-badge)](https://github.com/harry0703/MoneyPrinterTurbo/network)
[![GitHub license](https://img.shields.io/github/license/harry0703/MoneyPrinterTurbo.svg?style=for-the-badge)](https://github.com/harry0703/MoneyPrinterTurbo/blob/main/LICENSE)

简体中文 | [English](README-en.md) | Bahasa Indonesia

[![Trend Shift](https://trendshift.io/api/badge/repositories/8731)](https://trendshift.io/repositories/8731)

Cukup berikan topik atau kata kunci untuk video, dan itu akan secara otomatis menghasilkan naskah video, materi video, subtitle video, dan musik latar video sebelum mensintesis video pendek definisi tinggi.

## Demo
- Antarmuka Web
- Antarmuka API

## Terima Kasih Khusus 🙏

Karena penerapan dan penggunaan proyek ini, ada ambang batas tertentu bagi beberapa pengguna pemula. Kami ingin mengucapkan terima kasih khusus kepada:

[RecCloud](https://reccloud.com) (Platform Layanan Multimedia Berbasis AI) yang menyediakan layanan `AI Video Generator` gratis berdasarkan proyek ini. Ini memungkinkan penggunaan online tanpa penerapan, yang sangat mudah.

- Versi Tiongkok: https://reccloud.cn
- Versi Inggris: https://reccloud.com

## Terima Kasih atas Sponsorship 🙏

Terima kasih kepada [Picwish](https://picwish.com) yang mendukung dan mensponsori proyek ini, memungkinkan pembaruan dan pemeliharaan terus menerus.

Picwish berfokus pada bidang pemrosesan gambar, menyediakan berbagai alat pemrosesan gambar yang sangat menyederhanakan operasi kompleks, benar-benar membuat pemrosesan gambar lebih mudah.

## Fitur 🎯

- [x] Arsitektur MVC lengkap, struktur kode yang jelas, mudah dipelihara, mendukung `API` dan `antarmuka Web`
- [x] Mendukung naskah video yang dihasilkan AI, serta naskah yang disesuaikan
- [x] Mendukung berbagai ukuran video definisi tinggi
  - Potret 9:16, `1080x1920`
  - Lanskap 16:9, `1920x1080`
- [x] Mendukung pembuatan video batch, memungkinkan pembuatan beberapa video sekaligus, lalu memilih yang paling memuaskan
- [x] Mendukung pengaturan durasi klip video, memfasilitasi penyesuaian frekuensi pergantian materi
- [x] Mendukung naskah video dalam bahasa Tiongkok dan Inggris
- [x] Mendukung berbagai sintesis suara, dengan pratinjau efek secara real-time
- [x] Mendukung pembuatan subtitle, dengan `font`, `posisi`, `warna`, `ukuran` yang dapat disesuaikan, dan juga mendukung `outline subtitle`
- [x] Mendukung musik latar, baik musik acak atau file musik yang ditentukan, dengan `volume musik latar` yang dapat disesuaikan
- [x] Sumber materi video berdefinisi tinggi dan bebas royalti, dan Anda juga dapat menggunakan materi lokal Anda sendiri
- [x] Mendukung integrasi dengan berbagai model seperti OpenAI, Moonshot, Azure, gpt4free, one-api, Qwen, Google Qwen, Ollama, DeepSeek, ERNIE, Pollinations, OpenRouter dan lainnya

> Pengguna Tiongkok disarankan menggunakan **DeepSeek** atau **Moonshot** sebagai penyedia model besar (dapat diakses langsung dalam negeri, tidak perlu VPN. Pendaftaran memberikan kuota, cukup untuk penggunaan dasar).

## Rencana Mendatang 📅

- [ ] Dukungan dubbing GPT-SoVITS
- [ ] Optimalkan sintesis suara menggunakan model besar untuk output suara yang lebih alami dan kaya emosi
- [ ] Tambahkan efek transisi video untuk pengalaman menonton yang lebih halus
- [ ] Tambahkan lebih banyak sumber materi video, tingkatkan kesesuaian antara materi video dan naskah
- [ ] Tambahkan opsi panjang video: pendek, sedang, panjang
- [ ] Dukung lebih banyak penyedia sintesis suara, seperti OpenAI TTS
- [ ] Otomatis unggah ke platform YouTube

## Demo Video 📺

### Potret 9:16

| ▶️ Cara Menambahkan Kesenangan dalam Hidup Anda | ▶️ Apa Arti Kehidupan |
| --- | --- |

### Lanskap 16:9

| ▶️ Apa Arti Kehidupan | ▶️ Mengapa Berolahraga |
| --- | --- |

## Persyaratan Sistem 📦

- Direkomendasikan minimal 4 inti CPU atau lebih, 4G memori atau lebih, GPU tidak diperlukan
- Windows 10 atau MacOS 11.0, dan versi mereka yang lebih baru

## Mulai Cepat 🚀

### Jalankan di Google Colab

Ingin mencoba MoneyPrinterTurbo tanpa mengatur lingkungan lokal? Jalankan langsung di Google Colab!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1uBpT23JMtO-oO7V1pKTCGzCJ9L1sG1dB?usp=sharing)

### Paket Startup Windows

- Unduh paket startup satu klik, ekstrak dan gunakan langsung (hindari karakter Tiongkok, karakter khusus, dan spasi dalam jalur)
- Baidu Netdisk (v1.2.6): https://pan.baidu.com/s/1wg0UaIyXpO3SqIpaq790SQ?pwd=sbqx Kode Ekstrak: sbqx
- Google Drive (v1.2.6): https://drive.google.com/file/d/1HsbzfT7XunkrCrHw5ncUjFX8XX4zAuUh/view?usp=sharing

Setelah mengunduh, disarankan untuk mengklik dua kali `update.bat` terlebih dahulu untuk memperbarui ke kode terbaru, lalu mengklik dua kali `start.bat` untuk memulai.

Setelah memulai, browser akan terbuka secara otomatis (jika terbuka kosong, disarankan untuk menggunakan Chrome atau Edge).

### Sistem Lain

Paket startup satu klik belum dibuat. Lihat bagian Instalasi & Penerapan di bawah. Disarankan untuk menggunakan docker untuk penerapan, yang lebih nyaman.

## Instalasi & Penerapan 📥

### Prasyarat

- Usahakan jangan menggunakan jalur dengan karakter Tiongkok untuk menghindari masalah yang tidak terduga.
- Pastikan koneksi internet Anda normal. VPN perlu diatur ke mode `lalu lintas global`.

#### ① Klon Proyek

```bash
git clone https://github.com/harry0703/MoneyPrinterTurbo.git
