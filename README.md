# labpy3
1).Alur Agoritmanya :

-import random memanggil file random

-n = int(input("Masukan nilai N : ")) input variabel n, tipe data integer

-for i in range(n) : looping for, dengan jumlah perulangan sebanyak n

-a=random.uniform(0.0,0.5) variabel a berisikan random angka dari 0.0 sampai 0.5

-print ("data ke : ", i, "=> ", a) print data ke : i = index looping a = angka random sesuai syarat nomer 4

-print("Selesai") print Selesai di luar looping

-Tampilkan hasil kelayar

2).Berikut kode lengkapnya :

print('|---------------------------------------------------|')

print('|PROGRAM MENAMPILKAN NILAI BILANGAN ACAK LEBIH < 0.5|')

print('|---------------------------------------------------|')

print('')

import random

n = int(input("Masukan nilai N : "))

for i in range(n) :

    a=random.uniform(0.0,0.5)
    
    print ("Data ke : ", i, "=> ", a)
    
print("Selesai")


1).Alur Algoritmanya :

-a=1 //variable a diisi 1, agar bisa masuk ke syarat while max=0 //variable max diisi 0
    
-while a!=0 : looping while dengan syarat a bukan 0

-if x > max : max = a proses if untuk mencari nilai terbesar

-a = int(input("Masukan bilangan : ")) input nilai a dengan tipe data integer

-if a == 0 : break jika inputan a diisi angka 0 maka break alias berhenti looping

-print("Bilangan terbesar adalah : ",max) print nilai terbesar, variabel max


2).Berikut kode lengkapnya:

print ('|-------------------------------------|')

print ('|PROGRAM MENAMPILKAN BILANGAN TERBESAR|')

print ('|-------------------------------------|')

print ('')

a=1

max=0

while a!=0:

    if a>max:
    
        max=a
        
    a=int(input('Masukkan bilangan :'))
    
    if a==0:
    
         break
        
print ('Nilai terbesarya adalah :',max)

1).Alur Agoritmanya :

-x=100000000 modal 100,000,000, variable x

-sum=0 variable untuk menjumlah total laba

-y=0 variable untuk masa bulan

-lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2] 

*variable untuk jumlah laba perbulan, 

 dipisahkan dengan koma, tipe data integer
 
-for i in lb : looping for indexs i, dengan mengambil data dari lb

-sum=sum+i rumus untuk menghitung total laba perbulan

-y+=1 masa bulan, tiap looping menambah 1

-print("laba bulan ke-", y ,"sebesar :", i ) print : y = ambil masa bulan, i = ambil dari data yg ada di dalam lb

-print("Total laba adalah :", sum) print total laba

-Tampilkan hasil kelayar 

2).Berikut kode lengkapnya :

x=100000000

sum=0

y=0

lb = [int(0), int(0), int(x) * .1, int(x) * .1, int(x) * .5, int(x) * .5, int(x) * .5, int(x) * .2]

print('Modal awal seorang pengusaha        :',x)

for i in lb :

    sum=sum+i
    
    y+=1
    
    print('Laba bulan ke-', y ,'sebesar            :', i)

print('Total laba yang didapat adalah      :', sum)


![flowchart1](https://user-images.githubusercontent.com/43899133/52893529-cc793e80-31cf-11e9-9c59-c11bd905c0d6.png)

![flowchart2](https://user-images.githubusercontent.com/43899133/52893530-d00cc580-31cf-11e9-9359-106996608278.png)

![flowchart3](https://user-images.githubusercontent.com/43899133/52893531-d26f1f80-31cf-11e9-81f9-3af17a891615.png)


![latihan1](https://user-images.githubusercontent.com/43899133/52893735-63df9100-31d2-11e9-8fbe-4e1e4330a72f.png)

![latihan2](https://user-images.githubusercontent.com/43899133/52893738-680bae80-31d2-11e9-9302-a3a846b9f08e.png)

![program1](https://user-images.githubusercontent.com/43899133/52893740-6b9f3580-31d2-11e9-87cd-a28c1f0078a2.png)




