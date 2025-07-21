# **Game Interaktif : Warung Sekolah Ceria**

## **1\. Deskripsi**

"Warung Sekolah Ceria" adalah sebuah aplikasi web game simulasi bisnis sederhana yang dirancang untuk memberikan pengalaman belajar mengenai dasar-dasar kewirausahaan. Dalam game ini, pemain akan berperan sebagai seorang siswa yang membuka warung jajanan di sekolah. Pemain dibekali modal awal dan harus mengelola warungnya selama 7 hari (virtual) untuk mendapatkan keuntungan semaksimal mungkin.

Game ini bersifat dinamis, di mana setiap harinya akan ada "Informasi Acara Sekolah" yang berbeda-beda (dihasilkan oleh AI Gemini) yang akan memengaruhi permintaan pelanggan. Pemain harus pintar-pintar membaca situasi, membeli stok barang yang tepat, dan melayani pelanggan untuk mencapai target. Di akhir permainan, pemain akan mendapatkan laporan keuangan lengkap beserta analisis dan saran dari "Mentor Bisnis AI".

## **2\. Tujuan**

Tujuan utama dari game ini adalah sebagai media edukasi yang menyenangkan (edutainment) dengan beberapa target pembelajaran:

- Pengenalan Konsep Bisnis: Memperkenalkan konsep-konsep dasar dalam bisnis seperti modal, stok barang, harga beli (HPP), harga jual, pendapatan, dan keuntungan/kerugian.
- Melatih Pengambilan Keputusan: Mendorong pemain untuk membuat keputusan strategis berdasarkan data (informasi acara harian) untuk memaksimalkan penjualan.
- Dasar-Dasar Manajemen Stok: Mengajarkan pentingnya mengelola persediaan barang, yaitu kapan harus membeli barang baru dan kapan harus menghabiskan stok yang ada.
- Literasi Keuangan Sederhana: Membiasakan pemain dengan laporan keuangan harian dan akhir yang berisi istilah-istilah seperti BEP (Break-Even Point), laba/rugi, dan nilai aset (stok).
- Pemanfaatan Teknologi AI: Menunjukkan salah satu penerapan praktis dari teknologi AI (Gemini) dalam menghasilkan skenario yang dinamis dan memberikan analisis.

## **3\. Untuk Siapa**

Game ini dirancang khusus untuk:

- Siswa Sekolah Dasar (SD): Terutama untuk kelas 4, 5, dan 6 yang mulai diperkenalkan dengan pelajaran ekonomi atau ilmu sosial. Bahasa dan konsep yang digunakan dibuat sesederhana mungkin agar mudah dipahami.
- Guru dan Pendidik: Sebagai alat bantu ajar yang interaktif untuk mata pelajaran IPS, Ekonomi, atau sebagai materi dalam kegiatan ekstrakurikuler kewirausahaan.
- Orang Tua: Yang ingin mengenalkan konsep dasar bisnis dan pengelolaan uang kepada anak-anak mereka dengan cara yang seru dan tidak membosankan.

## **4\. Cara Memainkan**

Berikut adalah langkah-langkah untuk memainkan game "Warung Sekolah Ceria":

1. Mulai Permainan:
    - Buka aplikasi web game.
    - Isi Nama dan Kelas pada kolom yang tersedia.
    - Masukkan Kode API Gemini Anda. Berikut adalah cara mendapatkannya:
        1. Buka situs [Google AI Studio](https://aistudio.google.com/app/apikey).
        2. Masuk dengan Akun Google Anda.
        3. Klik tombol "Create API key in new project".
        4. Salin kode yang muncul di layar Anda.
        5. Tempel (paste) kode tersebut ke dalam kolom "Kode API Gemini" di game.
    - Klik tombol "Mulai Main!".
2. Pahami Aturan:
    - Sebuah popup akan muncul menjelaskan aturan dasar permainan. Baca dengan saksama, lalu klik "Mengerti!".
3. Siklus Permainan Harian (Hari 1 - 7):
    - Lihat Informasi Acara: Klik tombol "Lihat Informasi Acara Sekolah Hari Ini". Anda akan mendapatkan bocoran dari AI tentang acara apa yang sedang berlangsung di sekolah hari itu. Informasi ini adalah kunci untuk menentukan barang apa yang kemungkinan akan laku keras.
    - Belanja di Grosir: Setelah mengetahui informasi acara, pergilah ke bagian "🛒 Grosir". Klik tombol "Beli" pada barang-barang yang menurut Anda akan laku. Setiap pembelian akan mengurangi modal Anda. Barang yang dibeli akan masuk ke "🏠 Warungku".
    - Mulai Berjualan: Jika sudah siap dengan stok barang, klik tombol "Mulai Layani Pelanggan".
    - Layani Pelanggan: Pelanggan akan datang satu per satu. Permintaan mereka akan muncul di layar. Jika stok Anda tersedia, penjualan akan berhasil dan modal Anda akan bertambah. Jika stok habis, Anda akan kehilangan kesempatan penjualan.
    - Laporan Harian: Setelah semua pelanggan selesai dilayani, hari akan berakhir. Anda akan melihat popup Laporan Harian yang merinci total penjualan, keuntungan/kerugian, dan sisa stok. Anda bisa men-download laporan ini dalam format CSV.
4. Lanjut ke Hari Berikutnya:
    - Klik "Lanjut ke Hari Berikutnya" untuk memulai siklus baru. Ulangi langkah ke-3 hingga hari ke-7.
    - Anda dapat melihat ringkasan laporan hari-hari sebelumnya di bagian "Arsip Laporan Harian".
5. Akhir Permainan (Setelah Hari ke-7):
    - Setelah menyelesaikan penjualan di hari ke-7, permainan akan berakhir.
    - Anda akan dibawa ke layar Laporan Akhir yang merangkum seluruh performa bisnis Anda selama 7 hari, termasuk total laba/rugi dan kapan Anda mencapai BEP.
    - Di bagian bawah, akan ada "Kesimpulan dari Mentor Bisnis AI" yang memberikan analisis dan saran berdasarkan performa penjualan Anda.
6. Download Laporan Akhir:
    - Anda memiliki opsi untuk men-download laporan akhir yang komprehensif dalam format HTML (untuk tampilan yang rapi dan siap cetak) atau CSV (untuk diolah lebih lanjut di spreadsheet).
    - Klik "Main Lagi" untuk mengulang permainan dari awal.
