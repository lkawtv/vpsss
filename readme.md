AUTO INSTALLER DEBIAN 9-10

Script :
wget https://raw.githubusercontent.com/lkawtv/vpsss/master/ssh-vpn.sh && chmod +x ssh-vpn.sh && ./ssh-vpn.sh

Fitur :
OpenSSH        : 22
Dropbear       : 109, 110, 143, 456
SSL/TLS        : 222, 443, 777, 990
Port Squid     : 80, 3128, 8080 (limit to IP SSH)
OpenVPN        : TCP 1194 http://IP:81/client-tcp-1194.ovpn
OpenVPN        : UDP 2200 http://IP:81/client-udp-2200.ovpn
OpenVPN        : SSL 442 http://IP:81/client-tcp-ssl.ovpn
badvpn         : 7100-7300

Credit :
marloxxxssh.xyz

Reupload :
sshsedang.site
