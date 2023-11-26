# D. Menggunakan JSON Parsing

### a. Langkah Kerja
  1. Buatlah flow seperti pada gambar di bawah ini.
     
      ![langkah-4](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/c6a727f2-80bf-426c-b1e5-18624bd8f025)

  2. Konfigurasikan Inject Node, JSON Parser Node, dan Function Node seperti gambar berikut ini.

     ![job5d](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/80853a4c-96c6-4d34-886d-a8e6f6ecceff)

  3. Deploy flow dan dokumentasikan hasilnya.

### b. Hasil dan Pembahasan
Pada percobaan ini, menggunakan JSON Parsing dimulai dengan membuat flow dan mengkonfigurasi inject node, JSON Parser Node, dan Function Node. 
Node JSON Parser pada Node-RED digunakan untuk mengonversi data JSON yang diterima dalam format string menjadi objek JavaScript yang dapat diproses lebih lanjut 
dalam alur kerja, menyederhanakan manipulasi dan ekstraksi informasi dari struktur data JSON. Node ini memfasilitasi pengolahan data JSON dengan cara yang lebih mudah dan terintegrasi dalam alur kerja Node-RED.

Pada percobaan ini, yang terjadi adalah
- Node input menerima pesan (message) dengan properti msg.payload yang berisi data JSON: {"temp":27,"humidity":50} dan msg.topic dengan nilai /sensor.
- JSON Parser Node mengonversi data JSON menjadi objek JavaScript. Dalam hal ini, properti msg.payload diatur ulang sehingga berisi objek JSON yang sekarang dapat diakses oleh node berikutnya.
- Function Node mengambil nilai suhu (temp) dari objek JSON yang ada di dalam msg.payload dan menggantinya sebagai nilai baru untuk msg.payload. Dengan kata lain, hasil akhir pesan adalah msg.payload yang sekarang hanya berisi nilai suhu (27).

Sehingga, hasil keluarannya adalah seperti berikut

![hasil-4](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/6f4fbd35-96a2-4f0d-84c1-6b1b0a484a1c)
