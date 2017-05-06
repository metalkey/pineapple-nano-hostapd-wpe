# Hostapd-wpe on the Pineapple NANO for WPA2-Enterprise Attacks
ssh root@IP-OF-PINEAPPLE<br>
cd /tmp<br>
wget https://github.com/metalkey/pineapple-nano-hostapd-wpe/blob/master/hostapd-wpe_2014-06-03.1-1_ar71xx.ipk<br>
opkg install ./hostapd-wpe_2014-06-03.1-1_ar71xx.ipk<br>
cd<br>
wget https://github.com/metalkey/pineapple-nano-hostapd-wpe/blob/master/pineapple-hostapd-wpe.conf<br>
hostapd-wpe pineapple-hostapd-wpe.conf<br>
<br>
# Creds
https://github.com/TarlogicSecurity/hostapd-wpe-openwrt/raw/master/packages/ar71xx/generic/hostapd-wpe_2014-06-03.1-1_ar71xx.ipk<br>
https://forums.hak5.org/index.php?/topic/38982-hostapd-wpe/<br>
