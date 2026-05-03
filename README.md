# UTS Business-Intelligence

## Anggota:
- Rabiatul Hikmah (2409116049)
- Nayla Lelyanggraheni Hutomo (2409116061)
- Jemis Movid (2409116070)
- Marcela Persa Linthin (2409116072)

# Latar Belakang
Perkembangan industri ritel yang semakin pesat mendorong perusahaan untuk mampu mengelola dan menganalisis data penjualan secara efektif. Data penjualan yang dihasilkan setiap hari, khususnya pada sektor retail alkohol dan minuman keras, memiliki potensi besar untuk memberikan insight terkait perilaku konsumen, tren penjualan, serta performa produk di pasar. Namun, data tersebut umumnya masih tersebar dalam berbagai format dan belum terstruktur dengan baik, sehingga sulit untuk langsung digunakan dalam proses pengambilan keputusan.

Selain itu, data mentah yang tersedia sering kali mengandung ketidakkonsistenan, data kosong, serta format yang berbeda-beda. Hal ini menyebabkan proses analisis menjadi kurang optimal dan berpotensi menghasilkan informasi yang tidak akurat. Oleh karena itu, diperlukan suatu pendekatan yang mampu mengintegrasikan, membersihkan, dan menyusun data menjadi lebih terstruktur.

Salah satu solusi yang dapat diterapkan adalah dengan menggunakan konsep Business Intelligence (BI) melalui pembangunan Data Warehouse. Data Warehouse memungkinkan data dari berbagai sumber disimpan dalam satu tempat terpusat dengan struktur yang telah disesuaikan untuk kebutuhan analisis. Dalam proses pembangunannya, digunakan metode ETL (Extract, Transform, Load) untuk mengekstrak data dari sumber, melakukan transformasi agar data menjadi bersih dan konsisten, serta memuat data ke dalam sistem penyimpanan.

Dengan menerapkan proses ETL dan membangun Data Warehouse pada dataset retail penjualan alkohol dan minuman keras, diharapkan data yang semula tidak terstruktur dapat diolah menjadi informasi yang bernilai. Informasi tersebut kemudian dapat digunakan untuk menganalisis pola penjualan, mengidentifikasi produk yang paling diminati, serta mendukung pengambilan keputusan yang lebih tepat dan berbasis data.

# Dataset
Dataset yang digunakan dalam proyek ini adalah Retail Sales Data set of Alcohol and Liquor yang diperoleh dari Kaggle. Dataset ini berisi informasi terkait transaksi penjualan produk alkohol dan minuman keras pada berbagai toko dalam periode waktu tertentu.
Secara umum, dataset ini mencakup beberapa atribut penting, antara lain:
- Informasi produk (misalnya nama produk, kategori, atau jenis minuman)
- Data penjualan (jumlah barang terjual, harga, total penjualan)
- Informasi waktu (tanggal transaksi)
- Informasi lokasi/toko (jika tersedia)

Data-data tersebut masih dalam bentuk mentah sehingga belum terstruktur untuk kebutuhan analisis lebih lanjut. Oleh karena itu, perlu dilakukan proses identifikasi untuk menentukan elemen mana yang termasuk fakta dan dimensi dalam perancangan Data Warehouse.

Dalam konteks ini:

- Fakta (Fact) → data numerik yang bisa dihitung. Contoh: jumlah penjualan (quantity), total penjualan (total_sales)
- Dimensi (Dimension) → data deskriptif sebagai konteks. Contoh: produk, waktu, lokasi
