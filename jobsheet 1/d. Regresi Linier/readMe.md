# A. Regresi Linier

## 1. Simulasi Pemrosesan Data Menggunakan Regresi Linier

### a. Rangkaian
Rangkaian pada percobaan ini adalah sebagai berikut

![image](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/6f245b62-b8e1-44c0-a117-32e6a36571a4)

### b. Source Code
Kode program dapat dilihat <a href="code/soil_1/soil_1.ino">di sini</a> dan <a href="code/soil_2/soil_2.ino">di sini</a>

### c. Hasil dan Pembahasan
Percobaan ini merupakan simulasi pengambilan data dari sensor Capacitive Soil Moisture. Sensor ini berfungsi untuk mengukur tingkat kelembaban tanah. Fungsi utama dari sensor ini adalah untuk memberikan informasi tentang seberapa basah atau kering tanah di suatu area tertentu. Sensor ini mendeteksi kelembaban tanah dengan cara mengukur kapasitansi dielektrik tanah.
Digunakan juga 3-Way Soil Meter untuk mengukur parameter kelembaban dalam tanah pada kondisi tanah kering, medium, dan basah. Kemudian, kode program yang dijalankan berguna untuk membaca data dari sensor analog pada pin input dan menghitung rata-rata dari beberapa pembacaan yang kemudian dicetak ke Serial Monitor. Proses konversi melibatkan membagi nilai rata-rata dengan jumlah nilai oleh ADC (Analog-to-Digital Converter) sehingga muncul nilai rata-rata.

##### Tanpa Tanah

![tanpa-tanah](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/86c9655f-2bcb-4199-ba62-7dfdc07f65d8)


##### Tanah Kering

![hasil-2-1](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/853bc5d6-087f-4d35-a918-87981c5b087f)![hasil-2-2](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/90489dbd-de1d-4cb7-88ea-178b5cea7e5a)


##### Tanah Medium

![hasil-3-1](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/483fe41f-c6c1-4909-ba80-f9cec1c65879)![hasil-3-2](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/3cc91465-c445-480d-8f1e-0cae019d0dc6)


##### Tanah Basah

![hasil-4-1](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/b41b537b-b2c8-4656-a05b-9eb60e7f5355)![hasil-4-2](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/d41d2d7d-b010-40eb-861b-aad4d154c137)


##### Hasil Tabel

![hasil-tabel](https://github.com/farhanhisyam/sistemEmbedded/assets/94108385/472e4abd-4b12-4a80-a694-464f67e0f86c)
Pada hasil tabel diatas dapat dilihat bahwa nilai pembacaan ADC pada tanah kering > tanah medium > tanah basah <br>
Begitupula nilai rata-rata Vs yang didapat pada tanah kering > tanah medium > tanah basah
