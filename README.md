## Openwrt image builder
This repo create actions follow instruction at https://openwrt.org/docs/guide-user/additional-software/imagebuilder

### Default build information:

* Build target: **ramips/mt7621**
* Device profile: **jcg_q20**
* Openwrt version: **25.12.5**
* Image builder downloaded from: https://downloads.openwrt.org/releases/25.12.5/targets/ramips/mt7621/openwrt-imagebuilder-25.12.5-ramips-mt7621.Linux-x86_64.tar.zst
<details>
<summary>Installed package</summary>

```
apk-mbedtls base-files busybox ca-bundle cgi-io curl dnsmasq dropbear firewall4 fstools fwtool getrandom hostapd-common htop ip-tiny ip6tables-nft ipset iptables-mod-conntrack-extra iptables-mod-ipopt iptables-nft iw iwinfo jansson4 jshn jsonfilter kernel kmod-cfg80211 kmod-crypto-acompress kmod-crypto-aead kmod-crypto-authenc kmod-crypto-ccm kmod-crypto-cmac kmod-crypto-crc32c kmod-crypto-ctr kmod-crypto-des kmod-crypto-gcm kmod-crypto-geniv kmod-crypto-gf128 kmod-crypto-ghash kmod-crypto-hash kmod-crypto-hmac kmod-crypto-hw-eip93 kmod-crypto-kpp kmod-crypto-lib-chacha20 kmod-crypto-lib-chacha20poly1305 kmod-crypto-lib-curve25519 kmod-crypto-lib-poly1305 kmod-crypto-manager kmod-crypto-md5 kmod-crypto-null kmod-crypto-rng kmod-crypto-seqiv kmod-crypto-sha1 kmod-crypto-sha256 kmod-crypto-sha3 kmod-crypto-sha512 kmod-gpio-button-hotplug kmod-hwmon-core kmod-i2c-core kmod-ifb kmod-ip6tables kmod-ipt-conntrack kmod-ipt-conntrack-extra kmod-ipt-core kmod-ipt-ipopt kmod-ipt-ipset kmod-ipt-nat kmod-ipt-nat6 kmod-leds-gpio kmod-lib-crc-ccitt kmod-lib-crc32c kmod-lib-lzo kmod-mac80211 kmod-mt76-connac kmod-mt76-core kmod-mt7915-firmware kmod-mt7915e kmod-nf-conncount kmod-nf-conntrack kmod-nf-conntrack-netlink kmod-nf-conntrack6 kmod-nf-flow kmod-nf-ipt kmod-nf-ipt6 kmod-nf-log kmod-nf-log6 kmod-nf-nat kmod-nf-nat6 kmod-nf-reject kmod-nf-reject6 kmod-nfnetlink kmod-nft-compat kmod-nft-core kmod-nft-fib kmod-nft-nat kmod-nft-offload kmod-ppp kmod-pppoe kmod-pppox kmod-sched-cake kmod-sched-core kmod-slhc kmod-thermal kmod-udptunnel4 kmod-udptunnel6 kmod-wireguard libacl libatomic1 libattr libblobmsg-json20260213 libc libcurl4 libgcc1 libip4tc2 libip6tc2 libipset13 libiptext-nft0 libiptext0 libiptext6-0 libiwinfo-data libiwinfo20230701 libjson-c5 libjson-script20260213 liblua5.1.5 liblucihttp-lua liblucihttp-ucode liblucihttp0 libmbedtls21 libmnl0 libncurses6 libnftnl11 libnghttp2-14 libnl-tiny1 libopenssl-conf libopenssl-legacy libopenssl3 libpopt0 libpthread libspeedtestcpp libstdcpp6 libubox20260213 libubus-lua libubus20251202 libuci20250120 libuclient20201210 libucode20230711 libudebug libustream-mbedtls20201210 libxtables12 logd lua luci luci-app-argon-config luci-app-firewall luci-app-package-manager luci-app-usteer luci-base luci-compat luci-lib-base luci-lib-chartjs luci-lib-ip luci-lib-ipkg luci-lib-jsonc luci-lib-nixio luci-lib-uqr luci-light luci-lua-runtime luci-mod-admin-full luci-mod-network luci-mod-status luci-mod-system luci-proto-ipv6 luci-proto-ppp luci-proto-wireguard luci-ssl luci-theme-argon luci-theme-bootstrap mtd netifd nftables-json odhcp6c odhcpd-ipv6only openwrt-keyring ppp ppp-mod-pppoe procd procd-seccomp procd-ujail px5g-mbedtls resolveip rpcd rpcd-mod-file rpcd-mod-iwinfo rpcd-mod-luci rpcd-mod-rrdns rpcd-mod-ucode rsync speedtestcpp tc-tiny terminfo ubi-utils uboot-envtools ubox ubus ubusd uci uclient-fetch ucode ucode-mod-digest ucode-mod-fs ucode-mod-html ucode-mod-log ucode-mod-lua ucode-mod-math ucode-mod-nl80211 ucode-mod-rtnl ucode-mod-ubus ucode-mod-uci ucode-mod-uloop uhttpd uhttpd-mod-ubus urandom-seed urngd usign usteer wifi-scripts wireguard-tools wireless-regdb wpad-mesh-openssl xtables-legacy xtables-nft zlib
```
</details>

<details>
<summary>Disabled services</summary>

```
```
</details>

[Download sysupgrade image](https://github.com/hoang-rio/openwrt-image-builder/releases/download/jcg_q20%2F25.12.5/openwrt-25.12.5-ramips-mt7621-jcg_q20-squashfs-sysupgrade.bin)
