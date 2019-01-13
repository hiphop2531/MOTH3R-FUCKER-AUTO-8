SSH Debian7-8 x32 x64

Untuk Debian 8 (Jessie) 32 bit
1. wget https://raw.githubusercontent.com/hiphop2531/SSH-Debian7-8-x32-x64/master/deb32.sh
2. chmod +x deb32.sh
3. /deb32.sh

Untuk Debian 8 (Jessie) 64 bit
1. wget https://raw.githubusercontent.com/hiphop2531/SSH-Debian7-8-x32-x64/master/deb64.sh
2. chmod +x deb64.sh
3. ./deb64.sh

Debian 8 64 bit+32 bit
1. wget https://raw.githubusercontent.com/hiphop2531/SSH-Debian7-8-x32-x64/master/Debian8
2. chmod +x Debian8
3. ./Debian8

menu : แสดงรายการคำสั่งที่มี
usernew : สร้างบัญชี SSH
trial : สร้างบัญชีทดลองใช้
hapus : ลบบัญชี SSH
cek : ตรวจสอบการเข้าสู่ระบบของผู้ใช้
member : ตรวจสอบรายชื่อสมาชิก SSH
reboot : รีบูต VPS
speedtest : เชคความเร็วเน็ต VPS
info : แสดงข้อมูลระบบ
about : ข้อมูลเกี่ยวกับสคริปต์การติดตั้งอัตโนมัติ


OpenSSH, port : 22, 444
Dropbear, port : 143, 3128
SSL, port : 443
Squid3, port : 8000, 8080 (limit to IP SSH)
Badvpn : badvpn-udpgw port 7200
Webmin : http://IPVPS:10000/
Script menu : menampilkan daftar perintah yang tersedia
Script usernew : membuat akun SSH
Script trial : membuat akun trial
Script hapus : menghapus akun SSH
Script cek : cek user login
Script member : cek daftar member SSH
Script speedtest : speedtest VPS
Script info : menampilkan informasi sistem
Script about : informasi tentang script auto install
VPS auto reboot tiap jam 12 malam
