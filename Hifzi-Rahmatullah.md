# Tugas-Praktikum-Python-5

### 1. PROGRAM MENGHITUNG LUAS BANGUN DATAR

> Code

![images (1)](https://user-images.githubusercontent.com/93045470/142576935-09061e87-4014-4666-a0d1-a0b80ca4a3d0.png)

> Source Code
```py
def persegiPanjang():
    print("-----------------------------------------------")
    panjang = int(input("Masukkan panjang : "))
    lebar   = int(input("Masukkan lebar   : "))
    luas_PP = panjang * lebar
    print("Luas persegi panjang adalah :", luas_PP, "cm")
    print("-----------------------------------------------")

def segitiga():
    print("-----------------------------------------------")
    alas   = int(input("Masukkan alas segitiga   : "))
    tinggi = int(input("Masukkan tinggi segitiga : "))
    luas_S = float(1) / 2 * alas * tinggi
    print("Luas segitiga adalah     :", luas_S, "cm")
    print("-----------------------------------------------")

def lingkaran():
    print("-----------------------------------------------")
    r      = float(input("Masukkan ruas lingkaran : "))
    luas_L = 3.14 * r ** 2
    print("Luas lingkaran adalah   :", luas_L, "cm")
    print("-----------------------------------------------")

pilih = ""
print("      PROGRAM MENGHITUNG LUAS BANGUN DATAR")
print("-----------------------------------------------")
print("Persegi Panjang = [A]" + "   Lingkaran = [C]")
print("Segitiga        = [B]" + "   Keluar    = [exit]")
print("-----------------------------------------------")

while pilih != "exit":
    pilih = input("Pilihan : ")
    if pilih == "exit":
        break
    
    if pilih != "A" and pilih != "B" and pilih !="C":
        print("[!] Pilihan Tidak Dikenal")
        print("-----------------------------------------------")
        continue

    if pilih == "A":
        persegiPanjang()
    elif pilih == "B":
        segitiga()
    elif pilih == "C":
        lingkaran()

print("\n-----------------------------------------------")
print("\t\t TERIMA KASIH")
print("-----------------------------------------------")
```
> Hasil Output

![images (2)](https://user-images.githubusercontent.com/93045470/142576415-7a61adbd-6158-451c-9f37-343d713fc3de.png)

### 2. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 3. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 4. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 5. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 6. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 7. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>


### 8. PROGRAM 

> ### Source Code<br>
<br>
> ### Hasil Output<br>

