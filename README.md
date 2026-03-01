# Big Box - Project Management Dashboard

Big Box adalah platform manajemen proyek komprehensif yang dirancang untuk membantu Project Manager (PM) dan anggota tim dalam mengelola alur kerja, memantau kesehatan proyek, dan menangani hambatan (blockers) secara efisien.

## 🌟 Fitur Utama

* **Dashboard PM & Member**: Tampilan yang disesuaikan berdasarkan peran pengguna untuk memantau statistik proyek dan tugas harian.
* **Manajemen Proyek & Tugas**: Pembuatan, pengeditan, dan pelacakan status proyek serta tugas di dalam papan proyek.
* **Sistem Persetujuan (Approvals)**: Alur kerja untuk menyetujui atau menolak tahapan proyek tertentu.
* **Manajemen Risiko & Blockers**: Identifikasi dini risiko proyek dan pelaporan hambatan teknis atau operasional yang sedang dihadapi tim.
* **Notifikasi Real-time**: Pemberian peringatan langsung untuk tugas mendesak, tenggat waktu yang mendekat, atau pembaruan status proyek.
* **Visualisasi Data**: Grafik interaktif untuk beban kerja sumber daya, lini masa kemajuan, dan ringkasan risiko.

## 🚀 Teknologi yang Digunakan

* **Next.js**: Framework React untuk kebutuhan frontend dan backend (API Routes).
* **TypeScript**: Memberikan keamanan tipe data pada seluruh basis kode.
* **Prisma**: ORM untuk manajemen skema dan interaksi database.
* **Supabase**: Backend-as-a-Service untuk autentikasi dan penyimpanan data.
* **Tailwind CSS & Shadcn UI**: Untuk desain antarmuka yang responsif dan komponen UI yang konsisten.
* **Lucide React**: Library ikon untuk elemen visual.

## 📋 Prasyarat Instalasi

Sebelum memulai, pastikan Anda memiliki:

* Node.js versi terbaru (LTS direkomendasikan).
* Akun Supabase untuk database dan autentikasi.
* Package manager seperti `npm` atau `yarn`.

## 📂 Susunan Project

Proyek ini mengikuti struktur direktori Next.js App Router:

```text
src/
├── app/             # Route handler, halaman (app/auth, app/pm, app/member), dan API
├── components/      # Komponen UI global (sidebar, search, notification)
│   └── ui/          # Komponen dasar dari Shadcn UI
├── hooks/           # Custom hooks React
├── lib/             # Konfigurasi library eksternal seperti Prisma
├── utils/           # Fungsi utilitas untuk Supabase dan logika server
└── prisma/          # Skema database dan file migrasi
