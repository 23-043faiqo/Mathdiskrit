---
title: naive beyes

---

# NAIVE BEYES

## PENGERTIAN

NAIVE BEYES yaitu salah satu algoritma dalam *machine learning* yang berbasis pada teorema Bayes. Algoritma ini sangat populer untuk tugas klasifikasi, seperti *spam filtering*, analisis sentimen, dan pengenalan teks. 

### Penjelasan Singkat:
1. **Teorema Bayes**: 
2. $$
    P(AB) = \frac{P(BA) \cdot P(A)}{P(B)}
   $$
   Teorema ini digunakan untuk menghitung probabilitas suatu kejadian \(A\) dengan kondisi \(B\) sudah terjadi.

2. **Asumsi Sederhana (Naive)**:
   - Naive Bayes mengasumsikan bahwa semua fitur bersifat independen satu sama lain, meskipun ini jarang benar di dunia nyata.

3. **Proses Kerja**:
   - Menghitung probabilitas setiap kelas berdasarkan fitur yang diberikan.
   - Memilih kelas dengan probabilitas tertinggi sebagai hasil klasifikasi.

4. **Jenis-jenis Naive Bayes**:
   - **Gaussian Naive Bayes**: Digunakan jika data mengikuti distribusi normal.
   - **Multinomial Naive Bayes**: Digunakan untuk data diskrit, seperti frekuensi kata dalam dokumen.
   - **Bernoulli Naive Bayes**: Digunakan untuk data biner, misalnya keberadaan atau ketiadaan fitur.

Teorema Bayes
Teorema Bayes memberi tahu kita cara menghitung probabilitas bersyarat dari suatu kejadian berdasarkan pengetahuan sebelumnya tentang kejadian tersebut. Dengan kata lain, Teorema Bayes memungkinkan kita menghitung probabilitas posterior berdasarkan probabilitas sebelumnya :


Dalam persamaan ini, kita memiliki empat istilah berikut:

probabilitas posterior P(E | C) : probabilitas terjadinya peristiwa E , jika kondisi C benar;
probabilitas sebelumnya P(E) : satu-satunya probabilitas terjadinya peristiwa E , yang merupakan pengetahuan sebelumnya tentang peristiwa itu sendiri;
kemungkinan P(C | E) : probabilitas kondisi C benar, jika peristiwa E terjadi;
probabilitas marginal P(C) : satu-satunya probabilitas kondisi C yang benar.

\begin{array}{llll|}
\hline \text { No } & \text { Usia } & \text { Tekanan Darah } & \text { Penyakit (H/T) } \\
\hline 1 & \text { Muda } & \text { Normal } & \text { T } \\
2 & \text { Muda } & \text { Tinggi } & \text { T } \\
3 & \text { Paruh baya } & \text { Normal } & \text { T } \\
4 & \text { Paruh baya } & \text { Tinggi } & \text { H } \\
5 & \text { Tua } & \text { Normal } & \text { H } \\
6 & \text { Tua } & \text { Sangat Tinggi } & \text { H } \\
7 & \text { Muda } & \text { Normal } & \text { T } \\
8 & \text { Tua } & \text { Tinggi } & \text { H } \\
\hline
\end{array}


\begin{array}{|c|c|c|}
\hline \text { Temperature ( } X_1 \text { ) } & \text { Wind ( } X_2 \text { ) } & \text { Beach (B) } \\
\hline \text { low (L) } & \text { weak (W) } & \text { true (T) } \\
\text { high (H) } & \text { weak (W) } & \text { false (F) } \\
\text { medium (M) } & \text { strong (S) } & \text { false (F) } \\
\text { low (L) } & \text { normal (N) } & \text { true (T) } \\
\text { medium (M) } & \text { normal (N) } & \text { true (T) } \\
\hline
\end{array}