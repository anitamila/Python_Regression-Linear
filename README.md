**Objective Statement:**
1. Obtain correlation information between the independent variable and the dependent variable
2. Obtain information on the level of accuracy of the linear regression prediction model

**Data Understanding:**
- gre_score: GRE (Graduate Records Examination) score is the standard test for admission to graduate and business schools
- toefl_score: TOEFL (Test of English as a Foreign Language) score
- univ_ranking: university ranking
- motiv_letter_strength: scale of how strong the motivation letter is
- recommendation_strength: scale of how strong the recommendation given is
- gpa: final grade (GPA)
- research_exp: how long has experience in conducting research
- admit_prob: the probability of these values being acknowledged

**Data Preparation:**
- Checking missing values and duplicate data.
- Independent variables (X) consist of gre_score, toefl_score, univ_ranking, motiv_letter_strength, recommendation_strength, gpa, research_exp
- The dependent variable (y) is admit_prob
- Test the correlation between the independent variable and the dependent variable.

**Modelling:**
- Divide the dataset into training data and testing data with a proportion of 80% training data and 20% test data.
- Build a linear regression model using training data.

**Evaluation:**
- Predict admit probability values on training data and testing data.
- Measuring model performance using Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and R-squared (R2) on both data sets.

**Result Visualization:**
- Create scatter plots to compare actual values and predicted values on test data.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

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
