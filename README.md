**Objective Statement:**
1. Mendapatkan informasi korelasi antara variabel independen dan variabel dependen
2. Mendapatkan informasi tingkat akurasi model prediksi regresi linear

**Data Understanding:**
- gre_score: nilai GRE (Graduate Records Examination) adalah tes standar untuk masuk ke sekolah pascasarjana dan bisnis
- toefl_score: nilai TOEFL (Test of English as a Foreign Language)
- univ_ranking: peringkat universitas
- motiv_letter_strength: skala dari seberapa kuat motivation letter yang dibuat
- recommendation_strength: skala dari seberapa kuat rekomendasi yang diberikan
- gpa: nilai akhir perkuliahan (IPK)
- research_exp: berapa lama pengalaman dalam melakukan riset
- admit_prob: besaran probabilitas nilai-nilai tersebut untuk diakui

**Data Preparation:**
- Checking missing value dan duplikasi data.
- Variabel independent (X) terdiri dari gre_score, toefl_score, univ_ranking, motiv_letter_strength, recommendation_strength, gpa, research_exp
- Variabel dependent (y) yaitu admit_prob
- Menguji korelasi antara variabel independent dengan variabel dependent.

**Modeling:**
- Membagi dataset menjadi data latih dan data uji dengan proporsi perbandingan 80% data latih dan 20% data uji.
- Membangun model regresi linear menggunakan data latih.

**Evaluation:**
- Memprediksi nilai probabilitas admit pada data latih dan data uji.
- Mengukur kinerja model menggunakan Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), dan R-squared (R2) pada kedua set data.

**Visualisasi Hasil:**
- Membuat scatter plot untuk membandingkan nilai aktual dan nilai prediksi pada data uji.
