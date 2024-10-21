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

![WhatsApp Image 2024-10-22 at 01 22 55_6f632c0e](https://github.com/user-attachments/assets/ac47e83b-f4f9-4e87-9b28-4c08475b6b0e)

1. Kita mendefinisikan function mencari_bilangan_terbesar yang mengambil tiga parameter (a,b,c).
2. function tersebut menggunakan nested if-else statement untuk membandingkan angka yang diinputkan
3. Kemudian akan menampilkan Mana bilangan terbesar
4. Lalu di Program utamanya kita masukkan angka yang harus dimasukkan oleh user
5. Lalu kita panggil function mencari_bilangan_terbesar
6. Lalu output bilangan terbesar dari ketiga bagian yang diinput akan muncul

# 2. bilanganN.py

Program kedua adalah untuk membandingkan bilangan yang diinput, input akan terus berjalan kecuali user memasukkannya nilai 0

Flowchartnya

![WhatsApp Image 2024-10-22 at 01 32 00_f9ff4758](https://github.com/user-attachments/assets/dddfb495-edc7-4645-9ebc-6140b22e2ec6)

Program akan meminta kita untuk memasukkan angka untuk dibandingkan, input akan terus dimimta sebelum user memasukkan angka 0:

![image](https://github.com/user-attachments/assets/f002fe47-d50b-4776-a88f-b936e0a1f3ed)

Penjelasan Code
def find_largest_number():
Mendefinisikan fungsi bernama find_largest_number akan menangani logika utama program.
largest = float ("-inf")
Menginisialisasi variabel largest dengan nilai negatif tak terhingga. ini memastikan bahwa angka pertama yang dimasukkan akan selalu lebih besar.
*Maksud dari-infinity(Negatif tak hingga)
count = 0
Menganalisasi variabel count untuk menghitung jumlah bilangan yang dimasukkan.
while True:
Memulai loop tak terbatas. Akan terus berjalan sampai dihentikan oleh break.
num = float(input(f"
Meminta input dari pengguna, mengkonversinnya ke float, dan menyimpannya dalam variabel num.
if num == 0
           break
Jika input adalah 0, keluar dari loop.
count += 1
Menambanh penghitung jumlah bilangan yang dimasukkan
if num > largest:
            largest = num
Jika bilangan baru dimasukkan lebih besar dari largest saat ini, update largest.
return largest, count
Setelah loop selesai, kembalikan bilangan terbesar dari jumlah input.

print("Program untuk menentukan bilangan terbesar dari N bilangan")
print("Masukkan angka 0 untuk mengakhiri input\n")

Mencetak instruksi pengguna.
largest, count = find_largest
Memanggil fungsi find_largest_number() dan menyimpan hasilnya.
if count > 0:
Memeriksa apakah ada bilangan yang dimasukkan.

 print(f"\nJumlah Bilangan yang dimasukkan: count ")
    print(f"Bilangan terbesar adalah:largest ")
Jika ada bilangan yang dimasukkan, cetak jumlah input dan bilangan terbesar.

else:
    print("\nTidak ada bilanngan yang dimasukkan.")
Jika tidak ada bilangan yang dimasukkan (pengguna langsung memasukkan 0), program akan dijalankan dan menampilkan output bilangan.    
