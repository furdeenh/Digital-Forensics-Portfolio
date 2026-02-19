# Technical Notes: NTFS Alternate Data Streams

NTFS allows files to contain multiple data streams. Attackers may exploit this feature to hide data in a way that remains invisible in standard file explorers.

Detection requires specialized forensic tools capable of enumerating stream attributes.

This investigation demonstrates how ADS can be used to conceal communication or sensitive data.
