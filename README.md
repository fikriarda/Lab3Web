# Lab3Web
Tugas 3 membuat order list, unorder list, tabel dan form
###################################################################################################################################################################################
################################################################################ Membuat List######################################################################################
###################################################################################################################################################################################
Pertama-tama kita harus membuat file dengan ekstensi html. Pada percobaan kali ini saya membuat file dengan nama lab3_list.html
Untuk membuat order list kita bisa menggunakan tag <#ol> yang didalamnya ditambahkan tag <#li>. tag <#li> sendiri berfungsi untuk membuat list
 #screeenshot 1
 ![1 membuatlist](https://user-images.githubusercontent.com/59334580/115114836-7a085800-9fbb-11eb-9fe4-64baf75e97e2.png)
selanjutnya, kita akan membuat tag <#ul> untuk unorder list yang didalamnya ditambahkan tag <#li>. seperti yang ada di screenshot 1.
Setelah itu kita membuat Description list dengan menggunakan tag <#dl> yang didalamnya ada tag <#dt> dan tag <#dd>. <#dl> kepanjangan dari Definition List yang artinya daftar definisi.

elemen <#dl> harus digunakan ketika ingin memasukan definisi istilah dalam dokumen, sering digunakan dalam glosarium untuk mendefinisikan banyak istilah dan juga digunakan dalam dokumen ketika penulis ingin menjelaskan suatu istilah lebih detail.

<#dt> kepanjangan dari Definition Term yang artinya istilah definisi.

elemen <#dt> digunakan ketika ingin memberikan nama dalam daftar definisi, elemen ini mengandung data satu baris

<#dd> kepanjangan dari Definition Description yang artinya definisi deskripsi.

elemen <dd> berisi data yang menjelaskan istilah definisi, Data ini dapat berupa satu baris atau bisa lebih dari satu baris.

untuk lebih mudah memahaminya tag dl terdiri dari kelompok nama dan nilai, nama diberikan dalam elemen dt dan nilai diberikan dalam elemen dd.
#################################################################################################################################################################################
################################################################################ Membuat Tabel###################################################################################
#################################################################################################################################################################################

#Screenshot 2
![2 membuattable](https://user-images.githubusercontent.com/59334580/115115113-c56f3600-9fbc-11eb-8af3-a2bd8e41f4c1.png)
Pertama-tama kita harus membuat file dengan ekstensi html disini saya memberi nama file lab3_tabel
untuk membuat tabel kita membutuhkan tag <#table> <#thead> <#tbody> <#tr> <#th> dan <#td>
Tag <#table> untuk membungkus tabelnya
Tag <#thead> untuk membungkus bagian kepala tabel
Tag <#tbody> untuk membungkus bagian body dari tabel
Tag <#tr> (tabel row) untuk membuat baris
Tag <#td> (table data) untuk membuat sel
Tag <#th> (table head) untuk membuat judul pada header
Tag yang paling penting untuk diingat adalah tag <table>, <tr>, dan <td>. Sementara tag yang lain adalah tambahan (opsional), boleh digunakan boleh tidak.
 
 #################################################################################################################################################################################
################################################################################ Membuat Form####################################################################################
#################################################################################################################################################################################

#Screenshot 3
![3 membuatform](https://user-images.githubusercontent.com/59334580/115115284-cce30f00-9fbd-11eb-9a6b-158ad0cec484.png)
Form di HTML dapat kita buat dengan tag <#form>.

Tag ini memiliki beberapa atribut yang harus diberikan, seperti:

action untuk menentukan akasi yang akan dilakukan saat data dikirim.
method metode pengiriman data.
Untuk atribut action, kita dapat mengisinya dengan alaman URL dari endpoint yang akan memproses form.

Secara sederhana,pada contoh di atas kita akan menyuruh file prosess.php untuk memproses data form.

Ini nanti akan kita pelajari pada PHP.
Dalam screenshot 3 kita juga memerlukan tag <#legend> dan <#fieldset>
Tag fieldset adalah tag yang ada pada html yang memiliki fungsi untuk membungkus elemen – elemen input yang memilik kategori yang sama.

Tag legend adalah sebuah tag yang berfungsi untuk memberi atau menjadi caption dari tag fieldset.
