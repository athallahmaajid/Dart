# Contributing

**Contributor**

Kami sangat senang anda telah ikut berkontribusi dalam implementasi algoritma, struktur data atau memperbaiki error serta merilis implementasi materi basic learning Dart.

Semua orang boleh ikut berkontribusi walaupun hal kecil, dengan ketentuan sebagai berikut:

- Hasil pekerjaan anda adalah buatan anda sendiri dan tidak ada hak cipta dari orang lain, jika kami menemukan kesamaan maka kami tidak `merged`.
- Hasil kerja anda akan berlisensi [MIT](LICENSE) ketika permintaan pull anda sudah di merged
- Hasil kerja anda wajib mengikuti standar dan style koding dari kami (lihat bagian [Standar penulisan](#standar-penulisan))
- Untuk Flutter, hanya gunakan package dari [pub.dev](https://pub.dev) jika memang membutuhkan. Sebelumnya silahkan diskusi di [issue](https://github.com/bellshade/Dart/issues)
- Untuk Dartlang, hindari penggunaan library/package pada koding (jika dibutuhkan, silahkan diskusi di [issue](https://github.com/bellshade/JavascriptAlgorithm/issues))

## Kategori yang ada

**1. Basic Learning**

Basic learning adalah kumpulan implementasi kode materi mendasar dan fundamental untuk pemrograman Dart. Dikemas dengan keterangan kode yang mudah di mengerti sehingga bisa dijadikan referensi untuk kalian yang belajar pemrograman Dart.
> Semua implementasi kode untuk Basic Learning bisa ditemukan di **`/dartlang/basics`** 

**2. Algoritma**

Algoritma adalah langkah-langkah untuk menyelesaikan suatu pekerjaan dimana terdiri dari 3 bagian utama, yaitu:

- Input/masukan, sebelum menjalankan sebuah algoritma maka hal yang pertama harus dilakukan adalah menerima masukan. Input dapat berasal dari pengguna ataupun dari langkah sebelumnya.
- Proses, bagian utama dari algoritma yang melakukan pengolahan input yang akan menghasilkan output.
- Output/keluaran, output adalah hasil dari bagian proses. Output ini juga bisa digunakan untuk langkah selanjutnya (jika masih ada).

Algoritma harus dikemas sedemikian rupa sehingga memudahkan pembaca untuk memasukkannya ke dalam program yang lebih besar.

Algoritma harus memiliki:

- memiliki nama _class_ dan fungsi intuitif yang memperjelas tujuannya bagi pembaca
- fleksibel untuk mengambil nilai input yang berbeda
- memiliki dokumentasi penjelasan yang jelas dan/atau URL ke materi sumber
- gunakan hasil kembalian / _return_ daripada langsung mencetak ke layar

> Semua implementasi kode untuk Algorithm bisa ditemukan di **`/dartlang/algorithms`** 

## Standar Penulisan

Gunakan standar penulisan yang sudah ditentukan oleh Dart, dan direkomendasikan menggunakan fitur code formatter dari Flutter.

Untuk dokumentasi mengenai standar penulisan bisa dilihat di link berikut :
[1. Overview Bahasa Dart](https://dart.dev/guides/language/effective-dart)
[2. Gaya Penulisan Dart](https://dart.dev/guides/language/effective-dart/style)
[3. Pembuatan Dokumentasi Kode Dart](https://dart.dev/guides/language/effective-dart/documentation)
[4. Penggunaan Bahasa Dart](https://dart.dev/guides/language/effective-dart/usage)
[5. Penulisan Konsisten Pada Bahasa Dart](https://dart.dev/guides/language/effective-dart/design)


## Berkontribusi

**Pull request yang baik**

- lakukan fork pada repository ini
- setelah melakukan fork anda dibebaskan untuk mengubah atau menambah algoritma
  - untuk pull request "mengubah" diusahakan anda menerapkan algoritma yang lebih baik dan lebih mudah
- setelah mengubah, menambah, atau perbaikan dokumentasi, usahakan anda membuat branch baru

```bash
git checkout -b <branch_name>
git add .
git commit -m "add: menambahkan algoritma baru"
```

- lakukan push ke branch anda dan kemudian open pull request

**saran pesan commit**

- `add` untuk menambah algoritma atau tambahan lainnya
- `fix` untuk mengubah algoritma yang sudah ada atau memperbaiki
- `docs` untuk mengubah atau membuat dokumentasi
- `style` untuk mengubah atau memperbaiki style kode untuk contohnya bisa dilihat pada commit yang diatas

pull request `merged` jika:

- mengikuti standar dan arahan dari `CONTRIBUTING.md`
- lulus test dan cek dari beberapa test yang sudah kami siapkan

**tambahan**

- jika ada kendala atau masalah dalam pull request, anda bisa laporkan masalah pada [issue](https://github.com/bellshade/Dart/issues)
- jika ada test yang tidak lewat atau gagal, kami akan mengecek kembali perubahan.

untuk pull request kami sarankan untuk menjelaskan secara detail yang anda ubah atau tambahkan, dan bersikap sopan, serta selalu berterima kasih, itu salah satu bentuk tata krama yang baik terhadap sesama contributor dan programmer lainnya. Terima kasih sudah berkontribusi di **Bellshade/Dart**