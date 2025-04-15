# Capstone-2 Optimalisasi Diskon guna Memaksimalkan Laba Perusahaan (Case Study SaaS) 

## Latar Belakang
SaaS (perangkat lunak sebagai layanan) adalah model bisnis yang mendistribusikan perangkat lunak melalui internet, dengan fokus pada penyediaan layanan berkualitas tinggi kepada pelanggan. Keberhasilannya bergantung pada konsistensi produk dan harga, efisiensi operasional, strategi negosiasi harga, dan loyalitas pelanggan. Diskon adalah pendorong yang kuat dalam strategi penjualan dan pendapatan tersebut, jika digunakan dengan benar, diskon dapat meningkatkan konversi, loyalitas pelanggan, dan pangsa pasar. Namun, diskon yang tidak terstruktur atau berlebihan sering kali menyebabkan erosi margin, praktik penetapan harga yang tidak konsisten, dan masalah profitabilitas jangka panjang. Proyek ini menyelidiki perilaku diskon di berbagai segmen pelanggan, industri, produk, dan tingkat nilai (CLTV) di berbagai wilayah untuk mengembangkan kebijakan diskon yang terukur dan berbasis data.

## Definisi Masalah
Perusahaan tidak memiliki transparansi atas:
- Bagaimana diskon memengaruhi profitabilitas berbagai jenis pelanggan?
- Kelompok pelanggan, produk, dan ukuran bisnis mana yang berkontribusi terhadap kerugian?
- Di mana menarik garis antara transaksi yang berorientasi nilai atau berisiko terhadap margin?

Tanpa aturan yang jelas pada diskon:
- Keuntungan rentan terhadap keputusan penetapan harga yang bersifat impromptu (tanpa perencanaan) 
- Pelanggan dengan CLV tinggi tidak diperlakukan secara berbeda dari pelanggan dengan nilai rendah
- Tim penjualan tidak memiliki panduan terstruktur tentang ambang batas aman untuk laba margin

## Rekomendasi
- Implementasi kebijakan diskon yang telah dibuat ke dalam alur kerja CRM
- Pembatasan diskon pada wilayah, segmentasi, dan produk yang riskan terhadap margin 
- Mengubah pendekatan "one-product discount" menjadi penawaran-penawaran tambahan gratis yang menarik 
- Membuat promo bundling (antar produk atau minimum kuantitas pada suatu produk)
- Pengenalan ambang batas persetujuan (co: diskon >20% → membutuhkan tanda tangan manajer)
- Memberikan diskon berdasarkan CLV sehingga hubungan dengan loyal customer bisa terawat tanpa over-discounting pada customer yang tidak loyal
- Memantau dampak kebijakan setiap tiga bulan dan menyesuaikan berdasarkan pergeseran margin sehingga kebijakan diskon bersifat konsisten namun tetap adaptif
- Menghitung win rate vs discount sebelum memberikan tingkat diskon yang melebihi kebijakan diskon guna menilai sepadan atau tidaknya konversi dari transaksi tersebut
- Membuat simulator diskon untuk menguji skenario “what-if”

## Kesimpulan

Proyek ini berhasil:
- Mengidentifikasi ambang batas di mana diskon mengikis margin
- Menyoroti kombinasi risiko tinggi (misalnya SMB + CLV rendah + transaksi besar)
- Ilustrasi kinerja melalui heatmap pada segmen × CLV × ukuran transaksi
- Mengembangkan strategi diskon berjenjang dan bersyarat berdasarkan data riil
- Penjelasan tentang anomali untuk menghindari salah tafsir

Temuan utama adalah:
- Diskon di atas 45% sering kali menyebabkan kerugian  
- Pelanggan dengan CLV tinggi tidak kebal terhadap transaksi yang buruk ketika ukuran transaksi dan diskon terakumulasi sehingga tetap dibutuhkan batas atas yang konkrit
- Beberapa segmen, industri, dan wilayah (UKM/SMB, Tech, wilayah APJ) membutuhkan batas diskon yang lebih ketat  



