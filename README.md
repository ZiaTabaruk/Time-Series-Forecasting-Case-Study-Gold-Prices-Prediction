# Time Series Forecasting Case Study : Gold Prices Prediction

![{4B0DC994-8A60-4796-89CB-51886FBAD2C0}](https://github.com/user-attachments/assets/e0418474-e762-4b21-9a14-6973ab125627)

## Latar Belakang
Perusahaan melacak harga emas bulanan, yang berfluktuasi berdasarkan berbagai faktor ekonomi, tren pasar, dan peristiwa geopolitik. Emas adalah aset investasi dan cadangan yang signifikan bagi banyak industri, pemerintah, dan investor. Perkiraan harga emas yang akurat sangat penting untuk perencanaan keuangan, strategi investasi, dan manajemen risiko.

## Rumusan Masalah
Perusahaan perlu memprediksi harga emas di masa depan dengan menggunakan data historis bulanan. Tujuannya adalah untuk mengimplementasikan dan menyetel model peramalan deret waktu (ARIMA, SARIMA, dan Prophet) untuk mencapai prediksi yang paling akurat. Dengan membandingkan kinerja model-model ini, perusahaan bertujuan untuk memilih model yang paling efektif untuk meramalkan harga emas di masa depan.

## Tujuan
- Memprediksi harga emas bulanan untuk periode mendatang berdasarkan data historis.
- Bandingkan akurasi peramalan model ARIMA, SARIMA, dan Prophet.
- Gunakan tuning hyperparameter untuk mengoptimalkan setiap model untuk performa yang lebih baik.
  
## Pendekatan Analitik
1. **Data Preparation**: Siapkan data harga emas historis dengan mengatur Tanggal sebagai indeks dan Harga sebagai variabel target.
2. **Model Selection**:
   - Menerapkan model ARIMA, SARIMA, dan Prophet.
   - Melakukan tuning hiperparameter menggunakan validasi silang deret waktu untuk setiap model.
3. **Forecasting**: Menghasilkan prakiraan harga di masa depan dengan menggunakan model yang telah dilatih.
4. **Comparison**: Bandingkan hasil perkiraan berdasarkan metrik RMSE.

## Evaluasi Metrik
**Root Mean Squared Error (RMSE)**: Metrik ini akan digunakan untuk mengevaluasi akurasi peramalan. RMSE yang lebih rendah mengindikasikan model yang lebih akurat. Tujuannya adalah untuk meminimalkan RMSE dan memilih model dengan performa peramalan terbaik untuk harga emas.

## Kesimpulan
Di antara ketiga model (ARIMA, SARIMA, dan Prophet), model ARIMA memberikan performa terbaik dengan RMSE 65,9, menjadikannya model yang paling akurat untuk meramalkan harga emas di masa depan. Model ini dapat menangkap perubahan tren dari waktu ke waktu secara signifikan sehingga dapat meramalkan harga dengan akurasi yang lebih tinggi.

## Rekomendasi
Perusahaan sebaiknya menggunakan model ARIMA untuk memprediksi harga emas karena akurasinya yang superior. Untuk perbaikan yang berkelanjutan, disarankan untuk melakukan penyetelan dan pemantauan lebih lanjut terhadap performa model dalam merespons perubahan kondisi pasar.
