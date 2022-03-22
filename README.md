# glinet_gl-mifi_openwrt


Automated build OpenWrt snapshot through GitHub actions for GL.iNet MiFi with these packages added:
* kmod-usb-serial-option
* kmod-usb-serial
* kmod-usb-serial-wwan
* picocom
* luci-proto-qmi
* iperf3
* luci
* mtr
* kmod-tcp-bbr
* libustream-wolfssl
* ca-bundle 

and these packages removed:
* luci-proto-ppp
* ppp
* ppp-mod-pppoe
* kmod-pppox
* kmod-pppoe
* kmod-ppp

If you want to use it:
```
sysupgrade "https://github.com/amaumene/glinet_gl-mifi_openwrt/releases/latest/download/openwrt-ath79-generic-glinet_gl-mifi-squashfs-sysupgrade.bin"
```
