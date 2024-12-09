---
title: Algoritma

---

# Algoritma
## Definisi Algoritma

Pengertian umum dari suatu algoritma adalah urutan dari sejumlah langkah logis dan sistematis untuk memecahkan suatu masalah tertentu.
Algoritma adalah suatu langkah atau metode yang telah direncanakan secara matang sehingga terurut dan terorganisir dengan baik dan biasanya digunakan untuk memecahkan suatu masalah dengan memberikan suatu instruksi sehingga menjadi suatu tindakan.
Sedangkan dalam Kamus Besar Bahasa Indonesia (KBBI), algoritma adalah suatu prosedur sistematis untuk menyelesaikan masalah matematika dalam langkah-langkah terbatas atau urutan pengambilan keputusan yang logis untuk memecahkan masalah tersebut.

refensi :
https://www.gramedia.com/literasi/pengertian-algoritma/

### Algoritma sequential search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.

Algoritma ini termasuk salah satu algoritma pencarian yang paling sederhana dan sering digunakan dalam situasi di mana data tidak memiliki struktur tertentu.
Umumnya algoritma pencarian biner dikenal sebagai pencarian setengah interval atau pencarian logaritmik. Metode pencarian biner merupakan salah satu metode yang cepat dan efisien untuk menemukan nilai target tertentu dari sekumpulan item yang dipesan. Hal ini dikarenakan cara kerja algoritma pencarian biner yang memulai di tengah daftar yang diurutkan. Maka hal tersebut secara efektif memotong setengah ruang pencarian dengan menentukan apakah akan naik atau turun daftar berdasarkan nilai median.

referensi:
https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/

### Alagoritma binary search

Umumnya algoritma pencarian biner dikenal sebagai pencarian setengah interval atau pencarian logaritmik. Metode pencarian biner merupakan salah satu metode yang cepat dan efisien untuk menemukan nilai target tertentu dari sekumpulan item yang dipesan. Hal ini dikarenakan cara kerja algoritma pencarian biner yang memulai di tengah daftar yang diurutkan. Maka hal tersebut secara efektif memotong setengah ruang pencarian dengan menentukan apakah akan naik atau turun daftar berdasarkan nilai median.

referensi: 
https://tekno.kompas.com/read/2022/12/03/03000047/pengertian-binary-search-cara-kerja-dan-keunggulannya

### mengapa binary search lebih cepat dan efisien daripada sequential search

karena binary search datanya terurut dan pencarian berulang dan langsung mencari dari tengah, kemudian sebaliknya jika sequential search datanya tidak terurut dan harus mencari satu per satu 

## pseudocode

Pseudocode secara harfiah berarti ‘kode semu’. Maksudnya, pseudocode adalah sebuah cara penulisan program yang informal dan dapat dibuat dengan kaidah yang ditentukan sendiri. Dengan kata lain, pseudocode merupakan urutan logika yang bertujuan untuk dipahami manusia dengan mudah.

referensi
https://www.niagahoster.co.id/blog/apa-itu-pseudocode/
https://blog.rumahweb.com/pseudocode-adalah/

## Big O algoritma

Notasi Big O adalah bahasa yang kita gunakan untuk berbicara tentang berapa lama suatu algoritma berjalan (kompleksitas waktu) atau berapa banyak memori yang digunakan oleh suatu algoritma (kompleksitas ruang). Notasi Big O dapat menyatakan waktu berjalan terbaik, terburuk, dan kasus rata-rata dari suatu algoritma. Untuk tujuan kita, kita akan fokus terutama pada Big-O yang berkaitan dengan kompleksitas waktu.

referensi:
https://ichi.pro/id/notasi-big-o-penjelasan-sederhana-dengan-contoh-181845825280714#google_vignette

### hitung big o dari algoritma sequential search
*waktu komlpeksitas (time complexity)
*ruang komplesitas (space complexity)

Waktu Kompleksitas

Kasus Terbaik (Best Case): Elemen yang dicari berada pada posisi pertama. Dalam hal ini, algoritma hanya perlu melakukan satu perbandingan, sehingga waktu kompleksitasnya adalah O(1).
Kasus Terburuk (Worst Case): Elemen yang dicari tidak ada dalam list atau berada pada posisi terakhir. Dalam kasus ini, algoritma harus memeriksa semua elemen dalam list, sehingga waktu kompleksitasnya adalah O(n), di mana n adalah jumlah elemen dalam list.
Rata-rata (Average Case): Secara rata-rata, algoritma akan memeriksa setengah dari elemen dalam list. Namun, dalam notasi Big O, kita biasanya hanya mempertimbangkan batas atas, sehingga waktu kompleksitas rata-rata juga dianggap O(n).

Ruang Kompleksitas

Algoritma sequential search hanya membutuhkan ruang tambahan yang konstan untuk menyimpan variabel sementara seperti indeks dan nilai yang sedang dibandingkan. Oleh karena itu, ruang kompleksitasnya adalah O(1).
