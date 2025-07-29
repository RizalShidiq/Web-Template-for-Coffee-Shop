Cara Penggunaan dan Kustomisasi (Langkah-demi-Langkah):



Langkah 1: Siapkan Konten Anda

Sediakan materi yang dibutuhkan:

* Teks: Nama Brand/UMKM, tagline, deskripsi singkat, 3 fitur/keunggulan utama beserta penjelasannya, dan alamat (jika ada).
* Info Kontak: Nomor WhatsApp yang aktif.



Langkah 2: Buka dan Edit File index.html

* Buka file index.html dengan editor teks seperti Notepad, atau lebih baik lagi menggunakan Visual Studio Code untuk kemudahan membaca kode.



Langkah 3: Mengganti Teks Utama

* Gunakan fitur "Cari" (Ctrl + F atau Cmd + F) untuk menemukan dan mengganti teks berikut:
* Cari Nama UMKM Anda -> Ganti dengan nama bisnis Anda.
* Cari Solusi Inovatif untuk Kebutuhan Anda -> Ganti dengan tagline atau judul utama Anda.
* Cari paragraf di bawahnya -> Ganti dengan deskripsi singkat bisnis Anda.



Langkah 4: Menyesuaikan Fitur Unggulan

* Cari bagian dengan judul Kenapa Memilih Kami?.
* Di bawahnya, ada tiga kolom. Ganti judul seperti Kualitas Terjamin, Pelayanan Cepat, dan Harga Terjangkau dengan tiga keunggulan utama bisnis Anda.
* Ganti juga teks deskripsi di bawah setiap judul fitur tersebut.



Langkah 5: Mengganti Ikon (Opsional, tapi direkomendasikan)

* Ikon yang ada saat ini adalah kode SVG. Anda bisa menggantinya dengan mudah agar lebih sesuai dengan fitur Anda.
* Kunjungi situs Heroicons (dibuat oleh pengembang Tailwind CSS).
* Cari ikon yang paling mewakili keunggulan Anda (contoh: cari "truck" untuk pengiriman, "shield-check" untuk garansi).
* Klik ikon yang Anda suka, lalu pilih opsi "Copy SVG".
* Kembali ke file index.html Anda, temukan blok kode <svg> ... </svg> yang ingin Anda ganti, lalu hapus kode SVG lama dan tempel (paste) kode SVG baru yang sudah Anda salin.



Langkah 6: Mengatur Tombol Call to Action (CTA)

* Cari tautan <a> dengan tulisan "Chat via WhatsApp".
* Di dalamnya, Anda akan melihat href="https://wa.me/6281234567890?text=...".
* Ganti nomor: Ubah 6281234567890 menjadi nomor WhatsApp Anda (awali dengan 62).
* (Opsional) Ganti teks otomatis: Anda bisa mengubah pesan otomatis dengan mengedit teks setelah ?text=. Misalnya: ?text=Halo,%20saya%20mau%20tanya%20tentang%20layanan%20Anda. (Gunakan %20 sebagai pengganti spasi).



Langkah 7: Simpan dan Hosting

* Setelah semua perubahan selesai, simpan file index.html. File ini sudah siap untuk di-hosting. Anda bisa langsung mengunggahnya ke Netlify, Vercel, atau GitHub Pages untuk membuat website Anda online.
