![VPN PROXY INSTALLER](https://github.com/bangden07/VPN-Proxy-Installer/workflows/VPN%20PROXY%20INSTALLER/badge.svg) [![Build Status](https://travis-ci.com/bangden07/VPN-Proxy-Installer.svg?branch=master)](https://travis-ci.com/bangden07/VPN-Proxy-Installer)

# Auto Install VPN + Proxy

### Daftar Isi

- [Intro](#intro)
- [Fitur](#fitur)
- [Persyaratan](#persyaratan)
- [Cara Install](#cara-instalasi)
- [Cara Penggunaan](#cara-penggunaan)

### Intro
---
Script ini sengaja saya buat karena keperluan pribadi untuk instalasi masal ke server client saya. Namun dengan banyak permintaan dari kawan-kawan supaya script ini dipublish. Maka saya bersedia untuk mempublish script ini.

> Note: Saya tidak mensupport apapun itu mengenai kegagalan instalasi Anda.

Script ini saya buat dan ada beberapa script yang saya modifikasi sesuai dengan kebutuhan saya pribadi. Apabila Anda ingin mengubah dengan kebutuhan Anda, silahkan Anda ubah file config setelah instalasi selesai.

Saya tidak menginzinkan Anda untuk mengubah isi script instalasi. Jadi silahkan gunakan dan modifikasi confignya jika Anda membutuhkan itu.

### Fitur
---
Keunggulan utama script ini adalah dengan satu perintah, Anda bisa menginstall dua aplikasi sekaligus, yitu **squid-cache** dan **OpenVPN**.

- Installasi sangat mudah
- Squid Proxy Support SSL *(versi terbaru)*.
- Open VPN Kustom Port
- Easy Tambah USER
- Easy Hapus USER
- Pilih Protocol VPN
    - UDP / TCP
- Optimasi Squid Config lebih maksimal dan optimal.
- Support **"Custom Header Host"**
- Prioritas Fast Speed
- Minim bandwidth
- Tetap dalam kaedah server yaitu keamanan.

### Persyaratan
---

Sebelum masuk ke instalasi, ada beberapa persyaratan yang harus kamu penuhi.

- Fresh Server
- OS Ubuntu / Debian
- KVM, XEN, VMware
- CPU Minimal 1 Core
- RAM Minimal 1 GB
- SSD / HDD Minimal 20 GB
- Versi Kernel Terbaru
- Matikan firewall bawaan provider

### Cara Instalasi
---

Jalankan Perintah berikut:
*Note: Apabila belum menginstall wget*
```bash
sudo apt install wget -y && sudo apt install nano -y
```

```bash
wget https://git.io/JfKr7 -O install.sh && sudo chod +x install.sh

bash install.sh
```

### Cara Penggunaan:
---

COMING SOON