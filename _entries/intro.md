---
sectionid: intro
sectionclass: h1
title: Pengertian DevOps
number: 1000
---
Sekarang ini, dunia pengembangan perangkat lunak dituntut untuk semakin cepat memberikan hasil. Kecepatan proses pengembangan perangkat lunak tidak boleh melupakan aspek kualitas dari perangkat lunak yg dihasilkan.

Beberapa hal yang harus diperhatikan dalam pola pikir DevOps adalah:
1. __Fast feedback__
   - Fail fast, untuk tujuan pembelajaran.
   + Effective action, untuk memperkuat usaha terhadap hal yang kita yakini bisa meningkatkan nilai tambah perangkat lunak.
2. __Incremental__
   1. v1 dev -> v1 staging -> v1 prod
   2. v2 dev -> v2 staging -> v2 prod
   Pengembangan secara bertahap dari dev ke prod
3. __Rollback__, Tidak bisa dihindari, kadang kita akan menghasilkan fitur yang rusak. Meskipun proses pengerjaan sudah hati-hati, tetap saja ada hal-hal yang tidak terduga yang dapat membuat fitur kita rusak. Jika fitur yang sudah terlanjur kita deploy ke prod rusak, kita harus bisa segera rollback atau mengembalikan sistem kita ke keadaan sebelumnya.
4. __Automation__. Semua kegiatan DevOps di atas, akan sangat merepotkan apabila dilakukan secara manual. Selain repot, pekerjaan secara manual memiliki resiko lebih besar yang bisa membuat sistem error, misalnya ada tahapan yang lupa kita lakukan, atau kita memasukan data yang salah.

Kita akan mempelajari prinsip-prinsip DevOps secara bertahap.

DevOps adalah kolaborasi antara pola pikir pengembangan produk (Product Development) & operasional sistem (System Operational).