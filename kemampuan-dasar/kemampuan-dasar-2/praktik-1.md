<center> <h1><strong>Belajar Cara Berkolaborasi di Github</strong></h1> </center> 
<p>Saya akan memberikan cara untuk berkolaborasi dalam sebuah proyek menggunakan GitHub. ikuti langkah-lngkah dibawah ini:</p>
<br />
<h2><strong>Langkah 1: Membuat repositori baru</strong></h2>
<p>Buka Github dan klik tombol '+' di pojok kanan ats dan pilih 'New Repository'.</p>
<img src= "img/Screenshot (82).png" style="width:86%"/>

<br /><p>Kemudian isi kolom Repository name dan Description. Tetap publik, dan jangan "Inisialisasi repositori ini dengan README". Jangan mengubah apa pun. Klik "Buat repositori" seperti gambar dibawah ini.</p>
<img src= "img/Screenshot (83).png" style="width:86%"/>

<br /><p>Selanjutnya Anda akan melihat halaman github. Ini adalah instruksi untuk menghubungkan Repo yang baru saja Anda buat di Github ke direktori yang Anda buat di folder komputer dan masukkan intruksi tersebut kedalam terminal git yang ada pada komputer anda, seperti gambar dibawah ini.</p>
<img src= "img/Screenshot (84).png" style="width:86%"/>

<br /><p>Di repo lokal anda akan mendapatkan folder '.git'.</p>
<img src= "img/Screenshot (86).png" style="width:86%"/>

<br /><p>Dan jika Anda pergi ke halaman Repo Github Anda, Anda akan melihat ReadMe.</p>
<img src= "img/Screenshot (88).png" style="width:86%"/>

<br /><p>Sekarang mari kita perbarui Repo ini dengan file apapun. Kembali ke terminal git Anda dan ikuti seperti gambar dibawah:</p>
<img src= "img/Screenshot (89).png" style="width:86%"/>

<br /><p>Sekarang periksa repo Anda. repo Anda di halaman Github akan bertambah, seperti gambar dibawah ini:</p>
<img src= "img/Screenshot (90).png" style="width:86%"/>

<br /><h2><strong>Langkah 2: Menambahkan tim kolaborasi</strong></h2>

<p>Sekarang Anda perlu menambahkan tim Anda ke repo agar mereka dapat berkolaborasi.</p>

<br /><p>Klik pada tab "Settings", lalu "Collaborators" lalu cari pengguna Github dan tambahkan mereka dengan mengklik "Add people":</p>
<img src= "img/Screenshot (102).png" style="width:86%"/>

<br /><p>Mereka akan menerima email yang memberitahukan bahwa Anda menambahkan mereka dan akan terdaftar sebagai kolaborator.</p>
<img src= "img/Screenshot (91).png" style="width:86%"/>

<br>Jika Anda seorang kolaborator, buka halaman Github Repo, Git Clone proyek dengan menyalin link yang ada di github, seperti di bawah ini.</br>
<img src= "img/Screenshot (92).png" style="width:86%"/>
```
$ git clone https://github.com/rhinochristiajir/github-guide.git
```

<br /><h2><strong>Langkah 3: Berkolaborasi</strong></h2>
<p>Cara berkolaborasi adalah dengan membuat cabang baru untuk fitur baru dan menggabungkannya ke dalam Master setelah selesai.</p>

<br /><p>Untuk memulai berkolaborasi, kita akan membuat cabang(branch) terlebih dahulu di terminal git anda.</p>
```
$ git co -b create_user
```
<p>"checkout" yang digunakan untuk berpindah antar cabang. Menambahkan "-b" dan nama di akhir membuat cabang baru.</p>

<br /><p>Dan anda sekarang dicabang baru, untuk mengeceknya ketikan:</p>
```
$ git branch
```

<p>Tampilan di terminal git anda akan seperti ini:</p>
<img src= "img/Screenshot (96).png" style="width:86%"/>
<p>Anda sekarang bisa melakukan kolaborasi dengan proyek tim anda.
</p><br/>

*catatan: Anda harus sering git add dan git commit ketika Anda menyelesaikan sesuatu di proyek anda. Seperti gambar dibawah ini:*

<img src= "img/Screenshot (103).png" style="width:86%"/>

<br/>Jika anda sudah menyelesaikan proyek dicabang anda, selanjutnya kita akan melakukan git push cabang yang sudah kita seleaikan di terminal git anda.
```
$ git push
```

<br/>Sekarang pergi ke halaman Repo Github. Anda akan melihat cabang yang Anda dorong di bilah kuning di bagian atas halaman dengan tombol "Pull request" and "Compare".

<img src= "img/Screenshot (97).png" style="width:86%"/>

<br/>Klik "Compare & pull request". Ini akan membawa Anda ke halaman "Open a pull request". Dari sini, Anda harus menulis deskripsi singkat tentang apa yang sebenarnya Anda ubah. Dan Anda harus mengklik tab 'Reviewers" dan memilih siapa pun yang diputuskan oleh tim Anda sebagai "Merge Master". Setelah selesai, klik "Create pull request".

<img src= "img/Screenshot (98).png" style="width:86%"/>


<br/> *Perhatikan bahwa jika Anda seorang kolaborator, Anda dapat menggabungkan permintaan tarik Anda sendiri. Namun, sekali lagi, jika Anda bekerja dalam tim, lebih masuk akal jika satu orang melakukan semua penggabungan dan semua orang lainnya mengirimkan "Pull Requests" dan menetapkan Penggabungan Utama (Master Merger) sebagai peninjau hanya untuk memastikan Anda berurusan dengan konflik gabungan apa pun satu cabang pada satu waktu.*

<br/>Selanjutnya silakan dan klik tombol "Add your review".

<img src= "img/Screenshot (99).png" style="width:86%"/>

Ini akan membawa Anda ke halaman Pull Request

<img src= "img/Screenshot (100).png" style="width:86%"/>

Dan sekarang anda berada di halaman pull request, disini anda ditugaskan untuk mengecek perubahan yang dibuat oleh tim anda. Jika sudah dicek klik "submit riview".

<br/>Saat Anda puas dengan pull request, pergi ke bagian bawah pull request dan klik "Merge pull request".

<img src= "img/Screenshot (101).png" style="width:86%"/>

<br/>Selamat!! Anda telah menyelesaikan belajar cara mengkolaborasi di Github.

TerimaKasih!.