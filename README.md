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

