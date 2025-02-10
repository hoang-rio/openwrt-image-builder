## Openwrt image builder
This repo create actions follow instruction at https://openwrt.org/docs/guide-user/additional-software/imagebuilder

### Default build information:

* Build target: **ramips/mt7621**
* Device profile: **xiaomi_mi-router-3g**
* Openwrt version: **23.05.5**
* Image builder downloaded from: https://downloads.openwrt.org/releases/23.05.5/targets/ramips/mt7621/openwrt-imagebuilder-23.05.5-ramips-mt7621.Linux-x86_64.tar.xz
<details>
<summary>Installed package</summary>

```
adguardhome aria2 ariang attr avahi-dbus-daemon base-files block-mount busybox ca-bundle ca-certificates cgi-io coreutils coreutils-nohup curl dbus ddns-scripts ddns-scripts-cloudflare ddns-scripts-services dnsmasq dropbear firewall4 fstools fwtool getrandom git git-http hostapd-common htop https-dns-proxy ip-tiny ip6tables-nft ip6tables-zz-legacy ipset iptables-mod-conntrack-extra iptables-mod-ipopt iptables-mod-ipsec iptables-nft iptables-zz-legacy iw iwinfo jansson4 jshn jsonfilter kernel kmod-cfg80211 kmod-crypto-acompress kmod-crypto-aead kmod-crypto-authenc kmod-crypto-cbc kmod-crypto-ccm kmod-crypto-cmac kmod-crypto-crc32c kmod-crypto-ctr kmod-crypto-deflate kmod-crypto-des kmod-crypto-echainiv kmod-crypto-gcm kmod-crypto-gf128 kmod-crypto-ghash kmod-crypto-hash kmod-crypto-hmac kmod-crypto-kpp kmod-crypto-lib-chacha20 kmod-crypto-lib-chacha20poly1305 kmod-crypto-lib-curve25519 kmod-crypto-lib-poly1305 kmod-crypto-manager kmod-crypto-md5 kmod-crypto-null kmod-crypto-rng kmod-crypto-seqiv kmod-crypto-sha1 kmod-crypto-sha256 kmod-crypto-sha512 kmod-fs-exfat kmod-gpio-button-hotplug kmod-ifb kmod-ip6tables kmod-ipsec kmod-ipsec4 kmod-ipsec6 kmod-ipt-conntrack kmod-ipt-conntrack-extra kmod-ipt-core kmod-ipt-ipopt kmod-ipt-ipsec kmod-ipt-ipset kmod-ipt-raw kmod-iptunnel4 kmod-iptunnel6 kmod-l2tp kmod-leds-gpio kmod-lib-crc-ccitt kmod-lib-crc32c kmod-lib-zlib-deflate kmod-lib-zlib-inflate kmod-mac80211 kmod-macvlan kmod-mt76-core kmod-mt7603 kmod-mt76x02-common kmod-mt76x2 kmod-mt76x2-common kmod-nf-conncount kmod-nf-conntrack kmod-nf-conntrack-netlink kmod-nf-conntrack6 kmod-nf-flow kmod-nf-ipt kmod-nf-ipt6 kmod-nf-log kmod-nf-log6 kmod-nf-nat kmod-nf-reject kmod-nf-reject6 kmod-nfnetlink kmod-nft-compat kmod-nft-core kmod-nft-fib kmod-nft-nat kmod-nft-offload kmod-nls-base kmod-ppp kmod-pppoe kmod-pppol2tp kmod-pppox kmod-sched-cake kmod-sched-core kmod-scsi-core kmod-slhc kmod-tun kmod-udptunnel4 kmod-udptunnel6 kmod-usb-core kmod-usb-ledtrig-usbport kmod-usb-storage kmod-usb-xhci-hcd kmod-usb-xhci-mtk kmod-usb3 kmod-wireguard libatomic1 libattr libavahi-client libavahi-dbus-support libblkid1 libblobmsg-json20230523 libbz2-1.0 libc libcap libcares libcurl4 libdaemon libdbus libev libevdev libexpat libffi libgcc1 libgdbm libgmp10 libgnutls libip4tc2 libip6tc2 libipset13 libiptext-nft0 libiptext0 libiptext6-0 libiwinfo-data libiwinfo-lua libiwinfo20230701 libjson-c5 libjson-script20230523 libldns liblua5.1.5 liblucihttp-lua liblucihttp-ucode liblucihttp0 liblzma libmbedtls12 libmnl0 libncurses6 libnetfilter-conntrack3 libnettle8 libnfnetlink0 libnftnl11 libnghttp2-14 libnl-tiny1 libopenssl3 libpam libpopt0 libpthread libpython3-3.11 libreadline8 librt libsodium libsqlite3-0 libstdcpp6 libtasn1 libtirpc libubox20230523 libubus-lua libubus20230605 libuci-lua libuci20130104 libuclient20201210 libucode20230711 libudev-zero libusb-1.0-0 libustream-mbedtls20201210 libuuid1 libuv1 libxtables12 logd lua luci luci-app-alpha-config luci-app-argon-config luci-app-aria2 luci-app-ddns luci-app-firewall luci-app-mwan3 luci-app-opkg luci-app-samba4 luci-app-sqm luci-base luci-compat luci-lib-base luci-lib-ip luci-lib-ipkg luci-lib-jsonc luci-lib-nixio luci-lib-uqr luci-light luci-lua-runtime luci-mod-admin-full luci-mod-network luci-mod-status luci-mod-system luci-proto-ipv6 luci-proto-ppp luci-proto-wireguard luci-ssl luci-theme-alpha luci-theme-argon luci-theme-bootstrap mtd mwan3 nano netifd nftables-json nload odhcp6c odhcpd-ipv6only openwrt-keyring opkg ppp ppp-mod-pppoe ppp-mod-pppol2tp procd procd-seccomp procd-ujail px5g-mbedtls python3 python3-asyncio python3-base python3-cgi python3-cgitb python3-codecs python3-ctypes python3-dbm python3-decimal python3-distutils python3-email python3-light python3-logging python3-lzma python3-multiprocessing python3-ncurses python3-openssl python3-pip python3-pydoc python3-readline python3-sqlite3 python3-unittest python3-urllib python3-uuid python3-xml resolveip rpcd rpcd-mod-file rpcd-mod-iwinfo rpcd-mod-luci rpcd-mod-rrdns rpcd-mod-ucode rsync samba4-libs samba4-server sqm-scripts strongswan strongswan-charon strongswan-ipsec strongswan-minimal strongswan-mod-aes strongswan-mod-des strongswan-mod-gmp strongswan-mod-hmac strongswan-mod-kernel-netlink strongswan-mod-mgf1 strongswan-mod-pubkey strongswan-mod-random strongswan-mod-sha1 strongswan-mod-sha2 strongswan-mod-socket-default strongswan-mod-stroke strongswan-mod-updown strongswan-mod-vici strongswan-mod-x509 strongswan-mod-xauth-generic strongswan-mod-xcbc strongswan-swanctl tc-tiny terminfo ubi-utils ubox ubus ubusd uci uclient-fetch ucode ucode-mod-fs ucode-mod-html ucode-mod-lua ucode-mod-math ucode-mod-nl80211 ucode-mod-rtnl ucode-mod-ubus ucode-mod-uci ucode-mod-uloop uhttpd uhttpd-mod-ubus urandom-seed urngd usbutils usign wireguard-tools wireless-regdb wpad-basic-mbedtls xl2tpd xtables-legacy xtables-nft zlib
```
</details>
