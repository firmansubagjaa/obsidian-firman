#binus #computerscience #calculusandcientificcomputing #limitdanfungsi 
___
1.  Diberikan 
$$\begin{align}
f(x) = 5x^2 + 7x
\end{align}$$
	Lalu carikan lim x->3 f(x)
	**Jawab:**
	Kita lakukan subtitusi x ke dalam fungsi, yang mana
	$$\begin{align}
x &= 3
\end{align}$$
	Sehingga,
	$$\begin{align}
f(3) &= 5(3)^2 + 7(3) \\
     &= 45 + 21 \\
     &= 66
\end{align}$$
2.  Diberikan :
$$
\begin{align}
f(x) &= \frac{4x^2 + 2x}{2x}
\end{align}
$$
	Lalu carikan lim x->0 f(x)
	**Jawab:**
	Langkah pertama yaitu mencoba substitusi langsung 
$$\begin{align}
\frac{4(0)^2 + 2}{2(0)} = \frac{0}{0}
\end{align}$$
	Ini adalah bentuk tak terdefinisi, sehingga harus menyederhanakan ekspresi ini terlebih dahulu dengan memfaktorkan **pembilang.** dan **penyebut**.

	Pembilang :
	$$\begin{align}
4x^2 + 2x = 2x(2x + 1)
\end{align}$$
	Sehingga fungsi menjadi :
$$\begin{align}
\frac{2x(2x + 1)}{2x}
\end{align}$$
	Kita bisa menyederhanakan 2x pada pembilang dan penyebut, dengan syarat x != 0 :
	$$\begin{align}
&= 2x + 1
\end{align}$$
	Sekarang, kita bisa langsung substitusi x = 0 ke dalam ekspresi yang sudah disederhanakan:
	$$\begin{align}
2(0) + 1 = 1
\end{align}$$
	Jadi, hasilnya adalah **1**!

4.  Diberikan :
$$\begin{align}
f(x)= \frac{x^2-1}{x - 1}
\end{align}$$
	Lalu kita carikan lim x->1 f(x)!
	**Jawab:**
	- Langkah pertama yaitu melakukan subtitusi yang mana x = 1 akan dimasukkan ke dalam fungsi
$$\begin{align}
f(1) &= \frac{1^2-1}{1-1} \\
     &= \frac{0}{0}\\
\end{align}$$
	- hasilnya adalah 0/0 tetapi ini merupakan salah satu bentuk tak terdefinisi, sehingga harus menyederhanakan terlebih dahulu
$$\begin{align}
\frac{x^2 - 1}{x-1} &= \frac{(x- 1)(x+1)}{x-1} \\
\end{align}$$
	- kita bisa menyederhanakan x - 1 pada pembilang dan penyebut, dengan syarat x != 0
$$\begin{align}
&= x + 1 \\
\end{align}$$
	- Sekarang kita bisa menyederhanakan dengan cara subtitusi x = 1:
$$\begin{align}
f(1) &= 1 + 1 \\
&=2
\end{align}$$
	- Hasilnya adalah 2

5.  Diberikan
$$\begin{align}
f(x) = \frac{6x^2 - 12}{x-2} \\
\end{align}$$
	Lalu kita disuruh untuk mencarikan lim x->2 f(x)
	**Jawab:**
	- Pertama, kita mencoba untuk melakukan subtitusi dimana x = 2 dan melakukan pengecekan apakah limit dan fungsi ini hasilnya terdefinisi atau tak terdefinisi :
$$\begin{align}
f(2) &= \frac{6(2)^2 - 12}{2-2} \\
&= \frac{24 - 12}{2-2} \\
&= \frac{12}{0}
\end{align}$$
	- Hasilnya adalah 0/0 dan ini menyatakan kalau limit tersebut tak terdefinisi, sehingga kita harus melakukan penyerdehanaan terlebih dahulu dalam pembilang dan penyebut :

$$\begin{align}
&= 6x^2 - 12  &  \\
&= 6(x^2 - 2)
\end{align}$$
	- Kita bisa melakukan x = 2 pada pembilang dan penyebut dengan syarat x != 0
$$\begin{align}
f(2) &= \frac{6(2^2 - 2)}{2-2}  \\
&= \frac{6(x - 2)(x + 2)}{x-2} \\
&= 6(x+2) \\
&= 6(2 + 2) \\
&= 6(4) \\
&= 24
\end{align}$$