# Aplikasi Inventori Toko Apotek

Aplikasi sederhana berbasis Python CLI untuk mengelola stok obat di toko apotek. Cocok untuk usaha kecil atau inventaris manual tanpa sistem database.

---

## Fitur

- Tambah data obat baru
- Tampilkan semua data obat
- Edit jumlah stok
- Hapus obat
- Laporan stok (diurutkan dari yang terbanyak)
- Simpan data ke file JSON

---

## Cara Menjalankan

1. **Install Python 3** jika belum tersedia.
2. Simpan file Python dengan nama `inventori_apotek.py`.
3. Jalankan aplikasi melalui terminal:
   ```bash
   python inventori_apotek.py
| File                    | Deskripsi                        |
| ----------------------- | -------------------------------- |
| `inventori_apotek.py`   | Kode utama aplikasi              |
| `inventori_apotek.json` | File data obat dalam format JSON |
| `README.md`             | Dokumentasi penggunaan aplikasi  |

## Panduan Penggunaan 
Saat dijalankan, aplikasi menampilkan menu berikut
1. Tambah Obat
2. Lihat Semua Obat
3. Edit Stok Obat
4. Hapus Obat
5. Laporan Stok
6. Simpan & Keluar

Contoh:

Tambah Obat
Kode obat: OBT001
Nama obat: Paracetamol
Jumlah stok: 100

Edit stok  
Masukkan kode obat yang ingin diedit: OBT001
Stok baru: 50

Catatan Teknis
Data obat disimpan dalam format:
[
  {
    "kode": "OBT001",
    "nama": "Paracetamol",
    "stok": 50


  }
  


]
Untuk menyimpan data secara manual, pilih opsi 6 (Simpan & Keluar) di menu utama.





