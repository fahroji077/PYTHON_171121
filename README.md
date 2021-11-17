# PYTHON_171121

1. PROGRAM MENAMPILKAN HARGA BENSIN

```y
judul = "PROGRAM MENAMPILAKAN HARGA BENSIN"
print(judul.rjust(50))
print("-"*70)
satuan = 0
harga = 0
a = 0
b = float(input("Masukkan Bensin yang akan di beli : "))
print("_"*40)
print("Satuan        |       Harga         |")
while a < 100:
    a += 1
    satuan = a * 0.5
    harga = a * 800
    
        
    print("-"*40)
    print(f"{satuan} ltr       |   Rp.  {harga}          |")
    if satuan == b:
        break

print(f"\nAnda Membeli {b} liter Bensin, Maka Anda Harus Membayar Rp. {harga}")
```
![image](https://user-images.githubusercontent.com/93015185/142193665-080c2af8-52be-4c2e-b260-7e8f5feaaf34.png)
![image](https://user-images.githubusercontent.com/93015185/142193698-5fa05248-8186-4cff-81e3-7d3cc4b0661b.png)

2. PROGRAM DERET GEOMETRI

```y
awal = int(input ("masukan nilai awal : "))
suku = int(input("masukan nilai akhir : "))
rasio = int(input("masukan rasio : "))


while awal <= suku :
    deret = awal
    awal += rasio
    print(deret)
```
![image](https://user-images.githubusercontent.com/93015185/142194788-42302082-c292-4bfe-8e4b-052a9a34b122.png)

3. PROGRAM MENGHITUNG NILAI RATA-RATA & TOTAL

```y
judul = "MENGHITUNG NILAI RATA-RATA & TOTAL"
print(judul.rjust(45))
print("-"*70)

data = int(input("Jumlah angka : "))

a = []

for i in range(1, data+1):
   p = int(input(f"Angka {i} : "))
   a.append(p)
print(f"Total : {sum(a)}")    
print(f"Rata-rata : {sum(a)/data}")
```
![image](https://user-images.githubusercontent.com/93015185/142196198-6317b2cf-a7a0-407b-b971-2d1bd3033a1d.png)

4. PROGRAM MENCARI BILANGAN REAL DAN BILANGAN BULAT

```y
judul = "PROGRAM MENCARI BILANGAN REAL DAN BILANGAN BULAT"
print(judul.center(40))
print("-"*50)

x = float(input("Masukkan bilangan real (x) : "))
y = int(input("Masukkan bilangan bulat (y) : "))

z= x ** y
print("maka jumlah pangkat (x pangkat y) : ", z)

```
![image](https://user-images.githubusercontent.com/93015185/142197929-f275a51a-4fc2-4c73-862e-8129330a6493.png)

5. PROGRAM MENGHITUNG NILAI N

```y
judul = "PROGRAM MENGHITUNG NILAI N"
print(judul.rjust(40))
print("-"*70)

def fa(n):
    if n == 0:
        return 1
    else:
        return n*fa(n-1)


n = int(input("Masukkan nomor : "))
print(f"{n}! = ",' * '.join(map(str, range(n, 0, -1))), " = ", fa(n))
```
![image](https://user-images.githubusercontent.com/93015185/142198165-005c710e-872a-49d1-97c4-52c14eb619a8.png)
6. TEBAK ANGKA DENGAN BILANGAN INTEGER

```y
judul = "TEBAK ANGKA DENGAN BILANGAN INTEGER"
print(judul.rjust(45))
print("-"*55)

import random

angka = random.randint(1, 10)



while True:
    jawab = int(input("Masukkan angka 1 sampai 10 : "))
    if jawab == angka:
        print("Selamat tebakkan anda benar ")
        break
    else:
        print("Tebakkan anda terlalu",
             "Kecil" if jawab < angka else "Besar"
              )
```
![image](https://user-images.githubusercontent.com/93015185/142199766-567fa51c-8ced-435c-9089-c314e76173dc.png)

7. MENAMPILKAN & MENJUMLAHKAN SEMUA BILANGAN

```y
judul = "MENAMPILKAN & MENJUMLAHKAN SEMUA BILANGAN"
print(judul.rjust(45))
print("-"*55)

x = int(input("x = "))
y = int(input("y = "))

kist = []
for i in range(x, y):
    kist.append(i) 
kist.pop(0)
toString = ' '.join(map(str, kist))

print("Deret = ",toString)
print(f"Jumlah = {sum(kist)} ")
```
![image](https://user-images.githubusercontent.com/93015185/142200388-6c70e737-555e-462a-8219-f9f28baa69f2.png)

8. PROGRAM MENAMPILKAN BENTUK

```y
judul = "PROGRAM MENAMPILKAN BENTUK"
print(judul.rjust(45))
print("-"*55)

n = int(input("Masukkan nilai N :"))

for i in range(1, n+1):
    for j in range(i+n):
        print(i*j, end=" ")
    print("")
```
![image](https://user-images.githubusercontent.com/93015185/142201270-eff3a099-a83c-44c2-97cb-4f8302ba0122.png)

   
