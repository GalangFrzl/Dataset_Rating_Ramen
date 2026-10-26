MAE (Mean Absolute Error) dan MSE (Mean Squared Error) adalah metrik untuk mengukur eror (kesalahan) prediksi model. Nilai MAE dan MSE tidak harus lebih dekat dengan angka 1, melainkan harus sedekat mungkin dengan angka 0.
Semakin kecil nilainya (mendekati 0), artinya prediksi model semakin akurat karena erornya semakin sedikit.
Sementara itu, R² (R-squared atau Koefisien Determinasi) memiliki aturan yang berbeda. Nilai R² justru harus sedekat mungkin dengan angka 1 (atau 100%) agar model dianggap sangat baik.
Berikut adalah penjelasan ringkas untuk masing-masing metrik:

1. MAE (Mean Absolute Error)
- Definisi: Rata-rata dari selisih mutlak antara nilai prediksi dan nilai aktual.
- Target Nilai: Mendekati 0.
- Analogi: Jika MAE = 0, artinya model Anda 100% tepat menebak semua data tanpa ada meleset sama sekali. Nilainya tidak terbatas pada angka 1; jika data Anda bernilai ribuan, nilai MAE bisa saja puluhan atau ratusan, namun targetnya tetap sekecil mungkin.

3. MSE (Mean Squared Error)
- Definisi: Rata-rata dari selisih prediksi dan aktual yang dikuadratkan. Karena dikuadratkan, metrik ini memberikan penalti yang besar untuk eror yang besar (outlier).
- Target Nilai: Mendekati 0.
- Analogi: Sama seperti MAE, semakin kecil nilainya, semakin bagus. Karena efek kuadrat, nilai MSE biasanya lebih besar dari MAE jika model membuat kesalahan besar pada beberapa data.

3. R² (R-squared)
- Definisi: Mengukur seberapa baik model Anda menjelaskan variasi pada data aktual dibandingkan dengan model rata-rata sederhana.
- Target Nilai: Mendekati 1.
- Arti Skala:
  - R² = 1: Model sempurna, menjelaskan seluruh variasi data.
  - R² = 0: Model Anda sama saja (atau tidak lebih baik) dengan hanya menebak menggunakan nilai rata-rata.
  - R² < 0 (Negatif): Model Anda sangat buruk, bahkan lebih buruk daripada menebak nilai rata-rata secara acak.
