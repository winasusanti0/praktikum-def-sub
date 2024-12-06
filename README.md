# WINA SUSANTI R - 352310473 
# Penjelasan Perintah Program Def/Sub

## 1. Struktur Perintah Program

Program ini dibuat untuk mengelola data mahasiswa, dengan fokus pada operasi dasar seperti penambahan, penampilan, pengubahan, dan penghapusan data. Berikut ini tampilan perintah program di phyton :

![perintah program 1](https://github.com/user-attachments/assets/7c73f968-fd40-4bb3-b538-b5e123be91c8)
![perintah program 2](https://github.com/user-attachments/assets/6bbda5a4-9962-4a14-8527-a3bdafb4dddf)

## 2. Komponen Program

### Daftar Mahasiswa
Variabel `mahasiswa` merupakan list kosong yang akan menampung data mahasiswa. Setiap mahasiswa disimpan sebagai dictionary yang memiliki dua kunci: `nama` dan `nilai`.

### Fungsi `tambah(nama, nilai):`
Fungsi ini digunakan untuk menambahkan data mahasiswa baru ke dalam daftar. 
- **Parameter:** 
  - `nama`: Nama mahasiswa.
  - `nilai`: Nilai yang diperoleh.
- **Proses:** 
  Membuat dictionary baru dengan kunci `nama` dan `nilai`, lalu menambahkannya ke dalam list `mahasiswa`. Fungsi ini juga mencetak pesan konfirmasi setelah berhasil.

### Fungsi `tampilkan():`
Fungsi ini berfungsi untuk menampilkan semua data mahasiswa yang ada dalam daftar.
- **Proses:** 
  Memeriksa apakah list `mahasiswa` kosong. Jika ya, mencetak pesan "Daftar mahasiswa kosong". Jika tidak, mencetak semua nama dan nilai mahasiswa dengan menggunakan loop.

### Fungsi `hapus(nama):`
Fungsi ini digunakan untuk menghapus data mahasiswa berdasarkan nama.
- **Parameter:** 
  - `nama`: Nama mahasiswa yang ingin dihapus.
- **Proses:** 
  Menggunakan list comprehension untuk membuat list baru yang berisi semua mahasiswa kecuali yang memiliki nama sesuai dengan `nama` yang diberikan. Kemudian, list baru ini disimpan kembali dalam variabel `mahasiswa`, dan mencetak pesan konfirmasi.

### Fungsi `ubah(nama, nilai_baru):`
Fungsi ini berfungsi untuk mengubah nilai mahasiswa berdasarkan nama.
- **Parameter:** 
  - `nama`: Nama mahasiswa yang nilainya ingin diubah.
  - `nilai_baru`: Nilai baru yang akan diberikan.
- **Proses:** 
  Mencari mahasiswa di dalam list `mahasiswa`. Jika ditemukan, nilai mahasiswa tersebut akan diubah dan mencetak pesan konfirmasi. Jika tidak ditemukan, akan mencetak pesan bahwa data tidak ada.

## 3. Contoh Penggunaan

Di bagian akhir program, terdapat contoh penggunaan untuk fungsi-fungsi yang telah didefinisikan:
1. Program menambahkan lima mahasiswa beserta nilai mereka ke dalam daftar.
2. Fungsi `tampilkan()` dipanggil untuk menunjukkan semua data mahasiswa.
3. Fungsi `ubah()` digunakan untuk mengubah nilai dari mahasiswa tertentu.
4. Fungsi `hapus()` digunakan untuk menghapus data mahasiswa sesuai nama.
5. Fungsi `tampilkan()` dipanggil kembali untuk menunjukkan daftar mahasiswa setelah adanya perubahan dan penghapusan.

## 4. Hasil tampilan Perintah program F5 (RUN) : 

![finishing](https://github.com/user-attachments/assets/9551c252-3794-41c3-a258-73ae9bc744d7)

## 5. Flowchart proses perintah program : 

![flowchart](https://github.com/user-attachments/assets/52cd3297-d69f-4335-9de9-416dcb75d77c)

