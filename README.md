# TUTORIAL GIT for AWAK DEWE

### Instalasi Git

```
	$ git init
```
> <span style="color:red">git init</span> adalah perintah untuk **_menginisialisasi_** direktori atau folder
> misalkan kita mempunyai folder bernama **_project_** kemudian ingin menginisialisasi
> git kedalamnya maka kita perlu masuk dulu ke dalam foldernya
```
	$ cd project
	$ git init
```
dengan begitu kita sudah menginisialisasi folder **_project_** untuk menggunakan **_.git_**



### Mendownload Project ke Local

```
	$ git clone %url
```
> __*git clone*__, seperti nama nya berfungsi untuk mengclone sebuah project ke local
> atau bahasa awamnya mendownlaod repositori / project keLocal

example :
```
	$ git clone https://github.com/ahmadbasir/sinaugit.git
```

### Cek-Updated file
```
	$ git status
```
> ketika kita melakukan perubahan pada sebuah file, atau ingin mengetahui fila apasaja yang telah kita rubah, maka __$ git status__ adalah perintah untuk melakukannya

misalkan kita memiliki file __.ubah1__ dengan isi sebagai berikut :
```
! ini isi 1
```
kemudia kalian merubah menjadi :
```
! menjadi isi 2
```
jika kalian melakukan ```$ git status``` maka akan muncul informasi ```modified : .ubah1``` dengan tulisan warna merah

### Penambahan Track-File

```
	$ git add %name_file
```
> berfungsi untuk memnambahkan file untuk __dipantau__, misalkan kita memiliki file __.gaje__ dalam keadaan default file tersebut sudah terpantau, namun jika kita memnambahkan file baru misalkan __.gaje2__ untuk bisa melihat perubahan pada __.gaje2__ kita perlu manmbahkan daftar pantau dengan comment

```
	$ git add .gaje2
```
maka file __.gaje2__ akan automatis terTrack jika ada perubahan

> menyangkut dari perintah ``` $ git status``` yang tulisan ```**modified : %file-name**``` seletah di ```$ git add ..``` maka tulisan akan berubah menjadi hijau yang artinya file tersebut sudah ditambahkan.


### Commit message .updating repositori
```
	$ git commit -m 'ini pesan'
```
> ```$ git commit``` merupakan perintah untuk mengirim notifikasi sekaligus memferifikasi apa yang berubah pada repositori

__perlu dicatat__ setiap perubahan pada repositori yang ingin di __push__ harus melakukan ```git commit``` terlbih dahulu. karena git commit disini memberitahukan apa saja yang telah berubah. jadi ketika kita sedang mengerjakan sebuah proyek bersama kita tahu dimana kita mengubah file ataupun membuat direktori baru.
