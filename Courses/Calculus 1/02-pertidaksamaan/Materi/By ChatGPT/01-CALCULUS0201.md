#gradient #calculus1 #pertidaksamaan 

#### Apa Itu Pertidaksamaan?

Pertidaksamaan adalah pernyataan matematis yang membandingkan dua nilai atau ekspresi menggunakan tanda ketidaksamaan. Tanda-tanda tersebut adalah:
- "$<$": Lebih kecil dari
- "$>$": Lebih besar dari
- "$\leq$": Lebih kecil atau sama dengan
- "$\geq$": Lebih besar atau sama dengan

Contoh:
1. $x > 3$ artinya $x$ adalah bilangan yang lebih besar dari $3$.
2. $x \leq 7$ artinya $x$ adalah bilangan yang lebih kecil atau sama dengan $7$.

___

#### Sifat-Sifat Pertidaksamaan

Sifat-sifat ini penting untuk menyelesaikan pertidaksamaan dengan benar.
1. **Penjumlahan dan Pengurangan**
   Anda dapat menambahkan atau mengurangi bilangan yang sama di kedua sisi tanpa mengubah tanda pertidaksamaan.
   - Contoh:
     $x + 3 > 5 \rightarrow x > 5 - 3 \rightarrow x > 2$
1. **Perkalian dan Pembagian dengan Bilangan Positif**
   Anda dapat mengalikan atau membagi kedua sisi dengna bilangan positif tanpa mengubah tanda pertidaksamaan.
   - Contoh:
     $2x < 10 \rightarrow x < \frac{10}{2} \rightarrow x < 5$
1. **Perkalian dan Pembagian dengan Bilangan Negatif**
   Jika Anda mengalikan atau membagi kedua sisi dengan bilangan negatif, tanda pertidaksamaan harus dibalik.
   - Contoh:
     $-2x > 8 \rightarrow x < \frac{8}{-2} \rightarrow x < -4$
1. **Pertidaksamaan Bergabung**
   Jika terdapat dua pertidaksamaan, Anda bisa menggabungkannya untuk membentuk pertidaksamaan rangkap.
   - Contoh:
     Jika $x > 3$ dan $x < 7$, maka $3 < x < 7$

___

#### Garis Bilangan

Untuk memvisualisasikan solusi dari pertidaksamaan, garis bilangan adalah alat yang sangat berguna:
- Misalnya, $x > 3$ direpresentasikan sebagai garis mulai dari $3$ ke kanan, tanpa mencakup titik $3$ (ditandai dengan lingkaran kosong pada $3$).
- Jika $x \geq 3$, maka titik $3$ dicakup (ditandai dengan lingkaran penuh)

___

#### Jenis-Jenis Pertidaksamaan

1. **Pertidaksamaan Linear**
   - Berbentuk $ax + b > c$, dimana $a, b, c$ adalah bilangan real.
   - Contoh: $3x + 2 \leq 8$.
2. **Pertidaksamaan Kuadrat**
   - Berbentuk $ax^2+bx+c > 0$, melibatkan eksponen 2.
   - Contoh: $x^2 - 4 < 0$.
3. **Pertidaksamaan Rasional**
   - Melibatkan pecahan, seperti $\frac{P(x)}{Q(x)} > 0$
   - Contoh $\frac{x+1}{x-2}\geq 0$.

___

#### Contoh Pertidaksamaan Sederhana

##### 1. Menyelesaikan $2x-3 > 7$:
- Tambahkan $3$ ke kedua sisi:$$
    \begin{aligned}
    2x - 3 &> 7 \\
    2x &> 7 + 3 \\
    2x &> 10
    \end{aligned}
    $$
- Bagi kedua sisi dengan $2$: $$\begin{aligned}
  2x &> 10 \\
  x &> \frac{10}{2} \\
  x &> 5
    \end{aligned}$$
##### 2. Menyelesaikan $-3x + 2 \leq 8$:
- Kurangi $2$ dari kedua sisi: $$
\begin{aligned}
-3x + 2 &\leq 8 \\
-3x &\leq 8 - 2 \\
-3x &\leq 6 \\
\end{aligned}
$$
- Bagi kedua sisi dengan $-3$ (ingat untuk membali tanda!):
$$
\begin{aligned}
-3x &\leq 6 \\
x &\leq \frac{6}{-3} \\
x &\leq -2
\end{aligned}
$$

___
##### Contoh soal pertidaksamaan kuadrat
1. $x^2 - 4 \geq 0$
   **Jawab:**
   1. Faktorkan persamaan kuadrat
      $$
	      \begin{aligned}
	      x^2 - 4 = (x-2)(x+2)
	      \end{aligned}
	     $$
   2. Tentukan nilai-nilai kritis (akar-akar) dari faktorisasi:
      $$
	      \begin{aligned}
	      (x-2)(x+2) = 0 \ \ \ \implies \ \ \ \ x = 2 \ atau \ x = -2
	      \end{aligned}
	     $$
   3. Tentukan tanda dari faktor-faktor tersebut dengan membuat interval berdasarkan akar-akar yang ditemukan: $(-\infty, 2),(-2,2), (2, \infty)$
      - Untuk $(-\infty, -2)$, pilih nilai $x = -3$:$$
	      \begin{aligned}
	      (-3 - 2)(-3+2) = (-5)(-1) = 5 > 0
	      \end{aligned}
	     $$
      - Untuk $(-2,2)$, pilih nilai $x=0$:  $$
	      \begin{aligned}
	      (0 - 2)(0+2) = (-2)(2) = -4 < 0
	      \end{aligned}
	     $$
      - Untuk $(2, \infty)$, pilih nilai $x = 3$:  $$
	      \begin{aligned}
	      (3 - 2) (3 + 2) = (1)(5) = 5 > 0
	      \end{aligned}
	     $$
   4. Berdasarkan tanda positif dan negatif, solusi untuk $(x-2)(x+2) \geq 0$ adalah: $$
	      \begin{aligned}
	      x \in (-\infty, -2 | \cup | 2, \infty)
	      \end{aligned}
	     $$___
	     
2. $x^2 + 4x - 5 < 0$
   1. Faktorkan persamaan kuadrat: $$\begin{aligned} 
      x^2+ 4x -5 = (x - 1)(x + 5)
      \end{aligned}$$
   2. Tentukan nilai-nilai kritis (akar-akar) dari faktorisasi: $$\begin{aligned} 
      (x-1)(x+5) = 0 \ \ \ \ \implies \ \ \ \ x = 1 \ atau \ x = -5
      \end{aligned}$$
   3. Tentukan tanda dari faktor-faktor tersebut dengan membuat interval beredasarkan akar-akar yang ditentukan: $(-\infty, -5), (-5,1), (1, \infty)$
      - Untuk $(-\infty, -5)$, pilih nilai $x = -6$: $$\begin{aligned} 
      (-6 - 1)(-6+5) &= (-7)(-1) \\
      &= 7 > 0
      \end{aligned}$$
      - Untuk $(-5, 1)$, pilih nilai x = 0:$$\begin{aligned} 
      (0 - 1)(0 + 5) &= (-1)(5) \\
      &= -5 < 0
      \end{aligned}$$
      - Untuk $(1, \infty)$, pilih nilai $x = 2$: $$\begin{aligned} 
      (2 - 1)(2 + 5) &= (1)(7) \\
      &= 7 > 0
      \end{aligned}$$
   4. Berdasarkan tanda positif dan negatif, solusi untuk $(x - 1)(x + 5) < 0$ adalah: $$\begin{aligned} 
      x \in (-5, 1)
      \end{aligned}$$

___


3. $x^2-2x-3 \geq 0$
   1. Faktorkan persamaan kuadrat:
   2. Tentukan nilai-nilai kritis dari faktorisasi
   3. Tentukan tanda dari faktor-faktor tersebut dengan membuat interval beredasarkan akar-akar yang ditentukan: $(-\infty, -1), (-1,3), (3, \infty)$
   4. Berdasarkan tanda positif dan negatif