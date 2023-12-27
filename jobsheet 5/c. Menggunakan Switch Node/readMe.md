# C. Menggunakan Switch Node

### a. Langkah Kerja
  1. Buatlah flow seperti pada gambar berikut
     ![langkah-3](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/ec4262a0-e368-4a1a-9d72-65659b930523)

  2. Konfigurasi Input/Inject Node. Isikan Payload pada Inject Node 1 dengan angka 30. Kemudian pada Inject Node 2, isikan Payload dengan angka 27.
  3. Konfigurasi Switch Node seperti pada gambar di bawah.
     
     ![job5c](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/ebbf8f0e-ee57-4912-8e61-d3999b69ff6c)

  4. Deploy flow dan dokumentasikan hasilnya.

### b. Hasil dan Pembahasan
Pada percobaan menggunakan switch node dimulai dengan membuat flow dan konfigurasi Input/Inject Node. Isikan Payload pada Inject Node 1 dengan angka 30. Kemudian pada Inject Node 2, isikan Payload dengan angka 27.
Kemudian mengkonfigurasi switch node seperti pada jobsheet. Switch Node pada Node-RED berfungsi sebagai alat untuk memisahkan jalur alur kerja berdasarkan kondisi atau nilai tertentu dalam pesan, memungkinkan kita untuk 
mengarahkan pesan ke cabang yang sesuai dengan aturan logika yang ditentukan. Pada percobaan ini, yang terjadi pada switch node adalah:
- input dengan nilai >28 diarahkan ke output pertama, sedangkan output kedua kosong
- input dengan nilai <=28 diarahkan ke output kedua, sedangkan output pertama kosong

Sehingga hasil keluaran pada debug node setelah deploy adalah seperti berikut

![hasil-3](https://github.com/iamanisaamalia/sistemembedded/assets/147674408/0df147e7-577a-4cf5-a49d-65aa5d151437)
