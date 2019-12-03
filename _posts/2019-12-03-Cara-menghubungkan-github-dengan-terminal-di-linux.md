---
layout:     post
title:      Cara upload file ke github menggunakan terminal di linux
date:       2019-12-02 22:22:22
summary:    pada artikel kali ini saya akan membahas tentang cara mengupload file ke github menggunakan perintah git di terminal linux
categories: celotehan post
---

pada artikel kali ini saya akan membahas tentang cara mengupload file ke github menggunakan perintah git di terminal linux

Sebelumnya saya asumsikan kalian sudah membuat repositori di akun github kalian bagi yang belum bisa membuatnya terlebih dahulu.

## Mengupload folder(repositori lokal)

Sebelum melakukan upload pastikan di PC atau laptop sudah tersedia git, kalian bisa menginstallnya dengan perintah `sudo apt-get install git`

jika sudah memiliki proyek yang ingin diletakkan di repository online, buka saja folder project tersebut dengan perintah command line jika sudah maka ketikan perintah dibawah ini secara urut

```
git init 
git add . 
git commit -m "first commit" 
git remote add origin https://github.com/aisy/js-belajar-react.git 
git push --force origin master
```
Keterangan perintah diatas seperti ini :
### git init

untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali
### git add “.” atau nama file

untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload kalian bisa menggunakan perintah tersebut. Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan “nama file” untuk memberikan status commit. Ini adalah contohnya apabila ingin menggunakan “git add” :
```
// mengupload keseluruhan file pada repo (hanya digunakan saat upload pertama saja)
git add .
// mengupload file sesuai dengan nama file
git add index.html
// mengupload file pada dalam folder
git add pages/index.html
```
### git commit -m “isi commit”

untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh).

`git remote add origin “link repo online”`

untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format “.git”, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.
git push origin “nama branch”

Perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online.

Setelah melakukan semua perintah silahkan cek di github, apakah file yg di upload sudah masuk atau tidak? jika iya maka anda berhasil mengelola git untuk tahap awal, jika ada kesalahan bisa menghubungi saya melalui [Facebook](https://web.facebook.com/profile.php?id=100024240161916) atau kontak saya.