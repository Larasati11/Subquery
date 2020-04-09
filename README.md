# Subquery
Subquery (disebut juga subselect atau nested select / query atau inner- select) adalah query SELECT yang ada di dalam perintah SQL lain— misalnya  SELECT, INSERT, UPDATE, atau DELETE. 

1. Scalar Subquery 
Subquery baris tunggal (scalar) hanya mengembalikan hasil satu baris data.Subquery baris tunggal dapat menggunakan operator baris tunggal =, >, >=, <, <=, atau <>. 


![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20scalar.png)

2.  Multiple-Row Subquery 
 
Pada subquery ini, kita menggunakan operator komparasi IN, ANY / SOME, atau ALL. 

Operator IN 

Operator IN memiliki arti : sama dengan member di dalam list


![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20in.png)


Operator AN Y / SOME 

Operator ANY / SOME memiliki arti : membandingkan suatu nilai dengan setiap nilai yang dikembalikan oleh subquery. 


![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20any.png)
 
 
Operator ALL 
 
Operator ALL memiliki arti : membandingkan suatu nilai dengan semua nilai  yang dikembalikan oleh subquery. 


![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20all.png)
 
 
 3.Multiple-Column Subquery 
 
Subquery kolom ganda (atau tabel) juga menggunakan operator komparasi IN, ANY / SOME, atau ALL. 

![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20multiple.png)


4.Operator EXISTS dan NOT EXISTS 
 
Operator EXISTS dan NOT EXISTS digunakan pada correlated subquery untuk memeriksa apakah subquery mengembalikan hasil atau tidak. Apabila subquery mengembalikan hasil, EXISTS akan mengembalikan nilai true. Begitu pula sebaliknya, jika tidak mengembalikan hasil. 

![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20exist.png)

![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20not%20exist.png)


5.Subquery dan Fungsi Agregat 
 
Operasi-operasi pada subquery juga dapat melibatkan fungsi-fungsi agregat. 
 

![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20%26%20fungsi%20agregat.png)


6.Subquery dan Join 
 
Dalam beberapa kasus sederhana, fungsionalitas subquery dan join dapat dipertukarkan. Dengan kata lain, keduanya dapat digunakan untuk menyelesaikan persoalan yang sama. 

![AltText](https://github.com/Larasati11/Subquery/blob/master/subquery%20%26%20join.png)


TUGAS PRAKTIKUM 

1. Dapatkan data mahasiswa yang alamatnya sama dengan mahasiswa dengan nim102, tidak termasuk mahasiswa tersebut. 

2. Dapatkan matakuliah yang tidak diajar oleh dosen terdaftar. 

3. Dapatkan data dosen yang mengajar matakuliah dengan sks lebih kecil dari sembarang sks. 

4. Dapatkan nim, nama, dan alamat mahasiswa yang tempat tinggalnya sama dengan dosen yang mengajar matakuliah dengan jumlah sks terbanyak.  
