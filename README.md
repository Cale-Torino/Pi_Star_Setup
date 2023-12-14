# Using Pi-Star post 2021 (on a Pi 4)

Download files from [www.pistar.uk](https://www.pistar.uk/downloads)

Installing package `Pi-Star_RPi_V4.1.5_30-Oct-2021.zip`.

Using the tool `imager_1.8.1.exe`.

[Wifi Builder](https://www.pistar.uk/wifi_builder.php)

[Configure](http://pi-star.local/admin/configure.php)

[Brandmeister Login](https://brandmeister.network/?page=login)

# WPA Supplicant

```conf
ctrl_interface=DIR=/var/run/wpa_supplicant GROUP=netdev
update_config=1
ap_scan=1
fast_reauth=1
country=ZA

network={
	#ssid="test"
	ssid=74657374
	#psk="testing"
	psk=c58c8065c51f332ccfe00fb233ec33644df0fdfc7b0b242382be00d5df158c05
	id_str="0"
	priority=100
	scan_ssid=1
}
```




# Topics
- https://www.reddit.com/r/DMR/comments/14bk1e1/hotspot_goodbye_pistar/?rdt=50763&onetap_auto=true
- https://forum.pistar.uk/viewtopic.php?t=4061
- https://amateurradionotes.com/pi-star.htm#backinguppistar
- https://amateurradionotes.com/pi-star-updates.htm#upgrading4










