# 🎉 EventNow – Platform Manajemen dan Pendaftaran Acara ITERA

EventNow adalah platform web yang dirancang untuk membantu civitas akademika ITERA dalam mengelola dan mengakses informasi seputar event kampus seperti Studium Generale, seminar, dan kegiatan Himpunan maupun UKM. Aplikasi ini dilengkapi dengan fitur login Google, sistem CRUD event, dan tampilan antarmuka yang responsif.

---

## 🚀 Deskripsi Aplikasi

EventNow bertujuan menjadi pusat informasi terintegrasi untuk semua kegiatan mahasiswa ITERA. Setiap pengguna yang login menggunakan akun Google dapat melihat daftar event, mengelola event sesuai kategorinya, serta melakukan pendaftaran secara digital. Platform ini dibangun menggunakan Python Pyramid untuk backend dan React JS untuk frontend, dengan komunikasi melalui RESTful API.

---

## ⚙️ Teknologi & Dependensi

### 🔧 Backend
- [Python Pyramid](https://trypyramid.com/)
- PostgreSQL
- SQLAlchemy
- `google-auth` (untuk verifikasi token Google OAuth2)
- Pyramid RESTful API
- `pytest` (untuk unit testing ≥ 60% coverage)

### 🎨 Frontend
- [React JS](https://react.dev/)
- React Router DOM
- Context API
- Axios
- Tailwind CSS
- `@react-oauth/google` (untuk Google Login)

---

## 📁 Fitur Aplikasi

- Login dengan akun Google (OAuth2)
- Daftar semua event yang sedang berlangsung
- Filter berdasarkan kategori (Himpunan, UKM, IKM, Umum)
- Tambah, edit, dan hapus event (CRUD)
- Detail event lengkap (poster, deskripsi, tanggal, lokasi)
- Dashboard untuk melihat event yang dibuat pengguna
- UI responsif dan mobile-friendly

---

## 📦 Struktur Folder
---

## 🧪 Endpoint API (Contoh)

| Endpoint              | Method | Fungsi                          |
|-----------------------|--------|----------------------------------|
| `/api/login`          | POST   | Login & verifikasi token Google |
| `/api/events`         | GET    | Daftar semua event              |
| `/api/events/:id`     | GET    | Detail satu event               |
| `/api/events`         | POST   | Tambah event                    |
| `/api/events/:id`     | PUT    | Edit event                      |
| `/api/events/:id`     | DELETE | Hapus event                     |

---

## 🛡️ Autentikasi

- Login menggunakan akun Google
- Token Google dikirim ke backend untuk divalidasi
- Setelah valid, server mengizinkan akses protected route

---

## 📌 Referensi

---

## 📝 Penulis

- Nama: **Handayani**
- NIM: **122140166**
- Kelas: **Pemrograman Web RB**

---

## 🔗 Link Repository

> Repositori aktif sejak minggu pertama  
> 🔗 [https://github.com/han5474ni/eventnow](https://github.com/han5474ni/eventnow)
