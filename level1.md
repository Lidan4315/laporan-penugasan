# Laporan Penugasan 1

## No 1

![Github](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-1.png)

Langkah pertama yang saya lalukan adalah masuk ke github dan membuat repository baru.

</br>

![Membuat Repo](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-2.png)

Sesuai dengan soal yang diberikan, saya memberi nama **ajk-lidan-penugasan18** sebagai nama repository yang akan saya buat.

</br>

![Repo kosong](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-3.png)

Disini saya membuat repository yang kosong terlebih dahulu(tanpa README.md) agar tidak ada branch main yang terbuat dan saya dapat menamai main branch saya sesuai dengan nama yang diperintahkan pada nomor 2.

</br>

![file lokal repo](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-4.png)

selanjutnya saya membuat file dengan nama yang sama seperti repository yang sudah saya buat.

</br>

![inisialisai](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-5.png)

Masuk ke dalam VSC dan saya melakukan _git init_ untuk melakukan inisialisasi file tersebut sebagai lokal reposistory.

</br>

![remote repo](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-6.png)

Setelah melakukan inisialisasi saya membuat file `README.md` lalu melakukan remote repository menggunakan _git remote add origin <url repo>_ untuk menghubungkan lokal repository saya dengan remote repository yang ada di github. Selanjutnya, saya ingin menambahkan file `README.md` tersebut ke remote repository saya dengan menggunakan _git add README.md_ dan melakukan commit dengan _git commit -m "initial commit"_. Sebelum saya melakukan push disini saya membuat branch dulu yang bernama **master** sebagai branch main saya dan barulah saya melakukan push dengan _git push -u origin master_ untuk menambahkan perubahan yang terjadi di lokal repo saya ke remote repo di branch **master**.

</br>

![Laporan Level](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-7.png)

Disini saya menambahkan file `level-1.md`, `level-2.md`, `level-3.md`, dan `level-4,md`. Lalu seperti file `README.md` sebelumnya saya melakukan _add_, _commit_, dan _push_ kedalam branch **master**.

</br>

![CodeBase](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-8.png)

Selanjutnya saya menambahkan folder src didalamnya saya tambahkan file `index.html` dan sebuah gambar, lalu _add_, _commit_, dan _push_ kedalam branch **master**.

</br>

![Repo Now](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/1-9.png)

Dan ini adalah tampilan Repository github saya setelah ditambahkan file-file dari lokal repository dan sudah sesuai dengan struktur repo yang diminta pada nomor 1.

</br>

## NO 2

![Add Branch](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/2-1.png)

Untuk menyelesaikan no 2 saya membuat 3 branch baru yaitu **development**, **featureA**, dan **featureB**. Untuk branch **master** sudah saya buat di awal-awal sebagai main branch. Disini saya menggunakan perintah _git branch nama-branch_ dan untuk melihat branch apa saja yang saya miliki menggunakan perintah _git branch_ dan nama branch yang ditandai `*` adalah branch tempat kita berada atau dapat juga dilihat jika kita menggunakan git bash atau extendsion git graph.

</br>

## NO 3

![Add Bootstarp](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-1.png)

Pertama-tama saya pindah ke branch **developmnet** menggunakan perintah _git checkout development_. Setelah itu saya menambahkan bootstrap pada `index.html` dan saya commit dengan _git commit -am "feat: add bootstarp"_.

> disini saya memang langsung melakukan _commit_ saja tetapi, meggunakan `-am` yang otomatis sudah melakukan _add_. Ini saya gunakan untuk perubahan dalam suatu file saja tanpa menambahkan file lain.

</br>

![git stash](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-4.png)

> text yang berwarna hijau itu adalah perubahan yang saya lakukan

Untuk melihat perubahan yang sudah saya buat di branch **development** terhadap branch **master** disini saya menggunakan perintah _git diff master_ saat berada di branch **development**, lalu setelah yakin saya melakukan push ke remote repository menggunakan perintah _git push -u origin development_ (tidak terlihat digambar).

</br>

Selanjutnya saya berpindah ke branch **featureA** untuk mengerjakan fitur-fitur yang akan saya tambahkan.

</br>

![featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-5.png)

Namun seperti yang terlihat pada git graph diatas isi dari branch **featureA** masih sama dengan isi dari branch **master**(belum ada bootstrap).

</br>

![git pull origin](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-6.png)

> note: `style.css` disitu bukanlah hasil dari _pull origin developmnet_, itu disebabkan karena saya sudah menambahkan file `style.css` baru lah saya ss.

Maka, saya menggunakan _git pull origin development_ untuk mengambil semua perubahan pada branch **development** yang ada di remote repository. Bisa kita lihat di `index.html` bahwa sudah ada bootstarp disana.

</br>

![commit featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-7.png)

Di branch **featureA** saya menambahkan file `style.css` lalu melakukan _add_, _commit_, dan _push_ yang dapat dilihat di terminal pada gambar.

</br>

![cange featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-8.png)

Ini adalah perubahan yang saya lakukan di `index.html` pada branch **featureA**.

</br>

![all commit featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-9.png)

Untuk setiap setiap perubahan yang saya lakukan saya berikan _commit_ masing-masing, lalu saya push sekaligus ke remote repository branch **featureA**.

</br>

![featureB](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-10.png)

Disini saya berpindah lagi ke branch **fetureB**, lalu agar bisa melanjut fitur-fitur yang mau saya tambahkan saya melakukan _pull origin featureA_. Jadi disini branch **featureB** isinya sudah sama dengan branch **featureB**.

</br>

![change style.css](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-11.png)

Di branch **featureB** ini saya menambahkan fitur-fitur di `syle.css`, lalu setiap perubahan atau penambahan yang saya lakukan saya berikan _commit_ masing-masing.

</br>

![git graph now](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-12.png)

ini adalah kondisi graph terkini saya

</br>

![git reset](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-13.png)

Disini saya sadar bahwa ada yang salah dengan _commit_ terakhir saya. Maka, agar tidak melakukan _commit_ saya disini saya menghapus _commit_ terakhir saya menggunakan perintah _git reset HEAD~_.

</br>

![git graph now2](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-14.png)

Dapat dilihat pada git graph bahwa _commit_ terakhir saya sudah tidak ada dan kembali ke _commit_ sebelumnya.

</br>

![font weight](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-15.png)

Saya memperbaiki kesalahan ukuran font-wightnya yang harusnya 500 sebelumnya 400, lalu saya _commit_ ulang.

</br>

![continue featureB](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-16.png)

lalu saya melanjutkan untuk menambahkan fitur-fitur pada `style.css` dengan setiap perubahan atau penambahannya di _commit_ masing-masing seperti pada gambar.

</br>

![back to featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-17.png)

Disini saya sudah kembali ke branch **featureA** menggunakan _git checkout featureA_

</br>

![git merge](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-18.png)

Selanjutnya, untuk mengambil perubahan yang sudah saya lakukan di **featureB** saya melakukan merge dengan perintah _git merge --no-ff featureB_.

> Kenapa tidak menggunakan _git pull origin_ saja? itu karena pada branch _featureB_ perubahan yang ada belum saya push ke remote reposutory jadi jika di _git pull origin_ tidak akan terjadi apa-apa karena remote repository **featureB** masih kosong.

</br>

![git graph now3](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-19.png)

Ini adalah kondisi graph setelah dilakukan merge.

</br>

![back to development](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-20.png)

Karena semua fitur saya rasa sudah selesai maka saya kembali ke branch **development** untuk melakukan merge.

</br>

![merge featureA](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-21.png)

Maka saya lakukan merge antara branch **development** dan branch **featureA** menggunkan _git merge --no-ff featureA_.

</br>

![git graph now4](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-22.png)

Ini adalah kondisi graph setelah dilakukan merge.

</br>

![change color](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-23.png)

Setelah saya lihat hasil webnya rasanya wana hitam pada text "welcome back!" terlihat jelek, jadi saya kembali ke branch **featureB** dan mengganti warna menjadi putih. Tetapi saya belum melakukan _commit_.

</br>

![git stash](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-24.png)

Karena saya ingin melihat keadaan branch lain terlebih dahulu maka, untuk berpindah branch tanpa melakukan _commit_ pada perubahan yang ada saya menggunkan _git stash_ dimana perubahan tersebut akan tersimpan sementara di stash.

</br>

![featureA again](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-25.png)

Lalu saya berpindah ke branch **featureA** dengan perintah _git checkout featureA_ seperti biasa. Saya sudah pastikan tidak ada perubahan di **featureA** dimana warna "Welcome back!" masi hitam.

</br>

![back to featureB](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-26.png)

Kemudian saya kembali ke branch **featureB** dan terlihat bahwa tidak ada perubahan yang saya kerjakan sebelumnya.

</br>

![git graph now5](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-27.png)

ini adalah kondisi graph setelah melakukan _git stash_.

</br>

![stash apply](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-28.png)

Untuk mengambil kembali perubahan yang tersimpan sementara di stash maka, saya menggunakan perintah _git stash apply_ dan terlihat bahwa warna `h3` yang sebelumya hitam sudah menjadi putih. Selanjutnya perubahan tersebut saya _commit_.

</br>

![push featureB](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-29.png)

Lalu saya mengepush semua _commit_ ke remote repository branch **featureB**.

</br>

![development again](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-30.png)

Disini saya kembali lagi ke branch **development** untuk mengambil perubahan pada branch **featureB**.

</br>

![merge featureB](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/3-31.png)

Seperti biasa saya melakukan merge dengan _git merge --no-ff nama-branch_ dan bisa dilihat bahwa warna `h3` nya sudah berubah.

</br>

## NO 4

Setelah melihat-lihat hasil dari web saya saya memutuskan untuk menambahkan shadow pada tulisan "Welcome back!".

</br>

![text shadow](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/4-1.png)

Saya memutuskan untuk mengerjakan pada branch **featureA** dan menambahkan _text-shadow_ pada `h3`, kemudian penambahan tersebut saya _commit_.

</br>

![conflict](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/4-2.png)

Setelah itu saya kembali ke branch **development** lalu melakukan merge dengan branch **featureA** untuk mengambil penambahan _text-shadow_. Disinilah terjadi conflict seperti yang digambar dimana saya lupa bahwa warna `h3` sudah berubah menjadi putih di branch **development** hasil dari merge dengan branch **featureB** sebelumnya. Untuk menangani conflict ini saya memilih **Accept Incoming Change** dimana dia akan mengambil perubahan pada merge terakhir(featureA).

</br>

![solve conflict](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/4-3.png)

Hasilnya adalah `h3` dengan color hitam dan penambahan _text-shadow_ karena, saya berpikir bahwa warna masi bisa diganti lagi di branch **development** sebelum di merge ke branch **master**.

</br>

## NO 5

![Back to master](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/5-1.png)

Kembali ke branch **master** yang isinya masih benar-benar sama dengan diawal belum ada perubahan atau penambahan. Karena, web yang saya kerjakan sudah selesai(di branch development) maka, saya harus merge ke branch **master**.

</br>

![merge no ff](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/5-2.png)

Disini saya menggunakan _git merge --no-ff development_ untuk menggabungkan branch **master** dengan branch **development** dan hasilnya semua yang saya kerjakan tadi sudah ada di branch **master**.

</br>

![forgot color](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/5-3.png)

Setelah saya melihat-lihat lagi hasilnya, ternyata di `style.css` warna dari `h3` belum diganti menjadi putih saat di branch **developmnet**. Jadi, saya memutuskan untuk merubahnya langsung di master dan melakukan _commit_ lalu _push_ ke remote repository di github.

</br>

## Kondisi akhir

- **Git Graph**

  ![git graph end](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/5-4.png)

- **Github**

  ![github end](https://github.com/Lidan4315/laporan-penugasan/blob/main/img/5-5.png)
