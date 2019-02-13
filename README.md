# Labpy1


Algoritma menentukan nilai terbeasar dari 3 buah bilangan.
Diketahui 3 buah bilangan Bil1, Bil2, Bil3 akan dicari nilai terbesar.
1.Mulai

2.Inisiasi Bil1, Bil2, Bil3 sebagai Integer

3.Baca Bil1

4.Baca Bil2

5.Baca Bil3

6.Jika Bil1 > Bil2 dan Bil1 > Bil3 maka kerjakan langkah nomor 8, selain itu.

7.Jika Bil2 > Bil1 dan Bil2 > Bil3 maka kerjakan langkah nomor 9, selain itu kerjakan langkah nomor 10

8.Cetak "Bilangan terbesar bilangan pertama"
![bilangan pertama 1](https://user-images.githubusercontent.com/46749088/52723884-e6a0fa00-2fe0-11e9-827a-84a756a51a09.png)
9.Cetak "Bilangan terbesar bilangan kedua"
![bilangan kedua2](https://user-images.githubusercontent.com/46749088/52723907-f28cbc00-2fe0-11e9-8459-401ccfa9fab3.png)

10.Cetak "Bilangan terbesar bilangan ketiga"
![bilangan ketiga](https://user-images.githubusercontent.com/46749088/52723921-fb7d8d80-2fe0-11e9-99d8-85001868a687.png)


Selesai

Berikut dibawah ini Flowchart dari program tersebut
flowchart-1

![52652029-e5f45f00-2f1f-11e9-9b94-a1f268311b74](https://user-images.githubusercontent.com/46749088/52723814-ca9d5880-2fe0-11e9-904f-30207f7da012.jpg)

Gunakan statement if untuk A sebagai inisiasi Bilangan Pertama.
Gunakan statement elif untuk B sebagai inisiasi Bilangan Kedua.
Gunakan statement else untuk C sebagai inisiasi Bilangan Ketiga.
Kemudian Run
Silahkan lihat contoh di bawah ini :
print ("Program mencari bilangan terbesar dari 3 bilangan\n")

A = int(input("Masukkan Bilangan Pertama: "))

B = int(input("Masukkan Bilangan Kedua: "))

C = int(input("Masukkan Bilangan Ketiga: "))

if A > B > C :

print("\nBilangan Pertama adalah Bilangan Terbesar = %s" % A)
elif B > C :

print("\nBilangan Kedua adalah  Bilangan Terbesar = %s" % B)  
else:

print("\nBilangan Ketiga adalah Bilangan Terbesar = %s" % C)
Berikut hasil screenshot dari program tersebut :
Bilangan Pertama yang menjadi bilangan terbesar.if

Bilangan Kedua yang menjadi bilangan terbesar.elif

Bilangan Ketiga sebagai bilangan terbesar.else