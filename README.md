# Basda_Laporan3
# Tabel Erd
![ered](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/0aff8994-a81b-4710-9c59-7257c1e5e67b)
Pembahasan :
Pada gambar diatas merupakan tabel erd sistem transaksi bank yang memiliki beberapa entitas yaitu transaksi,nasabah,menyetor,teller,dan direktur.

# Nasabah
![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/619e2237-e704-4f45-b674-7165198ef606)




Pembahasan :
Gambar diatas merupakan tabel nasabah. pada tabel tersebut yang menjadi primary key adalah id_nasabah, pada tabel tersebut digunakan sebagai entitas dari nasabah yang berisi KTP,jenis_kelamin,alamat_nasabah,no_hp,dan nama_nasabah.nasabah nantinya akan menyetor sejumlah uang ke teller untuk dimasukkan ke dalam tabungan maupun transfer lalu menggunakan primary key yaitu no_rek.

![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/cb92d706-2d90-4d3c-bed9-121649715ada)

Pembahasan :
Pada gambar diatas merupakan data dari pengguna atau nasabah yang telah dimasukkan.

# Teller 
![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/e3434da3-da99-49e2-a35c-ec210702fe95)
Pembahasan :
Pada gambar diatas merupakan database dari teller dengan primary yaitu id_teller lalu pada teller memiliki relasi dengan direktur dengan menggunakan relasi one to many disini teller mengambil data dari direktur yang dijadikan sebagai foreign key yaitu id_direktur relasi ini digunakan sebagai laporan dari teller kepada direktur.

![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/4006d3a9-6c7c-4f28-80bd-059e7e7521b3)


Pembahasan :
Pada gambar diatas merupakan data teller yang telah dimasukkan kedalam tabel teller.

# Menyetor
![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/bad11fe3-3089-4f1d-8516-d70565ada8f3)

Pembahasan :
Pada gambar ini yaitu gambar tabel baru yang tercipta dari relasi antara many to many dari entitas nasabah maupun teller pada tabel menyetor membuat primary yaitu id_setoran lalu mengambil data dari teller maupun nasabah sebagai foreign key pada menyetor data yang menjadi foreigkey tersebut adalah id_teller dan no_rek.

![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/2c420be1-a13d-4889-b127-fef629bc89f5)


Pembahasan :
Pada gambar diatas merupakan data dari nominal yang ingin dimasukkan pengguna untuk menyetor uang.

# Transaksi :
![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/66080f47-5c31-4f3f-b0bf-86af280166f4)


Pembahasan :
Pada gambar diatas merupakan database transaksi/tabungan yang digunakan untuk memasukkan uang ataupun mengambil uang pada tabel ini menggunakan primary key yaitu no_rek lalu mengambil data dari menyetor sebagai foreign key yang digunakan untuk proses penyetoran uang foriegn key tersebut yaitu id_setoran.

![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/908afd9d-409f-46ea-99f3-86331600b2b3)


Pembahasan :
Gambar diatas merupakan data dari tabungan nasabah tersebut.

# Direktur
![2direktur]
![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/5c701569-cbef-45d8-b2a4-5ca42f64b803)
Pembahasan :
Pada Gambar diatas merupakan database dari direktur disini direktur menggunakan primary key yaitu id_direktur,direktur tidak mengambil foreign key sebab pada direktur hanya menggunakan relasi one to many ke teller yang tahapannya yaitu teller melapor kepada direktur.

![image](https://github.com/kevnrnldi/Basda_Laporan3/assets/131644812/530cbd30-bb6b-4b2d-8cba-7c2eb373d563)
Pembahasan :
Pada gambar tersebut merupakan data dari direktur bank.
