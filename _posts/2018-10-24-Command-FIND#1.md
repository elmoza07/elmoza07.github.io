---
layout: post
title: "Command FIND#1"
date: 2018-10-24
description: 
image: /assets/images/ss3.png
author: Alrusyd
tags: 


---

Di pembahasan kali ini kita akan membahas salah satu command di linux atau ubuntu. 
Command yang akan kita bahas kali ini adalah command FIND, yang berfungsi untuk mencari suatu file akan tetapi kita lupa dalam menaruh file tersebut dimana.

##Bagaimana kita menjalkan command tersebut?

oke langsung saja disini saya mempunyai file dengan nama "test.txt" di dalam folder nopal.

<img src="/assets/images/ss1.png">

Terus suatu ketika saya lupa dengan file tersebut, dan gak tau posisinya di mana hanya mengingat nama file saja
maka kita jalan kan command:

<img src="/assets/images/ss2.png">

Nah.. ketemu lah file itu.  jika di kosongi (langsung ‘-name’) berarti dia akan mencari di current direktori(tempat sekarang kamu berada). Kalau saya ganti menjadi tempatnya menjadi Downloads maka tidak akan keluar hasil apa2, karna di Downloads tidak ada file itu.

Trus kalo bener2 lupa di mana tempat nyimpannya gimana?? ya.. tinggal mulai pencarian dari akar semua file “/”. Tapi untuk metode ini butuh hak akses root jadi harus di tambah command “sudo” sebelum find

<img src="/assets/images/ss3.png">

Ini dulu pembahasan kita tentang command . TERIMAKASIH
