OpenWrt repository for vlmcsd
========
Binaries built from this repository on 2019-08-22 can be downloaded from http://dwfreed.github.io/openwrt-vlmcsd/.
To install the vlmcsd package, run
```
echo "src/gz openwrt-vlmcsd http://dwfreed.github.io/openwrt-vlmcsd/OpenWrt/arm_cortex-a15_neon-vfpv4/base" >> /etc/opkg.conf
opkg update
opkg install vlmcsd
```