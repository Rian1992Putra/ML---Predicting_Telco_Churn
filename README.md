Business Problem Understanding

Latar Belakang

Sebuah perusahaan yang bergerak di bidang telekomunikasi ingin meningkatkan profit serta mengurangi kerugian dengan menugaskan salah satu pegawainya untuk melakukan analisa dan pengolahan data untuk dapat menghasilkan kesimpulan yang dapat membantu dalam pembuatan kebijakan/produk/layanan yang lebih baik. Perusahaan memiliki data terkait 'Customer Churn' dan ingin melakukan prediksi terhadap pelanggan mana yang akan tetap berlangganan dan pelanggan yang akan berhenti berlangganan.

Target :

0 : Pelanggan yang masih berlangganan/tidak churn

1 : Pelanggan yang berhenti berlangganan/churn


Rumusan Masalah :

Ditemukannya sejumlah pelanggan yang berhenti berlangganan berdasarkan data 'Customer Churn'. Apabila perusahaan salah melakukan prediksi terhadap pelanggan, sebagai contoh pelanggan diprediksi akan berhenti berlangganan namun ternyata pelanggan tersebut tetap berlangganan maka alokasi sumber daya akan tidak efektif. Sebaliknya apabila pelanggan diprediksi akan tetap berlangganan namun ternyata pelanggan tersebut berhenti berlangganan maka perusahaan akan kehilangan jumlah pelanggan dan akan mempengaruhi profit perusahaan.

Tujuan :

Berdasarkan permasalahan yang ada, perusahaan ingin memiliki kemampuan untuk memprediksi kemungkinan seorang pelanggan akan tetap berlangganan atau tidak. Lalu perusahaan juga ingin mengetahui faktor/variabel apa yang membuat seorang pelanggan akan tetap berlangganan atau tidak sehingga dapat membuat kebijakan/produk/layanan yang sesuai dengan kebutuhan pelanggan.

Pendekatan Analisis :

Melakukan analisis data untuk menemukan pola yang membedakan pelanggan yang tetap berlangganan dengan yang tidak. Selanjutnya akan dibuat model klasifikasi yang akan membantu perusahaan untuk dapat memprediksi kemungkinan seorang pelanggan akan tetap berlangganan atau tidak.

Metrik Evaluasi :

Metrik evaluasi yang akan digunakan adalah ROC AUC karena untuk mengukur performa model secara keseluruhan dengan memberikan gambaran keseluruhan tentang kemampuan model dalam memisahkan kelas positif dan negatif. Selain itu perlu juga untuk meminimalisir false positive dan false negative agar lebih seimbang.

False Positive : Pelanggan yang diprediksi akan berhenti berlangganan tetapi kenyataannya tetap berlangganan. Konsekuensinya adalah alokasi sumber daya yang tidak efektif (contoh = pemberian diskon tidak tepat sasaran).

False Negative : Pelanggan yang diprediksi akan tetap berlangganan tetapi kenyataannya berhenti berlangganan. Konsekuensinya adalah kehilangan jumlah pelanggan yang akan berdampak pada penurunan profit.
