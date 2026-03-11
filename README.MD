# Data Preprocessing & Handling

Latihan ini meliputi teknik preprocessing untuk data kesehatan, termasuk outlier, missing values, encoding, scaling, transformasi, dan imbalance.

---

## 1. Outlier Detection & Handling
- Z-Score untuk `bmi` dan `blood_sugar` dengan boxplot.
- IQR dan winsorizing pada fitur numerik ekstrem.
- Jelaskan alasan metode sesuai data kesehatan.

## 2. Handling Missing Values
- Imputasi `blood_pressure_sys` menggunakan median.
- Imputasi `smoker_status` menggunakan mode.
- Tunjukkan perubahan statistik dan jumlah missing.
- Jelaskan dampak kesalahan imputasi pada analisis kesehatan.

## 3. Encoding Categorical Data
- Ordinal Encoding pada `diagnosis_risk` (Low < Medium < High).
- Binary/Frequency Encoding pada `city` (high-cardinality).
- Jelaskan konsekuensi pemilihan encoding yang salah.

## 4. Scaling & Normalization
- Min-Max Scaling pada `age`.
- Robust Scaling pada `bmi`.
- Bandingkan distribusi hasil scaling.
- Jelaskan pentingnya scaling untuk model prediksi risiko.

## 5. Distribution Transformation
- Log Transform pada `blood_sugar` dan periksa skewness.
- Yeo-Johnson Transform pada `bmi` dan tampilkan histogram.
- Jelaskan kapan transformasi tidak boleh digunakan.

## 6. Imbalance Data
- Tampilkan class distribution `diagnosis_risk` sebelum & sesudah balancing.
- Terapkan SMOTE untuk menyeimbangkan kelas minoritas.
- Jelaskan risiko oversampling berlebihan.
