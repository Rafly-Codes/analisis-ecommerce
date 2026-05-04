# analisis-ecommerce
# Analisis Penjualan E-Commerce

## Business Question
Dari data yang ada, saya ingin mengetahui:
- Produk mana yang memiliki harga tinggi tetapi penjualannya rendah
- Bagaimana karakteristik pelanggan berdasarkan aktivitas belanja
- Kategori produk mana yang paling efektif dalam penggunaan iklan
- Apakah iklan benar-benar berpengaruh terhadap penjualan

---

## Data Wrangling
Sebelum melakukan analisis, data dibersihkan terlebih dahulu:
- Mengisi nilai kosong pada kolom Total_Sales dengan perhitungan Quantity × Price_Per_Unit
- Mengubah format Order_Date menjadi datetime
- Memastikan data dapat digunakan untuk analisis tanpa error

---

## Insights

### 1. Underperformer Product
Dari hasil visualisasi, terlihat bahwa beberapa produk dengan harga tinggi justru memiliki jumlah penjualan yang rendah.  
Hal ini menunjukkan bahwa harga yang terlalu mahal dapat menjadi penghambat dalam penjualan produk.

---

### 2. RFM Analysis
Berdasarkan analisis Recency, Frequency, dan Monetary:
- Pelanggan yang sering belanja dan mengeluarkan banyak uang memiliki kontribusi besar terhadap penjualan
- Pelanggan yang sudah lama tidak belanja berpotensi untuk diberikan promo agar kembali aktif

---

### 3. Efisiensi Kategori Produk
Dari perbandingan antara total penjualan dan anggaran iklan:
- Terdapat kategori yang menghabiskan banyak biaya iklan tetapi hasil penjualannya kecil
- Ada juga kategori yang lebih efisien dengan hasil penjualan tinggi

---

### 4. Pengaruh Iklan terhadap Penjualan
Hasil perbandingan menunjukkan bahwa:
- Kelompok dengan iklan tinggi cenderung memiliki penjualan lebih besar
- Namun, tidak semua iklan memberikan hasil yang maksimal

---

### 5. Regresi Linear
Dari model regresi:
- Terdapat hubungan antara iklan dan penjualan
- Tetapi pengaruhnya tidak sepenuhnya kuat, sehingga ada faktor lain yang mempengaruhi

---

## Recommendation
Berdasarkan hasil analisis:
- Menyesuaikan harga produk yang terlalu tinggi
- Memberikan promo kepada pelanggan agar tetap aktif
- Mengoptimalkan penggunaan anggaran iklan
- Fokus pada kategori produk yang paling menguntungkan

---

## Kesimpulan
Dari analisis ini dapat disimpulkan bahwa harga, perilaku pelanggan, dan strategi iklan sangat berpengaruh terhadap penjualan.  
Dengan strategi yang tepat, perusahaan dapat meningkatkan performa bisnis secara keseluruhan.
