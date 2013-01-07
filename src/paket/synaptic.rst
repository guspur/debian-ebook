Synaptic - Pemasangan perangkat lunak dengan GUI
================================================

Selain menggunakan apt, dpkg, dselct, kita juga dapat menggunakan antarmuka
grafis dengan synaptic. Untuk mengakses synaptic package manajer dapat dengan
mengetikkan synaptic bila menggunakan gnome-shell atau dengan memilih **Aplikasi>
Perkakas System > Administrasi> Synaptic Package Manajer** bila menggunakan
gnome-clasic.

.. figure:: ../images/paket/synaptic-menu.png
    :align: center
    :figclass: align-center
    
    Tampilan layar bila menjalankan synaptic menggunakan gnome-classic

.. figure:: ../images/paket/synaptic-gnome3.png
    :align: center
    :figclass: align-center
    
    Tampilan layar bila menjalankan synaptic menggunakan gnome-shell


Untuk desain synaptic dan penjelasanya dapat dijelaskan dari gambar dibawah 
ini

.. figure:: ../images/paket/synaptic-layout.png
    :align: center
    :figclass: align-center

    Tampilan desain synaptic package manager

#. Daftar perangkat lunak.
#. Paket perangkat lunak untuk setiap kategori.
#. Status perangkat lunak/paket yang terpasang, belum terpasang, rusak dan 
   lain-lain.
#. Informasi lanjut dari paket yang terpilih.

Untuk mencari nama paket atau deskripsi paket dapat menggunakan fasilitas
pancarian, fasilitas pencarian dapat diluncurkan dengan menekan **CTRL + F**.
Misalnya seperti pada gambar dibawah ini.

.. figure:: ../images/paket/synaptic-find.png
    :align: center
    :width: 207px
    :height: 127px
    :figclass: align-center

    Fasilitas Pencarian

Pemasangan paket
-------------------------------

Untuk melakukan pemasangan paket, klik kanan dan pilih **Tandai untuk
dipasang** atau klik dua kali pada daftar paket.

.. figure:: ../images/paket/synaptic-select.png
    :align: center
    :figclass: align-center

    Pilih paket yang akan dipasang

Setelah itu, klik **Apply** dan akan ada jendela konfirmasi ikhtisar dari 
paket yang akan dipasang.

.. figure:: ../images/paket/synaptic-apply.png
    :align: center
    :width: 220px
    :height: 218px
    :figclass: align-center

    Jendela konfirmasi paket yang akan dipasang

.. note::
    
    Anda dapat menggunakan CTRL+P untuk melakukan apply

Setelah itu masukkan kata sandi root dan tekan enter.

.. figure:: ../images/paket/synaptic-enter-password.png
    :align: center
    :width: 249px
    :height: 229px
    :figclass: align-center

    Jendela yang mewajibkan kita untuk memasukkan kata sandi.

Silakan tunggu pada saat proses pemasangan, durasi pemasangan ini tergantung
pada kekuatan sistem pada saat memproses. Proses akan selesai bila kita
menjumpai tampilan layar sebagai berikut.

.. figure:: ../images/paket/synaptic-sukses.png
    :align: center
    :width: 234px
    :height: 133px
    :figclass: align-center

    Jendela konfirmasi penyelesaian proses pemasangan

Pencopotan paket
----------------

Untuk melakukan pengucangan/pencopotan paket, silakan klik kanan paket dan 
pilih **Mark for Removal** dari menu. Kemudian klik **Apply**, kemudian 
tampilan layar akan seperti pemasangan.

Pemutakhiran paket
------------------

Untuk melakukan pemutakhiran (**upgrade**) paket, silakan pilih paket dan
klik kanan, kemudian pilih **Mark for Upgrade** atau tekan **CTRL+U** dan
tekan **Apply**.


