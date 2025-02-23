# Praktikum-4
| Nama        | Abdullah Husin |
|--------------|------------|
| NIM        | 09030582327103 |
| Program Studi | Teknik Komputer |

# tugas!

Proses Input Output I/O

1. Lihat daftar secara lengkap pada direktori aktif, belokkan tampilan standard output ke file baru.
![Gambar WhatsApp 2025-02-24 pukul 02 51 49_910346a4](https://github.com/user-attachments/assets/c610b3e9-8200-4952-a83d-6398669883be)


Menampilkan isi direktori latihan5 secara lengkap dan menyimpannya ke daftar_latihan5.txt.

2. Lihat daftar secara lengkap pada direktori /etc/paswd, belokkan tampilan standard output ke file baru tanpa menghapus file baru sebelumnya.
![Gambar WhatsApp 2025-02-24 pukul 02 51 49_ed6fab20](https://github.com/user-attachments/assets/36c95156-e0a1-4ff9-95c4-26efe5485ee6)


Menyimpan informasi file /etc/passwd ke dalam daftar_passwd.txt tanpa menghapus data lama.

3. Urutkan file baru dengan cara membelokkan standard input.

![Gambar WhatsApp 2025-02-24 pukul 02 51 50_6d0a9f3b](https://github.com/user-attachments/assets/f25ea2e5-db3d-49ca-a771-848080c79cd1)

Mengurutkan isi daftar_latihan5.txt tanpa menyimpannya ke file baru.

4. Urutkan file baru dengan cara membelokkan standard input dan standard output ke file baru.urut.
![Gambar WhatsApp 2025-02-24 pukul 02 53 21_025d6bdc](https://github.com/user-attachments/assets/f137a1cf-08bf-4b72-a2dc-f9d2556aba91)

Mengurutkan isi daftar_latihan5.txt dan menyimpan hasilnya ke baru.urut.

5. Buatlah direktori latihan6 sebanyak 2 kali dan belokkan standard error ke file rmdirerror.txt.
![Gambar WhatsApp 2025-02-24 pukul 02 53 21_92144559](https://github.com/user-attachments/assets/2f860fd2-26e9-4eae-8aa0-be0991cfbc48)


Direktori latihan6 dibuat sekali. Jika Percobaan gagal karena latihan6 sudah ada, dan error maka disimpan ke rmdirerror.txt.

6. Urutkan kalimat berikut : Jakarta Bandung Surabaya Padang Palembang Lampung Dengan menggunakan notasi here document (<@@@ …@@@)
![Gambar WhatsApp 2025-02-24 pukul 02 53 22_9ff6f27a](https://github.com/user-attachments/assets/5078d03e-22a3-44fb-9548-a90e9af4e8ce)


Memasukkan daftar kota secara manual dan mengurutkannya langsung tanpa menyimpan ke file.

7. Hitung jumlah baris, kata dan karakter dari file baru.urut dengan menggunakan filter dan tambahkan data tersebut ke file baru.

![Gambar WhatsApp 2025-02-24 pukul 02 54 03_3460978d](https://github.com/user-attachments/assets/8faff66f-0ce9-42c6-bac8-cf2cfb9372d9)

Menghitung jumlah baris, kata, dan karakter dalam baru.urut. Menambahkan hasilnya ke hasil_wc.txt.

8. Gunakan perintah di bawah ini dan perhatikan hasilnya. $ cat /etc/passwd | sort | pr –n | grep tty03 $ find /etc –print | head $ head /etc/passwd | tail –5 | sort
![Gambar WhatsApp 2025-02-24 pukul 02 54 05_9b6f511e](https://github.com/user-attachments/assets/bb6da2f4-c1db-43c0-9011-8ced5a07cddd)


Perintah ke 1 untuk Menampilkan isi /etc/passwd, mengurutkannya, lalu mencari entri dengan tty03. Perintah ke 2 untuk Menampilkan daftar file dalam /etc, tetapi hanya 10 baris pertama. dan Perintah ke 3 untuk Mengambil 10 baris pertama dari /etc/passwd, lalu menyaring 5 baris terakhir sebelum mengurutkannya.

9. Gunakan perintah $ who | cat | cat | sort | pr | head | cat | tail dan perhatikan hasilnya.

![Gambar WhatsApp 2025-02-24 pukul 02 54 05_c3eb3807](https://github.com/user-attachments/assets/949ef92a-3d9d-4f7b-b1b9-c077780401ce)

- who > Menampilkan daftar pengguna yang sedang login. tamam seat0 2025-02-23 19:11 (login screen) → Pengguna tamam login di seat0 pada 19:11. tamam tty2 2025-02-23 19:11 (tty2) → Pengguna tamam login di tty2 pada 19:11.

cat | cat >Tidak mengubah output, hanya meneruskan data yang sama. sort > Mengurutkan daftar login berdasarkan abjad, tapi karena hanya ada satu user tamam, urutan tetap sama. pr > Memformat output agar terlihat seperti dokumen dengan tambahan "Page 1" dan timestamp 2025-02-21 22:53. head > Mengambil beberapa baris pertama dari output. cat | tail > tail menampilkan bagian akhir dari hasil sebelumnya, sehingga tetap menampilkan seluruh output jika jumlah baris tidak terlalu banyak.

KESIMPULAN
Melalui latihan-latihan ini, pengguna dapat memahami dan mempraktikkan konsep dasar pengalihan input dan output di sistem operasi, yang esensial untuk pengelolaan file dan automasi tugas sehari-hari.
