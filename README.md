    NAMA     : Christian Amsal Asimaro Lumban Tobing
    NIM      : 2409116053
# PostTest3PBO

# A. DESKRIPSI SINGKAT
Hasil Pengerjaan PostTest dengan Tema _**"Manajemen Daftar Komik Online"**_ merupakan sebuah Aplikasi Manajemen Komik berbasis Teks dengan membuat 3 Package untuk menjalankan programnya yaitu :
1. Package Model {_'SuperClass.java', 'ManhwaData.java' & 'ManhuaData.java'_} (Sebagai tempat atribut dan constructor)
2. Package Service {_'InteractManhwa/Manhua.java'_} (CRUD: tambah, tampil, update, hapus & tambahan fitur Search)
menerapkan konsep CRUD (Create, Read, Update, Delete) yang dimana memungkinkan pengguna untuk :
- Menambah Data Manhwa
- Melihat Daftar Manhwa
- Mengubah Data Manhwa
- Menghapus Data Manhwa.
3. Package Main {_'Main.java'_} (Sebagai Menu Utama Program)

# B. DESKRIPSI CLASS
1. SuperClass (Superclass)
  - untuk menyimpan atribut umum seperti title (judul), author, status.
  - Menerapkan Encapsulation (getter & setter).
  - Membuat Method showInfoManhwa/Manhua() untuk menampilkan informasi umum publikasi.
2. ManhwaData (Subclass dari SuperClass)
  - Tambahan atribut Seperti chapter, genre.
  - Override method showInfoManhwa/Manhua() untuk menampilkan detail lebih lengkap.
3. ManhuaData (Subclass dari SuperClass)
  - Struktur sama seperti ManhwaData, tapi digunakan untuk komik Manhua.
4. InteractManhwa/Manhua (Service)
  - Menyediakan fitur CRUD:
      - Add Untuk menambah data manhwa baru.
      - Show untuk menampilkan seluruh daftar manhwa.
      - Update untuk mengubah data berdasarkan nomor manhwa.
      - Delete untuk menghapus data dari daftar.
      - Search untuk mencari manhwa berdasarkan judul.
  - Menggunakan ArrayList untuk menyimpan data.
5. Main (Program Utama)
  - Menyediakan menu interaktif.
  - Memanggil service CRUD dari InteractManhwa/Manhua.
  - Menambahkan Tampilkan data ManhuaData.

# ALUR PROGRAM
1. User menjalankan File Main.java.
2. Menu ditampilkan:
   - Tambah Manhwa
   - tampilkan List Manhwa
   - update Manhwa
   - hapus Manhwa
   - cari manhwa.
   - Lihat data Manhua yang ada.
3. Program berjalan secara berulang, sampai user memilih keluar.

# PENJELASAN ENCAPSULATION, INHERITANCE DAN OVERRIDING
## ENCAPSULATION
Menggunakan Encapsulation dengan mengatur semua atribut bersifat Private, yang dimana akses data hanya bisa dilakukan dengan Getter & Setter.
## INHERITANCE
Membuat file java baru (SuperClass) untuk mengaturnya menjadi file Superclass yang dimana file ManhwaData.java dan ManhuaData.java menjadi subclass yang mewarisi atribut dan method dari superclass (SuperClass.java).
## OVERRIDING
Membuat method showInfoManhwa/Manhua di SuperClass.java dioverride oleh ManhwaData.java dan ManhuaData.java agar dapat menampilkan info tambahan dari SuperClass.java

# OUTPUT

<img width="264" height="515" alt="image" src="https://github.com/user-attachments/assets/28b72345-0c4f-4dd9-9048-6413fbc0ae31" />

Menampilkan List Manhwa

<img width="398" height="243" alt="image" src="https://github.com/user-attachments/assets/9181c1e3-cddf-428e-a70b-b6ca427b5909" />

Menampilkan List Manhua
