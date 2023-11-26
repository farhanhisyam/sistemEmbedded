# JOBSHEET 3 - TOPOLOGI JARINGAN LOKAL DAN WIFI

## Abstrak
<p align="justify">WiFi, singkatan dari Wireless Fidelity, adalah teknologi yang menggunakan gelombang radio dalam rentang 2,4GHz hingga 5GHz untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat mikrokontrol seperti ESP32 dan ESP8266 ke jaringan lokal nirkabel guna mengakses internet. Untuk terhubung dengan WiFi, perangkat-perangkat ini perlu berada dalam satu titik akses atau hotspot jaringan nirkabel. Jangkauan umumnya mencapai 20 meter di dalam ruangan dan lebih dari 20 meter di luar ruangan. Awalnya digunakan untuk jaringan LAN, WiFi kini menjadi kebutuhan sehari-hari untuk akses internet dan IoT. Data yang dikirim dan diterima melalui WiFi didistribusikan melalui gelombang radio, memerlukan wireless adaptor untuk terhubung ke WiFi. Gelombang radio ini dikirim ke router untuk dipecahkan, dan setelah terbaca, data dikirim ke jaringan internet melalui koneksi ethernet. Karena jaringan WiFi beroperasi dalam dua arah, setiap data yang diterima secara simultan diubah menjadi kode pada setiap paket data dan dikirim kembali sebagai sinyal radio yang diterima oleh adaptor komputer nirkabel.</p>

<p align="justify">Jobsheet ini bertujuan untuk dapat memahami cara kerja protokol topologi jaringan lokal
yang memanfaatkan Wi-Fi untuk berkomunikasi serta dapat merancang topologi jaringan yang memanfaatkan Wi-Fi
untuk penerapan Wireless Sensor Network (WSN) dan Internet of Things
(IoT).</p>

Sub-job pada jobsheet ini, antara lain:
  1. ESP32 Wi-Fi Modes dan Wifi-Scan
  2. Menghubungkan ESP32 dengan Jaringan Wi-Fi
  3. Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi
  4. Mengganti Hostname ESP32
  5. Mengirim Data Sensor ke Database

## Alat dan Bahan

Alat dan bahan yang digunakan dalam jobsheet ini, antara lain:
  1. ESP32
  2. Breadboard
  3. Kabel jumper
  4. Sensor DHT 11, RFID
  5. LED (5) dan Push Button (3)
  6. Servo
  7. Resistor 330, 1K, 10K Ohm (@3)

> [!NOTE]  
> *Buka folder-folder subjob untuk melihat laporan percobaan*
