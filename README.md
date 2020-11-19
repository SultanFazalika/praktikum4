##Praktikum 4


Buat sebuah list dengan sebanyak lima elemen dengan nilai bebas

Akses list :
- Menampilkan elemen ketiga
- Ambil elemen kedua sampai ke-empat
- Ambil elemen terakhir

Ubah elemen list :
- Ubah elemen ke 4 dengan nilai lainnya 
- Ubah elemen 4 sampai dengan elemen terakhir

Tambah elemen list :
- Ambil 2 bagian dari list pertama (A) dan jadikan list ke 2 (B)
- Tambah list B dengan nilai string
- Tambah list B dengan 3 nilai
- Gabungkan list B dengan list A


#Penjelasan

Membuat list :
  
  a = [10, 20, 30, 40, 50]
  
  print(a[2])
  print(a[1:4])
  print(a[4])
  
Mengubah elemen list : 
  
  a[3] = 200
  a[3:4] = [200, 300]
  
Menambah elemen list:
  
  a = [30, 40, 50]
  b = [10, 20]
  
  b.append(10)
  b.extend([60, 90, 70])
  
  c = a + b
  print(b[0:3])
  
