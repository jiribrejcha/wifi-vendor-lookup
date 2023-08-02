# Very much work in progress

# Wi-Fi Vendor Lookup
Wi-Fi Vendor Lookup tool is an Apple iOS Shortcut for iPhones/iPads. It allows user to quickly check who the vendor of an access point is when the AP is not visibly installed.
The oui-vendor.csv file provides OUI <-> Wi-Fi AP vendor mapping and it is Wi-Fi centric.

# Format
CSV with 3 columns with larger vendors towards the top of the list

# Source - the third column

- Wireshark - Wireshark's OUI database from IEEE and other sources 
- Field - The OUI was seen on the air using a Wi-Fi scanner and vendor of the AP has been visually confirmed
- Documentation - Vendor's documentation
- HW Address - The HW Address tool https://hwaddress.com/oui-iab/74-83-C2/, https://hwaddress.com/oui-iab/80-2A-A8/

# Known matches
- BT Hub 6 - Sagemcom Broadband
- WLAN Pi M4 with MT7922 - Cloud Network Technology Singapore

# Help us keep the database up to date
Simply clone our repo, and submit a Pull Request with your suggested update. Ideally, include a Wi-Fi scan result and a photo of the AP (including the label if you can access it).
