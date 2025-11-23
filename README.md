# 🗺️ Game Maps Inside Earth

[![Netlify Status](https://api.netlify.com/api/v1/badges/YOUR_NETLIFY_ID/deploy-status)](https://app.netlify.com/sites/YOUR_SITE_NAME/deploys)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**Game Maps Inside Earth** adalah aplikasi web interaktif *Single Page Application* (SPA) yang dirancang untuk membantu pengguna memvisualisasikan dan membandingkan **skala ukuran sebenarnya dari peta dunia video game populer** (seperti GTA V, PUBG, Elden Ring, dll.) ketika diletakkan di atas peta dunia nyata (menggunakan OpenStreetMap).

Proyek ini dibangun dengan fokus pada performa, akurasi, dan estetika desain modern **Glassmorphism**.

---

## ✨ Fitur Utama (Key Features)

* **Perbandingan Skala Akurat:** Menggunakan Leaflet.js dan prinsip Geodesi untuk menskalakan data GeoJSON peta game secara akurat sesuai dengan dimensi dunia nyata.
* **Penempatan Peta Dinamis:** Peta game dapat ditambahkan, dihapus, dan **dipindahkan** (*drag and drop*) ke mana saja di peta dasar, memungkinkan perbandingan yang unik dan visualisasi yang realistis (misalnya, menempatkan Los Santos di perairan New York).
* **Sidebar Interaktif:** Sidebar responsif dengan desain *Glassmorphism* yang elegan, dilengkapi dengan fitur **pencarian** (*search filtering*) untuk akses cepat ke game.
* **Desain Modern:** Implementasi UI/UX minimalis, bersih, dan kontemporer.
* **Ramah Seluler (Mobile-Friendly):** Dioptimalkan untuk tampilan desktop dan seluler dengan *toggleable sidebar*.

---

## 🛠️ Tumpukan Teknologi (Tech Stack)

Proyek ini bersifat *client-side only* (statis) dan dibangun di atas:

| Kategori | Teknologi | Deskripsi |
| :--- | :--- | :--- |
| **Pemetaan Inti** | **Leaflet.js** | Library JavaScript terkemuka untuk peta interaktif yang ringan. |
| **Logika** | **Vanilla JavaScript (ES6)** | Mengelola semua logika aplikasi, interaksi pengguna, dan *state* peta tanpa *framework* berat. |
| **Desain** | **HTML5 / CSS3** | Struktur dan styling, termasuk implementasi `backdrop-filter` untuk efek Glassmorphism. |
| **Peta Dasar** | **OpenStreetMap / CARTO** | Menyediakan *tile layers* (lapisan peta) dunia nyata. |

---

## 🚀 Instalasi dan Panduan Lokal

Proyek ini adalah aplikasi web statis yang sangat mudah dijalankan.

### Prasyarat

Hanya membutuhkan peramban web modern (Chrome, Firefox, Edge, dll.).

### Langkah-langkah

1.  **Clone Repositori:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
    cd YOUR_REPO_NAME
    ```

2.  **Jalankan Secara Lokal:**
    Cukup buka file `index.html` langsung di *browser* Anda. Untuk pengalaman pengembangan yang lebih baik, gunakan ekstensi *live server* (seperti Live Server di VS Code).

---

## 🌐 Deployment

Proyek ini ideal untuk *deployment* di platform hosting statis seperti Netlify atau GitHub Pages.

## 🤝 Kontribusi

Kontribusi sangat disambut! Jika Anda memiliki saran untuk penambahan peta game baru, perbaikan *bug*, atau peningkatan desain visual, silakan buka *issue* atau kirimkan *pull request*.

## 📜 Lisensi

Proyek ini dilisensikan di bawah **MIT License**.

