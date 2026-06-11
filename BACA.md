[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?style=flat)](https://github.com/ellerbrock/open-source-badges/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?logo=github&color=%23F7DF1E)](https://opensource.org/licenses/MIT)
![GitHub last commit](https://img.shields.io/github/last-commit/cakraawijaya/IoT-Based-Smart-Conveyor-System-with-PWM-Speed-Control-and-Real-Time-Item-Counting?logo=Codeforces&logoColor=white&color=%23F7DF1E)
![Project](https://img.shields.io/badge/Project-Arduino%2C%20STM8%2C%20ESP-light.svg?style=flat&logo=STMicroelectronics&logoColor=white&color=%23F7DF1E)
![Type](https://img.shields.io/badge/Type-Personal%20Experiment-light.svg?style=flat&logo=gitbook&logoColor=white&color=%23F7DF1E)

# IoT-Based Smart Conveyor System with PWM Speed Control and Real-Time Item Counting
Sistem terdiri dari tiga mikrokontroler yang saling terhubung dalam arsitektur Master–Slave, yaitu Arduino Pro Mini (Slave 1), STM8S103F3P6 (Slave 2), dan ESP32-S3 UNO (Master). Arduino Pro Mini bertanggung jawab atas pengendalian motor konveyor, termasuk pengaturan kecepatan dan arah putaran motor. STM8S103F3P6 berfungsi sebagai modul penghitung barang otomatis yang menampilkan hasil perhitungan secara lokal melalui LCD I2C. Seluruh data dari kedua slave dikumpulkan oleh ESP32-S3 UNO dan dikirimkan ke Ubidots menggunakan protokol MQTT. Melalui integrasi ini, pengguna dapat memantau jumlah barang dan status sistem secara real-time melalui dashboard cloud dari mana saja.

<br><br>

## Apresiasi
Jika karya ini bermanfaat bagi anda, maka dukunglah karya ini sebagai bentuk apresiasi kepada penulis dengan mengklik tombol ``` ⭐Bintang ``` di bagian atas repositori.

<br><br>

## Penafian
Aplikasi ini merupakan hasil karya saya sendiri dan bukan merupakan hasil plagiat dari penelitian atau karya orang lain, kecuali yang berkaitan dengan layanan pihak ketiga yang meliputi: pustaka, kerangka kerja, dan lain sebagainya.

<br><br>

## LISENSI
LISENSI MIT - Hak Cipta © 2026 - Devan C. M. Wijaya, S.Kom

Dengan ini diberikan izin tanpa biaya kepada siapa pun yang mendapatkan salinan perangkat lunak ini dan file dokumentasi terkait perangkat lunak untuk menggunakannya tanpa batasan, termasuk namun tidak terbatas pada hak untuk menggunakan, menyalin, memodifikasi, menggabungkan, mempublikasikan, mendistribusikan, mensublisensikan, dan/atau menjual salinan Perangkat Lunak ini, dan mengizinkan orang yang menerima Perangkat Lunak ini untuk dilengkapi dengan persyaratan berikut:

Pemberitahuan hak cipta di atas dan pemberitahuan izin ini harus menyertai semua salinan atau bagian penting dari Perangkat Lunak.

DALAM HAL APAPUN, PENULIS ATAU PEMEGANG HAK CIPTA DI SINI TETAP MEMILIKI HAK KEPEMILIKAN PENUH. PERANGKAT LUNAK INI DISEDIAKAN SEBAGAIMANA ADANYA, TANPA JAMINAN APAPUN, BAIK TERSURAT MAUPUN TERSIRAT, OLEH KARENA ITU JIKA TERJADI KERUSAKAN, KEHILANGAN, ATAU LAINNYA YANG TIMBUL DARI PENGGUNAAN ATAU URUSAN LAIN DALAM PERANGKAT LUNAK INI, PENULIS ATAU PEMEGANG HAK CIPTA TIDAK BERTANGGUNG JAWAB, KARENA PENGGUNAAN PERANGKAT LUNAK INI TIDAK DIPAKSAKAN SAMA SEKALI, SEHINGGA RISIKO ADALAH MILIK ANDA SENDIRI.