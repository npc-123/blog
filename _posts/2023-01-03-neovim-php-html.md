---
layout: post
title: Neovim PHP & HTML
date: 2023-01-03 16:32:25 0500
categories: [Tutorial, Vim]
tags: [Linux, Vim, Neovim]
---

Halo kawan, jadi waktu saya ngoding php di neovim ada masalah, yaitu autocomplete html tidak
keluar saat menggunakan filetype php dan itu tentu masalah besar, karena itu saya bikin tutor ini.

kalian tinggal ketik
```
:set filetype=html | set syntax=php
```

>**CARA DIBAWAH TIDAK EFISIEN LAGI, PAKAI CARA DIATAS**
{: .prompt-danger }
1. Pertama kalian set file php ke php.html (mksudnya php & html) :
```
:set filetype=php.html
```
2. Kalian Jalankan Lsp HTML jika ingin:
```
:LspStart html
```
3. Dan selesai, kalian bisa dapat autocomplete HTML di PHP :)

info tambahan : https://stackoverflow.com/questions/3008575/vim-activiting-html-snippets-on-php-files
