


# First Project : Housing Prediction 

**Dibuat oleh : Wendi Kardian**

Project Pertama dalam Predictive Analytics untuk memenuhi submission project dari Dicoding, dalam kelas Machine Learning Terapan. Project ini membuat model machine learning yang dapat memprediksi harga rumah berdasarkan features tertentu

![enter image description here](https://www.dijones.com.au/-/media/project/dijones/corporate/library/news/blog-article-images/october-2023/understanding-the-housing-policy-landscape-header.jpg?rev=f273f5da59404f02869c35194327266f)
Gambar 1. Miniatur Housing
## Domain Project

### Latar Belakang
Proyek ini berfokus pada prediksi harga rumah berdasarkan berbagai fitur atau atribut tertentu. Melalui analisis data dan penerapan model machine learning, mengidentifikasi faktor-faktor yang paling berpengaruh terhadap nilai properti. Tujuan dari proyek ini adalah untuk memberikan pandangan yang lebih akurat dan objektif terkait estimasi harga rumah, yang dapat bermanfaat bagi pemilik rumah, calon pembeli, dan pemangku kepentingan lainnya di industri properti.

Dalam lingkungan pasar properti yang dinamis, konsumen semakin menuntut informasi harga yang transparan dan akurat untuk membuat keputusan sewa yang informatif. Bagi perusahaan properti, memiliki strategi penetapan harga yang tepat dapat meningkatkan daya saing dan mengoptimalkan pendapatan. Model prediksi harga dapat menjadi alat yang sangat berharga dalam pengambilan keputusan ini. Adopsi teknologi dan kecerdasan buatan (AI) semakin meningkat dalam industri properti. Model prediksi harga adalah contoh konkrit dari bagaimana teknologi dapat digunakan untuk meningkatkan efisiensi dan ketepatan dalam pengelolaan properti. Mengingat ketidakpastian ekonomi dan perubahan tren pasar, kemampuan untuk merespons dan mengadaptasi strategi penetapan harga secara cepat dapat menjadi kunci kesuksesan di industri properti. Analisis data semakin menjadi elemen kritis dalam pengambilan keputusan bisnis. Model prediksi harga membuktikan kekuatan analisis data dalam memberikan wawasan yang mendalam untuk mendukung strategi bisnis.


Pemilik rumah dan investor dapat memanfaatkan prediksi harga untuk membuat keputusan investasi yang lebih cerdas, mengoptimalkan portofolio properti, dan merencanakan strategi finansial jangka panjang.

Proyek ini membantu mengidentifikasi faktor-faktor yang paling berpengaruh terhadap harga rumah. Hal ini dapat memberikan wawasan berharga bagi pemangku kepentingan untuk mengenali tren pasar dan mengukur dampak perubahan dalam lingkungan sekitar.

Dengan memberikan estimasi harga yang lebih akurat, proyek ini juga dapat meningkatkan transparansi pasar properti. Peningkatan transparansi ini dapat menguntungkan semua pihak yang terlibat dalam transaksi properti.

Daftar Referensi : 
- https://media.neliti.com/media/publications/431010-machine-learning-based-prediction-of-hou-95945440.pdf
- https://www.researchgate.net/publication/367317216_Machine_Learning_for_Housing_Price_Prediction


## Businesss Understanding 

Proyek ini dirancang untuk mendukung perusahaan properti yang memiliki atau membeli rumah dan apartemen, dan kemudian menyewakannya kepada konsumen. Fokus utama proyek ini adalah menyediakan layanan konsultasi harga sewa untuk properti yang dimiliki oleh perusahaan tersebut.

### Problem Statement : 

 - Bagaimana meningkatkan ketepatan penentuan harga sewa rumah dan apartemen agar lebih optimal untuk meningkatkan pendapatan perusahaan properti?
 - Bagaimana membuat model machine learning untuk memprediksi harga rumah di pasaran ? 
 - Apakah faktor-faktor apa saja yang paling berpengaruh terhadap penetapan harga sewa properti, dan bagaimana mengidentifikasinya untuk meningkatkan strategi penetapan harga perusahaan properti?

### Goals

- Meningkatkan ketepatan penentuan harga sewa rumah dan apartemen untuk mencapai optimalisasi pendapatan perusahaan properti.
- Membuat model machine learning untuk memprediksi harga rumah berdasarkan features tertentu
- Mengidentifikasi faktor-faktor yang paling berpengaruh terhadap penetapan harga sewa properti untuk meningkatkan strategi penetapan harga perusahaan properti.


### Solution Statement

- Mengimplementasikan model machine learning yang canggih untuk memprediksi harga sewa rumah dan apartemen berdasarkan karakteristik properti dan faktor-faktor lainnya.
- Mengembangkan dan mengimplementasikan model machine learning yang dapat memprediksi harga rumah berdasarkan features tertentu seperti luas tanah, jumlah kamar, fasilitas, dan lokasi geografis.
- Melakukan analisis mendalam untuk mengidentifikasi faktor-faktor yang paling berpengaruh terhadap penetapan harga sewa properti.

### Manfaat
Proyek prediksi harga sewa properti memiliki potensi dampak positif yang signifikan bagi berbagai pemangku kepentingan dalam industri properti. Berikut adalah identifikasi potensi dampak positif secara lebih rinci untuk beberapa pihak terkait:

1.  **Pemilik Rumah:**
    
    -   Pemilik rumah dapat mengoptimalkan pendapatan dari penyewaan properti pemilik rumah dengan menggunakan model prediksi harga. Dengan menetapkan harga sewa yang akurat dan kompetitif, pemilik rumah dapat memaksimalkan pendapatan secara efisien.
    -   Model ini dapat membantu pemilik rumah dalam pengambilan keputusan terkait penetapan harga sewa berdasarkan karakteristik properti dan kondisi pasar saat ini.

2.  **Calon Pembeli atau Penyewa:**
    
    -  Calon pembeli atau penyewa akan mendapatkan manfaat dari transparansi harga yang diberikan oleh model. Pembeli dapat membuat keputusan yang lebih informasional dan tepat berdasarkan prediksi harga yang akurat.
    -  Dengan pemahaman yang lebih baik tentang harga sewa yang diharapkan, calon pembeli atau penyewa dapat melakukan negosiasi yang lebih efektif dengan pemilik rumah.

3.  **Pemangku Kepentingan Industri Properti:**
    
    -  Proyek ini mencerminkan inovasi dalam industri properti dengan menerapkan teknologi dan kecerdasan buatan. Ini dapat merangsang tren positif dalam penerapan solusi data-driven di sektor properti.
    -   Pemangku kepentingan di perusahaan properti dapat meningkatkan daya saing pihak berkepentingan dengan mengadopsi model prediksi harga. Ini membantu pihak perkepentingan mengoptimalkan portofolio properti dan strategi penetapan harga.


## Data Understanding 

Dataset yang digunakan berasal dari https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data

### Informasi dataset

- Berbentuk CSV (Comma separated values)
- Berisi : 545 rows × 13 columns
- Price akan dijadikan sebagai column yang akan diprediksi, 12 column lain sebagai featuresnya 
- Tidak terdapat missing value di dalam dataset tersebut

### Variabel Dalam dataset tersebut 

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

### Data Visualization


![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85186dZbsSUad3iYw_8pS8ZrannaU_bxIHyXu_Z0fiZxp1nGm3qRT9ThDPoojenObPB4WwNkzEilW_Tg6JEAbe7d6Ymh2ncNcVsJfTbgJZhm-8xIpnWW3ANTl_5dwho5UpGUomBzXEUhsKw_q8r0VjQ4XTvoy_JR7M5XPzz0XdmcKRZSxehA72K-HoUGS9-vVZDe-XD4lNV-lEsbDuzKVNI9w7kUpjJSlw9wzn1W8hUru0pZFIfCn6KFBTgzDbQdZ4CDcnfjRcX8mbCrusEiWgubOCsidMChsR7h0eCKOfMx3yaX9g2ITqeI8HdOQY1qj7sPqOwHFWhs-8qgANMSwaRnwnly01FsMYEOVeJYsU1-mCLxYhrZoNb-hPAI5FFTDgwNm2s3cofbqO7mpyC-5bA-A7zFPvZPBSqKjywZXDkrum6hkcdgmP_qKLUFWA6C9M3jdRT_GtiN8NeQmQsE-ijjziq0hfdmKJJEZQfnbNLjiropCnLpcoyuFHcoR9IHcC6uGAZHT84ZtzeWWC_GCCoayq07XOWX75Us4nHOqWB5X3l21RkBjBVqbNwwpu5iVvMd2B9LtYBrZWpMMn_e7xMJyHD4tpA6KgnuGLUAOYv-w1voiJMIJEZyETxcqjvxgl6cu3KAJLL1iE8qLzMpVa0Cbw3AUVxPKrsfFJ18LVrsotVqz6Mo4BVyrF3SX5t-ZiP1bQ_CbiqIPvoxQajSJ83YzfaD03NQ8JPM-MAKZcMjXesGI6--ORLKWJgj6l7OXTbyiIlDXban4pmPOwqraHiixj6V3lrRPMs0EP66GoRexudIXm8hBrAGxWiyxJPTa-EpKRRCFSAqN0U2JxMD6As3zxDlIuMh0IK95xSZW0gxHzyl2FE9a4nEnD90_2i0A=w846-h547-s-no-gm?authuser=0)
Gambar 2. Box plot antara harga dan kondisi airconditioning



![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85Vr9E8Wgrao3BUUSr93xN4qE-pX5qJ_PyfVe0GD5hZdYT5Zh8A6-z7iohERmmCuBbQInui9TtkvJVIiA69_cBMSAvmKRI-aD0DtsAyt5Y2AF7e__OYj8fVrYwKLDFt6iaMs84tD2y9bKrBoh5I-rGUghjr6ax-B-HuZ2hv0GHwmO-aPq5XzNCjpJCiEy6aupWECpWkrGADym_CaVx7dTGRSzQ5b7VAOl6qM3G-vdLfZP5VObTdveklMbGTD1VArmPvYbXr283gCF53QClGPau8RBlN8fZCldPteQRT_3TRX4Jx4RGaw-mQkaP9SImpasg5KXPuR3pFbylb40HukboJCb6y1kkRQkmEPk32E6jRW3z-6dKSqqZOmxQttrqZc3VGAfS44X3fqruk31cSmT_lx72u7lz3b1EbO4GmhVDpOJGbpGn45QdafLP9xc3wqnH-6rTOCEeZ_Py4agpyRr3bkMzXOLIuSbxELluLwy6KUbdXL77JHRiZVvrEg9Sb3ZUNBmw8_ZXENfE-kgzJYicm18yqjlNtDWQJfciwTctPD4Z9eLdgBHXNu0awg5y89rwvT9cvpjdtQPrZ-pqs67-4DVmE8ZmaoiLxQT29LptlwVzDVnYbkPnxwiL2Fvk7ipoHtw2-tFb4fo1oFrM5oiu7gNtoBpBLEy_8Pcy5XyLzaEcApLqN4HQ1DVTZORlFJU4WMU8n3e6p_RqC3gh2IS__XvN1urKh9oqx-mQBwkLHv16dioat1Y9gFcS6Jjvqrs9luUEJnhn040xbhTO60TXAfwOWoxQVU3XY5IIw8T24uuq3X8tQQ3O7jXA8zPRG9yeKqS3J6iWGaWk_yUzeRIZxkCmOcpQ2SITm6i6fvXrPtVWfN4d3CjlHNMUF2MEXtw=w846-h547-s-no-gm?authuser=0)
Gambar 3. Scatterplot antara area dan harga


![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87oFwmh2dyHEq97JI6lHcu1dLN-w3ByHXs2M8-GIMQ1EdIyAFeAeXAt94KrlzWrPZ8fR3nOO-2yxfUbdOAniteSiruk83Mu1Qa6YAaGHER65RDkeXBZ1ErVZOz6pf3STm6pvwitMO6FtCgGm4LWrSZp8Okhi2mB0PB3WuqotgOp95SnXNyG8YysVEZX2sV1NxUAjqSKU3bfICur5K0fdBtwqikKJyBxrwd2a_pU8BhB_MQ-c7sCk3HU7REk-rz2mLkwNb9WeskVqzUpYzAkiSnHXQQqxXTP7n35yYL1nSsxXmX-9KoGNY2SVDO6x0XhkNt9Z902siCeNqfcKBagP7ARTtKqHsPvtbHuJJ6fx5wcAtEotsHvWKay1GVGpCM_YmAxgCEoTbd0Cq-jUAqtaiFpezLloZqqDA10VIFemofOyjymXD0BQGRG59WOSuK7ciKVFE1NkCbNMJz8XieZqc0ahOAFhiD7rLAU353DHp-apoeI5cv7WHrcqhAZjVo7fXr2Z89pwEpczFWdvBMcyqKEG4ZYqwTyct0oVHTnpvluLVT12jVPw4OvShq4V4XzSta7MgaYBZkTGBsphf7UJpvM8JRByNSHywiWHF-hpcoV7b8DMhORyFeJl1ffiSHpMXvJDTPDSqVZ4xQJmn11S1Lze-l9y5xNqU2VG3VHAtZU80d7dVbu-IgvwvBsBA-uAS-wxRAIvLo5eBzEBF50ZexpSBDxR2tnOREf2vzN2so8bahYjjazDepAut7O11j9HFRsG1CE_JoSc18SoricLGrWfA2C3R_qwqk6pOcQPBaidTWWhT7ZiXhUhXi0I38WnRqTzzgtdyF7qUTWLLNFHHCqc3K6nAcRU_IxyR6J0AH0myd5JDwt39B5FrsJnf7d_A=w1001-h547-s-no-gm?authuser=0)
Gambar 4. Harga berdasarkan kamar tidur dan kamar mandi


![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85bB3s5_YH8FKTIN8lEjcZJr8aNzCVZUVqo_LF3A9gAakQVH4OLx5sXTNGUrF1U5-m5ax9dGr7Wh2COLBQ3VyDUts9r4CfrF8HrbdJu7jqYXOmX66PnONw26qtqgoG4YuDwfqtwy0NtJfcJ-gFPc6nN1XvjzzSAtvOrJC2uQ5aBNzkWbsigzXhI0tzX-SbEBaNOecAZAmOaX6YytEzxrWlMKcQQXdR-aSblq7lgGmaK4ecTVh6UvGawhlE27zX2OpQZKbmTcdo7EJlVXusuObCqGswTlFgWDRMikLE2hiccecUzv63FFebuy-4XuEyHZ0y8jUvQlysKvCh65ZRqcVDKk3k8wivbDNqWuAQgZOatpLrfAocMI8Be1ee7jIQejdu0f1fe9FILWeViknHT58SNXei2YfpM_8ipRHLlUukP1f4Lu2jaZUetmOqSl-3_ZDhwf9cys7Xg2gyOj0JsrFiw6h1zDYa6t_sn7ACzF7bgikZX-jVxhrMoVlEFGdcAkcLeivPNJ6gA8nKvniUgg_lkCNI0Z44EU1GT1hjSv1xL91foNucxY5jZTC62mwRMPUS2xwS9cj-dVfe7ArGYKpAp4qajKmD1HGo9NEQlXxOHmG7kfyPrIQOgPPmxH1JKWgdR1LB1WrsdpNuDmUpe3zik66E7PqF1xGVJJ4ffF7Bf91XDOSsbbk1-K3JFcXRCAmmN4TcEhwAE7tNyH7vwoX9w3ehd6fMfzSchSFIHq8aynozbKBr8PtdVnobD-bbxFbDat1lUe0GGvF7xWwUhL29w2j-e45tiPiiNtxgvsdFy97k5K43wff_raeQPgJMCD0Ut6QcPiF5wP7ltpCHZS7KFm0ALvgOjL-Tjxx2oPvIRbQ1lDAW4SSJnsmQdtT2ZKw=w1160-h470-s-no-gm?authuser=0)
Gambar 4. Countplot perbandingan *parking availability* dan ketersediaan air conditioning


![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85FVi4AClL-HLOYfvyx2fOAySS_Uvk7jDPjRUcHx2MrfbT1KM48asB6BuE6n2Mt511oJ9onxgi-BTDP1JzMw1u49cu1JacvjN-3Coeto_Gt2zul4mNGnz9yiDtBhGd_gwGsuwBSv4XsUbsXBC32nxhhWCa0NFWnUfxCDA7Vgk0Ei-chHGzP2m3m4HKsmW2v7rCvcM50CYP5Fs86p2hp-5Tc_dhFDDAmksWvWLKqW-uNwKNWCA3qJnEsLbr50FrxTOTE8JPknALUR7GmYtltMofGeQrvz5lORVqafw-wgigePyI_LSMjlBzHtStp95l55kT6wQzGYDaKFDK5IvGUlCIPw2ioRPds-N9uP8T9eScDBWLGyOBqdJ_aFZWnjsm21A0qlESaKjBiwSje4Hp0ePaoWrCyjUqVdXJqBMUWUdfwmmbWUjNMLBcTZ7dHnUIMuJLrKOdoSdKBU8daM9mgSCycutwkE4JKX2tNVVBY_-qVWvMdA3UIDT0gcjwBwre1q4fg7hViDrrDpasvs49lUrJRYYEnLg63e83eU9rycjXhfXwJtxAl2N3WxhpQV8_5iK5xgYUqKIGbhkmXu8pji7xGC2GCv0j-c-qbKHnZ5j8TSvN1G7aYY4aKFZq-sQn9_IRWcyOJcEm01vIrd7vyG_OATrE-6Gie0qC_CrH81tqOkh5Rl4TrIN6CwbF0WAZEYRqwbTQHRv4E0L1arS42UBJYlo3DAjS227sCFdWG15kMjy1QzIBqBjllcu-nMaoXYpIYHJqM_ypztSfkwHdaUle9T_-YrM8ThXvgJJ96yssex1yX2x895h0sRIyS4o8ePJ2dOkgYOQWPija19VjE8fAm_KlIyTCZh6qCIQi7oaXr49Q07qoCReiEVRrBEN5AKg=w764-h682-s-no-gm?authuser=0)
Gambar 5. Analisis korelasi harga dengan feature lain 


![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87mOPoLknUlVcwUubiymho93oyWZ9nZctn83zqrj5k7ZbJR7nRW_uFwRjwK_4G5gREPl8fGbDA1z7JxKA7Jt68zdEy3MziWS2Fao9P24GA9TStIUWwDAuWhJeGZrgYw9hv78Y66PbzoINZSdbbIr3GA9sKuH64CsD4x4nc5bvqgpli1ho2m17wr_6ybpVr7Sgg-Z9wlh_HMKP9mgapvatqJlUkTNVM9cu8JCszQGV2sbcTjR3xfExr6cl4zC2cC7RQC4LEopTIZ0mbOnHaYMUdnoMyai3t5fYE700nL-NA0MZjro0Yeha7ekES9KPpGC2hvKn3Y3XAIZQsVC5a-Z-QlD6evKsTjRxi8lX-DnTikcHNSdn3_ChC1oZLdxbUrAk5jW6w3YhVG-ImYhynVJzZ7vlyGQUB0kRCvPzhNAfAPVykrAGYjbIjLle83MDRvQrEnksofzfClMJkCuXduEk_Kzd06LfJ0o8QdcASpiBj2ddKwTJliBO68TlTe_OSvj7MmCbQFcy_oVdVd5M7u_AtBBkflnwsTISOwz6jUaXBqLA6TthihL7d2aL-BTkpCpp8C_z6P1a0usZiOqY2mwo5MZWmkBodTwxZX3A3eCqzo50t6hFGV1YT8nXwpafKFhqyN4dVlJiHw96RvZKgLQ1b8I_xVdJRudtteRnC1YV_HiNY-QQ6H9D6fbxq2cYghUhX86r8X2ZVO_UxwoiIbYkMylPVkC0FLZUkN5qJYVhAFlLVstMBuj3lnYiOLGA48NP_nrz8qCTZ4kdIwyumZnvGT4mGzCikFJAtrTK_XsbIUGLU64xBLUgSD_OsJjNSStid4AbOlxwAzOQeFqyNe2vvpOv9lGb9iAqbtuW_342P6H4kiVaqB673gBB98UW675w=w841-h547-s-no-gm?authuser=0)
Gambar 6. Distribusi Harga




![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV84ZJ_5z3xQiNbK2rr8tgYg2DqhLF4aiuhZ7-d5JX5b4CPFPmxgYwYULU9e1ASJSnipC2kGY21CdyJoDMt5yIEAYnUNfobQTHgo3_4SgRhb1NqBREfdJCK5rSELbTUFY6s1Ak13K2EMKv-8KOtz8kXeh0Qv6ZM9PSbjFrD3AG88f4R3UhNUkIB5iRcuQDnuPd36gn4YgsGA37yOzZMfg2eJknNElh8Q1FFOgzBUekPqXzOfZL5gQjPvn1n7wCf9Jp67wqt1MUAjG4OYwY6S1eRZmuFRyQjlG03jcr5Jf2AbR7vak3xaLxez7wJCvjEY3aJvXZDpzv6Em-cTds-zhY8clhnO3LcOO2sI7InIFf8-KqPMQa88gC0adIxODyq7WhD3kkyV62Bv7mjXWHh5SY2ZFnpQ8UsCzeA2roIzrHnv7WhSKwPx7C3jbhseYKbhJp0uIo5u7sivfXWwOgf--vpKFq08e_1NAiTJR2yReqvnZkxzdRpdjAoNBfbUPtJLjj_A7MYxYlbdHiv9c9Ya7brN-gaH1F7JCw1C4x_HWyR750zDB9nwKD1T-tbyKHMmrklL6dnetaVyZRH1QUrVmDxQQ8rhAA49c8yUHt9LTyhoPDxcr6MnGQTEdPvzPLjQKH1i1KAbr2hoEMz2DE5t19SFxi_G1QFxeAESoHJeoqC77V3z_M2WZDMuQSvZ0a9JVfr8wGrCTPoxZ5kE598TxP8oYBeSSjOxRczczx-geK9l8od9gvNhtJ9oaYsEeiSg8neR_Nb4aP4BfmS48PL3rqcXwsaLIw6KRBKroAos9qOq2Ezhwe-rLq5bHfgAa4AniofzlZ02SoHa-J2VLjQpO9n3HzriuNRa2adxLPtFtxxeOQp7A2U2j4eh4MUSD5xYYKg=w968-h968-s-no-gm?authuser=0)
Gambar 7. Pairplot antar features dalam dataset

### Data Preparation

- ***One Hot Encoding / Create a Dummy Variabel***
Dalam tahapan ini, dengan melakukan pengkodean atau transformasi terhadap variabel kategorikal pada dataset menggunakan metode one-hot encoding. Variabel kategorikal seperti 'mainroad', 'guestroom', dan lainnya diubah menjadi representasi numerik biner (0 atau 1) untuk memungkinkan penggunaan algoritma machine learning. Penggunaan fungsi `get_dummies` dari pandas membantu menghasilkan kolom-kolom baru yang merepresentasikan setiap nilai unik dari variabel kategorikal, sambil menghindari jebakan multikolinearitas dengan mengatur `drop_first=True`. Hasilnya adalah dataset yang siap digunakan untuk melatih model machine learning dengan fitur-fitur yang telah dikodekan dengan tepat.
Berikut adalah data sebelum proses ini :
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87nTcXZfZfCEir9ZmbyyWiLapDxiAB-K5Wzj1VF0ZuL7g-mTtNsZ0q5R_Sb__W2P8pk34SQ2ouiB42OKmBeRlkDv9ssOhB1l47_pRW2QOR3tDrqunJPVCZoav8ilpuQbSiZ2Dt9LaAZ1vcbkAn8-kks5TmHzf2zk8MxxQ0hsxMwHTBpZ4fYkDZCPNWqrYC9dFFtsFoN7OXCW7vn8PiPrR6-1Uuh2Xdjz0nIPW2dkSLiMfBm92JIeo6S4_ASElrv1jcXEubK0cVS0xG6r6-_XUogHG82pTN7kzBkX9cX_A9zyuimRFZ3eZIQoRkgim2JUbsCBqANt5RDXEyG5Ycok19xv3DHN5tA-6iNEvn0iRXHVxKQp5qOyOBWeVVw0YhZVjQPVJtVmhA7h_ZuxGmE6r1vVX2SM7Lvd-GcyF4FkVwaXy99SDVsm-VururViHZPb4ElIYwS8yC8NA90y8WmHmQAEtLUkSrTQ1HRPfpdRVYQMhqihjHckcCa3KeAEvJJboTbzIk0YZeMdW35bBXowOQtyigfEg-9QNk17iq65CvBHb9Xmn84eS_XKHEULrG659-5c8zJ-uqLKk45FQ-1DOcp_B5IT3XstiMu9xC-619IF1Olpc8QXnqCK4QdulRFVsDd2QysSkkuqUT1K6K9hAPZlohimhebPNChFOTLJ2gujnQVGhLeT6RsO_qBgqFaRNHm8CoIc0qo16Db7zQiQUo5MzgR9s8fe1cAaipq3q0imJsBGzGykt48yIe5jnNx8j2EN4EAPFDYu5mIwioeVCYhOgqc_H4gUH3MbUDfZbzKcmADDXtAAqrcM8bPdZ4vKNOg70OwZVm1erA7Z_yhTDEkm0VRI2BJVolIizSyOpSmO0v4G8XUNeUzNbVVQu2-nQ=w1496-h522-s-no-gm?authuser=0)
Gambar 8. Sebelum tahap *One Hote Encoding*

Setelah proses *One Hot Encoding* : 
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV85Mo6a-ExIXNqjrUeiq_SNk9eDTgkfgSWjBdbprqjDCykn0x6SrdPirUHwW_LHe5tRUH2rUEWLqfKZbhlJs7kVeNCDo8PXcUQ810PACBuV16Zxa4dhAzgHobo_yoXQIB5l6DTvQjADKk9yP8IUgXug8VMi66Bq880FLzD1kqoSJxXS2qP3Orejg_atKrwMaY9tzdB5BnL1yQ7x7Z9rvUxYiikORSRQrjCryoyub-8krARxFPTKmHw6OiG8nmHnsNg-fctcQ0iBGSw_p9NkJjsX0fTZnsL-TGr1_j4cL3pIaGDsPspYTine_byPpww8kHT_wja1yfmKdAgsG4NrZxBIGn-jgaRl5_0-dl8n34lqLEsNbfcmy9TR71U-G0I0tSm1zFag8w8es0LW_aQcBFcrxwNkLLb_N2bxlVZT-uO9FbZsReZaOJPNhYHi_QUOo9ahjExOFumW7UWm5Aj3rX6HAGzjvw6KLc050VAgn5qSNAk0kwJU3cIeywUw32V8L4M04wlNTT2mDyZZTuDwFfnRaPtMyo_fH_LGMHKR_6_7e4oOYemZns2WaT_pGvZradTDR_lEYeJFAL3UkZnUw22u01muLQQeVigIfMmkTH9H-nHkXWZa1Row7PEPVqWa_55eG5PZI_owk_MMl1qj9T-xaqcfs_PhdHYHvSzgOhxZ1yxagYyVpfqTUEFhCFttRpox-R53Lns6wBeOzGhYGQI4ndf3sI_pVWDKjcdenrTwE7NmPrCNuPx1L7iDtXh3Isir_A8qj_8qg4evlFy-udCfT6xBVEqotkFYGYez9FGWd9MCOiajKendnv5pVFFAPisWu9E__KDIvSq4v3TFQpaO7XJKkefUqQefQ67FbTdZZop_iClvFc8ZmlT4WmYlZ5w=w1496-h522-s-no-gm?authuser=0)
Gambar 9. Setelah tahap *One Hote Encoding*

- ***Data Normalization***
Pada tahap ini, dengan menggunakan `MinMaxScaler` dari scikit-learn untuk melakukan normalisasi pada variabel numerik seperti "area", "bedrooms", dan "price". Normalisasi dilakukan dengan mengubah nilai-nilai tersebut ke dalam skala antara 0 dan 1, memastikan setiap variabel numerik memiliki rentang nilai yang seragam. Hal ini membantu meningkatkan kinerja model machine learning, terutama pada algoritma yang sensitif terhadap skala variabel. Hasilnya adalah dataset yang telah dinormalisasi dan siap digunakan untuk pelatihan model.
Berikut adalah hasil dari proses data normalisasi : 
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV87P8kBkkpk6lDrDSoqRL-Hqy5XaIi5b4LsQFkn1tGQhUxc8jXLCygGQT1-4Uvw7PjDVK21bm4LPKqyReQv-h5taaecznesawckqOUxJuIpOmx7ZN5lqBSzH-ERbpt1UhYLZw_4hYCyf2lRtqNik9nyqTq25mK_YHtiFbU0uje0A-RBgWq2APFbAjezbht-CuTXcq6VPSrfXsKmvzDY9usirxYw_1-EFcyVbFkmalA87QQ_LIoVozBJnyTrqgE39ztdKPfV2zxv1UJDeBN0ldSWFkPnM_RI9syYyv6uNtJhTtWmcapkH37zUvYSSYfKAuJo-5t66uO-lZqlXWgPImlkrh-YNTnOYFpavmGAu5K5bCelsH9pCzHLANrFbig99PFUJiJbqkkh-NFgtCP09B-SPO80e22XN71VMvD7xHb9p5Wo_Oy4triWSparHOWgcinTOgqXeG_57nwThRf_gFZdGrYAdTqQRfjL_D-j9-E9a0mlk9ZraLnfDUjVibCP5GNDsj4pKy_x2aDhaTpWgY75cmZBBb6LyGB0V00lC1y4Owx2KG16NBZ-f30n0WuZovyjoBk8nn3qww-ikRWH6axIif0iXROB6hGuXnyWqr1wSbJo5MlXUpkRXjl7XkuVHGE2H5zgVjN15fMLyMnoXWB0TYS7rxm5CoU1tSRCIXRsE9i2MahaIN9AqJ9KxQtJHQdwHs3wENHkQmHiiDjB1U93pthOQ3FgyjplW8PdUO5dJG1zxpiaRP3aASO8JCeDeDT6ixhzs0e5kEGwkLCqjfpPrDOhbSvp2ficj8Uzvs3O3KB8dUMcuOyyYGlSmeDZzA5TR4989Jq-dJL3MNPuvz7LofI_58KxMJ52VUWXgGbAuKHRh3_jjMFfnlyQD3co4iQ=w1496-h522-s-no-gm?authuser=0)
Gambar 10. Hasil data normalisasi

Dengan visualisasi perbandingan seperti di bawah ini : 
![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV84VAVM0MDBgCcgWc5spo5OWiidqXWs05USq-Mm7mOmXHRkdNsBq4vFkKz7aq69KhXkpv40njw3Yt0dndn903GR4ERFrKbr0qGU7OX-_WksZDnKqZG0i_JFCOX40-QaqJ8_pLOOzsPhPze6WGXEiqO77JM1dob6celGfWV_xriFpB3sHcvJWmZO6QTr6SZx1kEmQ1D_5XtaZp3Z5j4LDWdCGTpqA0MDvAj7dJWxw-Re-RFJ1elZ4iEwpKe4YesMKpyTUzibTpGu8x8bmShXd2cJ9RNO82otkZXfseSRoNak1TyXXbzSAgHuN0ryWPhDPtE5KDUVbDlUKJdkz69ZONx5KBkhSbVkio0glAplHlEr_xi7tw-utIVBwL_IxjCGSzgJMX-DCqmd9jOHb5mYsddjK8tziTxM-5X7iWY5BW80tLJYkFuWG9GYE-R0DYzsSIuLd7QR0cvyNMRgSY-TAquQkboEdaLJ32CemPpXyIppyqEtf99Oce_nUPOqrqgNZ0OM7aIUZ0wmTEdWtOfbc5brwtpO_q7JPPQg_UhnPQNo-n8fb3JjwjVo0q1w96OujDmV8SEAstUnAzKgF-Fd1WxUwNojULpgHymZlBeqGU2LWd59cw2a5fWlkK5RT43A84TnjmOu2jv2IWfPmDlnXyNdQ1z1YH4Maz29C3qH1Jyt4pmSSlJBvXHc67vr3XVVOiEzDeSgPCkXxkrfAvoQ9Rks7JDep482SU34RH1vwCPzZyhvPyWHI7RmPJosJqJV7A5s50a7F-17pZ31dIeTe114tJARTiDDFHTur86fTmA03uRa8cqQUWfvyM9qEGHZQGyt6d_l23_Y_W5NlE1UCP2hTKzr7dL1ywPVObnoJS0LBbbf_iD2a6LW4M-nDnluv8g=w968-h528-s-no-gm?authuser=0)
Gambar 11. Perbandingan data sebelum dan sesudah di normalisasi

- ***Split the Data*** 
Pada tahap ini, dengan menggunakan `train_test_split` dari scikit-learn untuk membagi dataset menjadi dua subset, yaitu data latih (training set) dan data uji (test set). Variabel independen (X) berisi fitur-fitur yang akan digunakan untuk memprediksi variabel dependen (y), yang dalam kasus ini adalah "price" atau harga properti. Pengaturan `test_size=0.20` menentukan bahwa 20% dari data akan dialokasikan sebagai data uji, sementara 80% digunakan sebagai data latih.


### Modeling 
Dalam membuat model ini menggunakan 3 jenis algoritma yang akan dibandingkan, yaitu Linear Regression, Random Forest, dan Gradient Boosting

1.  ***Linear Regression:***
    
    -   **Deskripsi:** Algoritma regresi linear digunakan untuk memodelkan hubungan linear antara variabel independen (fitur) dan variabel dependen (harga sewa).
    -   **Kelebihan:** Sederhana, mudah diinterpretasi, cocok untuk kasus di mana hubungan antar variabel bersifat linear.
    -   **Keterbatasan:** Tidak efektif untuk pola yang kompleks atau hubungan non-linear.
2.  ***Random Forest:***
    
    -   **Deskripsi:** Algoritma ensambel yang membangun beberapa pohon keputusan secara bersamaan dan menggabungkan hasilnya untuk meningkatkan keakuratan dan kinerja model.
    -   **Kelebihan:** Dapat menangani pola yang kompleks, memiliki toleransi terhadap overfitting, dan dapat memberikan wawasan tentang pentingnya fitur.
    -   **Keterbatasan:** Kompleksitas model dapat membuat interpretasi kurang langsung.
3.  ***Gradient Boosting:***
    
    -   **Deskripsi:** Algoritma ensambel lain yang membangun serangkaian model prediktif dan mengkombinasikan hasilnya, dengan fokus pada memperbaiki kesalahan model sebelumnya.
    -   **Kelebihan:** Efektif untuk mengatasi overfitting, memberikan kinerja yang baik, dan cocok untuk data kompleks.
    -   **Keterbatasan:** Proses training mungkin membutuhkan waktu lebih lama dibandingkan dengan algoritma lain.

Dalam tahap ini,  dengan melakukan Grid Search CV untuk mencari parameter terbaik pada setiap algoritma. Berikut adalah pembagian singkat untuk masing-masing algoritma dengan hasil terbaik:

1.  ***Linear Regression:***
    
    -   ***Best Score:*** 0.696927
    -   ***Best Parameters:*** Tidak ada parameter yang dioptimalkan karena model Linear Regression bersifat linier dan tidak memiliki hyperparameter yang diatur.
2.  ***Random Forest:***
    
    -   ***Best Score:*** 0.675772
    -   ***Best Parameters:*** {'max_depth': 10, 'n_estimators': 150}
    -   **Interpretasi:** Model Random Forest memberikan kinerja terbaik ketika kedalaman maksimum pohon (max_depth) diatur pada 10 dan jumlah pohon (n_estimators) diatur pada 150.
3.  ***Gradient Boosting:***
    
    -   ***Best Score:*** 0.672297
    -   ***Best Parameters:*** {'learning_rate': 0.1, 'n_estimators': 150}
    -   **Interpretasi:** Model Gradient Boosting memberikan hasil optimal dengan tingkat pembelajaran (learning_rate) sebesar 0.1 dan jumlah estimator (n_estimators) sebanyak 150.

Berikut adalah tabel yang merangkum pemilihan algoritma berdasarkan karakteristik data dan tujuan model:

Tabel 1. Perbandingan algoritma *machine learning* yang digunakan
| Algoritma           | Karakteristik Data                                       | Tujuan Model                                                                                                                                              |
|---------------------|----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|
| *Linear Regression*   | - Data relatif linier<br> - Hubungan antar variabel linear | - Menjadi model dasar untuk pemahaman awal data<br> - Memodelkan hubungan linier antar variabel                                                          |
| *Random Forest*       | - Data kompleks dan tidak linear<br> - Berbagai fitur     | - Meningkatkan akurasi prediksi dengan memanfaatkan ensambel pohon keputusan<br> - Mengevaluasi pentingnya fitur pada prediksi harga sewa properti            |
| *Gradient Boosting*   | - Data kompleks dan tidak linear<br> - Menangani overfitting | - Meningkatkan akurasi prediksi dengan membangun serangkaian model<br> - Mengurangi overfitting<br> - Fokus pada mengurangi kesalahan model sebelumnya |

Dengan kombinasi *Linear Regression, Random Forest*, dan *Gradient Boosting*, proyek ini dapat memanfaatkan kekuatan masing-masing algoritma untuk menghasilkan model prediksi harga sewa properti yang optimal sesuai dengan karakteristik data dan tujuan yang ditetapkan.

### Evaluation

Metriks evaluasi yang digunakan untuk mengukur kinerja model adalah sebagai berikut:

1.  ***Linear Regression:***
    
    -   ***Mean Squared Error (MSE):*** 0.015291
        -   Merupakan rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual. Semakin rendah nilainya, semakin baik modelnya.
    -   ***Mean Absolute Error (MAE):*** 0.094039
        -   Merupakan rata-rata dari nilai absolut selisih antara nilai prediksi dan nilai aktual. Semakin rendah nilainya, semakin baik modelnya.
    -   ***R-squared:*** 0.674593
        -   Merupakan proporsi variabilitas dalam data yang dapat dijelaskan oleh model. Nilai maksimumnya adalah 1, dan semakin tinggi nilainya, semakin baik modelnya.
2.  ***Random Forest:***
    
    -   ***Mean Squared Error (MSE):*** 0.002743
    -   ***Mean Absolute Error (MAE):*** 0.037614
    -   ***R-squared:*** 0.941625
        -   Hasil R-squared yang tinggi menunjukkan bahwa model Random Forest mampu menjelaskan sebagian besar variabilitas dalam data.
3.  ***Gradient Boosting:***
    
    -   ***Mean Squared Error (MSE):*** 0.007734
    -   ***Mean Absolute Error (MAE):*** 0.065887
    -   ***R-squared:*** 0.835422
        -   Meskipun R-squared Gradient Boosting tidak sebaik Random Forest, nilai tersebut tetap tinggi dan menunjukkan kemampuan model dalam menjelaskan variasi dalam data.

Dengan melihat metriks-metriks ini, mengevaluasi dan membandingkan kinerja relatif dari ketiga model tersebut. **Model *Random Forest*** memberikan hasil yang sangat baik dengan nilai MSE dan MAE yang rendah, serta *R-squared* yang tinggi, menunjukkan kemampuannya dalam memprediksi harga sewa properti dengan akurat.

Contoh pengujian di atas menunjukkan nilai prediksi dari tiga model (*Linear Regression, Random Forest,* dan *Gradient Boosting*) untuk beberapa data uji (*y_true*) dengan hasil berikut:

![enter image description here](https://lh3.googleusercontent.com/pw/ABLVV84nG0xuAqT0ypozZJf_gfGh8zRt8130atAtgD-jGzHPelLXDFZPNxbSx6sUZ9gGK2Ck7_DYKbT73Xe7hp3_VDT28bJqCCMg7wBB4tINiFJECNLCT5Ct_zSRvfxViW2QVqi1oSh1twUVlLKpvAmbxavWL7cSy80o4UxHL0mabYwov3uxb9muULrS0qO4rQc2eSaUi-THx7o9QkrsMwgP_qR4UgoKVJTNDWOhKXxrE2jsGqt6PMulz-iem7XqxK-0K9GOn6lvL5wzoaY55IBtaEBoLD8FRkSvJK6AwMNH2X03UsLqf0bjPtvopMpy7vqFs47DpmCoVBkgL3ff0-zpsVH3sZPyZistxk3n9feiDqwY0d0H32NdTbQ-28ynfP7Yo_oWV0BcpTOfnMmAZ_GKNJwLG8tkYBUsqPSDQFFfJlw-AGO2rJThMUdiVaJ-fl6Z3idpyPu8UseZpXT--EofBRYBSpse9TiiG05wfFV0PQ_GXzEkhojDkwlE3CSJHQ-YVG9J6lXHrIsTLDhKbz8P5kaYDoO8gs7UVFljLlBiTB0bnupQks5HIvPL7kfS9_0S1gMZFIKpMSIQStU9HkHQ24jwMf4IOXi2oTmqBCPYdmb3gwmIKyDYPSfjIgfQJmlhbXCOlHqgoag9rY3SdDkyYfFwJES3QqIEW-NLuDa0pq6KKVa3rS0DOMFq50rL0rGpeN8WeA3b3ayvfcwxaoPhJ55C8ImJ-By6dixw7AUZOaZD-AF6bKLWMFBG00zJ8WNv4PkWuVd2LDc3Z7O_BDY5wmnGqVpr_z5zUMFUYx57RwxhHefrTdM8OqHA1hyGGIWNsGqe84LDZXlUiqzzjiSehDP9T150gDURxK7AVAKoI_Rd2hzTgSF4K9GFH5OcA3pVuA=w742-h259-s-no-gm?authuser=0)
Gambar 12. Contoh hasil percobaan pengujian

Dari gambar tersebut, dengan membandingkan nilai prediksi dari masing-masing model untuk setiap data uji dengan nilai sebenarnya (*y_true*). Evaluasi kinerja model dapat dilakukan dengan membandingkan sejauh mana nilai prediksi mendekati nilai sebenarnya. Secara visual, melihat perbedaan antara kolom prediksi dari masing-masing model dengan kolom y_true. Evaluasi lebih lanjut dapat dilakukan dengan menggunakan metriks seperti *Mean Squared Error (MSE)* atau *Mean Absolute Error (MAE)* untuk membandingkan secara kuantitatif.


## Kesimpulan

Proyek prediksi harga sewa properti berhasil mencapai tujuannya dengan memilih dan mengintegrasikan tiga algoritma: *Linear Regression, Random Forest*, dan *Gradient Boosting*. *Linear Regression* memberikan pemahaman dasar tentang hubungan linier antar variabel, sementara *Random Forest* dan *Gradient Boosting*, sebagai algoritma *ensambel*, mampu meningkatkan akurasi prediksi dengan menangani kompleksitas dan non-linearitas dalam data. Model *Random Forest* memberikan hasil akurasi tertinggi dibandingkan dengan model yang lain, mengidentifikasi faktor-faktor yang mempengaruhi harga sewa properti. Keseluruhan, proyek ini mencapai tujuan meningkatkan ketepatan penentuan harga sewa, menciptakan model machine learning yang optimal, dan mengidentifikasi faktor-faktor penting dalam penetapan harga properti. Rekomendasi untuk evaluasi faktor-faktor eksternal dan penambahan fitur baru memberikan langkah-langkah untuk pengembangan lebih lanjut, menjadikan proyek ini sebagai landasan yang kuat untuk meningkatkan kualitas dan akurasi model prediksi harga sewa properti di masa depan.


## Daftar Pustaka

- Fabian  Pedregosa  et  al.  Python's  Scikit-learn library for  machine learning, Journal of  Machine  Learning Research.  12:2825–830.
- Jae Kwon Bae, Byeonghwa Park. Housing Price Forecast Using Machine Learning Algorithms. 42:2928–2934.
- Suganya, T., Gowtham, M., & Raja, H. S. T. (2022). Machine learning based prediction of house price. International Journal of Health Sciences, 6(S3), 9554²9567.
- TY  - CHAP AU  - Annamoradnejad, Rahimberdi AU  - Annamoradnejad, Issa PY  - 2022/10/14 SP  - 2728 EP  - 2739 SN  - 9781799892205 T1  - Machine Learning for Housing Price Prediction VL  - DO  - 10.4018/978-1-7998-9220-5.ch163 ER  -
