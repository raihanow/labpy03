# labpy03
# Latihan1

![](https://github.com/raihanow/labpy03/blob/master/Latihan1coding.png)

### Mencari bilangan Random yang bersifat N : 5
Seperti ini algoritmanya
1. import random :: Untuk mengambil bilangan random,
2. N = int(input("Masukan nilai N : ")) // menangkap variabel 
dengan huruf N, dan mendata untuk integer
3. for x in range(n) // melooping sebuah bilang x dengan variabel 
yg sudah ada
4. b = random.uniform(0.0,0.5) // membuat bilangan random yang 
menghasilkan 0.0 s/d 0.5
5. print ("Data ke : ",a,"==>",b) ,, print data ke : a = index 
looping b = angka random yang sudah di buat varibelnya
6. print("Selesai") // membuat kata akhir setelah dikerjakan yang 
akan muncul " Hasil"
7. while jawab == "lanjutkan" // itu menandakan bahwa perulangan 
terjadi 8._ Hitung +=1 // itu mengubah atau menambahkan dari bilangan 
hitung = 0
8. if jawab == "lanjuttkan" : // hanya jika menjawab bilangan
9. break // untuk berrhenti jika ada syntax yang ia berikan.

### Codingan 
```print('====== Bilangan Acak Yang Lebih Kecil Dari 0.5 ======')
    print(' ')
    import random
    N = int(input("Masukan nilai N : "))
    a = 0
    for x in range(N):
        a += 1
        b = random.uniform(.0,.5)
        print('Data ke:',a,'==>',b)
    print('Selesai')
    print('')
    jawab = 'lanjutkan'
    hitung = 0
    while jawab == "lanjutkan":
        hitung += 1
        jawab = input('Ingin Mengulang? (yes/no) : ')
        if jawab == "Lanjutkan":
            break
    print('Total perulangan : ' + str (hitung))
 ```
### Gambar hasil dari codingannya

![](https://github.com/raihanow/labpy03/blob/master/Resultcode1.png)		

Latihan2

![](https://github.com/raihanow/labpy03/blob/master/Latihan2coding.png)

Pertama menentukan variabel untuk menghitung, dan menentukan kapan 
perulangan berhenti. kalau pengguna menjawab tidak maka perulangan akan 
terhenti.
jawab = 'ya' hitung = 0

Melakukan perulangan dengan while, kemudian menambah satu variabel 
hitung setiap kali mengulang. lalu menanyakan kepada pengguna, apakah 
mau berhenti mengulang atau tidak?

While (jawab == 'ya'): hitung += 1 jawab = raw_input("Ulang lagi tidak? 
") Setelah selesai mengulang, cetak berapa kali perulangan tersebut 
terjadi

### Codingan
```#!/usr/bin/python3
print("\nMenentukan Bilangan Terbesar")
print("\n")
max=0
while True:
    a=int(input("Masukan Bilangan :"))
    if max < a:
        max = a
    if a==0:
        break
print("Bilangan Terbesar = ", max)
input("\n")
```
### Gambar dari Hasil Codingan

![](https://github.com/raihanow/labpy03/blob/master/Resultcode2.png)

# Program1

![](https://github.com/raihanow/labpy03/blob/master/Program1coding.png)

Jika urutan berisi daftar ekspresi, itu dievaluasi terlebih dahulu. 
Kemudian, item pertama dalam urutan ditugaskan ke variabel iterating 
iterating_var . Selanjutnya, blok pernyataan dieksekusi. Setiap item 
dalam daftar ditugaskan ke iterating_var , dan blok pernyataan 
dieksekusi sampai seluruh urutan habis.

### Codingan
```a=100000000
for x in range(0,9):
        if(x>0 and x<=2):
                b=a*0
                print("laba bulan ke-",x," :",b)
        if(x>=3 and x<=4):
                c=a*0.1
                print("laba bulan ke-",x," :",c)
        if(x>=5 and x<=7):
                d=a*0.5
                print("laba bulan ke-",x," :",d)
        if(x==8):
                e=a*0.2
                print("laba bulan ke-",x," :",e)
total = b+b+c+c+d+d+d+e
print("\ntotal : ", total)
input("\n")
```
### Gambar dari hasil codingan

![](https://github.com/raihanow/labpy03/blob/master/Resultcode3.png)

