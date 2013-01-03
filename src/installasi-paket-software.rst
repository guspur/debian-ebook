=======
BAB 3
INSTALASI PAKET SOFTWARE GNU/LINUX
=======
3.1 Instalasi Paket Software dari Source Code
Instalasi paket software dari kode sumber (source code) merupakan cara instalasi yang berlaku umum untuk semua distribusi GNU/Linux yang ada. Perintah umum yang sering digunakan adalah:
debian:~# tar zxvf paketsoftware.tar.gz
debian:~# tar jxvf paketsoftware.tar.bz2
Keterangan:
Opsi -x dan -j digunakan untuk tipe kompresi yang berbeda. Opsi -x untuk tipe kompresi *.gz dan opsi -j untuk tipe kompresi *.bz2.
Setelah ekstraksi paket software, langkah berikutnya adalah konfigurasi, kompilasi, dan terakhir adalah instalasi software.
debian:~# cd paketsoftware
debian:~# ls
debian:~# more readme
debian:~# ./configure
debian:~# make
debian:~# make install
