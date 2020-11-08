# praktikum7

Repository ini dibuat untuk memenuhi tugas Dosen pertemuan 7 - lab 3

***Nama : Antini Permatasari***

***NIM : 312010095***

***Kelas : TI.20.B1***


## Tugas Praktikum lab 3

Pada repository ini saya mendapatkan tugas dari dosen bahasa pemrograman pada latihan 1 dan latihan 2.
<br>

* **latihan 1**

Pada latihan 1 saya akan membuat program dengan perulangan bertingkat **(nested)** for : <br>
 ***(nested)*** for : <br>
![Tugas_Latihan1_lab3](picture/Tugas_Latihan1.PNG)

<br>

berikut source code yang saya buat dalam program latihan 1 tau pada link berikut [link_latihan1](latihan1.py).
<br>
``` python
print(list(range(0, 10, 1)))
print(list(range(1, 11, 1)))
print(list(range(2, 12, 1)))
print(list(range(3, 13, 1)))
print(list(range(4, 14, 1)))
print(list(range(5, 15, 1)))
print(list(range(6, 16, 1)))
print(list(range(7, 17, 1)))
print(list(range(8, 18, 1)))
print(list(range(9, 19, 1)))
print()
```
<br>
* Keterangan : <br>
Perulangan ***for*** disebut juga sebagai counted loop (perulangan yang terhitung), yaitu perintah yang di eksekusi secara berulang berdasarkan jumlah perulangan tertentu.<br>
Nested loop atau pengulangan bersarang dimana for yang juga berada didalam pernyataan (perulangan didalam perulangan)

Pada source code tersebut akan menghasilkan Output : <br>
![Output_latihan1](picture/Output_latihan1.PNG)

<br>

* **latihan 2** 

Pada latihan 2 saya akan membuat program tampilan ***n*** bilangan acak yang lebih kecil dari 0.5. <br>
![tugas_latihan2](picture/)
<br>
Pada tugas tersebut saya menggunakan kombinasi ***(import random dan uniform)***, dengan source code sebagai berikut atau pada link 
[link_latihn2](lab3_)
```python
n=int(input("Masukkan Nilai N :  "))
print("\n")

import random

for a in list(range(1,n+1,1)):
    print(random.uniform(0,0.5))

print()
```

Pada source code tersebut akan menghasilkan output sebagai berikut : <br>
![Output_latihan2](picture/Output_latihan2.PNG)
 
* ket : <br>
fungsi random() akan menghasilkan angka yang menghasilkan angka yang memiliki tipe data float dan berada pada rentand 0,0 hingga 1,0. pada fungsi ini tidak perlu menambahkan argument. <br>
uniform sendiri berfungsi untuk menampilkan bilangan float random dengan batas awal bilangan dan batas akhir.

<br>
Demikian repository dari saya, semoga bisa bermanfaat dan memenugi tugas saya sendiri khususnya.


<br>
<br>
### ***===== Antini permatasari ====***
### ***===== 312010095 ===========***
### ***===== T1.20.B.1 ===========***