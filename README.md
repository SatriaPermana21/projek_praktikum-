# Tugas pertemuan ke 6
## Operator pada python
***
## Profil
__Nama : Muhammad Safri Satria Permana__

__NIM : 312010337__

__Kelas : TI.20.A.2__

## Daftar Isi
| No | ISI | Link |
| -- | --- | ---- |
| 1. | Pertemuan ke 6 - Lab 1 | [lihat](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/README.md#pertemuan-ke-6---lab-1) |
| 2. | Pertemuan ke 6 - Lab 1 bagian 2 | [lihat](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/README.md#pertemuan-ke-6---lab-1-bagian-2) |
| 3. | Pertemuan ke 6 - Lab 2 | [lihat](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/README.md#pertemuan-ke-6---lab-2) |

### Pertemuan ke 6 - Lab 1
Pada pertemuan kali ini saya di beri tugas oleh Dosen yaitu mempelajari Operator Aritmatika menggunakan bahasa python. Berikut adalah source code yang diberikan dosen kepada saya [source code lab 1](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/tugas6-lab2.py)

![output](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%201.PNG)

#### Penggunaan END
> end `end=''` digunakan untuk memberi karakter diakhir baris dipisah oleh tanda koma (,)

```python
# penggunaan end
print('A', end='')
print('B', end=' ')
print('C', end='\n')
print()
print('X')
print('Y')
print('Z')
```

Penjelasan

* Penggunaan `end` digunakan untuk memberi karakter diakhir baris dipisah oleh tanda koma (,)
```python
# tidak ada
print('A', end='')

# menambah space

print('B', end=' ')

# membuat baris baru dengan \n
print('C', end='\n')
```

* Penggunaan `print()` digunakan untuk membuat baris baru tanpa pemanggilan variable atau yang bukan variable
```python
print()
```

* Jika tanpa `end` maka akan langsung membuat baris baru
```python
print('X')
print('Y')
print('Z')
```
Maka hasilnya akan seperti berikut

![output](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%203.PNG)

#### Penggunaaan Separator
> Separator  `sep=''` adalah syntax yang digunakan untuk memberi pemisah pada baris yang dipisah oleh tanda koma (,)

```python
# penggunaan separtor
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep='+')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
Penjelasan

* Pendeklarasian variable
```python
w, x, y, z = 10, 15, 20, 25
```

* Pemanggilan variable tanpa separator

```python
print(w, x, y, z)
```
* Pemanggilan variable dengan separator
```python
print(w, x, y, z, sep='+')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')
```
Maka hasilnya akan seperti berikut

![output2](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%204.PNG)

### Pertemuan ke 6 - Lab 1 bagian 2

* String Format

> Metode `format ()` memformat nilai yang ditentukan dan memasukkannya ke dalam tempat penampung string (placeholder) yang di tentukan menggunakan tanda kurung kurawal :{}, dan mereturn string yang diformat.

Penggunaan string format yang diberikan Dosen sebagai berikut

```python
# String format 1
print(0, 10 ** 0)
print(1, 10 ** 1)
print(2, 10 ** 2)
print(3, 10 ** 3)
print(4, 10 ** 4)
print(5, 10 ** 5)
print(6, 10 ** 6)
print(7, 10 ** 7)
print(8, 10 ** 8)
print(9, 10 ** 9)
print(10, 10 ** 10)

# String format 2
print('{0:>3}{1:>16})'.format(0, 10 ** 0))
print('{0:>3}{1:>16})'.format(1, 10 ** 1))
print('{0:>3}{1:>16})'.format(2, 10 ** 2))
print('{0:>3}{1:>16})'.format(3, 10 ** 3))
print('{0:>3}{1:>16})'.format(4, 10 ** 4))
print('{0:>3}{1:>16})'.format(5, 10 ** 5))
print('{0:>3}{1:>16})'.format(6, 10 ** 6))
print('{0:>3}{1:>16})'.format(7, 10 ** 7))
print('{0:>3}{1:>16})'.format(8, 10 ** 8))
print('{0:>3}{1:>16})'.format(9, 10 ** 9))
print('{0:>3}{1:>16})'.format(10, 10 ** 10))
```
Berikut adalah source code yang diberikan dosen kepada saya [Source code lab 1 bagian 2](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/tugas6-lab1-bagian-2.py)

Penjelasan

* Pada # String format 1 terdapat 2 outputan tanpa string format yang hanya akan memberikan jarak `1 space` yang dimana yang sebelah kiri menampilkan 0 sampai 10 dan yang sebelah kanan menampilkan operator aritmatika bilangan berpangkat ( ** ) dari 10 pangkat 0 sampai 10 pangkat 10

Maka hasilnya akan sebagai berikut

![output 3](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%206.PNG)

* Pada # String format 2 terdapat 2 outputan menggunakan string format __'{0:>3}{1:>16}.format(a,b)'__. Pada `{0:>3}` menjelaskan bahwa untuk __index ke - 0__ yaitu a dengan tanda __>3__ maka akan rata ke kanan sebanyak 3 karakter, begitupun untuk `{1:>16}` maka untuk __index ke - 1__ yaitu b dengan tanda __>16__ maka akan rata ke kanan sebanyak 16 karakter.

Maka hasilnya akan sebagai berikut

![output 4](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%207.PNG)

* Tidak hanya rata kiri `<` ataupun rata kanan `>`, bisa juga rata tengah menggunakan tanda `^`, seperti gambar di bawah.

![output 5](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%208.PNG)



### Pertemuan ke 6 - Lab 2
Pada lab/latihan 2 ini saya akan menjelaskan tentang Konversi variable. Tugas yang di berikan dosen bisa di akses di [source code lab 2](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/tugas6-lab2.py)

```python
# sebelum di konversi nilainya adalah string
a = input("Masukkan Nilai a = ")
b = input("Masukkan Nilai b = ")
print("Variable a = ", a)
print("Variable b = ", b)
print("Hasil penggabungan {0} & {1} = %s".format(a,b) % (a+b))

# Konversi nilai variable ke dalam integer
a = int(a)
b = int(b)
print("Hasil penjumlahan {0} + {1} = %d".format(a,b) % (a+b))
print("Hasil pembagian {0} / {1} = %d".format(a,b) % (a/b))
```

Maka hasilnya akan sebagai berikut

![output 6](https://github.com/RezaRiyaldi/projek_praktikum/blob/master/gambar/gambar%209.PNG)
