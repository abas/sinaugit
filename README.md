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

### Penambahan Track-File 

```
	$ git add %name_file
```
> berfungsi untuk memnambahkan file untuk __dipantau__, misalkan kita memiliki file __.gaje__ dalam keadaan default file tersebut sudah terpantau, namun jika kita memnambahkan file baru misalkan __.gaje2__ untuk bisa melihat perubahan pada __.gaje2__ kita perlu manmbahkan daftar pantau dengan comment

```
	$ git add .gaje2
```
maka file __.gaje2__ akan automatis terTrack jika ada perubahan
