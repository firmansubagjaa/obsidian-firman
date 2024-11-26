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

int main() {
	int x = 5;
	printf("f(%d) %d\n", x,  fungsi(x)); // Output: f(5) = 13
	return 0;
}
```
Di sini:
- Input x diberikan ke fungsi **fungsi**.
- Output dihitung sebagai 2*x* + 3, lalu dikembalikan ke pemanggil fungsi.

### Hubungan dengan Machine Learning

Dalam Machine Learning, fungsi ini berkembang menjadi model yang lebih kompleks, seperti jaringan saraf tiruan ( **Neural Networks** ), yang menggunakan ribuan fungsi kecil untuk memodelkan hubungan data.


___


## Latihan Awal: Memahami Fungsi

1. Diberikan fungsi $$\begin{align}
f(x) &= 3x - 5
\end{align}$$
	hitung nilai $$\begin{align}
f(2), \ f(0), \ dan \ f(-1)
\end{align}$$

___


2. Jika fungsi : $$\begin{align}
g(x) = x^2 + 2x + 1
\end{align}$$
	bagaimana grafik fungsi ini?
	- Jawab: 
		- **Langkah - langkah Analisis Fungsi**
			Fungsi tersebut adalah **fungsi kuadrat** yang berbentuk: $$\begin{align}
g(x) = ax^2 + bx + c
\end{align}$$
			Dimana:
			- a = 1 (koefisien x^2)
			- b = 2 (koefisien x)
			- c = 1 (konstanta)
		
			Fungsi kuadrat seperti ini menghasilkan grafik berbentuk **parabola**. Arah parabola ditentukan oleh nilai *a*:
			- Jika *a* > 0, parabola terbuka ke atas.
			- Jika *a* < 0, parabolah terbuka ke bawah.
		
			Karena *a* = 1 > 0, parabolah ini terbuka ke atas.

		- **Cara Menganalisis Grafik**
			1. **Faktorisasi Fungsi**
				Kita akan memfaktorkan menjadi: $$\begin{align}
g(x) = (x + 1)^2
\end{align}$$
				Ini berarti parabola memiliki **akar ganda** di x = -1.

2. Tulis program sederhana dalam bahasa apa pun yang Anda kuasai untuk merepresentasikan fungsi : $$\begin{align}
h(x) = 4^2 - 7
\end{align}$$i
