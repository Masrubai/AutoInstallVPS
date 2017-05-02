# AutoInstallVPS
Install VPS dengan Mudah

Info

Wajib OS Debian 7 32 bit
Pastikan sebelum install server kondisi fresh belum terinstall apa-apa.
Kenapa Harus fresh? karena takut terjadi bentrok port
Auto-Installer-VPS

Melakukan install service seperti SSH,VPN,Dropbear dll dengan script auto installer yang sangat mudah.
Caranya:

    Login VPS
    wget https://raw.githubusercontent.com/rizal180499/Auto-Installer-VPS/master/debian7-32.sh
    chmod +x debian7-32.sh
    ./debian7-32.sh
    tunggu sampai proses selesai > reboot vps anda


# Service OpenVPN : TCP 1194
OpenSSH : 22, 143
Dropbear : 109, 110, 443
Squid3 : 8080 (limit to IP SSH)
badvpn : badvpn-udpgw port 7300
Webmin
VNSTAT
MRTG
more cek log install

# OCS PANEL Melakukan Install Web Panel SSH Reseller Secara otomatis.
Caranya:
1. Login VPS
2. # wget https://raw.githubusercontent.com/rizal180499/Auto-Installer-VPS/master/ocs_panel/ocs-deb7-32.sh
3. # chmod +x ocs-deb7-32.sh
4. # ./ocs-deb7-32.sh
5. Ikuti proses sampai selesai
Simple Web SSH dan VPN

Melakukan Konfigurasi Web SSH dan VPN Secara otomatis.
Caranya:

    Login VPS
    wget https://raw.githubusercontent.com/rizal180499/Auto-Installer-VPS/master/simplewebssh/simplewebssh.sh
    chmod +x simplewebssh.sh
    ./simplewebssh.sh
    Ikuti proses sampai selesai 
