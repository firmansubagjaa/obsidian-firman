#binus #computerscience #calculusandcientificcomputing #fungsidanmodel 


## Definisi dan Komponen Fungsi

Kita akan mulai dari konsep **fungsi** secara matematis. Fungsi dalah **relasi** yang menghubungkan setiap elemen dari sebuah himpunan ( disebut *domain* ) dengan tepat satu elemen dalam himpunan lain (disebut *range* ).

#### 1. Notasi fungsi

Fungsi biasanya dinotasikan sebgai: $$\begin{align}
f:X &\to Y \\
&or \\
f(x) &= y
\end{align}$$Di mana:
- X: Domain (kumpulan semua nilai input yang mungkin).
- Y: Range (kumpulan semua nilai output yang mungkin).
- x: Variable Input
- f(x):  Hasil dari fungsi untuk input tertentu (output).


### 2. Contoh Fungsi

Misalkan : $$\begin{align}
f(x) &= 2x + 3
\end{align}$$
- Jika x = 1, maka:  $$\begin{align}
f(1) &= 2(1) + 3 = 5
\end{align}$$
- Jika x = 2, maka: $$\begin{align}
f(2) = 2 (2) + 3 = 7
\end{align}$$
Fungsi ini secara sederhana mengilustrasikan hubungan antara vairable input *x* dengan output *f(x)*.


___


## Visualisasi Fungsi

Untuk mempermudah pemahaman, fungsi sering divisualisasikan dalam grafik. Misalnya, fungsi $$\begin{align}
f(x) &= 2x + 3 \\
\end{align}$$
- Jika kita menggambarkan di sistem koordinat kartesius, *x* adalah sumbu horizontal, dan *f ( x )* adalah sumbuh vertikal.
- Grafik fungsi ini berupa garis lurus, dengan kemiringan (*slope*) 2 dan titik pototng di sumbu *y* adalah 3.

Dalam Pemrogramam, grafik fungsi ini mirip dengan data yang di-*plot* dalam  sbeuah tabel atau diagaram.


___


## Hubungan Fungsi dengan Model Matematika

Fungsi menjadi dasar dalam pembuatan **model matematika**. Model matematika adalah pendekatan untuk mendeskripsikan fenomena nyata dengan menggunakan fungsi atau persamaan.

### Contoh dalam kehidupannya Nyata

1. **Sistem Rekomendasi Film**
	- Input: Film yang ditonton pengguna, genre, rating.
	- Fungsi: Algoritma yang menghitung skor rekomendasi berdasarkan preferensi pengguna.
	- Output: Daftar film yang mungkin disukai pengguna.
2. **Prediksi Kecepatan Internet**
	- Input: Kondisi jaringan, jumlah pengguna aktif.
	- Fungsi: Model yang memprediksi kecepatan berdasarkan parameter tersebut.
	- Output: Kecepatan yang diharapkan (dalam Mbps).


___


## Fungsi dalam Pemrograman

Pada level praktis, fungsi dalam matematika sering diterjemahkan ke dalam fungsi dalam pemrograman. Misalnya:

#### Kode Program dalam C

Berikut adalah contoh fungsi sederhana yang merepresentasikan 
***f(x)* = 2*x* + 3**:
```c
#include <stdio.h>

// Definisi fungsi
int fungsi (int x) {
	return 2 * x + 3;
}
```