---
sectionid: conventional-method
sectionclass: h2
parent-id: intro
title: Metode Konvensional
number: 1100
---
Sebelum lebih dalam belajar tentang DevOps, sebaiknya kita mulai dari sistem operasional konvensional. Kita akan merasakan cara operasional yang kurang praktis & memiliki banyak resiko human. Dengan demikian, ketika nanti kita mulai belajar DevOps, kita akan merasakan manfaat penerapan DevOps. Pertama-tama, kita harus menyiapkan sebuah virtual machine. Kita akan membuat virtual machine dengan vagrant. Jalankan perintah berikut
`vagrant init`
Kemudian edit menjadi
```
config.vm.box = "ubuntu/xenial64"
```

Kemudian nyalakan virtual machine tersebut dengan menjalankan perintah berikut `vagrant up`

Masuk ke server, dengan perintah `vagrant ssh` kemudian kita persiapkan server virtual kita dengan langkah2 berikut:
1. update server: `sudo apt update`
2. install nginx webserver: `sudo apt install nginx`
3. install database postgresql: `sudo apt install postgresql postgresql-server-dev-9.5`
4. install package management python `sudo apt install python3-pip`
4. lakukan konfigurasi nginx `sudo cp djblog/server_configs/djblog.conf /etc/nginx/conf.d/`
5. hapus konfigurasi nginx default: `sudo rm /etc/nginx/sites-enabled/default`
6. buat database user untuk aplikasi djblog 