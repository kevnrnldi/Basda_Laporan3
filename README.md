# Basda_Laporan3
# Tabel Erd
![ered](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/0aff8994-a81b-4710-9c59-7257c1e5e67b)
Pembahasan :
Pada gambar diatas merupakan tabel erd sistem transaksi bank yang memiliki beberapa entitas yaitu transaksi,nasabah,menyetor,teller,dan direktur.

# Nasabah
![nasabah](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/c8d89c68-eb79-428a-925d-b3d04f79a3e0)
Pembahasan :
Gambar diatas merupakan tabel nasabah. pada tabel tersebut yang menjadi primary key adalah no_rek, pada tabel tersebut digunakan sebagai entitas dari nasabah yang berisi KTP,jenis_kelamin,alamat_nasabah,no_hp,dan nama_nasabah.nasabah nantinya akan menyetor sejumlah uang ke teller untuk dimasukkan ke dalam tabungan maupun transfer.

![2nasabah](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/94e604b8-74cd-4f54-9a3b-77bfeca3c240)

Pembahasan :
Pada gambar diatas merupakan data dari pengguna atau nasabah yang telah dimasukkan.

# Teller 
![teller](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/230954d6-20a6-409e-9d62-f500a0cc8f31)
Pembahasan :
Pada gambar diatas merupakan database dari teller dengan primary yaitu id_teller lalu pada teller memiliki relasi dengan direktur dengan menggunakan relasi one to many disini teller mengambil data dari direktur yang dijadikan sebagai foreign key yaitu id_direktur relasi ini digunakan sebagai laporan dari teller kepada direktur.

![2teller](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/51f56556-8985-48ad-a5b5-e768ea319a08)

Pembahasan :
Pada gambar diatas merupakan data teller yang telah dimasukkan kedalam tabel teller.

# Menyetor
![menyetor](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/9a6c0851-af42-42cd-8a7d-4ff58b5ff9ea)
Pembahasan :
Pada gambar ini yaitu gambar tabel baru yang tercipta dari relasi antara many to many dari entitas nasabah maupun teller pada tabel menyetor membuat primary yaitu id_setoran lalu mengambil data dari teller maupun nasabah sebagai foreign key pada menyetor data yang menjadi foreigkey tersebut adalah id_teller dan no_rek.

![2menyetor](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/677746e0-0ded-488e-b97e-e1cffcde603a)

Pembahasan :
Pada gambar diatas merupakan data dari nominal yang ingin dimasukkan pengguna untuk menyetor uang.

# Transaksi :
![transaksi](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/0ca3463d-8673-486f-af86-2eeda055bd1b)
Pembahasan :
Pada gambar diatas merupakan database transaksi/tabungan yang digunakan untuk memasukkan uang ataupun mengambil uang pada tabel ini menggunakan primary key yaitu kode_transaksi lalu mengambil data dari menyetor sebagai foreign key yang digunakan untuk proses penyetoran uang foriegn key tersebut yaitu id_setoran.

![2transaksi](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/07dba141-4966-44de-8c25-9b5d6c8f621c)

Pembahasan :
Gambar diatas merupakan data dari tabungan nasabah tersebut.

# Direktur
![2direktur](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/c3c4862d-06dd-489d-8ddd-65cc439c56e5)
Pembahasan :
Pada Gambar diatas merupakan database dari direktur disini direktur menggunakan primary key yaitu id_direktur,direktur tidak mengambil foreign key sebab pada direktur hanya menggunakan relasi one to many ke teller yang tahapannya yaitu teller melapor kepada direktur.

![direktur](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/87938f22-2643-4da4-808d-e7e0ccfeb7b3)
Pembahasan :
Pada gambar tersebut merupakan data dari direktur bank.
