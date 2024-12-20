#calculus1 

#### Selesaikan pertidaksamaan berikut:
1. $x^2-5x+6 > 0$
   **Jawab**
   1. Mencari faktor:
   - Identifikasi a,b,c: $a = 1, b = -5, c = 6$
   - Mencari misalkan $m$ dan $n$:
     - $m \cdot n = a \cdot c = 1 \times 6 = 6$
     - $m + n = b = -5$
     - Nilai yang memenuhi adalah $m=-3$ dan $n = -2$, karena:
       - $m \cdot n = -3 \times (-2) = 6$
       - $m + n = -3 + (-2) = -5$
   - Faktorkan:
      $$
	      \begin{aligned}
	      x^2-5x+6 &= x^2 -3x-2x+6\\
	      &=(x^2-3x)+(-2x+6)\\
	      &=x(x-3)-2(x-3)\\
	      &= (x-2)(x-3)
	      \end{aligned}
	     $$
   - Hasil pemfaktoran: $$(x-2)(x-3)$$
	2. Nilai-nilai kritis dari faktorisasi:
	  $$ \begin{aligned}
	  (x-2)(x-3) &\implies x = 2 \ atau \ x = 3
		\end{aligned}$$
	3. Mencari faktor dengan membuat interval $(-\infty,2), \ (2,3), \ (2, \infty):$
	   - Interval $(-infty,2), \ x = 0$: $$(0-2)(0-3)=(-2)(-3) = 5 > 0$$
	   - Interval $(2,3), x = 2.5$: $$(2.5-2)(2.5-3)=(0.5)(-0.5) = -0.25 < 0$$
	   - Interval $(3, \infty), \ x= 4$: $$ (4 - 2)(4 - 3) = (2)(1) = 2 > 0 $$
	4. Gunakan syarat pertidaksamaan
	   Karena $x^2-5x+6 > 0$, pilih interval dengan tanda positif $(+)$: $$x \in (-\infty,2)\cup(3, \infty)$$
2. $x^2+x-6 \leq 0$
   **Jawab:**
   1. Identifikasi a, b, dan c:
      - $a = 1$
      - $b=1$
      - $c = -6$
   2. Menggunakan Rumus ABC:
       $$\begin{aligned}
	       x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a} \\
	       &= \frac{-1 \pm \sqrt{1-4(1)(-6)}}{2(1)}\\
	       &= \frac{-1 \pm \sqrt{1+24}}{2(1)}\\
	       &= \frac{-1 \pm \sqrt{25}}{2}\\
	       &= \frac{-1 \pm 5}{2}\\
	       x_1&= \frac{-1 + 5}{2} = \frac{4}{2} = 2\\
	       x_2&= \frac{-1 - 5}{2} = -\frac{6}{2} = -3\\
	      \end{aligned}$$
	3. Menentukan 3 interval:
	   - $(-\infty, -3)$
	   - $(-3, 2)$
	   - $(2, \infty)$
	4. Menentukan tanda pada setiap interval
	   - $(-\infty, -3), x = -4$:
	     $$-4^2+4-6 = 16 + 4 - 6 = 14 \ (+)$$
	   - $(-3, 2), x = 0$: $$0^2+0-6 = -6 \ (-)$$
	   - $(2, \infty), x = 3$ : $$3^2+3-6 = 9 + 3 - 6 = 6 \ (+)$$
	5. Kesimpulan
	   Jadi, solusi dari pertidaksamaan $x^2 + x - 6 \leq 0$: $$x \in [-3,2]$$
      
     
3. $2x^2-3x-2 < 0$
   **Jawab:**
   1. Indentifikasi a, b, dan c: $a = 2, b = -3, c=-2$
   2. Menggunakan rumus Kuadrat:
       $$
      \begin{aligned}
      x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}\\
      &= \frac{-(-3) \pm \sqrt{(-3)^2 - 4(2)(-2)}}{2(2)}\\
      &= \frac{3 \pm \sqrt{9 + 16}}{4}\\
      &= \frac{3 \pm \sqrt{25}}{4}\\
      &= \frac{3 \pm 5}{4}
      \end{aligned}
      $$Kita bagikan menjadi dua solusi:
      $$
      \begin{aligned}
      x_1 &= \frac{3 + 5}{4} = \frac{8}{4} = 2 \\
      x_2 &= \frac{3-5}{4} = -\frac{2}{4} = -\frac{1}{2} 
      \end{aligned}
       $$
   3. Menentukan Interval: kita bagi menjadi 3 interval:
      - $(-\infty, -\frac{1}{2})$
      - $(-\frac{1}{2}, 2)$
      - $(2, \infty)$
   4. Tentukan tanda pada setiap interval
      - Interval $(-\infty, -\frac{1}{2})$, nilai $x$ = -1: $$2(1)^2 -3(-1) - 2 = 2(1) + 3 - 2 = 3 \ \ (+)$$Hasilnya positif
      - Interval $(-\frac{1}{2}, 2)$, nilai $x = 0$: $$2(0)^2 - 3(0) - 2 = 0 - 0 - 2=-2 \ (-)$$Hasilnya negatif
      - Interval $(2, \infty)$, nilai $x = 3$: $$2(3)^2 - 3(3)-2 = 18 - 9 - 2 = 7 \ (+)$$Hasilnya positif
	5. Jadi, solusi dari pertidaksamaan $2x^2-4x-2 < 0$ adalah : $$x \in (-\frac{1}{2}, 2)$$ 

4. $4x^2-4x+1 \geq 0$
   **Jawab:**
   1. Identifikasi a,b,c :
      - a = 4
      - b = -4
      - c = 1
   2. Menggunakan Rumus ABC:
       $$
	       \begin{aligned}
	       x &= \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}\\
	       &= \frac{-(-4) \pm \sqrt{(-4)^2 - 4(4)(1)}}{2(1)}\\
	       &= \frac{4 \pm \sqrt{16 +16}}{2}\\
	       &= \frac{4 \pm 32}{2}\\
	       x_1&= \frac{4 + 32}{2} = \frac{36}{2} = 18\\
	       x_2&= \frac{4 - 32}{2} = -\frac{28}{2} = -14 \\
	       \end{aligned}
	      $$
   1. 
1. $x^2-2x-8 > 0$