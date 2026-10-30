# Pertemuan 11 — Dictionary/Map

## Identitas Mahasiswa

- **Nama:** Anastasya Putri Kirana
- **NIM:** 2225250041
- **Kelas:** 3A
- **Mata Kuliah:** Algoritma dan Pemrograman

## Tujuan

Memodelkan data pendidikan menggunakan dictionary dan pasangan key-value. Mempelajari cara mengakses, menambah, mengubah, menghapus, dan menelusuri data berdasarkan key.

## Struktur Data

Program menggunakan dictionary dengan NIM sebagai key utama.

Setiap value berupa dictionary yang berisi:
- `nama`: nama mahasiswa.
- `kelas`: kelas mahasiswa.
- `nilai`: nilai mahasiswa.

Struktur ini memudahkan pencarian informasi mahasiswa berdasarkan NIM tanpa harus mencari berdasarkan indeks list.

## Struktur Folder

```text
pertemuan-11-dictionary-2225250041/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_dasar_dictionary.py
│   ├── 02_akses_get.py
│   ├── 03_manipulasi_dictionary.py
│   ├── 04_iterasi_dictionary.py
│   ├── 05_dictionary_bersarang.py
│   └── 06_fungsi_dictionary.py
└── praktik/
    └── data_mahasiswa.py
```

## Deskripsi Latihan

1. Dasar Dictionary: membuat dictionary dan mengakses value menggunakan key.
2. Akses get(): mengambil value dengan aman dan memberikan nilai default jika key tidak tersedia.
3. Manipulasi Dictionary: menambah, mengubah, dan menghapus pasangan key-value.
4. Iterasi Dictionary: menelusuri key dan value menggunakan `items()`.
5. Dictionary Bersarang: menyimpan dictionary di dalam dictionary.
6. Fungsi Dictionary: membuat fungsi untuk mencari data mahasiswa.

## Praktik — Sistem Data Mahasiswa

Program menyimpan data minimal lima mahasiswa menggunakan NIM sebagai key. Program dapat mencari mahasiswa, menangani NIM yang tidak ditemukan, menambahkan mahasiswa baru, memperbarui nilai, menampilkan seluruh data, dan menghitung rata-rata nilai.

Dua fungsi utama yang digunakan:
- `cari_mahasiswa(data, nim)`: mencari mahasiswa berdasarkan NIM.
- `rata_rata_nilai(data)`: menghitung rata-rata nilai seluruh mahasiswa.

## Cara Menjalankan

Jalankan melalui terminal:

```bash
py latihan/01_dasar_dictionary.py
py latihan/02_akses_get.py
py latihan/03_manipulasi_dictionary.py
py latihan/04_iterasi_dictionary.py
py latihan/05_dictionary_bersarang.py
py latihan/06_fungsi_dictionary.py
py praktik/data_mahasiswa.py
```

## Test Case dan Hasil Pengujian

| Kasus | Input/Aksi | Hasil Aktual |
|---|---|---|
| Pencarian tersedia | A003 | Data Citra ditemukan |
| Pencarian tidak tersedia | A999 | Data tidak ditemukan |
| Pembaruan nilai | A002 menjadi 82 | Nilai berubah menjadi 82 |
| Penambahan data | A006 | Fajar, kelas B, nilai 80 berhasil ditambahkan |
| Rekap data | items() | Seluruh enam mahasiswa ditampilkan |
| Rata-rata | Seluruh data | 83.50 |

Seluruh test case praktik berhasil dijalankan sesuai hasil yang diharapkan.

## Refleksi

Melalui praktikum ini, saya mempelajari bahwa dictionary menyimpan data dalam bentuk pasangan key-value sehingga informasi dapat dicari berdasarkan identitas tertentu seperti NIM. Saya juga memahami penggunaan `get()` untuk menghindari KeyError, `items()` untuk menelusuri pasangan key-value, serta dictionary bersarang untuk menyimpan data yang memiliki beberapa atribut. Penggunaan fungsi membuat operasi pencarian dan perhitungan menjadi lebih terstruktur.

## Referensi dan Bantuan

- Bahan Ajar Algoritma dan Pemrograman — Pertemuan 11: Dictionary/Map dan Pasangan Key-Value dalam Python.
- Python Software Foundation, Python 3 Documentation — Dictionaries.
- Visual Studio Code Documentation.
- Bantuan AI digunakan untuk membantu memahami konsep dan menyusun solusi. Kode dan hasil pengujian diperiksa kembali.