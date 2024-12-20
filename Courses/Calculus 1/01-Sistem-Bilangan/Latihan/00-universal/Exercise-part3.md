#gradient #calculus1 

## Latihan: Sistem Bilangan dan Sifat-Sifatnya

1. **Pengenalan Himpunan Bilangan**
   Diberikan himpunan bilangan berikut:
   $A = \{-2,-1,0,1,2,3,4\}$.
   - Tentukan elemen mana saja yang termasuk bilangan asli!
     **Jawab:**
     Secara bilangan asli, kita bisa melihat bahwa nilai $\{1,2,3,4\}$ merupakan kelompok bilangan asli.
     
   - Tentukan elemen mana saja yang termasuk bilangan bulat tetapi bukan bilangan asli! 
     **Jawab:**
     Secara bilangan bulat tetapi bukan bilangan asli, $\{-2,-1,0\}$ adalah bilangan yang termasuk bilangan bulat dengan secara konsep memiliki nilai bilangan negatif, nol, dan positif.

___

2. **Ekspansi Desimal**
   Ubah bilangan pecahan berikut ke dalam bentuk desimal (hingga tiga angka di belakang koma):
   - $\frac{1}{3}$
     **Jawab:** 
     - Pembilang : 1
     - Penyebut : 3
     - Proses :
       Lakukan pembagian $1 \div 3$: 
	    - $10 - 9 = 1 \rightarrow$ Tambahkan $0$ pada pembilang. 
	    - $10 - 9 = 1 \rightarrow$ Tambah 0 lagi
	    - $10-9 = 1 \rightarrow$ Tamabh 0 lagi
	    - Pola terus berulang.
     Nilai ekspansi desimal : $0.333\dots$ atau $0.\overline{3}$.
     
   - $\frac{7}{8}$
     **Jawab:**
     - Pembilang : 7
     - Penyebut : 8
     - Proses :
       Lakukan pembagian $7 \div 8$:
	     - $70-64 = 6$
	     - $60 - 56 = 4$
	     - $40 - 40 = 0$
     - Nilai ekspansi desimal : $0.875$.
       
   - $\frac{22}{7}$
     **Jawab:**
     - Pembilang : 22
     - Penyebut : 7
     - Proses : 
       Lakukan pembagian $22 \div 7$:
	     - $22 - 21 = 1$
	     - $10 - 7 = 3$
	     - $30 - 28 = 2$
	     - $20-14=6$
     - Nilai ekspansi desimal : $3.142$.

___

3. **Kenapa $\pi$ bukan $\frac{22}{7}$**
   Hitung hasil $\frac{22}{7}$ hingga lima angka di belakang koma dan bandingkan dengan nilai $\pi$ sebenarnya ($3.14159\dots$). Apakah nilainya sama? Apa yang membedakan keduanya.
	**Jawab:**
	- Mari kita uraikan dari pecahan $\frac{22}{7}$ hingga lima angka di belakang koma dengan melakukan ekspansi desimal.
		- Pembilang: $22$
		- Penyebut: $7$
		- Proses:
		  Lakukan pembagian $22 \div 7$:
		  - $22 - 21 = 1 \rightarrow$ Menambah 0 di pembilang.
		  - $10 - 7 = 3 \rightarrow$ Menambah 0 lagi.
		  - $30 - 28 = 2\rightarrow$ Menambah 0 lagi.
		  - $20 - 14 = 6 \rightarrow$ Menambah 0 lagi.
		  - $60 - 56 = 4 \rightarrow$ Menambah 0 lagi.
		  - $40 - 35=5 \rightarrow$ Menambah 0 lagi.
		  - $50-49=1 \rightarrow$ Menambah 0 lagi.
		  - Pola terus berulang.
		- Nilai ekspansi desimal: $3.142857$
	- Dari hasil pencarian dari pecahan $\frac{22}{7}$ adalah $3.142857$ dan dibandingkan dengan nilai $\pi$ $\approx 3.141592\dots$ :
		- Nilai $\pi \approx 3.14159\dots$
		- Nilai $\frac{22}{7} \approx 3.\overline{142857}$
	  
	  Dan kita bisa dilihat dari **hampir sama dengan**, dari semua itu adalah **berbeda** karena :
	  1. **Irrasional vs Rasional**
	    - $\pi$ adalah bilangan irrasional, yang artinya memiliki ekspansi desimal yang tidak pernah berakhir dan tidak ada polang yang berulang, sedangkan
		- $\frac{22}{7}$ adalah bilangan rasional, yang artinya ekspansi desimalnya berulang secara periodik ("$142857$").
	  2. **Ketepatan Angka Desimal**
		- $\pi$ memiliki nilai yang lebih akurat dan lebih mendekati nilai sebenarnya, sedangkan \frac{22}{7} hanya mendekati $\pi$ dalam angka pertama, namun semakin jauh hasilnya akan berbeda.
	
		    

___

4. **Sifat Aljabar Real - Komutatif Pertambahan**
   - Jika diketahui:
	   - $a = 5$
	   - $b = 8$
	- Buktikan bahwa operasi $a + b = b + a$ memenuhi sifat komutatif.
	- Hitung $a + b$.

___

5. **Lapangan Real 0 Komutatif Perkalian**
   - Diketahui:
		- $x=4$
		- $y=7$
	- Buktikan bahwa operasi $x \cdot y = y \cdot x$ memenuhi sifat komutatif.
	- Hitung hasil perkalian $x \cdot y$,


___

6. **Mengapa Tidak Boleh Membagi dengan 0?**
   Jelaskan apa yang akan terjadi jika kamu mencoba menghitung $\frac{5}{0}$. Gunakan penjelasan sederhana untuk mendukung jawabanmu.
   **Jawab:**
   - Jika kita mencoba menghitung $\frac{5}{0}, kita akan menghadapi masalah karena **tidak ada bilangan yang dapat dikalikan dengan 0 untuk menghasilkan 5**. Dalam bentuk lain, pembagian dapat dipikirkan sebagai mencari $x$ sehingga: $$0 \cdot x = 5$$
     Karena $0 \cdot x = 0$ untuk semua nilai $x$, tidak ada nilai $x$ yang memenuhi persamaan tersebut. Oleh karena itu, $\frac{5}{0}$tidak terdefinisi.
   - Selain itu, jika kita mencoba memaknai $\frac{5}{0} = \infty$, maka kita memasuki konsep limit (bukan hasil pembagian biasa). Tetapi di sini, konsep tak terhingga ($\infty$) tidak benar-benar bermakna dalam konteks pembagian sederhana karena mengacu pada hasil yang tak terdefinsi.  
   - **Kesimpulan:** Membagi dengan dol tidak diperbolehkan karena hasilnya tidak terdefinisi dan akan menyebabkan ketidakkonsistenan dalam perhitungan matematika.

___

7. **Darimana Asal Rumus ABC?**
   Jika persamaan kuadrat diberikan dalam bentuk $x^2 - 5x + 6 = 0$, gunakan rumus ABC untuk menemukan nilai $x$. Tuliskan langkah-langkahnya secara lengkap.
   **Jawab:**
   Persamaan kuadrat : $$x^2 - 5 + 6 = 0$$
   **Langkah 1: Identifikasi nilai a, b, dan c.**
   Bentuk umum persamaan kuadrat adalah $ax^2+bx+c=0$, sehingga: $$a = 1, \ \ b = -5, \ \ c = 6$$
___

   **Langkah 2: Subtitusi ke dalam rumus ABC.**
   Rumus ABC adalah: $$x = \frac{-b\pm\sqrt{b^2-4ac}}{2a}$$
   Masukkan nilai $a = 1,\ b= -5, \ c = 6$: $$x = \frac{-(-5)\pm\sqrt{(-5)^2-4(1)(6)}}{2(1)}$$

___


   **Langkah 3: Sederhanakan ekspresi di bawah akar($\Delta = b^2-4ac$)**. $$b^2 - 4ac = (-5)^2 0- 4(1)(6)=25-24 = 1$$
   Jadi: $$x = \frac{-(5) \pm \sqrt{1}}{2(1)}$$

___


   **Langkah 4: Sederhanakan hasil subtitusi**
   $$x = \frac{5\pm\sqrt{1}}{2}$$
   Karena $\sqrt{1}=1$, maka: $$x = \frac{5\pm1}{2}$$

___


   **Langkah 5: Pisahkan menjadi dua solusi.**
   1. Untuk $x_1$: $$x_1= \frac{5+1}{2}=\frac{6}{2}=3$$
   2. Untuk $x_2$: $$x_2=\frac{5-1}{2} = \frac{4}{2} = 2$$

___

**Kesimpulan:**
Nilai $x$ adalah: $$x_1 = 3, \ \ x^2 = 2$$
Kedua nilai ini adalah solusi dari persamaan kuadrat $x^2-5x+6=0$.