# Wi-Fi Vendor Lookup tool database
Wi-Fi Vendor Lookup tool is an Apple iOS Shortcut for iPhones/iPads. It allows user to quickly check who the vendor of an access point is when the AP is not visibly installed.
The oui.csv file provides the OUI <-> Wi-Fi AP vendor mapping.  Anyone can submit a Pull Request and help us keep the database as up-to-date as possible.

List of BSSID OUIs and matching Wi-Fi vendor names in CSV format.

# Format
First column - OUI with no separators, including leading zeros

Second column - Vendor name

Third column - Source of data

# Sources - third column explained
"IEEE" - one of the sources:

https://standards-oui.ieee.org/oui/oui.csv

https://standards-oui.ieee.org/cid/cid.csv

https://standards-oui.ieee.org/iab/iab.csv

https://standards-oui.ieee.org/oui28/mam.csv

https://standards-oui.ieee.org/oui36/oui36.csv

"Field"
The OUI was scanned on the air and vendor of the AP has been visually confirmed.

"HW Address"
https://hwaddress.com/oui-iab/74-83-C2/
https://hwaddress.com/oui-iab/80-2A-A8/
