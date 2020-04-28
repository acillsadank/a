# install
Auto Install Debian 9 Debian 10
OpenSSH: 22
Dropbear: 442, 443, 990
SSL: 444
Squid3: 80, 8080 (batas untuk IP SSH)
SSL: http: // myip: 81 / ssl.conf
OpenVPNSSL: http: // myip: 81 / openvpnssl.ovpn
OpenVPN: TCP 1194 (konfigurasi klien: http: // myip: 81 / client.ovpn )
badvpn: badvpn-udpgw port 7200
nginx: 81

Pemasang Otomatis

apt-get update && apt-get upgrade -y && wget https://raw.githubusercontent.com/acillsadank/install/master/install.sh && chmod + x install.sh && ./install.sh
