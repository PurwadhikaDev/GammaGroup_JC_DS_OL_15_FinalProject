# GammaGroup_JC_DS_OL_15_FinalProject

# Bank Marketing Campaign

Anggota Kelompok:
- Audia Khairunnisa
- Relita Manurung
- Nabila Saniaputri Trispantia


Tableau Link: https://public.tableau.com/views/BankMarketingCampaignDashboard_17325516392890/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link


## Latar Belakang

Dalam kampanye pemasaran yang dilakukan oleh sebuah bank, terlihat adanya penurunan signifikan dalam tingkat penerimaan tawaran dibandingkan dengan kampanye sebelumnya. Kampanye sebelumnya berhasil mencatatkan tingkat penerimaan sebesar 25,2%, sementara pada kampanye kali ini hanya tercatat 11,8%. Penurunan ini terjadi meskipun jumlah nasabah yang dihubungi hampir tujuh kali lipat lebih banyak dibandingkan dengan kampanye sebelumnya. Hal ini menunjukkan bahwa meskipun jumlah kontak yang dilakukan meningkat, strategi yang diterapkan belum efektif dalam menyasar segmen nasabah yang tepat.

Analisis lebih lanjut mengungkapkan bahwa sebagian besar penerima tawaran pada kampanye ini berasal dari segmen nasabah baru, yaitu mereka yang sebelumnya tidak terlibat dalam kampanye. Segmen nasabah baru ini menunjukkan potensi yang cukup besar, namun ketergantungan pada mereka juga mencerminkan kurangnya keberhasilan dalam mempertahankan nasabah lama yang sebelumnya memberikan respons positif terhadap tawaran.

Dengan total 36.658 calon pelanggan yang terlibat dalam kampanye ini, hanya 4.337 nasabah (11,8%) yang akhirnya berlangganan produk deposito berjangka. Persentase keberhasilan yang rendah ini, yang menurun dari 25,2% pada kampanye sebelumnya, menunjukkan bahwa mayoritas calon pelanggan tidak tertarik untuk menjadi pelanggan baru. Kondisi ini menimbulkan tantangan besar bagi perusahaan untuk menentukan strategi pemasaran yang lebih efektif dan relevan dalam kampanye mendatang, terutama dalam mempertahankan nasabah lama dan meningkatkan efektivitas penawaran kepada segmen nasabah yang tepat.

## Permasalahan

Meskipun kampanye pemasaran kali ini berhasil menjangkau lebih dari 36.000 calon pelanggan, tingkat keberhasilannya hanya mencapai 11,8%, yang lebih rendah dibandingkan kampanye sebelumnya dengan tingkat keberhasilan sebesar 25,2%. Penurunan ini kemungkinan disebabkan oleh jumlah nasabah yang dihubungi pada kampanye saat ini yang hampir tujuh kali lipat lebih banyak dibandingkan dengan kampanye sebelumnya. Hal ini menunjukkan bahwa meskipun jumlah nasabah yang dihubungi meningkat, efektivitas strategi kampanye dalam menjangkau segmen nasabah yang tepat belum maksimal.

Menghubungi seluruh nasabah untuk menawarkan produk deposito berjangka tentu tidak efisien dan akan memerlukan biaya yang sangat besar. Oleh karena itu, perusahaan ingin memprediksi nasabah mana yang memiliki kemungkinan besar untuk tertarik pada produk deposito, agar tim pemasaran dapat menargetkan mereka dengan cara yang lebih terarah, efektif, dan efisien.

## Fokus Analisa
1. Apa saja faktor yang memengaruhi keputusan nasabah untuk menerima tawaran deposito?
2. Bagaimana Pengaruh Status Kredit (Default, Housing, Loan) Terhadap Keputusan Nasabah Untuk Mengambil Produk Deposito?
3. Saluran komunikasi (contact) apa yang paling efektif untuk meningkatkan tingkat penerimaan tawaran deposito?
4. Bagaimana kondisi ekonomi makro memengaruhi keputusan nasabah untuk menerima tawaran deposito?
5. Kapan waktu terbaik untuk menjalankan kampanye promosi (berdasarkan month, day_of_week, pdays)?


## Tujuan

Perusahaan ingin meningkatkan efektivitas kampanye pemasaran dengan menargetkan nasabah yang lebih potensial untuk menerima tawaran term deposito. Berdasarkan masalah yang dihadapi terkait penurunan tingkat penerimaan tawaran dalam kampanye pemasaran sebelumnya, tujuan dari pemodelan ini adalah sebagai berikut:

1. **Meningkatkan Akurasi Prediksi Nasabah Potensial**:
   - Tujuan utama dari modeling ini adalah membangun dan menerapkan model klasifikasi yang dapat memprediksi nasabah yang memiliki probabilitas tinggi untuk menerima tawaran term deposito. Dengan menggunakan algoritma machine learning yang lebih canggih, model ini diharapkan dapat memberikan prediksi yang lebih akurat dibandingkan metode konvensional yang digunakan sebelumnya.

2. **Optimalisasi Strategi Kampanye Pemasaran**:
   - Dengan adanya model prediksi yang lebih tepat, divisi pemasaran dapat mengoptimalkan segmentasi dan penargetan nasabah, sehingga lebih efisien dalam mengalokasikan sumber daya dan mengurangi biaya serta waktu yang terbuang. Hal ini diharapkan dapat meningkatkan tingkat penerimaan tawaran dan meminimalkan pemborosan dalam kampanye mendatang.

3. **Menargetkan Segmen Nasabah yang Tepat**:
   - Pemodelan ini bertujuan untuk mengidentifikasi nasabah yang paling berpotensi dari berbagai segmen, baik nasabah lama yang pernah merespons positif maupun nasabah baru. Dengan menggunakan data dari kampanye sebelumnya dan informasi demografis nasabah, model ini diharapkan dapat menyaring nasabah yang cenderung lebih responsif terhadap penawaran term deposito.

4. **Meningkatkan Retensi dan Mengurangi Ketergantungan pada Nasabah Baru**:
   - Salah satu tujuan dari pemodelan ini adalah untuk mengurangi ketergantungan pada segmen nasabah baru, yang cenderung memiliki potensi lebih tinggi namun juga meningkatkan risiko. Fokus pada pemeliharaan hubungan dengan nasabah lama yang memberikan respons positif pada kampanye sebelumnya akan membantu meningkatkan keberlanjutan hasil kampanye.

5. **Hyperparameter Tuning untuk Meningkatkan Performa Model**:
   - Mengoptimalkan parameter model melalui proses hyperparameter tuning adalah bagian penting dari modeling ini. Dengan tuning yang tepat, diharapkan model dapat memberikan prediksi yang lebih presisi dan sesuai dengan kebutuhan bisnis.

Dengan mencapai tujuan-tujuan tersebut, perusahaan diharapkan dapat:
   - Meningkatkan **tingkat penerimaan** tawaran term deposito melalui segmentasi yang lebih akurat.
   - Mengoptimalkan **strategi pemasaran** dan **pengelolaan anggaran kampanye**.
   - **Meningkatkan loyalitas nasabah** dengan memberikan penawaran yang lebih relevan dan terpersonalisasi berdasarkan prediksi yang lebih tepat.


## Pendekatan Analisis
Langkah yang akan dilakukan adalah menganalisis data yang diperoleh untuk mengidentifikasi pola dari berbagai fitur yang ada, yang dapat karakteristik dari masing-masing nasabah. Model klasifikasi ini akan digunakan untuk membantu perusahaan dalam menyediakan alat prediksi nasabah potensial dengan bantuan algoritma machine learning. Secara detail, analisis yang akan dilakukan adalah sebagai berikut:

- **Data Cleaning**: Membersihkan data, memastikan tidak ada data hilang, memastikan dataset yang digunakan valid dan sesuai dengan fitur yang ada
- **Preprocessing Data**: Melakukan encoding untuk fitur kategorikal, normalisasi untuk fitur numerik, dan membagi data menjadi training dan testing set.
- **Benchmarking Model Klasifikasi**: Melakukan benchmarking model dengan beberapa model seperti Logistic Regression, Decision Trees, Random Forest, XGBoost dan lainya, serta Evaluasi menggunakan metrik seperti akurasi, precision dan recall.
- **Hyperparameter Tuning**: Melakukan tuning parameter model untuk optimasi kinerja.
- **Penerapan Model**: Menerapkan model pada data nasabah untuk memprediksi yang berpotensi menerima tawaran term deposito.

## Metrik Evaluation
Metrik evaluasi yang akan digunakan adalah Recall dan precision dengan keterangan sebagai berikut:

|  | Tidak Menerima Tawaran (0) | Menerima Tawaran (1) |
| --- | --- | --- |
| **Tidak Menerima Tawaran (0)** | **True Negative (TN)** | **False Positif (FP)** |
|  | Model memprediksi *client* tidak menerima tawaran deposito, dan *client* tidak menerima tawaran. | Model memprediksi *client* menerima tawaran deposito, tetapi *client* tidak menerima tawaran deposito.|
| **Menerima Tawaran (1)** | **False Negatif (FN)** | **True Positif (TP)** |
|  | Model memprediksi *client* tidak menerima tawaran deposito, tetapi *client* menerima tawaran. | Model memprediksi *client* menerima tawaran deposito, dan *client* menerima tawaran deposito.|


---



| **Tipe error** | **Konsekuensi** |
| --- | --- |
| False Positive | Kehilangan biaya *marketing* |
| False Negative | Kehilangan *potensial profit* |


Berikut merupakan gambaran perhitungan untuk melihat dampak biaya dari kesalahan prediksi:

**Asumsi Dasar**
1. Gaji bulanan telemarketing di: €2,497 [avg telemarketing salary](https://www.paylab.com/pt/salaryinfo/banking?__cf_chl_tk=xORZsn4gf7zdzxPFGIXUykggh5HjGybwuPypiiPyU2o-1731758313-1.0.1.1-MrwJOygNMBC0NagXVgQFTmIL7jsnSu35ompsOXQYWgE)
2. Hari kerja dalam sebulan: 22 hari [work-day](https://www.bluselection.com/blog/2022/12/working-days-in-portugal-everything-you-need-to-know?source=chatgpt.com)
3. Jam kerja dalam sehari: 8 jam [working-hour](https://www.bluselection.com/blog/2022/12/working-days-in-portugal-everything-you-need-to-know?source=chatgpt.com)
4. Rata-rata durasi panggilan telemarketing per orang: 180 detik [avg campaign call duration](https://simply-crm.com/blog/telemarketing-metrics-and-analytics-your-success-impact/)
5. Min jumlah deposit per nasabah: €100 [min deposito](https://www.nerdwallet.com/article/banking/savings/typical-minimum-balances-to-open-a-savings-account)
6. Interest rate (suku bunga tabungan): 4.5% [Portugal interest rate](https://tradingeconomics.com/portugal/interest-rate)
7. Lending rate (suku bunga pinjaman): 5.17% [Portugal landing rate](https://tradingeconomics.com/portugal/bank-lending-rate)
8. Biaya pulsa di Portugal: $0.03 (€0.029 per menit) [Portugal phone rate](https://www.openphone.com/rate/portugal)

**Perhitungan**

  **Hilangnya Biaya dan Waktu untuk Telemarketing**
    Biaya yang hilang dari waktu yang dihabiskan untuk setiap panggilan telemarketing dihitung sebagai berikut:

    1. Menghitung Upah Per Jam:
      - Gaji bulanan telemarketing: €2,497
      - Hari kerja per bulan: 22 hari
      - Jam kerja per hari: 8 jam
      - Upah per jam:
        - €2,497 dibagi dengan (22 hari x 8 jam) = €14.19 per jam.
      - Biaya pulsa per jam: €0.029 x 60 = €1.74  

    2. Menghitung Biaya untuk Satu Panggilan Telemarketing:
      - Durasi panggilan telemarketing per orang: 253 detik (4.2 menit)
      - Konversi durasi panggilan ke dalam jam: 253 detik / 3600 detik (1 jam) = 0.07 jam.
      - Biaya upah telemarketing: €14.19 x 0.07 = €0.993
      - Biaya pulsa perpanggilan: €1.74 x 0.07 = €0.122
      - Total biaya per panggilan: €0,122+€0,993 = €1,115.

      Kesimpulan
       Biaya yang hilang per panggilan telemarketing adalah sekitar €1,115 per orang.

  **Poin 2: Hilangnya Potensi Pendapatan**
    Potensi pendapatan yang hilang akibat perbedaan antara lending rate dan interest rate dihitung sebagai berikut:

    1. Menghitung Selisih antara Lending Rate dan Interest Rate:
      - Suku Bunga Pinjaman (Lending rate): 5.98%
      - SUku Bunga tabungan (Interest rate): 4.5%
      - Spread/ margin keuntungan bank
        Selisih antara lending rate dan interest rate: 5.98% - 4.5% = 1.48%

    2. Menghitung Hilangnya Potensi Pendapatan dari Deposit:
      - min deposit per nasabah: €100
      - Potensi pendapatan yang hilang: 1.48% x €100 = €1.48

      Kesimpulan
      Potensi pendapatan yang hilang per nasabah adalah €1.48.

Dari perhitungan di atas, dapat disimpulkan bahwa:
- **Biaya yang hilang untuk setiap panggilan telemarketing** adalah sekitar **€1.115** per orang.
- **Potensi pendapatan yang hilang akibat perbedaan lending rate dan interest rate** adalah sekitar **€1.48** per orang.

Berdasarkan informasi diatas, kerugian yang didapatkan untuk miss prediction FN lebih besar dibanding FP. Hal ini terjadi ketika model memprediksi bahwa seorang nasabah tidak akan melakukan deposit (negatif), tetapi kenyataannya mereka akan melakukannya. Nasabah potensial yang diabaikan mungkin merasa tidak diperhatikan oleh perusahaan, yang dapat berdampak negatif pada loyalitas mereka.

Untuk itu analisis ini akan menggunakan Recall sebagai metrix evaluasion utama dalam proses membangun model, guna menekan recall yang ada sehingga mengurangi potensi kerugian akibat salah prediksi, namun tetap memperhatikan nilai Precision sebagai informasi tambahan
