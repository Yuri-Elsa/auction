# 🔨 Auction App

Aplikasi lelang berbasis web yang memungkinkan pengguna untuk membuat lelang, melakukan penawaran secara real-time, dan melihat riwayat lelang mereka.

## 🛠️ Tech Stack

**Frontend**
- HTML, CSS, JavaScript

**Backend**
- Java 17
- Spring Boot 3

## ✨ Fitur

- **Autentikasi** — Register dan login akun pengguna
- **Buat Lelang** — Buat item lelang dengan harga awal dan batas waktu
- **Bid Real-time** — Lakukan penawaran secara langsung dan lihat update terkini
- **Riwayat Lelang** — Pantau lelang yang pernah dibuat atau diikuti

## 📁 Struktur Proyek

```
auction/
├── frontend/   # HTML, CSS, JavaScript
└── backend/    # Spring Boot 3 + Java 17
```

## 🚀 Cara Menjalankan

### Prasyarat

- Java 17+
- Maven 3.8+
- Browser modern (Chrome, Firefox, Edge)

### Backend

```bash
cd backend
./mvnw spring-boot:run
```

Backend akan berjalan di `http://localhost:8080`

### Frontend

```bash
cd frontend
```

Buka file `index.html` langsung di browser, atau gunakan live server (misal ekstensi Live Server di VS Code).

## 📦 Clone Proyek

```bash
git clone --recurse-submodules https://github.com/Yuri-Elsa/auction.git
cd auction
```

> Pastikan menggunakan flag `--recurse-submodules` agar folder `frontend` dan `backend` ikut ter-clone.

## 📄 Lisensi

MIT License
