## 1. Penjelasan Konsep dasar Array
Array adalah sekumpulan data yang menyimpan banyak data dalam satu wadah dengan tipe variabel yang sama, lalu disusun secara berurutan agar mudah dipahami dan terlihat sederhana. Setiap data memiliki indeks supaya mudah dihitung dimulai dari urutan awal pada indeks nya. Array memiliki indeks yang dimulai dari 0 sehingga kita dapat menghitung data secara terstruktur dan berurutan. Pada Python, tugas ini kita menggunakan Array untuk mencari nilai tertinggi dan terendah, dengan demikian kita menggunakan array lebih mudah dalam menentukan jumlah data yang akan kita hitung.


## Menganalisis Kelebihan dan kekurangan 

### Kelebihan✅
- Mudah digunakan
  artinya kita dapat mudah menggunakan nya secara sederhana, dan mudah di pahami. Sehingga sangat cocok untuk pemula yang ingin memulai belajar bahasa pemrograman.
- Mengggunakan (List Array)
  jika menggunakan list array, maka data didalam nilai tersimpan dalam satu variabel dan dapat mudah diolah.
- Mengakses Data dengan cepat
 didalam array, Tentu Array memakai *list* yang dimana kita dapat langsung mengambil data tanpa mencuri satu per satu dan hanya memanggil indeksnya saja.
- Data bersifat Final (jumlahnya tetap)
 jika kita membuat daftar nilai tetap dan tidak berubah sewaktu waktu, maka array sangat efektif digunakan.


### Kekurangan❌
- Kurangnya fleksibilitas.
 Jika kita ingin merubah jumlah data nya, maka harus disesuaikan ulang kembali dari awal.
- Jumlah Data Statis
  hanya bisa menginput 10 nilai dan tentunya tidak fleksibel.
- Memakan banyak memori.
  Disetiap array yang kita buat misal 100, hanya sedikit yang terpakai sekitar 20 saja, alhasil sisanya tetap terbuang.
- Ukuran Mutlak. Artinya jika data pada Array kurang, maka terdapat ruang kosong. Jika lebih, maka array tidak muat, dan harus membuat baru lagi.


## 2. Screenshot Hasil Eksekusi

<img width="272" height="233" alt="Screenshot 2026-03-25 193441" src="https://github.com/user-attachments/assets/5e38ea3a-4dc5-42c7-b824-f48ba466aff8" />

## Output teks di terminal

<img width="680" height="108" alt="Screenshot 2026-03-25 193506" src="https://github.com/user-attachments/assets/b2856a89-bc28-4bbe-b77d-96ef04c1500c" />

## Grafik Bar

<img width="669" height="519" alt="Screenshot 2026-03-25 193539" src="https://github.com/user-attachments/assets/e46d7316-cef2-42aa-ae7e-871491acfc4f" />


## 3. Analisis Kompleksitas 


| No | Kode Program                | Proses yang Terjadi                            | Time Complexity | Space Complexity |
| -- | --------------------------- | ---------------------------------------------- | --------------- | ---------------- |
| 1  | `nilai = []`                | Inisialisasi array kosong                      | O(1)            | O(1)             |
| 2  | `for i in range(10):`       | Perulangan untuk input 10 data                 | O(n)            | O(n)             |
| 3  | `input()`                   | Mengambil input dari user                      | O(1) per input  | O(1)             |
| 4  | `nilai.append(n)`           | Menambahkan nilai ke array                     | O(1) amortized  | O(n)             |
| 5  | `print(nilai)`              | Menampilkan seluruh isi array                  | O(n)            | O(1)             |
| 6  | `max(nilai)`                | Mencari nilai terbesar (menelusuri semua data) | O(n)            | O(1)             |
| 7  | `min(nilai)`                | Mencari nilai terkecil (menelusuri semua data) | O(n)            | O(1)             |
| 8  | `sum(nilai)`                | Menjumlahkan semua elemen                      | O(n)            | O(1)             |
| 9  | `len(nilai)`                | Menghitung jumlah elemen                       | O(1)            | O(1)             |
| 10 | `rata_rata = sum/len`       | Operasi pembagian                              | O(1)            | O(1)             |
| 11 | `for n in nilai:`           | Perulangan untuk cek kelulusan                 | O(n)            | O(1)             |
| 12 | `if n >= 60`                | Pengecekan kondisi                             | O(1) per data   | O(1)             |
| 13 | `jumlah_lulus += 1`         | Penambahan nilai counter                       | O(1)            | O(1)             |
| 14 | `len(nilai) - jumlah_lulus` | Menghitung jumlah tidak lulus                  | O(1)            | O(1)             |
| 15 | `plt.bar()`                 | Menampilkan grafik batang (2 data saja)        | O(1)            | O(1)             |
| 16 | `plt.pie()`                 | Menampilkan grafik pie berdasarkan hasil       | O(n)*           | O(1)             |





## 4. 📘Refleksi Pembelajaran Array

- Pada pengetahuan dasar saya memahami bahwa dalam suatu data, terdapat posisi pada data disebut INDEX, dimana fungsinya adalah memudahkan kita dalam mengambil dan mengubah data dengan cepat dan tepat.
- Didalam Python saya memanfaatkan fungsi python seperti Max(), Min(), dan Sum() untuk mengolah data dengan cepat tanpa kita harus menghitung manual lagi.
- Tentu tak hanya itu saja, adapun kekurangan dasar yang saya ketahui yaitu ukuran nya yang mutlak atau tidak fleksibel dan hanya menyimpan satu jenis data saja.
- Dengan adanya tugas ini kita tak hanya membuat saja tetapi mendapatkan informasi output data yang kita buat dalam bentuk grafik ,sehingga dapat membantu memahami informasi yang diberikan secara visual atau gambar dengan lebih jelas.
- Kedepan nya saya akan lebih banyak latihan membuat program kecil-kecilan yang kompleks, dari Tugas ini, saya bisa meningkatkan kemampuan logika kita, dan dapat memecahkan masalah dengan baik.








  


