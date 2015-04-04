client
dev tun
proto udp
remote 167.160.165.27 1194 #- ip public server openvpn dan port yg digunakan.
resolv-retry infinite
nobind
tun-mtu 1500
tun-mtu-extra 32
mssfix 1450
persist-key
persist-tun
ca ca.crt
auth-user-pass
comp-lzo
verb 3
client-to-client
asd