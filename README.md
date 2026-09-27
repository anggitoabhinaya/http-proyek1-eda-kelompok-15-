# http-proyek1-eda-kelompok-15-

Nama : Alief Shoufiya Nafi
NRP : 5027261006
Nama : Anggito Abhinaya Sulistyo
NRP : 5027261066
Nama : Daniel Darius Darrell S.
NRP : 5027261112
Kelompok 15
Topik: Smart City
Sumber : UCI Machine Learning Repository (https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume)
Link lisensi : https://creativecommons.org/licenses/by/4.0/legalcode
-----------------------------------------

3 Temuan Utama:

1. Ditemukan nilai anomali ekstrem pada kolom `rain_1h` (9.831,3 mm dalam 1 jam — jauh melampaui rekor dunia ~305 mm) dan `temp` (0 Kelvin, suhu mutlak nol yang mustahil secara fisik). Kedua anomali ini dihapus dari dataset sebelum analisis lebih lanjut.

2. Sebaran volume lalu lintas (`traffic_volume`) bersifat bimodal (dua puncak), bukan sekadar miring ke satu arah — menunjukkan dua kondisi lalu lintas berbeda dalam sehari: jam sepi (dini hari) dan jam ramai (siang/sore).

3. Tutupan awan (`clouds_all`) adalah variabel dengan variasi tertinggi di antara variabel numerik yang dianalisis, dengan simpangan baku 39,01% dari rata-rata 49,38% — menunjukkan kondisi langit yang sangat fluktuatif sepanjang periode pencatatan
--------------------------------------------

Cara Menjalankan Notebook melalui anaconda prompt

1. Clone repositori ini:
   git clone https://github.com/anggitoabhinaya/http-proyek1-eda-kelompok-15-
2. Buka Anaconda Prompt
3. Masuk ke folder hasil clone/extract:
cd http-proyek1-eda-kelompok-15-
4. Install:
conda install pandas matplotlib
5. Jalankan Jupyter Notebook:
  jupyter notebook
6. Di jendela browser yang terbuka, klik file `eda_KELOMPOK_15.ipynb`
7. Jalankan seluruh sel secara berurutan dari atas (`Kernel → Restart & Run All`)
8. Pastikan file dataset (`Metro_Interstate_Traffic_Volume.csv`) berada di dalam folder `data/`, sejajar dengan notebook
