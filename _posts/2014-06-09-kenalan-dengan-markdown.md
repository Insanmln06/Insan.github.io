---
layout:     post
title:      Kenalan Dengan Markdown
date:       2014-06-09 12:32:18
summary:    Dengan Markdown memungkinkan untuk membuat sebuah format html dengan sangat sederhana dan hemat. (easy-to-read dan easy-to write)
categories: pengetahuan post
---

## Apa itu Markdown? 

Markdown merupakan gaya penulisan text-to-HTML yang digunakan untuk membuat konten tertentu pada suatu web dengan kata lain konversi penulisan format berupa plain text yang dikonversi menjadi html pada web. Dengan Markdown memungkinkan untuk membuat sebuah format html dengan sangat sederhana dan hemat. (easy-to-read dan easy-to write)

Markdown dibuat pertama kali oleh John Gruber sejak 2004 dengan bahasa Perl. Tujuan utama dari pembuatan Markdown adalah untuk mempermudah penulisan format plain text dan sebagai opsi untuk bisa mengkonversinya ke HTML dan XHTML.

Pada saat ini markdown seringkali digunakan untuk membangun tampilan halaman web atau postingan blog dan semacamnya. Bahkan, situs web yang terkenal seperti [GitHub](https://github.com), [Reddit](www.reddit.com), [Stackoverflow](http://stackoverflow.com) dan [SourceForge](http://sourceforge.net) sudah menggunakannya.

## Penulisan Markdown

{% highlight ruby %}
# Markdown

**Markdown** is a text-to-HTML conversion tool for web writers. 
Markdown allows you to write using an *easy-to-read*, *easy-to-write* plain text format, 
then convert it to structurally valid XHTML (or HTML).

[Markdown](http://daringfireball.net/projects/markdown/ "Markdown")

"Markdown" is two things:

1. Plain text formatting syntax.
2. Software tool.

{% endhighlight %}

## Penulisan Format HTML

{% highlight ruby %}
<h1>Markdown</h1>

<p><strong>Markdown</strong> is a text-to-HTML conversion tool for web writers. 
Markdown allows you to write using an <em>easy-to-read</em>, <em>easy-to-write</em> plain text format, 
then convert it to structurally valid XHTML (or HTML).</p>

<p><a href="http://daringfireball.net/projects/markdown/" title="Markdown">Markdown</a></p>

<p>"Markdown" is two things:</p>

<ol>
	<li>Plain text formatting syntax.</li>
	<li>Software tool.</li>
</ol>

{% endhighlight %}

## Extensi File Markdown

Tidak ada persyaratan untuk ekstensi file markdown, seperti jawaban yang lain telah dijelaskan. Tapi agar editor atau parser untuk menjamin bahwa file yang mereka gunakan adalah format markdown, mereka akan mencari salah satu ekstensi berikut:

> .markdown
.mdown
.mkdn
.md
.mkd
.mdwn
.mdtxt
.mdtext
.text

Ada website seperti GitHub yang hanya menggunakan pilihan ekstensi ini untuk mengkonversi ke HTML sehingga para pengembang akan sesuai dengan standar mereka. (lihat contoh di bawah)

Secara pribadi, saya lihat .markdown dan .mdown sering digunakan dan sebagai pengguna Linux saya menghindari menggunakan .md karena hal ini juga dapat menjadi file deskripsi mesin untuk mengkompilasi kode dengan GCC.

Contoh penggunaan ekstensi:

a. GitHub: markdown, mdown, mkdn, MKD, md [(source)](https://github.com/github/markup/blob/b865add2e053f8cea3d7f4d9dcba001bdfd78994/lib/github/markups.rb#L1)

b. Elemen markdown Editor: markdown, mdown, mdwn, md

c. Vim markdown: markdown, mdown, mkdn, mdwn, MKD, md

d. Bitbucket: markdown, mdown, mkdn, MKD, md, teks [(source)](https://confluence.atlassian.com/display/BITBUCKET/Display+README+text+on+the+overview#DisplayREADMEtextontheoverview-Filenamingandprecedence)

Jika ingin mengetahui lebih lanjut mengenai markdown dan penulisannya dapat dilihat di sini:

[Help.github.com/search/?q=markdown](https://help.github.com/search/?q=markdown)
[Daringfireball.net/projects/markdown](Daringfireball.net/projects/markdown)
[Ghostforbeginners.com/basic-markdown-for-ghost-blogs](http://ghostforbeginners.com/basic-markdown-for-ghost-blogs)

Ingin menggunakan Markdown bisa ke sini:

[Daringfireball.net/projects/markdown/dingus](http://daringfireball.net/projects/markdown/dingus)

Ingin melihat tools yang bisa digunakan untuk Markdown ke sini:

[Mashable.com/2013/06/24/markdown-tools](http://mashable.com/2013/06/24/markdown-tools)

Sumber artikel: 

[http://www.codepolitan.com/kenalan-dengan-markdown](http://www.codepolitan.com/kenalan-dengan-markdown)

Semoga bermanfaat, feel free~
