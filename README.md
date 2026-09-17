### 💎 Hunter Papan Ultimate: Arena Perangkap Pro 🔮

Hunter Papan Ultimate adalah permainan papan taktis multiplayer berbasis web (*browser-game*) yang menggabungkan elemen intuisi, manajemen risiko, dan kalkulasi matematika ekonomi dinamis. Terinspirasi dari ketegangan navigasi ranjau dan mekanik catur tradisional, game ini menantang hingga 7 pemain untuk memperebutkan skor tertinggi di atas arena grid yang adaptif. 

### 🌟 Fitur Utama Pro

* **Sistem Radar Kedipan Konstan:** Bidak pemain akan mendeteksi ancaman di sekitarnya secara *real-time* melalui frekuensi kecepatan kedipan warna khusus (Merah untuk Bom, Ungu untuk Monster, Hitam-Putih untuk bahaya ganda).
* **Ekonomi Denda Persentase Dinamis:** Berbeda dengan ranjau biasa, entitas Monster akan memotong **50% dari total skor berjalan** pemain aktif. Semakin kaya seorang pemain, semakin besar kerugian risiko yang mereka hadapi!
* **Mekanik Proteksi Skor Terpuruk (*Catch-Up Mechanic*):** Jika skor pemain berada di posisi nol atau minus, denda monster otomatis melunak menjadi denda flat kecil (-10 poin) untuk memberikan peluang adil dalam membalikkan keadaan.
* **Perisai Diskon Golden Buff (40%):** Menginjak petak Buff Emas 👑 memberikan durasi perlindungan selama 4 giliran yang akan memotong nilai denda monster sebesar 40% dari total denda yang seharusnya dibayar.
* **Papan Peringkat Dinamis (*Auto-Sorting Leaderboard*):** Posisi kartu skor pemain pada sisi panel akan otomatis bergeser secara *real-time* mengurutkan pemimpin klasemen dari poin tertinggi ke terkecil.
* **Interaktif Drop-down Log Riwayat Poin:** Pemain dapat mengeklik tombol 📋 Log di samping nama mereka untuk memeriksa seluruh riwayat perolehan poin dan denda dari langkah pertama hingga langkah terakhir secara urutan terbaru.
* **Skalabilitas Grid Arena Dinamis:** Mendukung kapasitas bertarung dari 2 hingga 7 pemain secara bersamaan pada 3 varian ukuran luas peta yang fleksibel.

### 🎮 Aturan & Cara Bermain

1. **Persiapan Awal:** Tentukan jumlah pemain (2-7), pilih luas peta arena, atur persentase kerapatan poin, dan aktifkan sakelar **Blok Finish** jika ingin bermain dalam mode kilat. Klik **Mulai Game Baru**.
2. **Navigasi Langkah:** Klik bidak warna kamu sekali di area *Safe Zone* atau di atas peta, lalu klik petak target valid dalam radius lingkaran putus-putus (maksimal jangkauan 7 langkah) untuk mendarat.
3. **Membaca Sinyal Radar:** Perhatikan kartu peringatan di sisi kanan dan kecepatan kedipan warna pada bidakmu: 

  * 🔴 **Berkedip Merah:** Terdeteksi Bom dalam radius jangkauan dekat.
  * 🔮 **Berkedip Ungu-Hitam:** Terdeteksi Aura Monster Legendaris di sekitar.
  * 💥 **Berkedip Hitam-Putih:** Kondisi kritis! Kamu berada di dalam radius Bom dan Monster secara bersamaan.
4. **Pemicu Domino Sekitar:** Hati-hati, jika kamu memicu monster tersembunyi, ledakan monster tersebut akan otomatis membangunkan monster lain yang berada di dalam radius kotak 3x3 di sekitarnya secara berantai.
5. **Kondisi Akhir Game:** Permainan dinyatakan selesai apabila seluruh blok koin perak 🪙 di peta telah habis dibersihkan, ATAU jika salah satu pemain berhasil menemukan tepat 1 petak bendera **Blok Finish (🏁)** yang tersembunyi. Pemain dengan skor tertinggi di papan *Leaderboard* akhir dinyatakan sebagai Pemenang Utama!

*Proyek ini dibangun menggunakan HTML5 murni, CSS3 Animasi, dan Vanilla JavaScript tanpa library eksternal.*
