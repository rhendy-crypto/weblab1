# Membuat Kode Program dari flowchart pertemuan ke 5
Tugas Pertemuan ke 5
Nama: Rhendy Zhaky Alvian
Kelas TI 24 A3
NIM: 312410397
# 1. bilanganterbesar.py
Program pertama yang akan dibuat adalah program untuk menampilkan bilangan terbesar dari 3 Bilangan yang diinputkan
Berikut flowchartnya

![WhatsApp Image 2024-10-22 at 00 04 08_d4292dac](https://github.com/user-attachments/assets/264436cb-3c6e-4622-abd2-d3e777da93cb)

# Program akan meminta kita untuk memasukkan 3 angka untuk dibandingkan:
![image](https://github.com/user-attachments/assets/89513614-bedf-4a96-a179-56ecf048a9e7)

Penjelasan Code

def mencari_bilangan_terbesar(a, b, c):
    if a > b:
        if a > c:
            return a, "A adalah terbesar"
        else:
            return c, "C adalah terbesar"
    else:
        if b > c:
            return b, "B adalah terbesar"
        else:
            return c, "C adalah terbesar"

# Input bilangan A, B, C
print("Masukkan tiga bilangan:")
a = float(input("A: "))
b = float(input("B: "))
c = float(input("C: "))

# Menentukan bilangan terbesar
largest, message = mencari_bilangan_terbesar(a, b, c)

# Menampilkan hasil
print(f"\n{message}")
print(f"Bilangan terbesar adalah: {largest}")
