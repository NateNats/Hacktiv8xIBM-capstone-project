# BMW Car Sales Analysis
<!-- Project overview section -->
## _Project Overview_
### Tujuan Proyek 🎯
Untuk mengetahui Model apa saja yang banyak dibeli di seluruh wilayah yang tersebar, mengetahui total penghasilan yang didapatkan pada tahun tersebut, model dengan jenis transmisi apa saja yang digunakan pada wilayah tersebut, serta mengidentifikasi dan menganalisis faktor-faktor apa saja yang paling paling berpengaruh pada keberhasilan penjualan tersebut. Output dari analisis ini akan menjadi dasar strategi untuk pemasaran dan penjualan.

### Latar belakang 🏢
Di era saat ini, industri otomotif terkhususnya mobil memiliki pasar yang sangat besar di seluruh dunia. Mobil BMW merupakan mobil yang masuk ke dalam segmen premium sudah pasti memiliki pasar yang sangat kompetitif. Keberhasilan penjualan BMW tidak tidak hanya bergantung pada kualitas setiap produk, namun juga pada strategi penentuan harga, penargetan pasar, jenis mesin yang digunakan dan juga tahun pembuatan. Dengan menganalisis data penjualan mobil BMW yang ada, saya dapat menggali lebih mendalam tentang pasar dan preferensi pembeli. Lebih mengerti dan memahami mengapa beberapa mobil terjual dengan volume tinggi sementara yang lainnya tidak.

### Permasalahan ❓
1. Menentukan model terlaris di setiap wilayah.
2. Menghitung Total penghasilan per tahun.
3. Menganalisis transmisi yang paling banyak digunakan per wilayah.
4. Mengidentifikasi faktor / kolom apa saja yang paling berpengaruh pada penjualan.

### Pendekatan 🛣️
- _Exploratory Data Analysis (EDA)_: memahami data terlebih dahulu, yang melibatkan analisis statistik deskriptif dan pembuatan visualisasi seperti histogram dan boxplot untuk mengidentifikasi pola, distribusi, dan hubungan antar variabel atau kolom.
- _Data Preprocessing_: data yang telah dianalisis selanjutnya dibersihkan dan disiapkan untuk pemodelan, seperti mengubah variabel kategorikal menjadi format numerik menggunakan teknik _one-hot encoding_ agar dapat diproses oleh model.
- Pemodelan Machine Learning: model melakukan klasifikasi, disini saya menggunakan model _Random Forest Classifier_, model lalu dibangun dan dilatih menggunakan data yang telah melalui _preprocessing_. Selanjutnya, ditampilkan juga metrik _Feature Importance_ agar mengetahui kolom atau variabel apa yang berpengaruh terhadap hasil klasifikasi model.
- Evaluasi: model dievaluasi menggunakan metrik akurasi.
- Rangkuman dan rekomendasi.

## Raw dataset link
https://www.kaggle.com/datasets/sumedh1507/bmw-car-sales-dataset/data

## Tools
- Google Colab
- DataSpell
- LM Studio (IBM/Granite-3.2-8b)

## _Insight & Findings_
### _Insights_
1. Distribusi kelas High dan Low cukup berbeda jauh, yaitu .........
2. Distribusi kelas target berdasarkan transmisi
- Manual (High: 7651, Low: 157503)
- Otomatis (High: 7595, Low: 7595)
 
3. Rata-rata penjualan berkategori low daripada high
4. Transmisi didominasi jenis manual dengan total 25154 kendaraan terjual, sedangkan automatic dengan total 24846 terjual.
5. Harga rata-rata model mobil BMW adalah:
- 3 Series: $75288
- 5 Series: $75366
- 7 Series: $75017
- M3      : $75570
- M5      : $74475
- X1      : $75566
- X3      : $75262
- X5      : $74842
- X6      : $74708
- i3      : $74800
- i8      : $74435
6. Warna mobil yang 

### _Findings_

## _AI Support Explanation_

