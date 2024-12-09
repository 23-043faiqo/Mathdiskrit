---
title: 'Logika dan Pembuktian '

---

# Logika Matematika

## Negasi
Negasi adalah sebuah istilah yang digunakan untuk menyatakan ingkaran atau penyangkalan terhadap suatu pernyataan atau proposisi. Sederhananya, negasi adalah kebalikan dari suatu pernyataan.
Negasi ditandai dengan simbol (~). Jika preposisi awal (p) bernilai benar, maka pernyataan negasinya (~p) adalah salah.


| P | $\sim p$ | 
| -------- | -------- | 
| T  | F   |
| F  | T 

## Konjungsi 
Negasi adalah sebuah istilah yang digunakan untuk menyatakan ingkaran atau penyangkalan terhadap suatu pernyataan atau proposisi. Sederhananya, negasi adalah kebalikan dari suatu pernyataan.
Konjungsi disimbolkan dengan (^). Kebenaran kalimat dengan konjungsi dijelaskan dalam tabel kebenaran konjungsi.


| p | q | p $\land$ q |
| -------- | -------- | -------- |
| T | T |  T  |
| T | F |  F  |
| F | T |  F  |
| F | F |  F  |


## Disjungsi
Disjungsi adalah sebuah operasi dalam logika matematika yang menghubungkan dua atau lebih pernyataan menjadi satu pernyataan majemuk. Disjungsi ini sering diartikan sebagai "atau".
dan dilambangkan dengan “v”.


| p | q | p $\lor$ q |
| -------- | -------- | -------- |
| T | T |  T  |
| T | F |  T  |
| F | T |  T  |
| F | F |  F  |

## Implikasi
Implikasi dalam logika matematika adalah sebuah hubungan sebab-akibat antara dua pernyataan. Implikasi ini sering diartikan sebagai "jika ... maka ...", juga disimbolkan oleh karakter "→".


| p | q | p$\rightarrow$q |
| -------- | -------- | -------- |
| T | T |       T         |
| T | F |       F         |
| F | T |       T         |
| F | F |       T         |

## Biimplikasi
Biimplikasi dalam logika matematika adalah hubungan timbal balik antara dua pernyataan. Artinya, kedua pernyataan tersebut memiliki nilai kebenaran yang sama, baik benar atau salah. Biimplikasi sering diartikan sebagai "jika dan hanya jika".Implikasi ganda terjadi dalam kalimat majemuk dan diwakili oleh "↔".


| p | q | p $\leftrightarrow$ q |
| -------- | -------- | -------- |
| T | T | T |
| T | F | F |
| F | T | F |
| F | F | T |

Buatlah tabel kebenaran untuk~pernyataan berikut $$P\lor(R\to\ Q)$$

$$\begin{array}{c|c|c|c|cc}P&Q&R&\ Q&R\to\ Q&P\lor(R\to\ Q)\\\hline\text{Т}&\text{Т}&\text{Т}&\text{F}&\text{T}&\text{T}\\\text{Т}&\text{Т}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{T}&\text{F}&\text{T}&\text{T}&\text{F}&\text{T}\\\text{T}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{F}&\text{T}&\text{T}&\text{T}&\end{array}$$