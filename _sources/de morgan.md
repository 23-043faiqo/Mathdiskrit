---
title: Untitled

---

1. de morgan
 $\overline{A \cap B}=\bar{A} \cup \bar{B}$
 $\overline{A \cup B}=\bar{A} \cap \bar{B}$
Contoh:

Misalkan A: "Hujan", B: "Suhu dingin".

¬(A ∧ B): "Tidak hujan dan tidak suhu dingin".
¬A ∨ ¬B: "Tidak hujan atau tidak suhu dingin".
Bukti:

A	B	A ∧ B	¬(A ∧ B)	¬A	¬B	¬A ∨ ¬B
T	T	T	F	F	F	F
T	F	F	T	F	T	T
F	T	F	T	T	F	T
F	F	F	T	T	T	T

Hasil menunjukkan bahwa ¬(A ∧ B) sama dengan ¬A ∨ ¬B.

2. absorption
$A \cup(A \cap B)=A$ 
$A \cap(A \cup B)=A$

contoh :
Misalkan A: "Belajar", B: "Mendengarkan musik".

A ∧ (A ∨ B): "Belajar dan (belajar atau mendengarkan musik)".
Hasilnya: "Belajar".
Bukti:

A	B	A ∨ B	A ∧ (A ∨ B)
T	T	T	T
T	F	T	T
F	T	T	F
F	F	F	F
Hasil menunjukkan bahwa A ∧ (A ∨ B) sama dengan A.

3. complement
$A \cup \bar{A}=U$
$A \cap \bar{A}=\emptyset$

Contoh:

Misalkan A: "Belajar", B: "Mendengarkan musik".

A ∧ (A ∨ B): "Belajar dan (belajar atau mendengarkan musik)".
Hasilnya: "Belajar".
Bukti:

A	B	A ∨ B	A ∧ (A ∨ B)
T	T	T	T
T	F	T	T
F	T	T	F
F	F	F	F
Hasil menunjukkan bahwa A ∧ (A ∨ B) sama dengan A.