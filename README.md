# pytthagoras
postest ddp nim ganjil
#POSTEST DDP 1

#data diri
print("Masukkan data diri pengguna")
input('Masukkan nama = ')
input('Masukkan NIM = ')

print("Kode (SISFOR23)")
kode = input('Masukkan kode = ')

if kode == 'SISFOR23': 
    print("WELCOME TO PYTHAGORAS")

else:
    print("Kode salah, tapi gapapa aku maafin, NEXT")

#pythagoras
from math import sqrt
print("Sisi-sisi segitiga adalah a,b,c dengan c sebagai sisi miring")
rumus = input('Sisi manakah yang ingin kamu ketahui? = ')

if rumus == 'c':
    sisiA = int(input('Masukan panjang sisi a = '))
    sisiB = int(input('Masukan panjang sisi b = '))

    sisiC = sqrt(sisiA*sisiA + sisiB*sisiB)
    print('Panjang sisi c adalah', sisiC)

elif rumus == 'a':
    sisiC = int(input('Masukan panjang sisi c = '))
    sisiB = int(input('Masukan panjang sisi b = '))

    sisiA = sqrt(sisiC*sisiC - sisiB*sisiB)
    print('Panjang sisi a adalah', sisiA)

elif rumus == 'b':
    sisiC = int(input('Masukan panjang sisi c = '))
    sisiA = int(input('Masukan panjang sisi a = '))

    sisiB = sqrt(sisiC*sisiC - sisiA*sisiA)
    print('Panjang sisi b adalah', sisiB)

else:
    print('Input salah')

# flowchart
![image](https://github.com/anitares/pytthagoras/assets/144813869/4184feed-5539-4241-b9fc-fa7900aed95d)


# output
![image](https://github.com/anitares/pytthagoras/assets/144813869/e2b772f0-969e-46cc-baa3-099ff756f5a8)

jadi,output disini saya buat menggunakan login sederhana
yang pertama pengguna harus masukkan nama, nim, dan kode yang tertera
kemudian masukkan sisi yang akan dihitung, di output tertera saya memilih sisi a untuk dihitung
setelah itu masukkan sisi yang diketahui, di output tertera saya menuliskan sisi c = 15 dan b = 8
dan kemudian program saya akan menghitung menggunakan rumus yang telah diprogram untuk sisi a yaitu (sisiC*sisiC - sisib*sisiB)
selanjutnya program saya akan menampilkan hasil yang valid dari hasil perhitungan menggunakan rumus, di output tertera hasil dari sisi a (15*15 - 8*8) = 12
