#my name is: abdul Katasir
ini merupakan program lanjutan dari proyek sebelumnya. sistem ini merupakan alat pemantauan suhu dan ph air berbasis IoT yang terintegrasi dengan aplikasi telegram secara real-time.
Sistem ini dibangun menggunakan alat berikut ini:
1. mikrokontroller wemos d1 mini
2. sensor ph
3. sensor ds18b20
4. lcd 16x2 I2C
5. buzzer
6. konektor dc
7. adaptor 5v
8. kabel jumper

alat ini bekerja dengan mikrokontroller mengambil/menerima data dari sensor ds18b20 dan sensor ph air. data yang diterima kemudian ditampilkan di layar lcd 16x2 I2C.
user dapat mengetahui kondisi suhu dan ph dengan mengirim pesan melalui telegram dengan pesan /suhu untuk menerima data suhu, /ph untuk menerima data ph.
sistem juga akan mengirimkan pesan secara otomatis ke user melalui telegram ketika suhu <kurang></kurang> batas yang ditentukan <lebih> dan buzzer akan aktif dan berbunyi sebagai alaram di lapangan.

cara penggunaan nya:
1. #define ssid "isi dengan nama wifi"
2. #define pass "isi dengan pw wifi"
3. #define token "isi dengan token telegram mu"
4. String id = "isi dengan id telegram mu"

gambaran alat: ![image](https://github.com/Lioneole09/LeleEco_Monitor-alat-pemantauan-suhu-dan-ph-air-kolam-ikan-lele/assets/136927567/95f44369-6211-4079-9fe1-1302d95c1d0a)

![image](https://github.com/Lioneole09/LeleEco_Monitor-alat-pemantauan-suhu-dan-ph-air-kolam-ikan-lele/assets/136927567/8a4cb807-2bfe-46d5-896a-432401d726ba)

bisa juga dibeli di toko ini: https://s.shopee.co.id/1fxgdTj3Yn





jika bingung bisa hubungi email berikut ini: lioneole@gmail.com atau instagram: @abdulkatsir27
