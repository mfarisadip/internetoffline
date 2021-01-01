# homeserver

Home Server Standard for Ubuntu 18.04 LTS v1.0 Stable
------------------------------------------

Released 30/12/2020
-------------------

Aplikasi untuk membangun NAT, DHCP Server, access log, cache web, port forwarding, VPN Server, apache2, mysql-server, virtualhost, DNS Server & Samba secara cepat termasuk konfigurasinya. 

Cara menggunakan :
------------------

Pastikan di CPU anda sudah terinstall Ubuntu Server 18.04 dengan 2 LAN Card jika ingin dibangun router. Jika server aja, cukup 1 LAN Card.

Jika memakai Ubuntu 20.04 Menggunakan Repository Kambing UI
Cara Ubah :

- sudo nano /etc/apt/sources.list

- Copy & Paste
```
deb http://kambing.ui.ac.id/ubuntu/ focal main restricted universe multiverse
deb http://kambing.ui.ac.id/ubuntu/ focal-updates main restricted universe multiverse
deb http://kambing.ui.ac.id/ubuntu/ focal-security main restricted universe multiverse
deb http://kambing.ui.ac.id/ubuntu/ focal-backports main restricted universe multiverse
deb http://kambing.ui.ac.id/ubuntu/ focal-proposed main restricted universe multiverse
```

- Kemudian Update
```
sudo apt update
```

Perintah instalasi dan menjalankannya
-------------------------------------

- Download : 

- git clone https://github.com/mfaris16/internetoffline

- cd internetoffline

- chmod -R 777 *

- ./homerouter (untuk router)

- ./homeserver (untuk server)

Progammer 
---------

- Programmer : Faris. mfarisadip.my.id. mfaris@amnusatech.or.id

Rekomendasi Tambahan
---------

- https://github.com/frenck/awesome-home-assistant

Source
------

- https://github.com/kurniawandata/xcodepandawa2

List Pekerjaan
------

- LMS (Moodle)

License
------- 

- GNU General Public License 

Donasi :
--------
Jika ingin donasi untuk Faris

Saweria :

![alt text](https://mfarisadip.my.id/download.png)

