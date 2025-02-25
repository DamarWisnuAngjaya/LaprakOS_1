**TUGAS PENDAHULUAN**

**Nomor 1.**
Langkah-langkah instalasi Ubuntu di VirtualBox

a. Unduh ISO Ubuntu dari situs resminya.

b. Buka VirtualBox, buat VM baru dengan spesifikasi:
- CPU: 2 core
- RAM: 4096 MB
- HDD: 25 GB (dibagi menjadi / 20GB, /storage 5GB, dan swap 1.5GB)

c.  Masukan password "changeme" pada saat tampil menu user

d.  Klik kanan pada tampilan VM

e.  Konfigurasi OS:
-   Setelah masuk menu dekstop, pilih terminal.
-   Ketikan perintah sudo apt upgrade && sudo apt update di terminal.
-   Ketik perintah sudo nano /etc/hostname.
-   Gunakan crtl + o untuk menyimpan hostname baru tersebut.
-   Gunakan ctrl + x untuk keluar dari terminal tersebut
-   Ketik sudo reboot


**Nomor 2.**
Perbandingan Debian 11 dengan Debian 12

| ASPEK                | DEBIAN 11 (BULLSEYE) | DEBIAN 12 (BOOKWORM)  |
|----------------------|----------------------|-----------------------|
| Versi kernel         | Kernel 5.x           | Kernel 6.x            |
| Performa             | Stabil dan handal    | Optimalisasi lebih lanjut |
| systemd              | Versi sebelumnya     | Diperbarui dengan fitur-fitur terbaru |
| paket                | Stabil dari versi lama | Diperbarui dari versi-versi sebelumnya |
| Desktop environment  | GNOME 3.38, KDE Plasma 5.20, Xfce 4.16 | GNOME 41, KDE Plasma 5.24, Xfce 4.18 |
| keamanan             | Pembaruan keamanan yang rutin | Peningkatan dan perbaikan pada bug |


**Nomor 3.**
Cek Environment menggunakan CPU-X

```bash
Stoney Ridge
```

**Nomor 4.**
Cara lain mencari info list aplikasi & hardware menggunakan Shell

- Untuk info hardware secara lengkap:
```bash
lshw -short
```
- Untuk storage: 
```bash
df -h
```
- Cek RAM:
```bash
free -h
```
- Cek CPU:
```bash
lscpu
```
- Cek GPU:
```bash
lspci | grep
```
- Cek aplikasi yang terinstal:
```bash
dpkg --get-selections | grep -v deinstall
```
