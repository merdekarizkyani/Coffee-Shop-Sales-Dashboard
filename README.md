# Dashboard Penjualan Coffee Shop
Dashboard interaktif untuk menganalisis kinerja penjualan kedai kopi, mencakup total transaksi, pendapatan, keuntungan, kategori produk, karakteristik pelanggan, metode promosi, keanggotaan, dan perilaku kunjungan. Proyek ini bertujuan mengubah data transaksi menjadi informasi visual yang mudah dipahami untuk mendukung evaluasi kinerja bisnis dan pengambilan keputusan.

<img width="1212" height="692" alt="Dashboard Coffeeshop" src="https://github.com/user-attachments/assets/2746e085-ffed-4756-aba8-298b82edbeb4" />

## Pertanyaan Bisnis

| Dimensi | Pertanyaan Bisnis |
| :--- | :--- |
| **Penjualan** | 1. Berapa total penjualan dan keuntungan yang dihasilkan?<br>2. Bagaimana kinerja transaksi berdasarkan bulan? |
| **Produk** | 1. Kategori produk apa yang paling banyak terjual?<br>2. Bagaimana distribusi penjualan antar kategori produk? |
| **Pelanggan** | 1. Bagaimana distribusi transaksi berdasarkan gender?<br>2. Seberapa besar partisipasi pelanggan dalam program membership? |
| **Promosi** | 1. Metode promosi apa yang memiliki jumlah transaksi tertinggi? |
| **Prilaku Pelanggan** | 1. Bagaimana frekuensi kunjungan pelanggan?<br>2. Berapa lama pelanggan menghabiskan waktu di kedai kopi? |

## Visualisasi Dashboard
Dashboard dilengkapi dengan beberapa visualisasi utama untuk mempermudah analisis:
1. KPI Summary – Menampilkan jumlah transaksi, total penjualan, total item terjual, dan keuntungan.
2. Donut Chart – Menampilkan distribusi transaksi berdasarkan gender.
3. Bar Chart – Membandingkan jumlah transaksi berdasarkan kategori produk.
4. Pie Chart – Menampilkan frekuensi kunjungan pelanggan.
5. Bar Chart – Membandingkan metode promosi berdasarkan jumlah transaksi.
6. Bar Chart – Menampilkan jumlah pelanggan berdasarkan status membership.
7. Pie Chart – Menampilkan distribusi durasi kunjungan pelanggan.

## Pembersihan dan persiapan Data
1. Sebelum membuat visualisasi, dataset dipersiapkan untuk memastikan data lebih konsisten, terstruktur, dan siap dianalisis menggunakan Power Query di Microsoft Power BI.
2. Pemeriksaan Data: Memeriksa struktur dataset, jumlah baris, kolom, serta kelengkapan data.
3. Penanganan Missing Values: Mengidentifikasi nilai kosong pada kolom penting seperti ID, Timestamp, Category, dan Method. Baris yang tidak lengkap perlu divalidasi sebelum digunakan dalam analisis.
4. Pemeriksaan Duplikasi: Memeriksa duplikasi data dan memastikan setiap transaksi memiliki identitas yang sesuai.
5. Validasi Tipe Data: Menyesuaikan tipe data, seperti Timestamp menjadi Date, Income menjadi Whole Number, Qty menjadi Whole Number, dan kolom penilaian menjadi Whole Number.
6. Standardisasi Data: Memeriksa konsistensi penulisan kategori, gender, metode promosi, membership, serta kategori durasi dan frekuensi kunjungan.
7. Transformasi Waktu: Mengekstrak bulan dari Timestamp untuk mendukung analisis transaksi bulanan dan menyediakan filter berdasarkan bulan.
8. Persiapan Metrik: Menyiapkan pengukuran jumlah transaksi, total item, dan distribusi kategori menggunakan kolom yang sesuai. Perhitungan penjualan dan keuntungan perlu mengikuti definisi serta rumus yang digunakan pada model Power BI.

## Tools yang digunakan
1. Microsoft Power BI – Power Query untuk persiapan data, data modeling, DAX untuk perhitungan metrik, serta pembuatan visualisasi dan dashboard interaktif.
2. Microsoft Excel – Penyimpanan dan sumber dataset awal.
3. GitHub – Dokumentasi proyek dan publikasi portofolio analisis data.

## Insight Bisnis Utama (Key Business Insights)
Berdasarkan angka yang ditampilkan pada dashboard, berikut beberapa temuan utama:
1. Kinerja Penjualan: Dashboard menampilkan total penjualan sebesar Rp10.710.000, keuntungan Rp4.284.000, dan 112 transaksi.
2. Kategori Produk: Coffee mendominasi dengan 60 transaksi, diikuti Non Coffee sebanyak 23 transaksi.
3. Karakteristik Pelanggan: Pelanggan perempuan menyumbang 58 transaksi (51,79%), sedangkan laki-laki menyumbang 54 transaksi (48,21%).
4. Efektivitas Promosi: Social Media mencatat jumlah transaksi tertinggi, yaitu 60 transaksi. Namun, efektivitas promosi terhadap pendapatan dan keuntungan masih perlu dianalisis lebih lanjut.
5. Program Membership: Sebanyak 60 transaksi berasal dari pelanggan berstatus membership Yes, dibandingkan 52 transaksi berstatus No.
6. Frekuensi Kunjungan: Kategori Monthly mendominasi dengan 75 transaksi (66,96%), menunjukkan tingginya kontribusi pelanggan yang berkunjung setiap bulan.
7. Durasi Kunjungan: Durasi Below 30 mins merupakan kategori terbesar dengan 63 transaksi (56,25%).

## Rekomendasi Strategis 
1. Mengoptimalkan Promosi Digital: Evaluasi kampanye Social Media berdasarkan biaya promosi, konversi, penjualan, dan keuntungan untuk memastikan hasil yang optimal.
2. Meningkatkan Loyalitas Pelanggan: Kembangkan program membership, reward, dan penawaran khusus untuk mendorong kunjungan berulang.
3. Memaksimalkan Penjualan Produk: Pertahankan ketersediaan produk Coffee dan evaluasi peluang peningkatan penjualan kategori Non Coffee, Pastry, dan Dessert.
4. Meningkatkan Pengalaman Pelanggan: Gunakan penilaian produk, harga, suasana, Wi-Fi, dan pelayanan untuk mengidentifikasi aspek yang perlu ditingkatkan.
5. Mengembangkan Strategi Berdasarkan Perilaku Kunjungan: Evaluasi pola kunjungan dan durasi pelanggan untuk menyusun promosi yang sesuai dengan kebutuhan masing-masing kelompok.
6. Memvalidasi Metrik Keuangan: Pastikan rumus total penjualan dan keuntungan menggunakan dasar perhitungan yang jelas agar rekomendasi bisnis didukung oleh data yang akurat.
