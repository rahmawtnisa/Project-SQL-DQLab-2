# SQL WHERE & CASE WHEN - DQLab Bootcamp Summary

# 1. WHERE Clause
WHERE adalah klausa dalam SQL yang digunakan untuk memfilter data sesuai dengan kondisi tertentu.
Dengan WHERE, kita dapat memilih hanya data yang memenuhi kriteria yang ditentukan dalam query.

Fungsi utama dari WHERE adalah untuk menentukan kondisi yang harus dipenuhi oleh data dalam query. 
Beberapa operator yang sering digunakan dalam klausa WHERE antara lain:

=: untuk membandingkan kesamaan nilai.
>, <, >=, <=, <>: untuk membandingkan nilai lebih besar, lebih kecil, atau tidak sama dengan.
BETWEEN: untuk memilih nilai dalam rentang tertentu.
IN: untuk memilih nilai yang ada dalam daftar yang diberikan.
LIKE: untuk pencarian pola (misalnya menggunakan wildcard).
AND, OR: untuk menggabungkan beberapa kondisi.
IS NULL: untuk memfilter data yang memiliki nilai null.

# 2. CASE WHEN Statement
CASE WHEN adalah pernyataan kondisional dalam SQL yang memungkinkan kita untuk menerapkan logika IF-THEN-ELSE langsung di dalam query.
Dengan CASE WHEN, kita dapat mengubah nilai atau menentukan kategori berdasarkan kondisi tertentu.

CASE WHEN umumnya digunakan dalam SELECT untuk menampilkan hasil yang berbeda berdasarkan evaluasi kondisi. 
Setiap kondisi dievaluasi dalam urutan yang ditentukan, dan jika kondisi terpenuhi, hasil yang sesuai akan ditampilkan.

Kita dapat menggunakan CASE WHEN untuk:

Mengubah nilai kolom berdasarkan kondisi tertentu.
Menambahkan kategori atau label untuk hasil query.
Menggunakan beberapa kondisi bersarang untuk situasi yang lebih kompleks.

Dengan memahami WHERE dan CASE WHEN, Kita dapat melakukan pemfilteran data dan 
menambahkan logika kondisi langsung dalam query SQL, yang memungkinkan analisis data yang lebih fleksibel dan mendalam.
