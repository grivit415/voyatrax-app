# Voyatrax ✈️

Voyatrax adalah aplikasi pemesanan tiket pesawat berbasis web yang dibangun dengan **Next.js**, **Tailwind CSS**, dan **Supabase**. Aplikasi ini menyediakan fitur pemesanan tiket bagi pengguna, serta dashboard khusus untuk admin.

## Fitur Utama

### Untuk Pengguna

- **Login Page**: Masuk ke akun pengguna yang sudah terdaftar.
- **Register**: Daftar akun baru untuk mulai menggunakan aplikasi.
- **Orders**: Melihat dan mengelola pesanan tiket yang telah dibuat.
- **Tickets**: Melihat detail tiket pesawat yang telah dibeli.

### Untuk Admin

- **Dashboard**: Melihat ringkasan statistik dan aktivitas aplikasi.
- **Orders**: Melihat dan mengelola seluruh pesanan pengguna.
- **Ticket**: Membuat, mengedit, dan menghapus tiket penerbangan.
- **Vouchers**: Mengelola voucher diskon untuk promosi.

## Tech Stack

- [Next.js](https://nextjs.org/) — Framework React untuk aplikasi web modern.
- [Tailwind CSS](https://tailwindcss.com/) — Utility-first CSS framework untuk styling.
- [Supabase](https://supabase.com/) — Backend sebagai layanan (auth, database, dan storage).


## Struktur Folder

```
.
├── components
├── pages
│   ├── admin
│   │   ├── dashboard.tsx
│   │   ├── orders.tsx
│   │   ├── tickets.tsx
│   │   └── vouchers.tsx
│   ├── login.tsx
│   ├── register.tsx
│   ├── orders.tsx
│   └── tickets.tsx
├── styles
├── utils
└── ...
```
