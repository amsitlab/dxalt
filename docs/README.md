# dxalt

**Dxalt is alternative "dx" command line program for termux.** 
===============================================

Program ini saya buat karena program official "dx" dari termux tidak berjalan dengan baik di perangkat saya.
Jika anda mengalangi hal yang sama dengan saya, silahkan gunakan ini sebagia alternatif.

**Install**
===========

1. Dengan "**git clone**".
   1. Clone repository ini.
      ```bash
      git clone https://github.com/amsitlab/dxalt.git .
      ```
   1. Pindah directory.
      ```bash
      cd dxalt
      ```
   1. Beri akses execute untuk file **install**
      ```bash
      chmod +x ./install
      ```
   1. Jalankan file "./install"
      ```bash
      ./install
      ```
2. Install dengan command "**apt get**".
   1. Jalankan perintah:
      ```bash
      apt get ./dexalt_1.0_all.deb
      ```


**Rekomendasi**
===============
Rekomendasi agar perintah "dxalt" bisa di panggil dengan "dx".
Tulis code ini di file **$HOME/.bash_profile** atau file **$HOME/.profile**
```bash
alias dx=`which dxalt`
```
atau bisa juga dengan code:
```bash
alias dx="${PREFIX}/bin/dxalt"
```


