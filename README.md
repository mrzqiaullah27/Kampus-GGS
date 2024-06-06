# Kampus-GGS

## Deskripsi Masalah
Kampus GGS sedang membangun gedung baru di pusat kota Alaska. Sebanyak **N gedung** telah selesai dibangun dan siap digunakan untuk kegiatan perkuliahan. Namun, akses jalan/koridor yang menghubungkan setiap gedung belum dibangun, membuat gedung-gedung tersebut tidak dapat diakses.

## Tujuan
Membangun jalan/koridor sehingga semua gedung dapat saling terhubung dengan nyaman dan mudah diakses. Mahasiswa harus dapat pergi dari satu gedung ke gedung lain melalui satu atau beberapa jalan/koridor yang tersedia.

## Batasan
- Kondisi geografis tidak memungkinkan setiap gedung memiliki akses langsung ke setiap gedung lain.
- Biaya pembangunan yang terbatas.

## Input
- Beberapa test case.
- Baris pertama terdiri dari dua integer N dan M:
  - **N**: Jumlah gedung (2 <= N <= 1000).
  - **M**: Jumlah jalan/koridor yang ingin dibangun (0 <= M <= N(N-1)/2).
- M baris berikutnya merepresentasikan jalan/koridor yang dapat dibangun:
  - **A, B**: Gedung yang dihubungkan (1 <= A, B <= N, A != B).
  - **C**: Biaya pembangunan (1 <= C <= 10^4).

## Output
- Untuk setiap test case:
  - Jika tidak mungkin membangun jalan/koridor yang menghubungkan semua gedung: **"TIDAK MEMUNGKINKAN"**.
  - Tampilkan total biaya pembangunan minimum.

## Creator
| Nama             | NIM           |
|-------------------------|---------------|
| Imam Riyanto             | 2306963    |
| Mohammad Rizqi Aulia Abdillah           | 2301029     |
| Riyadhil Haqqy Arifin          | 2311156 |
| Sabrina Yulfrida Fajrin            | 2308145    |

### Mekatronika & Kecerdasan Buatan
