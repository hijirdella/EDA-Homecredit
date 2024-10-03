# EDA-Homecredit
This project covers descriptive statistics, univariate and multivariate analysis, and business insights for the Home Credit dataset. Key steps include identifying data quality issues, visualizing distributions, analyzing feature correlations, and deriving actionable business recommendations based on insights.

# 0. Distribusi Jumlah Kredit yang Diajukan
![0. Distribusi Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/bd1d5234e6c158e3e27dc9651fdc0c21cfa86a28/BI%20Graph/0.%20Distribusi%20Jumlah%20Kredit%20yang%20Diajukan.png)
Insight: Sebagian besar nasabah mengajukan kredit di bawah 500 ribu

Hasil: Sebagian besar nasabah mengajukan kredit dalam jumlah relatif kecil (di bawah 500 ribu), sementara hanya sedikit nasabah yang mengajukan kredit di atas 1 juta.

Rekomendasi Bisnis: Fokuskan strategi produk kredit pada segmen nasabah yang mengajukan pinjaman kecil. Misalnya, tawarkan kredit mikro dengan bunga yang lebih kompetitif atau produk yang disesuaikan untuk segmen ini.


# 1. Hubungan Pendapatan Nasabah dan Jumlah Kredit yang Diajukan
![1. Hubungan Pendapatan Nasabah dan Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/1.%20Hubungan%20Pendapatan%20Nasabah%20dan%20Jumlah%20Kredit%20yang%20Diajukan.png)
Insight: Nasabah dengan pendapatan tinggi cenderung mengajukan kredit lebih besar
Hasil: Ada kecenderungan bahwa nasabah dengan pendapatan lebih tinggi mengajukan kredit lebih besar, meskipun beberapa nasabah dengan pendapatan rendah juga mengajukan kredit besar.

Rekomendasi Bisnis: Lakukan verifikasi pendapatan secara ketat untuk nasabah dengan pendapatan rendah yang mengajukan kredit besar, untuk menghindari risiko gagal bayar.

# 2. Distribusi Usia Nasabah
![2. Distribusi Usia Nasabah](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/1.%20Hubungan%20Pendapatan%20Nasabah%20dan%20Jumlah%20Kredit%20yang%20Diajukan.png)
Insight: Sebagian besar nasabah berada di rentang usia 30-50 tahun

Hasil: Sebagian besar nasabah yang mengajukan kredit berada di rentang usia 30-50 tahun.

Rekomendasi Bisnis: Fokuskan pemasaran produk kredit pada segmen usia 30-50 tahun, misalnya untuk kredit perumahan atau kendaraan.

# 3. Hubungan Lama Bekerja (Tahun) dan Jumlah Kredit yang Diajukan
![3. Hubungan Lama Bekerja (Tahun) dan Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/3.%20Hubungan%20Lama%20Bekerja%20(Tahun)%20dan%20Jumlah%20Kredit%20yang%20Diajukan.png)

Insight: Nasabah dengan riwayat kerja lebih lama cenderung mengajukan kredit lebih besar

Hasil: Nasabah yang bekerja lebih lama cenderung mengajukan kredit dalam jumlah lebih besar, menunjukkan hubungan antara stabilitas pekerjaan dan kepercayaan dalam pengajuan kredit.

Rekomendasi Bisnis: Berikan penawaran kredit dengan bunga rendah dan tenor lebih panjang kepada nasabah yang memiliki riwayat kerja yang stabil.

# 4. Analisis Perilaku Pembayaran Secara Keseluruhan:
![4. Distribution of Days Instalment vs Days Entry Payment](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/4.%20Distribution%20of%20Days%20Instalment%20vs%20Days%20Entry%20Payment.png)
Insight: Mayoritas nasabah cenderung membayar cicilan mereka tepat waktu atau bahkan lebih awal dari tanggal jatuh tempo. Hal ini menunjukkan bahwa nasabah memiliki perilaku keuangan yang baik dan bertanggung jawab.
Rekomendasi: Buat program loyalitas atau tawarkan insentif seperti pengurangan suku bunga bagi nasabah yang konsisten melakukan pembayaran lebih awal. Ini dapat mendorong nasabah untuk terus membayar tepat waktu dan memperkuat hubungan dengan nasabah.

# 5. Korelasi Antara Jumlah Cicilan dan Jumlah Pembayaran
![5. Distribution of Days Instalment vs Days Entry Payment](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/5.%20Amount%20Instalment%20vs%20Amount%20Payment.png)
Insight: Terdapat korelasi positif yang kuat antara jumlah cicilan yang dijadwalkan dengan jumlah pembayaran aktual. Namun, ada beberapa nasabah yang sering membayar di bawah jumlah cicilan yang dijadwalkan, yang mengindikasikan adanya potensi kesulitan keuangan.
Rekomendasi: Segmentasi nasabah berdasarkan perilaku pembayaran mereka. Lakukan komunikasi proaktif dan tawarkan solusi yang disesuaikan (misalnya, program refinancing atau fleksibilitas pembayaran) bagi nasabah yang mengalami kesulitan membayar. Langkah ini dapat membantu mencegah terjadinya gagal bayar dan menjaga portofolio kredit yang sehat.

# 6. Analisis Versi Cicilan vs Jumlah Cicilan
![6. Box Plot of Instalment Version vs Instalment Number](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/6.%20Box%20Plot%20of%20Instalment%20Version%20vs%20Instalment%20Number.png)
Insight: Versi cicilan yang lebih rendah cenderung memiliki jumlah cicilan yang lebih tinggi dan bervariasi. Sebaliknya, versi cicilan yang lebih tinggi (produk cicilan yang lebih baru) cenderung memiliki jumlah cicilan yang lebih sedikit dan lebih seragam. Ini mengindikasikan adanya tren ke arah produk pinjaman dengan jangka waktu lebih pendek atau standar produk yang lebih ketat.
Rekomendasi: Pertimbangkan untuk menawarkan produk cicilan baru dengan durasi yang lebih singkat, karena ini tampaknya lebih diminati oleh nasabah. Untuk nasabah dengan jumlah cicilan yang tinggi, lakukan peninjauan kembali dan restrukturisasi pinjaman agar lebih sesuai dengan kemampuan finansial mereka, guna mengurangi risiko gagal bayar.