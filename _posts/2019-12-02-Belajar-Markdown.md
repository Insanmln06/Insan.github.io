---
layout:     post
title:      Belajar Markdown
comments:   true
date:       2019-12-02 22:38:19
summary:    Bagi yang sering bermain di Github dan web serupa, pasti sering melihat markdown. Biasanya markdown digunakan untuk menuliskan dokumentasi.
categories: celotehan post
---
Bagi yang sering bermain di Github dan web serupa, pasti sering melihat markdown. Biasanya markdown digunakan untuk menuliskan dokumentasi.

Pada dasarnya markdown sama seperti HTML. Namun, lebih sederhana dan mudah dibaca.

Saat ini markdown sudah digunakan untuk:
+ Dokumentasi;
+ SSG (Static Site Generator);
+ CMS seperti Ghost, Wordpress, Tumblr, dll.;
+ Penulisan Buku;
+ Format teks pada chat: Telegram, WA, Facebook;
+ dll.

Pada kesempatan ini, kita akan belajar dasar-dasar format markdown hingga format tingkat lanjut.

### Apa itu markdown ?
Markdown adalah (lightweight markup language) bahasa markup yang lebih ringan dari HTML untuk formatting teks.

Markdown bisa dikonversi ke dalam HTML menggunakan beberapa aplikasi. Biasanya menggunakan markdown editor itu sendiri.

Markdown dibuat pada tahun 2004 oleh John Gruber. Tujuannya untuk mempermudah penulisan dokumen web mudah ditulis dan mudah dibaca Karena menulis langsung HTML terasa melelahkan dan susah dibaca.

Contoh:

 ```Aku *sedang* belajar **menulis** dengan [markdown](https://en.wikipedia.org/wiki/Markdown).```

Teks ini akan dikonversi ke HTML menjadi seperti ini:

Aku *sedang* belajar **menulis** dengan [markdown](htpps://en.wikipedia.org/wiki/Markdown).

 
``` Aku <em>sedang</em> belajar <strong>menulis</strong> dengan <a href="https://en.wikipedia.org/wiki/Markdown">markdown</a>.```

Menurutmu mana yang lebih mudah ditulis?

Pasti banyak yang akan menjawab markdown.

Saya sendiri sudah merasakan perbedaannya.

## Editor untuk Menulis Markdown

Ada banyak sekali software atau editor untuk menulis markdown. Silahkan pilih yang kamu sukai.

### Markdown Editor di Mac OSX

+ Mou - Free
+ iA Writer - $19.99
+ Desk - $29.99
+ ByWord - $11.99
+ Day One - $9.99
+ SublimeText - $70

### Markdown Editor di Windows

+ WriteMonkey - Free
+ MarkdownPad - Free + $14.99 Pro version
+ Texts - $14.50
+ SublimeText - $70

### Markdown Editor di Linux

+ Remarkable - Free
+ Haroopad - Free
+ ReText - Free
+ UberWriter
+ Mark My Words

Pilih yang mana?

Saya sendiri memilih VS Code dengan [plug-in Mardkwon All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one).

## File Markdown

File markdown dapat kita simpan dengan ekstensi `.markdown` atau `.md`.

Contoh: `belajar-menulis.md` atau `belajar-menulis.markdown`

## Format dasar Markdown

Sekarang mari kita coba menulis format-format dasar markdown. Pertama, mari kita mulai dari:
## Membuat Heading

*Heading* atau judul di *markdown* dapat dibuat dengan tanda pagar `#`.

Contoh:
```
# Heading 1
## Heading 2
### Heading 3
``` 

Maka akan menghasilkan:
```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
```
Heading ini sampai level 6 seperti pada HTML. Jumlah tanda pagar di depannya menandakan levelnya.

Selain menggunakan tanda pagar, ada juga yang menggunakan simbol minus (`-`) dan samadengan (`=`) seperti ini:
```
Ini Headeing Level 1
====================

ini paragraf, bla bla bla...

Ini heading level 2
-------------------

ini paragraf, bla bla bla...
```

## Format Teks

Jika kamu ingin menulis teks tebal, miring, dan strikeline, maka bisa dilakukan seperti ini:
```
**Tebal**
*miring*
~~strikeline~~
```
Selain menggunakan tanda bintang, untuk teks tebal dan miring bisa juga menggunakan garis bawah (underscore) seperti ini:
```
__teks tebal__
_teks miring_
```
## Membuat Link

Link dapat kita buat dengan tanda kurung seperti ini:

```
[link ke petanikode](https://www.petanikode.com/)
```
Hasilnya:

[link ke petanikode](https://www.petanikode.com/)

Kita juga bisa menambahkan title untuk tooltips:
```
[link ke petanikode](https://www.petanikode.com/ "Pergi ke petanikode.com")
```
Hasilnya:

[link ke petanikode](https://www.petanikode.com/ "Pergi ke petanikode.com")

Selain menggunakan tanda kurung, kita juga bisa membuat link langsung dengan menuliskan URL lengkapnya.

Contoh:
```
https://en.wikipedia.org/wiki/Markdown
```
Maka akan menghasilkan:

https://en.wikipedia.org/wiki/Markdown

## Menyisipkan Gambar

Caranya hampir sama dengan membuat link. Kita tinggal tambahkan tanda seru (!) di depannya.

Contoh:
```
![Gambar teks editor VS Code](https://www.petanikode.com/img/markdown/markdown-vscode.png)
```
![Gambar teks editor VS Code](https://www.petanikode.com/img/markdown/markdown-vscode.png)

# Bagaimana Cara Menghapal Markdown?

Semakin sering diketik, semakin tajam pula ingatan kita. Sehingga tidak perlu dihapal.

# Referensi dan Sumber
+ https://www.petanikode.com/markdown-pemula/
+ https://blog.ghost.org/markdown/
+ https://en.wikipedia.org/wiki/Markdown
