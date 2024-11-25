# Customer Lifetime Value

**Created by**: Kevin Matthew Aditya

---

## **Domain Knowledge**
Dalam industri asuransi otomotif yang semakin kompetitif, perusahaan menghadapi tantangan besar dalam mempertahankan loyalitas pelanggan, mengingat banyaknya pilihan yang tersedia untuk memenuhi kebutuhan asuransi kendaraan. Salah satu kunci untuk meraih keberhasilan jangka panjang adalah memahami nilai pelanggan sepanjang siklus hidup mereka, yang sering diukur dengan **Customer Lifetime Value (CLV)**.

Customer Lifetime Value (CLV) adalah perkiraan total keuntungan yang dapat diperoleh sebuah perusahaan dari seorang pelanggan selama hubungan mereka. CLV memberi gambaran jelas tentang kontribusi seorang pelanggan terhadap pendapatan perusahaan dan menjadi panduan dalam pengambilan keputusan strategis, termasuk pemasaran, alokasi anggaran, dan peningkatan pengalaman pelanggan. Dengan memanfaatkan CLV, perusahaan asuransi otomotif dapat lebih fokus pada pelanggan yang berpotensi memberikan keuntungan berkelanjutan.

Penerapan CLV memungkinkan perusahaan untuk:
- Mengidentifikasi pelanggan yang memiliki potensi untuk menjadi loyal dan memberikan pendapatan jangka panjang.
- Lebih bijak dalam mengalokasikan anggaran pemasaran dan layanan pelanggan.
- Mengoptimalkan strategi retensi, seperti menawarkan produk tambahan, diskon, atau layanan yang disesuaikan.
- Mengurangi biaya akuisisi pelanggan baru dan memaksimalkan keuntungan dari pelanggan yang sudah ada.

Memahami CLV tidak hanya meningkatkan efisiensi operasional tetapi juga memperkuat posisi kompetitif perusahaan dalam pasar yang semakin padat.

---

## **Problem Statement**
Memprediksi **Customer Lifetime Value (CLV)** dengan akurat menjadi tantangan utama bagi perusahaan asuransi otomotif dalam menghadapi persaingan yang ketat. Untuk itu, perusahaan perlu mengembangkan model prediksi yang dapat memperhitungkan berbagai faktor yang memengaruhi CLV secara efektif. Penggunaan teknik **machine learning** diperlukan untuk mengidentifikasi pola dan tren yang dapat memprediksi nilai pelanggan secara akurat. Dengan demikian, perusahaan dapat mengoptimalkan strategi pemasaran dan retensi pelanggan serta meningkatkan efisiensi operasional.

---

## **Goals**
Tujuan utama dari pengembangan model ini adalah membangun algoritma **machine learning berbasis regresi** dengan tingkat akurasi dan predictive power yang tinggi untuk memprediksi **Customer Lifetime Value (CLV)** secara akurat pada perusahaan asuransi otomotif. 

Dengan akurasi dan predictive power yang tinggi, model diharapkan dapat:
1. Menyusun strategi pemasaran berbasis data.
2. Meningkatkan retensi pelanggan.
3. Mengoptimalkan efisiensi operasional.

---

## **Metric Evaluation**
Untuk mengevaluasi kinerja model, digunakan beberapa metric sebagai berikut:
1. **MAE (Mean Absolute Error)**: 
   - Menghitung rata-rata nilai absolute residual (selisih nilai prediksi dan nilai aktual).
   - Cocok digunakan jika dataset memiliki banyak outlier.
   - **Semakin kecil MAE, semakin baik kinerja model.**
   
2. **RMSE (Root Mean Squared Error)**:
   - Mengakarkuadratkan nilai MSE (rata-rata kuadrat residual).
   - Memberi bobot lebih tinggi pada error besar.
   - Cocok digunakan jika rentang nilai dari variabel target tidak terlalu besar.
   - **Semakin kecil RMSE, semakin baik kinerja model.**
   
3. **MAPE (Mean Absolute Percentage Error)**:
   - Mengukur kesalahan dalam bentuk persentase.
   - Dihitung dengan membagi nilai absolute residual dengan nilai aktual.
   
4. **R-Squared**:
   - Menjelaskan seberapa besar variasi variabel target (Y) yang dapat dijelaskan oleh model.
   - Nilainya berkisar antara 0 hingga 1.
   - **Semakin mendekati 1, semakin baik kinerja model.**

---

## **Analytical Approach**
Langkah-langkah dan metode yang digunakan dalam pengolahan data serta pemodelan adalah sebagai berikut:

1. **Business Understanding**: Memahami tujuan dan kebutuhan bisnis untuk membangun model CLV.
2. **Data Understanding**: Mengeksplorasi dan memahami dataset, termasuk sumber data, tipe data, dan potensi masalah dalam data.
3. **Exploratory Data Analysis (EDA)**: Melakukan analisis eksplorasi untuk memahami pola, outlier, dan hubungan antar variabel.
4. **Data Preprocessing**: Membersihkan dan menyiapkan data untuk pemodelan, termasuk handling missing values, encoding, dan normalisasi.
5. **Modeling**: Membangun model machine learning berbasis regresi untuk memprediksi CLV dengan menggunakan berbagai algoritma dan melakukan tuning hyperparameter.
6. **Conclusion and Recommendations**: Menyimpulkan hasil model dan memberikan rekomendasi strategis berdasarkan wawasan yang diperoleh.

--- 
