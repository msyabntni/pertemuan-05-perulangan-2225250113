# Pertemuan 05 - Perulangan Python

| **Keterangan** | **Data** |
|---|---|
| **Nama** | Masya Bantani |
| **NIM** | 2225250113 |
| **Kelas** | 3-E |
| **Jurusan** | Pendidikan Matematika |

## Tujuan

Pada pertemuan ini saya mempelajari penggunaan perulangan `for` dan `while` pada Python. Perulangan digunakan untuk menjalankan proses yang sama beberapa kali sesuai jumlah iterasi atau kondisi tertentu.

Selain itu, saya juga belajar menggunakan `if` di dalam perulangan, melakukan validasi input, serta menggunakan akumulasi untuk menghitung hasil dari proses yang dilakukan berulang.

## Struktur Program

```text
pertemuan-05-perulangan-2225250075/
├── README.md
├── .gitignore
├── latihan/
│   ├── 01_tabel_perkalian.py
│   ├── 02_jumlah_bilangan.py
│   ├── 03_validasi_input.py
│   └── 04_hitung_genap.py
└── kuis/
    └── kuis2_deret_aritmetika.py
```

## Latihan

### 1. Tabel Perkalian

Program menerima sebuah bilangan kemudian menampilkan perkalian bilangan tersebut dari 1 sampai 10 menggunakan perulangan `for`.

Contoh input:

```text
Bilangan: 4
```

Hasil:

```text
4 x 1 = 4
4 x 2 = 8
...
4 x 10 = 40
```

### 2. Jumlah Bilangan 1 sampai n

Program menghitung jumlah bilangan dari 1 sampai `n` menggunakan `for`.

Contoh:

```text
n: 5
Jumlah = 15
```

### 3. Validasi Input

Program meminta nilai ujian antara 0 sampai 100. Jika nilai yang dimasukkan berada di luar rentang tersebut, program akan meminta input kembali menggunakan `while`.

Contoh pengujian:

```text
Nilai 0-100: 120
Nilai tidak valid.
Nilai 0-100: -5
Nilai tidak valid.
Nilai 0-100: 75
Nilai diterima: 75.0
```

### 4. Menghitung Bilangan Genap

Program menghitung banyaknya bilangan genap dari 1 sampai `n`. Perulangan `for` digunakan untuk memeriksa setiap bilangan dan `if` digunakan untuk menentukan apakah bilangan tersebut genap.

Contoh:

```text
n: 10
Banyak bilangan genap = 5
```

## Kuis 2 - Deret Aritmetika

Program menerima:

- Suku pertama (`a`)
- Beda (`d`)
- Banyak suku (`n`)

Validasi `n` menggunakan `while`, sedangkan `for` digunakan untuk menghasilkan setiap suku dan menghitung jumlah seluruh suku.

### Algoritma

1. Memasukkan nilai suku pertama `a`.
2. Memasukkan nilai beda `d`.
3. Memasukkan banyak suku `n`.
4. Jika `n <= 0`, input akan diminta kembali.
5. Menentukan `total = 0`.
6. Menghasilkan setiap suku menggunakan perulangan `for`.
7. Menambahkan setiap suku ke dalam `total`.
8. Menampilkan setiap suku dan jumlah akhirnya.

### Hasil Pengujian

| Input a | Input d | Input n | Suku | Jumlah |
|---:|---:|---:|---|---:|
| 2 | 3 | 5 | 2, 5, 8, 11, 14 | 40.00 |
| 10 | -2 | 4 | 10, 8, 6, 4 | 28.00 |
| 1.5 | 0.5 | 3 | 1.5, 2.0, 2.5 | 6.00 |

## Cara Menjalankan

Pastikan Python 3 sudah terpasang, kemudian buka folder proyek di VS Code.

Untuk menjalankan latihan:

```bash
python3 latihan/01_tabel_perkalian.py
python3 latihan/02_jumlah_bilangan.py
python3 latihan/03_validasi_input.py
python3 latihan/04_hitung_genap.py
```

Untuk menjalankan Kuis 2:

```bash
python3 kuis/kuis2_deret_aritmetika.py
```

## Refleksi

Pada pertemuan ini saya memahami bahwa `for` lebih cocok digunakan ketika jumlah perulangan sudah diketahui atau terdapat urutan nilai yang jelas. Sedangkan `while` lebih cocok digunakan ketika perulangan bergantung pada suatu kondisi.

Saya juga belajar bahwa pada `while` harus ada perubahan pada variabel kontrol agar kondisi akhirnya menjadi `False`. Jika tidak ada perubahan, perulangan dapat menjadi infinite loop.

Selain itu, penggunaan `total = 0` sebelum perulangan penting karena nilai tersebut digunakan sebagai tempat untuk menyimpan hasil akumulasi dari setiap iterasi.

## Kesimpulan

Perulangan `for` dan `while` dapat digunakan untuk membuat program yang melakukan proses secara berulang. Dengan menggabungkan perulangan, percabangan `if`, validasi input, dan akumulasi, masalah yang membutuhkan proses berulang dapat dibuat lebih sederhana dan terstruktur.
