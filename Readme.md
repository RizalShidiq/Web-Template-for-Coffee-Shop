# **Cara Penggunaan dan Kustomisasi**

Anda tidak perlu menjadi seorang programmer untuk mengedit template ini. Cukup ikuti langkah-langkah berikut:

### **Langkah 1: Siapkan Konten Anda**

Sebelum menyentuh kode, siapkan dulu semua materi yang Anda butuhkan:

- Teks: Nama Brand/Usaha, deskripsi singkat, daftar layanan beserta harganya, alamat, dan jam buka.
- Foto: Siapkan beberapa foto terbaik dalam format .jpg atau .png. Pilih satu foto paling ikonik untuk Hero Section dan 4 foto lainnya untuk galeri.
- Info Kontak: Siapkan nomor WhatsApp bisnis Anda.

### **Langkah 2: Buka dan Edit File index.html**

Buka file index.html yang sudah Anda salin menggunakan editor teks sederhana seperti:

- Notepad (di Windows)
- TextEdit (di Mac)
- (Disarankan) Visual Studio Code atau Sublime Text (gratis dan lebih mudah dibaca)

### **Langkah 3: Mengganti Teks (Gunakan Fitur "Cari")**

Gunakan fitur "Cari" (Ctrl + F di Windows atau Cmd + F di Mac) untuk menemukan dan mengganti teks placeholder dengan konten Anda.

- Cari NamaBrand -> Ganti dengan nama usaha Anda.
- Cari Kualitas & Rasa yang Bicara -> Ganti dengan slogan utama Anda.
- Cari Nama Layanan/Produk 1 -> Ganti dengan nama layanan Anda, dan seterusnya.

### **Langkah 4: Mengganti Gambar (Bagian Terpenting)**

Untuk mengganti gambar, Anda memerlukan URL (link) dari gambar tersebut.

- Unggah foto Anda: Unggah semua foto yang sudah Anda siapkan ke layanan hosting gambar gratis seperti ImgBB atau Postimages.
- Salin URL: Setelah diunggah, salin "Direct link" atau "Tautan langsung" dari gambar tersebut.

Sekarang, ganti URL di dalam kode:

- **Untuk Gambar Utama (Hero Section):**

  Cari baris kode yang terlihat seperti ini:

  `<div class="absolute inset-0 bg-cover bg-center bg-no-repeat" style="background-image: url('https://images.unsplash.com/...');">`

  Ganti URL https://images.unsplash.com/... dengan URL gambar utama Anda.

- **Untuk Galeri Foto:**

  Cari tag <img ...> di bagian Galeri:

  `<img src="https://images.unsplash.com/photo-1511..." alt="Galeri 1" ...>`
  `<img src="https://images.unsplash.com/photo-1541..." alt="Galeri 2" ...>`

  Ganti setiap URL di dalam src="..." dengan URL foto galeri Anda.

### **Langkah 5: Mengganti Informasi Kontak dan CTA**

- WhatsApp: Cari https://wa.me/6281234567890 dan ganti 6281234567890 dengan nomor WhatsApp Anda (gunakan format 62, bukan 0).
- Alamat & Jam Buka: Cari "Jalan Usaha Jaya No. 45" dan "Buka Setiap Hari" lalu ganti dengan informasi yang sesuai.

### **Langkah 6: Simpan dan Hosting**

Setelah semua perubahan selesai, simpan file index.html Anda. File ini sekarang sudah siap untuk diunggah. Cukup seret (drag and drop) file index.html ini ke platform hosting seperti Netlify atau Vercel untuk membuatnya online secara gratis.
