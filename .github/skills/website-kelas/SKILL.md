---
name: website-kelas
description: "Membuat atau memperbarui website kelas yang berisi daftar siswa, mata pelajaran, jadwal piket, dan tugas. Gunakan saat diminta membuat halaman informasi kelas, dashboard kelas, atau portal kelas sederhana dengan HTML, CSS, dan JavaScript."
argument-hint: "Nama kelas, data siswa, mata pelajaran, jadwal piket, dan daftar tugas"
---

# Website Kelas

## Tujuan

Hasilkan website kelas yang rapi, mudah dipindai, responsif di ponsel dan desktop, serta menampilkan empat informasi utama: siswa, mata pelajaran, jadwal piket, dan tugas.

## Checklist

1. Baca file dan struktur project yang sudah ada sebelum mengubahnya. Pertahankan teknologi dan gaya yang digunakan; untuk project HTML sederhana, utamakan `index.html` dan aset lokal yang sudah tersedia.
2. Tetapkan identitas kelas dari konteks pengguna: nama kelas, tahun ajaran, wali kelas, dan informasi kontak hanya jika diberikan. Jangan mengarang data pribadi.
3. Buat navigasi atau susunan bagian yang jelas untuk:
   - daftar siswa, dengan nomor dan nama;
   - mata pelajaran, dengan guru atau keterangan jika tersedia;
   - jadwal piket, dengan hari dan anggota;
   - tugas, dengan mata pelajaran, tenggat, status, dan deskripsi singkat jika tersedia.
4. Gunakan data terstruktur di JavaScript bila data perlu ditampilkan berulang, sehingga perubahan daftar tidak memerlukan duplikasi markup.
5. Tambahkan interaksi yang relevan dan sederhana, seperti pencarian siswa, filter status tugas, tab bagian, atau penanda tugas selesai. Jangan menambahkan fitur login atau backend tanpa diminta.
6. Pastikan tampilan responsif: tabel boleh berubah menjadi kartu atau dapat digulir secara horizontal pada layar kecil; teks, tombol, dan ikon tidak boleh bertumpuk atau terpotong.
7. Gunakan HTML semantik, label yang jelas, fokus keyboard yang terlihat, kontras warna yang cukup, dan atribut aksesibilitas untuk kontrol interaktif.
8. Tambahkan keadaan kosong yang informatif jika salah satu daftar belum memiliki data. Hindari data contoh yang tampak sebagai data nyata tanpa penanda.
9. Validasi dengan membuka halaman di browser dan menguji navigasi, pencarian atau filter, perubahan status tugas, serta tampilan desktop dan mobile. Perbaiki error console dan tautan atau tombol yang tidak berfungsi.

## Kriteria Selesai

- Empat bagian informasi utama tampil dan dapat dipahami tanpa penjelasan tambahan.
- Data mudah diperbarui dan tidak berulang secara tidak perlu.
- Layout tetap terbaca pada desktop dan mobile.
- Interaksi yang ditambahkan bekerja dengan mouse dan keyboard.
- Tidak ada data pribadi atau fakta kelas yang dibuat-buat.
- Tidak ada error JavaScript atau elemen interaktif yang mati.
