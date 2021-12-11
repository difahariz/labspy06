# labspy06
## Latihan 1
- Ubahlah kode dibawah ini menjadi fungsi menggunakan *lambda*

```
import math
def a(x):
    return x**2

def b(x, y)
    return math.sqrt(x**2 + y**2)  

def c(*args):
    return sum(args)/len(args)

def d(s):
    return "".join(set(s))
```

### Input

![IMG 1](screenshot/1.png)

### Output

![IMG 2](screenshot/2.png)

## Tugas Praktikum
> Buat program sederhana dengan mengaplikasikan penggunaan fungsi yang akan menampilkan daftar nilai mahasiswa, dengan ketentuan:
> - Fungsi *tambah()* untuk menambah data
> - Fungsi *tampilkan()* untuk menampilkan data
> - Fungsi *hapus(nama)* untuk menghapus data berdasarkan nama
> - Fungsi *ubah(nama)* untuk mengubah data berdasarkan nama
> - Buatlah flowchart dan penjelasan programnya pada README.md

### Penjelasan
- Buatlah dictionary yang akan diinput dengan data
```
data = {}
```

- Membuat perulangan dan keterangan untuk pilihan menu
```
while True:
    c = input("\n(L)ihat, (T)ambah, (U)bah), (H)apus, (C)ari, (K)eluar: ")
```

- Menambahkan data yang akan diinput kemudian masuk ke dalam dictionary

![IMG 3](screenhot/3.png)

Output Menambahkan Data

![IMG 4](screenshot/4.png)

- Jika ingin menampilkan data dapat menggunakan

![IMG 5](screenshot/5.png)

Output menampilkan data

![IMG 6](screenshot/6.png)

- Mengubah data dapat menggunakan

![IMG 7](screenshot/7.png)

Output mengubah data

![IMG 8](screenshot/8.png)

- Menghapus data dapat menggunakan

![IMG 9](screenshot/9.png)

Output menghapus data

![IMG 10](screenshot/10.png)

- Mencari data dapat menggunakan

![IMG 11](screenshot/11.png)

Output mencari data

![IMG 12](screenshot/12.png)

- Jika sudah selesai input pilih menu 'K' untuk memberhentikan program
```
elif c. lower() == 'k':
        break
```

#### Flowchart

![IMG 13](flowchart.png) 