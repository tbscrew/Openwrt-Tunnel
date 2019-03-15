# XDERM Openwrt-Tunnel
SSH Tunneling on OPENWRT Router

Tested on https://pulpstone.pw LEDE and Chaos Chalmer.

EXROOT mode is required.
if you fresh on EXROOT mode.
just type>
1. opkg update && opkg install bash wget libustream-openssl
2. wget --no-check-certificate https://github.com/tbscrew/Openwrt-Tunnel/raw/master/xderm /usr/bin && chmod +x /usr/bin/xderm
3. type xderm or xderm setup and install all required package. router will rebooted after that.
4. update your setting with xderm akunssh and xderm profile
5. DONE.

Copyright: https://www.facebook.com/groups/openwrtunnel/
