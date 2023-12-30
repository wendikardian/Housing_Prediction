


# First Project : Housing Prediction 

**Dibuat oleh : ** Wendi Kardian

Project Pertama dalam Predictive Analytics untuk memenuhi submission project dari Dicoding, dalam kelas Machine Learning Terapan. Project ini membuat model machine learning yang dapat memprediksi harga rumah berdasarkan features tertentu

![enter image description here](https://www.dijones.com.au/-/media/project/dijones/corporate/library/news/blog-article-images/october-2023/understanding-the-housing-policy-landscape-header.jpg?rev=f273f5da59404f02869c35194327266f)

## Domain Project

### Latar Belakang
Proyek ini berfokus pada prediksi harga rumah berdasarkan berbagai fitur atau atribut tertentu. Melalui analisis data dan penerapan model machine learning, kita dapat mengidentifikasi faktor-faktor yang paling berpengaruh terhadap nilai properti. Tujuan dari proyek ini adalah untuk memberikan pandangan yang lebih akurat dan objektif terkait estimasi harga rumah, yang dapat bermanfaat bagi pemilik rumah, calon pembeli, dan pemangku kepentingan lainnya di industri properti.

Pemilik rumah dan investor dapat memanfaatkan prediksi harga untuk membuat keputusan investasi yang lebih cerdas, mengoptimalkan portofolio properti, dan merencanakan strategi finansial jangka panjang.

Proyek ini membantu mengidentifikasi faktor-faktor yang paling berpengaruh terhadap harga rumah. Hal ini dapat memberikan wawasan berharga bagi pemangku kepentingan untuk mengenali tren pasar dan mengukur dampak perubahan dalam lingkungan sekitar.

Dengan memberikan estimasi harga yang lebih akurat, proyek ini juga dapat meningkatkan transparansi pasar properti. Peningkatan transparansi ini dapat menguntungkan semua pihak yang terlibat dalam transaksi properti.

## Businesss Understanding 

Proyek ini dirancang untuk mendukung perusahaan properti yang memiliki atau membeli rumah dan apartemen, dan kemudian menyewakannya kepada konsumen. Fokus utama proyek ini adalah menyediakan layanan konsultasi harga sewa untuk properti yang dimiliki oleh perusahaan tersebut.

### Problem Statement : 

 - Bagaimana kita dapat meningkatkan ketepatan penentuan harga sewa rumah dan apartemen agar lebih optimal untuk meningkatkan pendapatan perusahaan properti?
 - Bagaimana kita dapat membuat model machine learning untuk memprediksi harga rumah di pasaran ? 
 - Apakah faktor-faktor apa saja yang paling berpengaruh terhadap penetapan harga sewa properti, dan bagaimana kita dapat mengidentifikasinya untuk meningkatkan strategi penetapan harga perusahaan properti?

### Goals

- Meningkatkan ketepatan penentuan harga sewa rumah dan apartemen untuk mencapai optimalisasi pendapatan perusahaan properti.
- Membuat model machine learning untuk memprediksi harga rumah berdasarkan features tertentu
- Mengidentifikasi faktor-faktor yang paling berpengaruh terhadap penetapan harga sewa properti untuk meningkatkan strategi penetapan harga perusahaan properti.


### Solution Statement

- Mengimplementasikan model machine learning yang canggih untuk memprediksi harga sewa rumah dan apartemen berdasarkan karakteristik properti dan faktor-faktor lainnya.
- Mengembangkan dan mengimplementasikan model machine learning yang dapat memprediksi harga rumah berdasarkan features tertentu seperti luas tanah, jumlah kamar, fasilitas, dan lokasi geografis.
- Melakukan analisis mendalam untuk mengidentifikasi faktor-faktor yang paling berpengaruh terhadap penetapan harga sewa properti.


## Data Understanding 

Dataset yang digunakan berasal dari https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data

Berikut adalah informasi dari dataset tersebut :

- Berbentuk CSV (Comma separated values)
- Berisi : 545 rows × 13 columns
- Price akan dijadikan sebagai column yang akan diprediksi, 12 column lain sebagai featuresnya 
- Tidak terdapat missing value di dalam dataset tersebut

Variabel Dalam dataset tersebut 

- Price: Harga sewa atau harga properti dalam mata uang tertentu.
- Area: Luas total tanah atau bangunan properti dalam satuan tertentu (misalnya, meter persegi).
- Bedrooms: Jumlah kamar tidur dalam properti.
- Bathrooms: Jumlah kamar mandi dalam properti.
- Stories: Jumlah lantai atau tingkat bangunan properti.
- Mainroad: Variabel biner yang menunjukkan apakah properti berada di jalan utama (1) atau tidak (0).
- Guestroom: Variabel biner yang menunjukkan apakah properti memiliki kamar tamu (1) atau tidak (0).
- Basement: Variabel biner yang menunjukkan apakah properti memiliki ruang bawah tanah (1) atau tidak (0).
- Hotwaterheating: Variabel biner yang menunjukkan apakah properti dilengkapi dengan pemanas air (1) atau tidak (0).
- Airconditioning: Variabel biner yang menunjukkan apakah properti dilengkapi dengan sistem pendingin udara (1) atau tidak (0).
- Parking: Jumlah tempat parkir yang tersedia untuk properti.
- Prefarea: Variabel biner yang menunjukkan apakah properti terletak di daerah yang disukai atau diinginkan (1) atau tidak (0).
- Furnishingstatus: Status furnitur dalam properti, seperti furnished (berperabot) atau unfurnished (tanpa perabot).

## Data Visualization

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85186dZbsSUad3iYw_8pS8ZrannaU_bxIHyXu_Z0fiZxp1nGm3qRT9ThDPoojenObPB4WwNkzEilW_Tg6JEAbe7d6Ymh2ncNcVsJfTbgJZhm-8xIpnWW3ANTl_5dwho5UpGUomBzXEUhsKw_q8r0VjQ4XTvoy_JR7M5XPzz0XdmcKRZSxehA72K-HoUGS9-vVZDe-XD4lNV-lEsbDuzKVNI9w7kUpjJSlw9wzn1W8hUru0pZFIfCn6KFBTgzDbQdZ4CDcnfjRcX8mbCrusEiWgubOCsidMChsR7h0eCKOfMx3yaX9g2ITqeI8HdOQY1qj7sPqOwHFWhs-8qgANMSwaRnwnly01FsMYEOVeJYsU1-mCLxYhrZoNb-hPAI5FFTDgwNm2s3cofbqO7mpyC-5bA-A7zFPvZPBSqKjywZXDkrum6hkcdgmP_qKLUFWA6C9M3jdRT_GtiN8NeQmQsE-ijjziq0hfdmKJJEZQfnbNLjiropCnLpcoyuFHcoR9IHcC6uGAZHT84ZtzeWWC_GCCoayq07XOWX75Us4nHOqWB5X3l21RkBjBVqbNwwpu5iVvMd2B9LtYBrZWpMMn_e7xMJyHD4tpA6KgnuGLUAOYv-w1voiJMIJEZyETxcqjvxgl6cu3KAJLL1iE8qLzMpVa0Cbw3AUVxPKrsfFJ18LVrsotVqz6Mo4BVyrF3SX5t-ZiP1bQ_CbiqIPvoxQajSJ83YzfaD03NQ8JPM-MAKZcMjXesGI6--ORLKWJgj6l7OXTbyiIlDXban4pmPOwqraHiixj6V3lrRPMs0EP66GoRexudIXm8hBrAGxWiyxJPTa-EpKRRCFSAqN0U2JxMD6As3zxDlIuMh0IK95xSZW0gxHzyl2FE9a4nEnD90_2i0A=w846-h547-s-no-gm?authuser=0)

Analisis korelasi harga dengan feature lain 

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85FVi4AClL-HLOYfvyx2fOAySS_Uvk7jDPjRUcHx2MrfbT1KM48asB6BuE6n2Mt511oJ9onxgi-BTDP1JzMw1u49cu1JacvjN-3Coeto_Gt2zul4mNGnz9yiDtBhGd_gwGsuwBSv4XsUbsXBC32nxhhWCa0NFWnUfxCDA7Vgk0Ei-chHGzP2m3m4HKsmW2v7rCvcM50CYP5Fs86p2hp-5Tc_dhFDDAmksWvWLKqW-uNwKNWCA3qJnEsLbr50FrxTOTE8JPknALUR7GmYtltMofGeQrvz5lORVqafw-wgigePyI_LSMjlBzHtStp95l55kT6wQzGYDaKFDK5IvGUlCIPw2ioRPds-N9uP8T9eScDBWLGyOBqdJ_aFZWnjsm21A0qlESaKjBiwSje4Hp0ePaoWrCyjUqVdXJqBMUWUdfwmmbWUjNMLBcTZ7dHnUIMuJLrKOdoSdKBU8daM9mgSCycutwkE4JKX2tNVVBY_-qVWvMdA3UIDT0gcjwBwre1q4fg7hViDrrDpasvs49lUrJRYYEnLg63e83eU9rycjXhfXwJtxAl2N3WxhpQV8_5iK5xgYUqKIGbhkmXu8pji7xGC2GCv0j-c-qbKHnZ5j8TSvN1G7aYY4aKFZq-sQn9_IRWcyOJcEm01vIrd7vyG_OATrE-6Gie0qC_CrH81tqOkh5Rl4TrIN6CwbF0WAZEYRqwbTQHRv4E0L1arS42UBJYlo3DAjS227sCFdWG15kMjy1QzIBqBjllcu-nMaoXYpIYHJqM_ypztSfkwHdaUle9T_-YrM8ThXvgJJ96yssex1yX2x895h0sRIyS4o8ePJ2dOkgYOQWPija19VjE8fAm_KlIyTCZh6qCIQi7oaXr49Q07qoCReiEVRrBEN5AKg=w764-h682-s-no-gm?authuser=0)

Distribusi Harga
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87mOPoLknUlVcwUubiymho93oyWZ9nZctn83zqrj5k7ZbJR7nRW_uFwRjwK_4G5gREPl8fGbDA1z7JxKA7Jt68zdEy3MziWS2Fao9P24GA9TStIUWwDAuWhJeGZrgYw9hv78Y66PbzoINZSdbbIr3GA9sKuH64CsD4x4nc5bvqgpli1ho2m17wr_6ybpVr7Sgg-Z9wlh_HMKP9mgapvatqJlUkTNVM9cu8JCszQGV2sbcTjR3xfExr6cl4zC2cC7RQC4LEopTIZ0mbOnHaYMUdnoMyai3t5fYE700nL-NA0MZjro0Yeha7ekES9KPpGC2hvKn3Y3XAIZQsVC5a-Z-QlD6evKsTjRxi8lX-DnTikcHNSdn3_ChC1oZLdxbUrAk5jW6w3YhVG-ImYhynVJzZ7vlyGQUB0kRCvPzhNAfAPVykrAGYjbIjLle83MDRvQrEnksofzfClMJkCuXduEk_Kzd06LfJ0o8QdcASpiBj2ddKwTJliBO68TlTe_OSvj7MmCbQFcy_oVdVd5M7u_AtBBkflnwsTISOwz6jUaXBqLA6TthihL7d2aL-BTkpCpp8C_z6P1a0usZiOqY2mwo5MZWmkBodTwxZX3A3eCqzo50t6hFGV1YT8nXwpafKFhqyN4dVlJiHw96RvZKgLQ1b8I_xVdJRudtteRnC1YV_HiNY-QQ6H9D6fbxq2cYghUhX86r8X2ZVO_UxwoiIbYkMylPVkC0FLZUkN5qJYVhAFlLVstMBuj3lnYiOLGA48NP_nrz8qCTZ4kdIwyumZnvGT4mGzCikFJAtrTK_XsbIUGLU64xBLUgSD_OsJjNSStid4AbOlxwAzOQeFqyNe2vvpOv9lGb9iAqbtuW_342P6H4kiVaqB673gBB98UW675w=w841-h547-s-no-gm?authuser=0)

### Data Preparation

- One Hot Encoding / Create a Dummy Variabel
Dalam tahapan ini, kita melakukan pengkodean atau transformasi terhadap variabel kategorikal pada dataset menggunakan metode one-hot encoding. Variabel kategorikal seperti 'mainroad', 'guestroom', dan lainnya diubah menjadi representasi numerik biner (0 atau 1) untuk memungkinkan penggunaan algoritma machine learning. Penggunaan fungsi `get_dummies` dari pandas membantu menghasilkan kolom-kolom baru yang merepresentasikan setiap nilai unik dari variabel kategorikal, sambil menghindari jebakan multikolinearitas dengan mengatur `drop_first=True`. Hasilnya adalah dataset yang siap digunakan untuk melatih model machine learning dengan fitur-fitur yang telah dikodekan dengan tepat.


- Data Normalization
Pada tahap ini, kita menggunakan `MinMaxScaler` dari scikit-learn untuk melakukan normalisasi pada variabel numerik seperti "area", "bedrooms", dan "price". Normalisasi dilakukan dengan mengubah nilai-nilai tersebut ke dalam skala antara 0 dan 1, memastikan setiap variabel numerik memiliki rentang nilai yang seragam. Hal ini membantu meningkatkan kinerja model machine learning, terutama pada algoritma yang sensitif terhadap skala variabel. Hasilnya adalah dataset yang telah dinormalisasi dan siap digunakan untuk pelatihan model.

- Split the Data 
Pada tahap ini, kita menggunakan `train_test_split` dari scikit-learn untuk membagi dataset menjadi dua subset, yaitu data latih (training set) dan data uji (test set). Variabel independen (X) berisi fitur-fitur yang akan digunakan untuk memprediksi variabel dependen (y), yang dalam kasus ini adalah "price" atau harga properti. Pengaturan `test_size=0.20` menentukan bahwa 20% dari data akan dialokasikan sebagai data uji, sementara 80% digunakan sebagai data latih.


### Modeling 
Dalam membuat model ini menggunakan 3 jenis algoritma yang akan dibandingkan, yaitu Linear Regression, Random Forest, dan Gradient Boosting

1.  **Linear Regression:**
    
    -   **Deskripsi:** Algoritma regresi linear digunakan untuk memodelkan hubungan linear antara variabel independen (fitur) dan variabel dependen (harga sewa).
    -   **Kelebihan:** Sederhana, mudah diinterpretasi, cocok untuk kasus di mana hubungan antar variabel bersifat linear.
    -   **Keterbatasan:** Tidak efektif untuk pola yang kompleks atau hubungan non-linear.
2.  **Random Forest:**
    
    -   **Deskripsi:** Algoritma ensambel yang membangun beberapa pohon keputusan secara bersamaan dan menggabungkan hasilnya untuk meningkatkan keakuratan dan kinerja model.
    -   **Kelebihan:** Dapat menangani pola yang kompleks, memiliki toleransi terhadap overfitting, dan dapat memberikan wawasan tentang pentingnya fitur.
    -   **Keterbatasan:** Kompleksitas model dapat membuat interpretasi kurang langsung.
3.  **Gradient Boosting:**
    
    -   **Deskripsi:** Algoritma ensambel lain yang membangun serangkaian model prediktif dan mengkombinasikan hasilnya, dengan fokus pada memperbaiki kesalahan model sebelumnya.
    -   **Kelebihan:** Efektif untuk mengatasi overfitting, memberikan kinerja yang baik, dan cocok untuk data kompleks.
    -   **Keterbatasan:** Proses training mungkin membutuhkan waktu lebih lama dibandingkan dengan algoritma lain.

Dalam tahap ini, saya melakukan Grid Search CV untuk mencari parameter terbaik pada setiap algoritma. Berikut adalah pembagian singkat untuk masing-masing algoritma dengan hasil terbaik:

1.  **Linear Regression:**
    
    -   **Best Score:** 0.696927
    -   **Best Parameters:** Tidak ada parameter yang dioptimalkan karena model Linear Regression bersifat linier dan tidak memiliki hyperparameter yang diatur.
2.  **Random Forest:**
    
    -   **Best Score:** 0.675772
    -   **Best Parameters:** {'max_depth': 10, 'n_estimators': 150}
    -   **Interpretasi:** Model Random Forest memberikan kinerja terbaik ketika kedalaman maksimum pohon (max_depth) diatur pada 10 dan jumlah pohon (n_estimators) diatur pada 150.
3.  **Gradient Boosting:**
    
    -   **Best Score:** 0.672297
    -   **Best Parameters:** {'learning_rate': 0.1, 'n_estimators': 150}
    -   **Interpretasi:** Model Gradient Boosting memberikan hasil optimal dengan tingkat pembelajaran (learning_rate) sebesar 0.1 dan jumlah estimator (n_estimators) sebanyak 150.


### Evaluation

Metriks evaluasi yang digunakan untuk mengukur kinerja model adalah sebagai berikut:

1.  **Linear Regression:**
    
    -   **Mean Squared Error (MSE):** 0.015291
        -   Merupakan rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual. Semakin rendah nilainya, semakin baik modelnya.
    -   **Mean Absolute Error (MAE):** 0.094039
        -   Merupakan rata-rata dari nilai absolut selisih antara nilai prediksi dan nilai aktual. Semakin rendah nilainya, semakin baik modelnya.
    -   **R-squared:** 0.674593
        -   Merupakan proporsi variabilitas dalam data yang dapat dijelaskan oleh model. Nilai maksimumnya adalah 1, dan semakin tinggi nilainya, semakin baik modelnya.
2.  **Random Forest:**
    
    -   **Mean Squared Error (MSE):** 0.002743
    -   **Mean Absolute Error (MAE):** 0.037614
    -   **R-squared:** 0.941625
        -   Hasil R-squared yang tinggi menunjukkan bahwa model Random Forest mampu menjelaskan sebagian besar variabilitas dalam data.
3.  **Gradient Boosting:**
    
    -   **Mean Squared Error (MSE):** 0.007734
    -   **Mean Absolute Error (MAE):** 0.065887
    -   **R-squared:** 0.835422
        -   Meskipun R-squared Gradient Boosting tidak sebaik Random Forest, nilai tersebut tetap tinggi dan menunjukkan kemampuan model dalam menjelaskan variasi dalam data.

Dengan melihat metriks-metriks ini, kita dapat mengevaluasi dan membandingkan kinerja relatif dari ketiga model tersebut. **Model Random Forest** memberikan hasil yang sangat baik dengan nilai MSE dan MAE yang rendah, serta R-squared yang tinggi, menunjukkan kemampuannya dalam memprediksi harga sewa properti dengan akurat.

Contoh pengujian di atas menunjukkan nilai prediksi dari tiga model (Linear Regression, Random Forest, dan Gradient Boosting) untuk beberapa data uji (y_true) dengan hasil berikut:

| y_true | pred_Linear Regression | pred_Random Forest | pred_Gradient Boosting |
|--------|-------------------------|--------------------|-------------------------|
| 20     | 0.952381                | 0.5                | 0.8                     |
| 21     | 0.942857                | 0.6                | 0.9                     |
| 22     | 0.938095                | 0.6                | 0.8                     |
| 23     | 0.938095                | 0.6                | 0.8                     |
| 24     | 0.928571                | 0.7                | 0.9                     |

Dari tabel tersebut, kita dapat membandingkan nilai prediksi dari masing-masing model untuk setiap data uji dengan nilai sebenarnya (y_true). Evaluasi kinerja model dapat dilakukan dengan membandingkan sejauh mana nilai prediksi mendekati nilai sebenarnya. Secara visual, kita dapat melihat perbedaan antara kolom prediksi dari masing-masing model dengan kolom y_true. Evaluasi lebih lanjut dapat dilakukan dengan menggunakan metriks seperti Mean Squared Error (MSE) atau Mean Absolute Error (MAE) untuk membandingkan secara kuantitatif.
