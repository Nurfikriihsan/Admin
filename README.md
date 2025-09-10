# 📌 AttendPro 

**AttendPro** adalah aplikasi manajemen absensi & data karyawan berbasis web modern. Dokumentasi ini berfokus pada fitur dan akses khusus **Admin** dalam sistem.

---

## 🚀 Fitur Utama 

* Semua fitur employee (login, absensi, pengajuan cuti/izin)
* Manajemen data karyawan (CRUD user & departemen)
* Approval cuti/izin dari karyawan
* Monitoring absensi harian (siapa yang hadir/tidak hadir)
* Generate & export laporan absensi ke PDF
* Dashboard HR dengan ringkasan data absensi & cuti
* Pengaturan aplikasi & notifikasi

---

## 👥 Hak Akses Admin

Admin memiliki wewenang penuh terhadap operasional HR sehari-hari. Detail hak akses:

* Melihat & mengelola data **users**
* Menyetujui atau menolak **leave\_requests**
* Mengakses semua data **attendances**
* Mengelola **departments** & **settings**
* Membuat laporan untuk kebutuhan HR/manajemen

---

## 📋 Ringkasan Fitur Admin

| Fitur                 |       Status       |
| --------------------- | :----------------: |
| Login & Autentikasi   |          ✅         |
| Clock In / Out        |          ✅         |
| Riwayat Absensi       | ✅ (semua karyawan) |
| Pengajuan Cuti/Izin   |    ✅ (approval)    |
| Manajemen Karyawan    |          ✅         |
| Dashboard HR          |          ✅         |
| Laporan & Export PDF  |          ✅         |
| Settings & Notifikasi |          ✅         |

---

## 📂 Struktur Project 

```
app/
├── admin/
│   ├── dashboard/      # Ringkasan data absensi & cuti
│   ├── employees/      # Manajemen data karyawan
│   ├── reports/        # Laporan absensi
│   ├── leave-requests/ # Approval cuti/izin
│   └── settings/       # Pengaturan & notifikasi
```

---

## 🧪 Testing 

1. Login sebagai **admin**
2. Cek data absensi harian karyawan
3. Approve/Reject pengajuan cuti dari employee
4. Tambahkan/ubah data karyawan
5. Generate laporan absensi → export ke PDF

---

## 📊 Database 

* **users** → manajemen akun karyawan/admin
* **attendances** → monitoring absensi harian
* **leave\_requests** → approval cuti/izin
* **departments** → struktur organisasi karyawan
* **settings, notifications** → konfigurasi & pemberitahuan

---

## 🛡️ Catatan

* Admin berfokus pada **operasional HR & monitoring absensi**.
* Tidak memiliki akses ke analitik strategis khusus **management**.

---

👨‍💻 **Kontributor**

* Nama: **Nurfikri Ihsan**
* Posisi: **Intern / Magang**
* Periode: **17 Maret - 17 September 2025**

---

📜 **Lisensi**
* **Project ini dibuat untuk keperluan magang dan pembelajaran**. 
* **Tidak untuk distribusi publik tanpa izin**.
