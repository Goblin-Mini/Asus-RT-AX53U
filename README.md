Install:

wget https://raw.githubusercontent.com/Goblin-Mini/Asus-RT-AX53U/main/openwrt-23.05.2-asus_rt-ax53u-factory.bin

mtd-write -i openwrt-23.05.2-asus_rt-ax53u-factory.bin -d Kernel

Packages:
base-files busybox ca-bundle dnsmasq-full dropbear firewall4 fstools kmod-gpio-button-hotplug kmod-leds-gpio kmod-mt7915-firmware kmod-nft-offload kmod-usb-ledtrig-usbport kmod-usb3 libc libgcc libustream-mbedtls logd luci mtd netifd nftables odhcp6c odhcpd-ipv6only opkg ppp ppp-mod-pppoe procd procd-seccomp procd-ujail uboot-envtools uci uclient-fetch urandom-seed urngd wpad-basic-mbedtls kmod-usb-storage block-mount ntfs-3g luci-app-ksmbd luci-i18n-ksmbd-ru wsdd2 minidlna luci-app-minidlna luci-i18n-minidlna-ru wireguard-tools kmod-wireguard luci-proto-wireguard ddns-scripts ddns-scripts-services luci-app-ddns luci-i18n-ddns-ru inadyn dnscrypt-proxy2 transmission-cli transmission-daemon transmission-remote transmission-web luci-app-transmission luci-i18n-transmission-ru openvpn-easy-rsa openvpn-openssl luci-app-openvpn luci-i18n-openvpn-ru openssh-sftp-server luci-i18n-base-ru  luci-i18n-firewall-ru luci-i18n-hd-idle-ru luci-i18n-opkg-ru hd-idle luci-app-hd-idle adblock luci-app-adblock luci-i18n-adblock-ru kmod-usb-net-rndis usb-modeswitch watchcat luci-app-watchcat luci-i18n-watchcat-ru drill
