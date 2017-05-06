# Hostapd-wpe on the Pineapple NANO for WPA2-Enterprise Attacks
ssh root@IP-OF-PINEAPPLE
cd /tmp
wget https://github.com/metalkey/pineapple-nano-hostapd-wpe/blob/master/hostapd-wpe_2014-06-03.1-1_ar71xx.ipk
opkg install ./hostapd-wpe_2014-06-03.1-1_ar71xx.ipk
cd
hostapd-wpe pineapple-hostapd-wpe.conf

# Creds
https://github.com/TarlogicSecurity/hostapd-wpe-openwrt/raw/master/packages/ar71xx/generic/hostapd-wpe_2014-06-03.1-1_ar71xx.ipk
https://forums.hak5.org/index.php?/topic/38982-hostapd-wpe/
