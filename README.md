# perkalian-web
Versi web dari game perkalian sampai mendekati bilangan tak-hingga!

### Panduan instalasi

Game ini dapat dijalankan secara online melalui situs web https://perkalian.netlify.app atau situs lainnya yang memuat permainan ini. Apabila Anda berminat untuk memuat permainan ini pada situs web Anda, Anda dapat melakukannya dengan memuat file `index.html` pada repositori ini ke dalam laman web.

Game ini juga dapat dimainkan secara offline dengan mengunduh proyek ini. Untuk membuka permainan, akses **index.html** dengan peramban web.

Catatan: game ini membutuhkan JavaScript. Kode sumber JavaScript dapat dipahami dengan mudah dan kami tidak mengoleksi data pribadi apapun.

### Panduan untuk instruktur/pengajar

Game ini melatih konsep perkalian dengan pembiasaan (deliberate practice). Adapun mekanisme game ini adalah menaikkan bilangan pengali satu per satu (secara acak) sebanyak satu. Misalnya, jika pada soal ke `n` adalah `a*b=...` maka salah satu di antara `(a+1)*b` atau `a*(b+1)` akan dipilih secara acak untuk menjadi soal berikutnya (soal ke `n+1`).

Instruktur dapat mengenalkan konsep perkalian sebagai penjumlahan berulang. Pada soal ke `n`, game akan menampilkan jawaban dari soal ke `n-1`. Ada dua skenario yang mungkin

1. Apabila soal ke `n-1` adalah `a*b=x` dan soal ke `n` adalah `(a+1)*b=...`, maka cara menjawabnya adalah dengan menguraikan `(a+1)*b=(a*b)+(1*b)`. Karena telah diketahui bahwa `a*b=x`, maka jawaban untuk soal ke `n` adalah `x+b`. Instruktur dapat meminta peserta untuk menambahkan jawaban sebelumnya dengan `b`.

2. Apabila soal ke `n-1` adalah `a*b=x` dan soal ke `n` adalah `a*(b+1)=...`, maka cara menjawabnya adalah dengan menguraikan `a*(b+1)=(a*b)+(a*1)`. Karena telah diketahui bahwa `a*b=x`, maka jawaban untuk soal ke `n` adalah `x+a`. Instruktur dapat meminta peserta untuk menambahkan jawaban sebelumnya dengan `a`.

Dengan demikian, instruktur dapat mengenalkan konsep perkalian sebagai penjumlahan berulang.

Sebagai contoh, apabila pada soal sebelumnya adalah `4*6=24` maka soal saat ini, yaitu (misalnya) `4*7`, dapat dijawab dengan menambahkan `24+4`, yaitu `28`. Apabila soal berikutnya adalah `5*7`, dapat dijawab dengan menambahkan `28+7`, yaitu 35.

### Lisensi

Game ini adalah perangkat lunak bebas dengan kode sumber terbuka (Free and Open Source). Ikutilah ketentuan lisensi dalam mereproduksi game ini.