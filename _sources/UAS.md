---
title: UAS

---

nama : faiqo noril laili
nim : 23-043
matkul : matematika diskrit
UAS, senin 09-des-2024

soal no 1

|P | Q | R | S | ( P $\rightarrow$ Q) |( R $\rightarrow$ S) |( P $\rightarrow$ Q) $\rightarrow$ ( R $\rightarrow$ S)|
|---|---|---|---|---|---|---|
| T | T | T | F | T | F | F |
| T | T | F | F | T | T | T |
| T | F | T | F | F | F | T |
| T | F | F | F | F | T | T |
| F | F | F | T | T | T | T |
| F | F | T | T | T | T | T |
| F | T | F | T | T | T | T |
| F | T | T | T | T | T | T |

soal no 2

hitung colssness centrality : g
beetwens centrality : f

titik a menyambung ke titik b dan g
titik b menyhambung ke titik a, d, f, g
titik d menyambung ke titik b dan f
titik f menyambung ke titik b dan d
titik g menhyambung ke titik a dan b

| A | B | D | F | G |
|---|---|---|---|---|
| B | A | B | B | A |
| G | D | F | D | B |
| - | F | - | - | - |
| - | G | - | - | - |


| A | B | D |
|---|---|---|
| G | F |   |

Maka Jawabannya 

1. closeness centrality g

total jarak = 6
rumus closeness
Cc(g) = n-1/total jarak
Cc(g) = 5-1/6
Cc(g) = 4/6
Cc(g) = 0,67

jadi hasil dari closeness centrality g adalah 0,67

2. betweenness centrality f  jalur terpendek 

a. dari a ke d melewati f
b. dari a ke f melewati f
c. dari g ke d melewati f
d. dari g ke f melewati f

setiapnpasangan berada di jalur terpendek, sehingga kntribusinya 1 per pasangan 

CB(f) = 1+1+1+1= 4

jadi hasil dari betwennes centrality f adalah 4

