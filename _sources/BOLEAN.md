---
title: BOLEAN

---

# BOOLEAN

## PENGERTIAN BOOLEAN
boolean adalah konsep dalam pemrograman, merujuk pada tipe data yang hanya memiliki dua nilai mungkin, yaitu true (benar) dan false (salah).

## FUNGSI BOOLEAN
Pengambilan keputusan: boolean dipakai untuk membuat keputusan dalam program. Misalnya, dalam struktur kontrol seperti pernyataan if, else, dan elif, boolean menentukan path mana yang akan diikuti program berdasarkan kondisi yang bernilai true atau false.
Operasi logika: boolean memungkinkan operasi logika seperti AND (&&), OR (||), dan NOT (!). Operasi ini digunakan untuk menggabungkan atau memodifikasi beberapa kondisi boolean.
Pengujian kondisi: dalam pemrograman, programmer sering kali perlu menguji apakah suatu kondisi terpenuhi atau tidak. Misalnya, dalam sebuah web app, mungkin perlu memeriksa apakah user sudah login (true) atau belum (false) sebelum mengizinkan akses ke halaman tertentu.
Pengendalian program flow: boolean dimanfaatkan untuk mengontrol program flow, seperti dalam loop atau iterasi. Contohnya, loop while atau for dalam banyak bahasa pemrograman menggunakan kondisi boolean untuk menentukan kapan loop harus berhenti.
Representasi status: boolean sering digunakan untuk merepresentasikan status on/off, ya/tidak, aktif/tidak aktif, berguna dalam pengembangan aplikasi dan sistem.

## CONTOH BOOLEAN

### PENGGUNAAN DALAMPERNYATAAN KONDISIONAL
isLoggedIn = True
if isLoggedIn:
    print("Pengguna telah login.")
else:
    print("Pengguna belum login.")
    
Dalam contoh di atas, isLoggedIn adalah variabel boolean. Jika isLoggedIn bernilai True, program akan menghasilkan "Pengguna telah login." Jika False, program menampilkan "Pengguna belum login."

### PENGGUNAAN DALAM OPERASI LOGIKA

a = True
b = False
print(a and b)  # Hasilnya False
print(a or b)   # Hasilnya True
print(not a)    # Hasilnya False

Contoh di atas menunjukkan penggunaan operasi logika AND, OR, dan NOT dengan variabel boolean.

### PENGGUNAAN DALAM PENGAMBILAN KEPUTUSAN KOMPLEKS

umur = 20
memilikiSIM = True
if umur >= 17 and memilikiSIM:
    print("Diperbolehkan mengemudi.")
else:
    print("Tidak diperbolehkan mengemudi.")
    
Dalam contoh ini, keputusan diambil berdasarkan dua kondisi, yaitu umur dan memilikiSIM. Kedua kondisi harus bernilai True untuk menghasilkan "Diperbolehkan mengemudi."

Refensi : https://revou.co/kosakata/boolean