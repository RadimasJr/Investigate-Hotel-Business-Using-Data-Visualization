# Latar Belakang
Analisis kinerja bisnis merupakan kunci penting bagi perusahaan untuk mencapai keberhasilan dalam bisnisnya. Perusahaan dapat melakukan analisis untuk mengidentifikasi permasalahan, kelemahan, dan kekuatan yang dimilikinya. Dalam bisnis perhotelan, penting untuk memahami perilaku pelanggan. Dengan memahami perilaku pelanggan, perusahaan dapat mengetahui faktor apa saja yang mempengaruhi pelanggan dalam melakukan pemesanan hotel. Selain itu, perusahaan juga dapat mengidentifikasi produk atau layanan apa yang kurang laku di pasar. Hal ini dilakukan untuk menyesuaikan strategi bisnis yang tepat guna sehingga perusahaan dapat meningkatkan pengalaman pelanggan dan dapat mencapai tujuan bisnis jangka panjang.

# Objektif
Membuat visualisasi berbasis data sebagai insight bagi bisnis hotel.

# Business Questions
* Jenis hotel apa yang paling sering dikunjungi oleh pelanggan?
* Apakah durasi menginap mempengaruhi tingkat pembatalan pemesanan hotel?
* Apakah jarak waktu antara pemesanan hotel dan hari kedatangan tamu mempengaruhi tingkat pembatalan pemesanan hotel?

# Data
Data yang digunakan adalah data dari perusahaan hotel dari tahun 2017 - 2019.

# Data Pre-Processing
* Terdapat 4 fitur yang memiliki null values, handling dari missing values tersebut ditindaklanjuti dengan mengisinya dengan value "unknown".
* Terdapat value yang tidak sesuai pada fitur kategorik  "meal", value tersebut ditindaklanjuti dengan melakukan .replace dengan value yang sesuai.

# Analisis
## **1. Analisis Jumlah Pemesanan Hotel per Bulan Berdasarkan Tipe Hotel**
<br>
<img src="images/Image 1.png" alt="Logo" width="1000" height="auto">
Berdasarkan gambar plot, peningkatan jumlah pemesanan Hotel mengalami penigkatan pada dua periode yaitu bulan Mei - Juli kemudian bulan Oktober - Desember. Peningkatan tersebut terjadi karena periode waktu tersebut telah memasuki musim liburan, untuk musim liburan pertama dari Mei - Juli yaitu libur musim panas, sedangkan musim liburan kedua adalah natal dan tahun baru.

## **2. Analisa Pengaruh Durasi Menginap terhadap tingkat Pembatalan Pemesanan Hotel**
<br>
<img src="images/Image 2.png" alt="Logo" width="1000" height="auto">
Tingkat pembatalan pemesanan ketegori City Hotel semakin meningkat seiring dengan lama durasi menginapnya. Sedangkan untuk kategori Resort Hotel tingkat pembatalan pemesanan memiliki persentase yang tinggi pada durasi menginap selama 2-3 minggu dan 3-4 minggu.

## **3. Analisis Pengaruh Lead Time terhadap Tingkat Pembatalan Pemesanan Hotel**
<br>
<img src="images/Image 3.png" alt="Logo" width="1000" height="auto">
Tingkat pembatalan pemesanan ketegori City Hotel secara umum meningkat seiring dengan lama durasi lead time. Sedangkan untuk kategori Resort Hotel tingkat pembatalan pemesanan memiliki persentase yang tinggi pada durasi lead time selama 9 bulan dan 11 bulan, namun jika dilihat secara keseluruhan grafik Resert Hotel juga dapat dikatakan memiliki persentase tingkat pembatalan yang semakin meningkat.

# Kesimpulan
* **Jenis hotel apa yang paling sering dikunjungi oleh pelanggan?**
<br>
Kategori "City Hotel" lebih banyak di book oleh pelanggan sebesar 66,4% dibandingkan "Resort Hotel". Peningkatan jumlah pemesanan City Hotel mengalami penigkatan pada dua periode yaitu bulan Mei - Juli kemudian bulan Oktober - Desember. Peningkatan tersebut terjadi karena periode waktu tersebut telah memasuki musim liburan.
<br>

* **Apakah durasi menginap mempengaruhi tingkat pembatalan pemesanan hotel?**
<br>
Korelasi antara lamanya durasi menginap dari seluruh rentang waktu 1 minggu sampai lebih dari 4 minggu memiliki pengaruh terhadap tingkat pembatalan pemesanan untuk kategori City Hotel. Namun, untuk kategori Resort Hotel memiliki persentase pembatalan paling tinggi pada durasi menginap 2-4 minggu.
<br>

* **Apakah jarak waktu antara pemesanan hotel dan hari kedatangan tamu (lead time) mempengaruhi tingkat pembatalan pemesanan hotel?**
<br>
Korelasi antara lamanya durasi lead time memiliki pengaruh terhadap tingkat pembatalan pemesanan untuk lebih spesifiknya untuk kategori City Hotel. Sedangkan untuk kategori Resort Hotel tingkat pembatalan pemesanan memiliki persentase yang tinggi pada durasi lead time selama 9 bulan dan 11 bulan, namun jika dilihat secara keseluruhan grafik Resert Hotel juga dapat dikatakan memiliki persentase tingkat pembatalan yang semakin meningkat.
<br>

# Rekomendasi
* Memberikan promosi terhadap City Hotel karena lebih sering dipesan oleh pelanggan, dan promosi dapat difokuskan pada musim liburan dimana jumlah pemesanan tinggi seperti Mei-Juli dan Oktober-Desember.
* Pihak Hotel dapat mempertimbangkan strategi untuk mengurangi tingkat lead time karena berpengaruh terhadap tingkat pembatalan pemesanan hotel, seperti memberikan promosi atau insentif bagi pelanggan yang memesan jauh hari.
