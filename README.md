# Wi-Fi Vendor Lookup Shortcut
Wi-Fi Vendor Lookup tool is an Apple iOS Shortcut for iPhones/iPads. It allows you to quickly check who the vendor of an access point. Very useful when the AP is not visibly installed.

# How to install
1. Open the "Wi-Fi Vendor Lookup.shortcut" on your iPhone/iPad and add it to your Shortcuts app.
2. Approve permission requests.
3. Open Shortcuts app and run it for the first time.
4. Either connect to a Wi-Fi network and we will automatically detect the BSSID you are connected to and find the vendor for you.
5. Alternatively, enter the OUI or the whole BSSID manually. Try this for example: ```00:01:42```

# Dabatase format
This Shortcut is using our own Wi-Fi-centric databse of OUIs and vendors. It is compiled from Wireshark's sources (mainly IEEE) with some additional Wi-Fi entries from Wi-Fi vendors' documentation. The database itself is a flat CSV file with 3 columns - OUI, Vendor name, Source. With larger Wi-Fi vendors towards the top of the list to optimise lookup time.

# Source - the third column

- Wireshark - Wireshark's OUI database from IEEE and other sources 
- Field - The OUI was seen on the air using a Wi-Fi scanner and vendor of the AP has been visually confirmed
- Documentation - Vendor's documentation
- HW Address - The HW Address tool https://hwaddress.com/oui-iab/74-83-C2/, https://hwaddress.com/oui-iab/80-2A-A8/

# Known matches

Some vendors ship Wi-Fi routers with various chipsets and OUIs. To help you identify the actual device model, these are some well-known matches:

- BT Hub 6 - Sagemcom Broadband
- WLAN Pi M4 with MT7922 - Cloud Network Technology Singapore

# Help us keep the database up to date
Simply clone our repo, and submit a Pull Request with your suggested update. Ideally, include a Wi-Fi scan result and a photo of the AP (including the label if you can access it).
