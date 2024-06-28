# Dashboard Billing Monitoring

![img](/contents/assets/project-higen-monitoring/1.png)

Ini adalah project yang dikerjakan bersama Tim Software engineer yang ada di kantor tempat saya bekerja.

Inti dari aplikasi ini hanya untuk monitoring penggunaan billing panggilan telepon setiap customer.

Namun dibalik semua itu terdapat business logic yang rumit untuk menyelesaikan masalah tersebut.

Project ini menggunakan Laravel versi yang paling baru pada saat itu.
Queues juga digunakan untuk memproses perhitungan yang memakan waktu lumayan lama. 
Selain Queues kami juga menggunakan cronjob yang bisa dieksekusi pada waktu tertentu untuk mengambil data dari server mereka untuk dapat kami proses supaya perhitungan billing dapat tampil didalam dashboard.

