# Wi-Fi Vendor - Detect vendor of a Wi-Fi access point with just your iPhone or iPad
Wi-Fi Vendor is an Apple iOS Shortcut for iPhones/iPads. It allows you to check the vendor of an access point. It is very useful when the AP is not visibly installed.

## Documentation
More documentation is [available on my blog here.](https://www.jiribrejcha.net/2023/08/wi-fi-vendor-detect-vendor-of-a-wi-fi-access-point-with-just-your-iphone-or-ipad/)

## Screenshots and video demos
![image](https://github.com/jiribrejcha/wifi-vendor-lookup/assets/18701525/11f7fd91-b582-46cf-8a32-5b4769542710)

Video demos [are available here](https://www.jiribrejcha.net/2023/08/wi-fi-vendor-detect-vendor-of-a-wi-fi-access-point-with-just-your-iphone-or-ipad/).

![image](https://github.com/jiribrejcha/wifi-vendor-lookup/assets/18701525/ec7d19b8-fedb-4304-a488-060cd8143db2)


## How to install
1. Download [Wi-Fi Vendor.shortcut](https://github.com/jiribrejcha/wifi-vendor-lookup/raw/main/Wi-Fi%20Vendor.shortcut) on your iPhone/iPad and add it to your Shortcuts app.
2. Follow our [video installation guide](https://www.jiribrejcha.net/2023/08/wi-fi-vendor-detect-vendor-of-a-wi-fi-access-point-with-just-your-iphone-or-ipad#install).
4. Either connect to a Wi-Fi network and we will automatically detect the BSSID you are connected to and find the vendor for you.
5. Alternatively, enter the OUI or the whole BSSID manually. Try this for example: ```00:01:42```

## Dabatase format
This Shortcut is using our own Wi-Fi-centric database of OUIs and vendors. It is compiled from Wireshark's sources (mainly IEEE) with some additional Wi-Fi entries from Wi-Fi vendors' documentation and few entries captured on the air in the field. The database itself is a flat comma-separated file with 3 columns:

<img width="399" alt="image" src="https://github.com/jiribrejcha/wifi-vendor-lookup/assets/18701525/5721e426-fe41-4202-9eb5-c0aad789092c">

With larger Wi-Fi vendors towards the top of the list to optimise lookup time.

### Source - the third column

- Wireshark - [Wireshark's OUI database](https://www.wireshark.org/tools/oui-lookup.html) from IEEE and other sources, huge thanks to the Wireshark team 
- Field - The OUI was seen on the air using a Wi-Fi scanner and vendor of the AP has been visually confirmed
- Documentation - Vendor's documentation

### Known matches

Some vendors ship Wi-Fi routers with various chipsets and OUIs. To help you identify the actual device model, these are some well-known matches:

- BT Hub 6 - Sagemcom Broadband
- WLAN Pi M4 with MT7922 - Cloud Network Technology Singapore
- Virgin Media Hub - Sagemcom Broadband SAS, ARRIS Group Inc.

## Help us keep the database up to date
Simply clone our repo, and submit a Pull Request with your suggested update. If you are proposing a new database addition or edit, include a Wi-Fi scan result screenshot, and a photo of the AP including the label, if you can access it.

## The mandatory boring bit

This tool is provided as is. If you spot anything that needs to be fixed, let us know, or even better submit a Pull Request including the fix. Blame Jiri for anything that needs to be fixed, not Cisco 😉
